# PostMini — Lightweight API Client

Lightweight Postman alternative in Chrome Side Panel. Send REST requests, view responses, history & cURL export.

**Chrome Web Store:**  
https://chromewebstore.google.com/detail/postmini-%E2%80%94-lightweight-ap/hjnjggohjpacnfpmpfggcidecojfadli

**Version:** see `manifest.json` in this folder.

---

## English

PostMini is a lightweight API client for Chrome. Send HTTP requests from the Side Panel beside your docs — no desktop app, no account.

### Why PostMini

- Side Panel (default), popup, or full tab — open how you work
- No account — collections and history stay local on your device
- Postman's core workflow without the weight

### Features

- All common HTTP methods; params, auth (Basic, Bearer, API Key, OAuth2), headers, body
- Body types: form-data, urlencoded, raw JSON/text, binary
- Response viewer: status, timing, body, headers, raw
- Projects, folders, multi-tab editor
- Per-request and global history
- Copy as cURL (includes proxy when enabled)
- Import from cURL · export workspace as JSON
- HTTP / HTTPS / SOCKS4 / SOCKS5 proxy with on-screen indicator
- Configurable timeout and redirect following

Built for frontend and full-stack developers who debug APIs while reading docs in the browser.

---

## 中文

PostMini 是 Chrome 里的轻量 API 客户端。在侧边栏里发 HTTP 请求，文档和调试并排 —— 无需桌面客户端，无需账号。

### 为什么选 PostMini

- 侧边栏（默认）、弹窗或标签页，按你的工作方式打开
- 无需账号，集合与历史记录保存在本机
- 保留 Postman 核心流程，没有臃肿负担

### 功能

- 常用 HTTP 方法；Params、鉴权（Basic、Bearer、API Key、OAuth2）、Headers、Body
- Body：form-data、urlencoded、Raw JSON/文本、二进制
- 响应：状态码、耗时、Body、Headers、Raw
- 项目、文件夹、多标签编辑
- 单请求与全局历史记录
- 复制为 cURL（启用代理时包含 `--proxy`）
- 从 cURL 导入 · 导出工作区 JSON
- HTTP / HTTPS / SOCKS4 / SOCKS5 代理，界面显示状态
- 可配置超时与是否跟随重定向

适合在浏览器里边看文档边调 API 的前端与全栈开发者。

---

## Support / 反馈

- **Email:** hbnu001@gmail.com
- **Privacy:** https://github.com/eddy5885/postmini#privacy
- **GitHub Issues:** https://github.com/eddy5885/postmini/issues
- **Report feedback:** https://github.com/eddy5885/postmini/issues/new

---

## Privacy

PostMini stores your requests, folders, settings, and history locally using Chrome's storage API on your device. Request traffic is sent directly from your browser to the URLs you specify (optionally via a proxy you configure). We do not operate a backend server and do not collect your API data.

Full policy: https://github.com/eddy5885/postmini#privacy

PostMini 将请求、文件夹、设置与历史记录保存在本机 Chrome 存储中。HTTP 请求由浏览器直接发往您填写的地址（可选经您配置的代理）。我们不运营后端服务器，不收集您的 API 数据。

隐私政策：https://github.com/eddy5885/postmini#privacy

---

## Install / 安装

Install from the [Chrome Web Store](https://chromewebstore.google.com/detail/postmini-%E2%80%94-lightweight-ap/hjnjggohjpacnfpmpfggcidecojfadli), or load this `dist` folder as an unpacked extension at `chrome://extensions` (Developer mode).

从 [Chrome 网上应用店](https://chromewebstore.google.com/detail/postmini-%E2%80%94-lightweight-ap/hjnjggohjpacnfpmpfggcidecojfadli) 安装，或在 `chrome://extensions` 开启开发者模式后加载本 `dist` 目录。
