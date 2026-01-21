# Rust

## 工具链
```bash
cargo fmt
cargo clippy --fix --allow-dirty
cargo test
```

## 规范
- 遵循 clippy 建议
- 错误处理: 优先 `?` 和 `thiserror`，避免 `.unwrap()`（除非确定安全）

## 边界处理
- Option/Result 必须处理
- 整数溢出（debug 模式会 panic）
