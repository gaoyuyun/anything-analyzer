# Anything Analyzer v3.6.10

## 修复

- **代理认证无法访问网页** — 修复配置带用户名密码的代理后，内嵌浏览器访问网页报错 `ERR_NO_SUPPORTED_PROXIES` (-336) 的问题
	- Chromium 的 `proxyRules` 不支持内嵌凭证格式 (`user:pass@host:port`)
	- 改为通过 `app.on('login')` 事件响应代理 407 认证质询

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.10.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.10-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.10-x64.dmg |
| Linux | Anything-Analyzer-3.6.10.AppImage |
