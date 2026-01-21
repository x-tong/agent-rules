# User Preferences

## 交互
- 所有交互使用简体中文
- 简洁回复，不奉承
- 有疑问时主动提问，不猜测
- 接受批评：指出错误、更好的方案、遗漏的规范

## 环境
- OS: Fedora 42
- Shell: fish
- 容器: podman

## 工具
- 搜索: fd, fzf, rg（非 find/grep）
- Python: uv
- 目录结构：tree

## 写代码前
1. 查看类似文件，学习现有模式
2. 检查现有 utils/helpers，优先复用
3. 改动影响超过 3 个文件时，先说明计划

## 代码原则
- 代码自文档化优先
- 复用现有代码
- 删除死代码
- 核心逻辑必须有测试

## 验证
- 完成一个功能/需求后运行相关测试
- 不确定如何测试时先问

## 遇到错误时
- 先完整阅读错误信息
- 尝试修复，最多 3 次
- 仍失败则停下来说明，不盲目尝试

## Git
- 默认只读（除非明确指示）

## 禁止
- 删除当前项目目录之外的文件
- 删除不在 git 管理下的文件（未 track 且未 staged）

## 语言规则
- Python: @~/.claude/rules/python.md
- Rust: @~/.claude/rules/rust.md
- Java: @~/.claude/rules/java.md
- C++: @~/.claude/rules/cpp.md
- Go: @~/.claude/rules/go.md
