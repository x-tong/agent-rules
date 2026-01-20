# Python Rules

## 工具链
```bash
ruff check --fix . && ruff format .  # lint + format
mypy src/                             # 类型检查
pytest tests/ -v                      # 测试
```

## 规范
- 行长: 88，引号: `"`
- 类型注解: 所有函数必须有
- Import: stdlib → 第三方 → 本地（字母序）
- 使用 `list[]` 非 `List[]`

## 文档字符串
```python
def func(param: Type) -> ReturnType:
    """简短描述。

    Args:
        param: 说明

    Returns:
        说明

    Raises:
        ErrorType: 说明
    """
```

## 边界处理（必须）
- 空数组/None 检查
- 除零保护
- NaN 处理

## 禁止
- `# noqa`、`# type: ignore`（无充分理由）
- 未使用的 import/变量
- 循环替代可向量化操作
