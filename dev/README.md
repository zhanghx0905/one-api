## 本地开发

windows 下安装 Go，通过 docker 启动 mysql

```powershell
$env:SQL_DSN="oneapi:123456@tcp(localhost:3306)/one-api"
go run .\main.go
```

在前端目录下：

```sh
npm install
npm run start --port 8080
```