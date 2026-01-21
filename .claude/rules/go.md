# Go

## 工具链
```bash
gofmt -w .
go vet ./...
golangci-lint run
go test ./...
```

## 规范
- 导出函数必须有文档注释
- 错误必须处理，不要 `_ = err`

## 边界处理
- nil 检查（slice, map, pointer, channel）
- error 不为 nil 时不要使用返回值
