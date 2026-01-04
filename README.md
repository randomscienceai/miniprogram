# AI 画廊 (AI Gallery) 小程序

这是一个基于微信小程序和微信云开发的 AI 绘画分享社区。用户可以通过文字描述生成 AI 画作，并将其分享到公共画廊中。

## 主要功能

- **首页 (Gallery)**: 浏览所有人分享的 AI 画作，支持无限滚动加载。
- **创作 (Create)**: 输入提示词（Prompt），由 AI 生成图片。支持一键发布到画廊。
- **我的 (Profile)**: 微信一键登录，管理个人创作的画廊。
- **原型预览**: 在 `miniprogram/prototype/` 目录下提供了完整的 HTML 原型，模拟了移动端的使用体验。

## 技术栈

- **前端**: 微信小程序原生框架
- **UI 组件库**: TDesign Weixin
- **后端**: 微信云开发 (Cloud Development)
- **AI 能力**: 集成第三方 AI 绘画 API (如 DALL-E, Stable Diffusion 等)

## 快速开始

1. 使用微信开发者工具打开项目。
2. 修改 `project.config.json` 中的 `appid` 为你自己的 AppID。
3. 开通云开发环境，并在 `app.ts` 中初始化你的环境 ID。
4. 创建必要的数据库集合（如 `artworks`, `users`）。

## 原型演示

你可以直接在浏览器中打开 `miniprogram/prototype/index.html` 来快速预览小程序的设计原型和交互逻辑。

