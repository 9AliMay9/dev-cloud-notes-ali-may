## 📦 一、新建 Git 仓库并上传（展示新项目）

适用于开发类项目首次上传至 GitHub。

### ✅ 1. 初始化本地仓库

```bash
git init                          # 初始化 Git 仓库
git branch -m main                 # 将默认分支改名为 main
git add .                          # 添加全部文件
git commit -m "initial commit"     # 提交更改
````

### ✅ 2. 配置远程地址（使用 SSH）

```bash
git remote add origin git@github.com:你的用户名（username）/你的仓库名.git
```

### ✅ 3. 推送至远程仓库（带 rebase 标签）

```bash
git pull --rebase origin main      # 解决首次连接时远程可能已有 README/gitignore/LICENSE等的情况
git push -u origin main            # 设置默认上游并推送
```

## ⚙️ Git rebase 遇到 `.gitignore`、`LICENSE`、`README.md` 冲突的快速解决方案

### 1. 删除本地冲突文件

`rm .gitignore LICENSE README.md`

### 2. 告诉 Git 删除已解决

`git add -A`

> `-A` 是 `--all` 的简写，表示包括删除的文件也一起添加到暂存区

### 3. 继续 rebase

 `git rebase --continue`

---

## 📖 二、笔记同步

### **Windows -> GitHub 上传**

1. **在 Windows 上创建或修改 Obsidian 笔记**
2. **打开 Git Bash/终端，进入笔记所在目录**
```bash
cd path/to/your/obsidian/directory
```

3. **添加修改文件**
```bash
git add .
```

4. **提交更改**
```bash
git commit -m "Update Obsidian notes"
```

5. **推送到 GitHub**
```bash
git push -u origin main
```

---

### **Linux -> GitHub 拉取更新**

1. **在 Linux 上进入笔记仓库**
```bash
cd ~/path/to/obsidian/directory
```

2. **拉取 GitHub 仓库更新**
```bash
git pull --rebase origin main
```

