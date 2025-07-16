## 基本请求

### 1. `-i` 或 `--include`
包括响应头信息（如状态码、日期等）。

```bash
curl -i http://127.0.0.1:8000/sync
````

### 2. `-X` 或 `--request`

指定 HTTP 请求方法（如 `GET`, `POST`, `PUT`, `DELETE` 等）。

```bash
curl -X POST http://127.0.0.1:8000/your-endpoint
```

### 3. `-H` 或 `--header`

添加请求头（Headers），常用于授权、指定内容类型等。

```bash
curl -H "x-token: secret-token" http://127.0.0.1:8000/ping
```

### 4. `-d` 或 `--data`

提交数据，通常与 `-X POST` 一起使用，模拟提交表单或 JSON 数据。

```bash
curl -X POST -d '{"name":"Ali"}' http://127.0.0.1:8000/your-endpoint
```

### 5. `-v` 或 `--verbose`

输出详细的调试信息，包括请求和响应的完整内容。

```bash
curl -v http://127.0.0.1:8000/sync
```

### 6. `-o` 或 `--output`

将响应保存到文件中而不是显示在终端。

```bash
curl -o response.json http://127.0.0.1:8000/sync
```

### 7. `-L` 或 `--location`

自动跟踪重定向。当请求的 URL 被重定向时，`curl` 会继续请求新的 URL。

```bash
curl -L http://127.0.0.1:8000/redirect
```

### 8. `-u` 或 `--user`

用于 HTTP 基本认证，指定用户名和密码。

```bash
curl -u username:password http://127.0.0.1:8000/protected
```

### 9. `-s` 或 `--silent`

静默模式，抑制进度信息，只输出响应内容。

```bash
curl -s http://127.0.0.1:8000/sync
```

---

## 补充说明：

- `-X` 和 `--request` 用来指定请求类型，它们是同义词。
- `-H` 用来添加 HTTP 请求头，它是 `--header` 的简写。
- `-d` 用来提交数据，通常与 `-X POST` 一起使用。