# 简付支付系统

简付支付系统是一款高效、安全、易用的在线支付解决方案，旨在为用户提供便捷的支付体验。我们的系统支持多种支付方式，包括信用卡、借记卡、电子钱包等，能够满足不同用户的需求。

## 特性

- **多种支付方式**：支持主流支付方式，快速响应用户选择。
- **高安全性**：采用先进的加密技术，确保用户信息和交易安全。
- **用户友好的界面**：简洁明了的界面设计，提供流畅的支付流程。
- **实时交易跟踪**：用户可以实时查看交易状态，方便管理个人财务。

## 安装指南

1. 确保你的环境满足以下要求：

   - Node.js 21+
   - VitePress 1.3.4+

2. 克隆仓库：

   ```bash
   git clone https://github.com/your-repo/jianfu.git
   ```

3. 安装依赖：

   ```bash
   npm install
   ```

4. 启动开发环境：

   ```bash
   npm run dev
   ```

5. 访问 http://localhost:3000/ 即可看到简付支付系统的首页。

## 开发指南

### 目录结构

```
├── docs
│   ├── .vitepress
│   ├── 404.md
│   ├── index.md
│   ├── README.md
│   └── guide
│       ├── README.md
│       ├── getting-started.md
│       ├── payment-methods.md
│       ├── payment-result.md
│       └── payment-status.md
├── src
│   ├── App.vue
│   ├── assets
│   ├── components
│   ├── main.js
│   ├── plugins
│   ├── router
│   ├── styles
│   └── views
└── package.json
```

1. `docs` 目录：存放文档相关文件，包括 `.vitepress` 配置文件、Markdown 文件等。
2. `src` 目录：存放项目源码，包括 `App.vue` 入口组件、路由配置、组件、样式等。
3. `package.json` 文件：项目依赖配置。

### 开发流程

1. 克隆仓库：

   ```bash
   git clone https://github.com/your-repo/jianfu.git
   ```

2. 安装依赖：

   ```bash
   npm install
   ```

3. 启动开发环境：

   ```bash
   npm run dev
   ```

4. 编写文档：

   - 在 `docs` 目录下编写 Markdown 文件，并在 `guide` 目录下创建对应的 `.md` 文件。
   - 在 `docs/.vitepress/config.js` 文件中配置侧边栏、顶部导航等。

5. 编写组件：

   - 在 `src/components` 目录下创建新的组件。
   - 在 `src/views` 目录下创建新的页面，并在 `router/index.js` 文件中配置路由。
   - 在 `src/App.vue` 文件中引入组件，并在模板中渲染。

6. 编写插件：

   - 在 `src/plugins` 目录下创建新的插件。
   - 在 `src/main.js` 文件中引入插件，并在 `Vue.use()` 方法中注册。

7. 提交代码：
   ```bash
   git add.
   git commit -m "commit message"
   git push origin master
   ```

## 贡献者

感谢以下贡献者对简付支付系统的贡献：

- [ZhuanZ](https://github.com/ZhuanZ)
- [zhoujiajie](https://github.com/zhoujiajie)
