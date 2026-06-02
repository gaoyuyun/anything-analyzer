# Anything Analyzer v3.6.42

## 修复

- **Anthropic/MiniMax 工具调用字段校验** — 避免缺少 id/name 的 tool_use 进入工具执行轮次
  - 工具调用入站阶段直接拒绝缺少 id 或 name 的 tool_use
  - 新增回归测试覆盖 Anthropic 兼容工具调用字段缺失路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.42.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.42-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.42-x64.dmg |
| Linux | Anything-Analyzer-3.6.42.AppImage |
