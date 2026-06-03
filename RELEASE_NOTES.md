# Anything Analyzer v3.6.49

## 修复

- **OpenAI 工具调用协议校验** — 拒绝 `tool_calls` 不是数组的 OpenAI Chat Completions 工具调用响应
  - 工具调用轮次不再把畸形 `tool_calls` 误判为缺少最终文本
  - 现在会在入站协议边界返回明确的工具调用格式错误

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.49.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.49-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.49-x64.dmg |
| Linux | Anything-Analyzer-3.6.49.AppImage |
