# Java

## 工具链
```bash
./gradlew spotlessApply  # 或 mvn spotless:apply
./gradlew test           # 或 mvn test
```

## 规范
- 遵循项目 checkstyle/spotless 配置
- 优先使用 Optional 而非 null

## 边界处理
- null 检查（或使用 @Nullable/@NonNull）
- 集合为空
