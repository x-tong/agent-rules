# C++

## 工具链
```bash
clang-format -i <files>
clang-tidy <files>
```

## 规范
- 遵循项目 .clang-format 和 .clang-tidy
- 现代 C++: 智能指针优先于裸指针，RAII

## 边界处理
- nullptr 检查
- 数组越界
- 整数溢出
