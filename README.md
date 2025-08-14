# AI Chat Tool

基于 React + TypeScript 的 AI 聊天工具

## 功能特性

- 💬 实时聊天界面
- 🌓 深色/浅色主题切换
- ⚙️ 可配置的 AI 设置
- 📱 响应式设计
- 🎨 现代化 UI 设计
- 🧹 清除聊天记录功能

## 技术栈

- **前端框架**: React 18
- **类型系统**: TypeScript
- **样式**: Tailwind CSS
- **图标**: Lucide React
- **构建工具**: Create React App

## 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm start
```

访问 [http://localhost:3000](http://localhost:3000) 查看应用。

### 构建生产版本

```bash
npm run build
```

## 项目结构

```
ai-chat-tool/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── App.tsx        # 主应用组件
│   ├── App.css        # 应用样式
│   ├── index.tsx      # 应用入口
│   └── index.css      # 全局样式
├── package.json
└── README.md
```

## 使用说明

1. **发送消息**: 在输入框中输入消息，按 Enter 或点击发送按钮
2. **主题切换**: 点击右上角的月亮/太阳图标切换深色/浅色主题
3. **设置**: 点击设置图标配置 API 密钥和模型参数
4. **清除聊天**: 点击垃圾桶图标清除所有聊天记录

## 配置 AI API

在设置面板中，你可以配置：

- **API 密钥**: 你的 AI 服务提供商的 API 密钥
- **模型选择**: 选择不同的 AI 模型（GPT-3.5, GPT-4, Claude 3）
- **温度参数**: 控制回复的创造性
- **最大 Token 数**: 控制回复的长度

## 部署

### 部署到 GitHub Pages

1. 安装 gh-pages:
```bash
npm install --save-dev gh-pages
```

2. 在 package.json 中添加 homepage 字段:
```json
"homepage": "https://yourusername.github.io/ai-chat-tool"
```

3. 部署:
```bash
npm run deploy
```

### 部署到 Vercel

1. 连接你的 GitHub 仓库到 Vercel
2. 设置构建命令为 `npm run build`
3. 设置输出目录为 `build`
4. 点击部署

## 开发

### 添加新功能

1. 克隆仓库
2. 创建新分支: `git checkout -b feature/your-feature`
3. 提交更改: `git commit -am 'Add some feature'`
4. 推送分支: `git push origin feature/your-feature`
5. 创建 Pull Request

### 自定义样式

项目使用 Tailwind CSS 进行样式设计。你可以在 `src/App.tsx` 中修改组件的样式类名。

## 贡献

欢迎提交 Pull Request 和 Issue！

## 许可证

MIT License

## 联系方式

如有问题或建议，请创建 Issue 或联系项目维护者。
