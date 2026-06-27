# 🧪 Prompt Playground

一个轻量级的 AI Prompt 测试工作台。纯前端实现，无需后端，直接在浏览器中测试和对比不同 Prompt 的效果。

## ✨ 特性

- **纯前端** — 无需后端服务，直接调用 OpenAI 兼容 API
- **实时测试** — 输入 Prompt 即时获取 AI 响应
- **配置灵活** — 支持自定义 API URL、模型、Temperature、Max Tokens
- **历史记录** — 自动保存测试历史，方便回溯对比
- **暗色主题** — 对开发者友好的终端风格 UI
- **快捷键** — Ctrl+Enter 快速发送

## 🚀 使用方式

1. 直接打开 `index.html`
2. 填入 API Key 和 API Base URL
3. 输入 System Prompt（可选）和 User Prompt
4. 点击发送或按 Ctrl+Enter

## 📦 部署

```bash
# 本地直接打开
open index.html

# 或部署到 GitHub Pages
# 推送到 GitHub 后，在 Settings → Pages 启用即可
```

## 🏗️ 项目结构

```
prompt-playground/
├── README.md
├── index.html         # 单文件应用
└── .gitignore
```

## License

MIT
