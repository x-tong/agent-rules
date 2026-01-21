# Python

## 工具链
```bash
ruff check --fix . && ruff format .
mypy src/
pytest tests/ -v
```

## 规范
- 类型注解: 所有函数签名
- 使用现代语法: `list[]`, `dict[]`, `X | None`

## 边界处理
- 空集合/None
- 除零
- NaN/Inf

## 禁止
- `# noqa`、`# type: ignore`（无说明）
