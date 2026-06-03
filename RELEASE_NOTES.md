# Anything Analyzer v3.6.50

## 修复

- **LLM 工具调用协议校验** — 拒绝非字符串的 OpenAI、Responses API 与 Anthropic/MiniMax 工具调用标识字段
  - 工具调用轮次不再让数字型 `id`、`name` 或 `call_id` 进入工具执行与结果回填路径
  - 畸形工具调用响应现在会在入站协议边界返回明确格式错误

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.50.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.50-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.50-x64.dmg |
| Linux | Anything-Analyzer-3.6.50.AppImage |
