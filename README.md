# 🍌 Banana AI - 智能图像生成工具

一款基于 **Nano Banana Pro (Gemini 3 Pro)** 模型的现代化 AI 图像生成应用，专为极致视觉体验而设计。

## ✨ 核心特性

- **文生图 (Text-to-Image)**: 支持 1K/2K/4K 超高清分辨率及多种宽高比适配。
- **图生图 & 融合 (Image-to-Image / Multi-Fusion)**: 
  - 支持上传 1-10 张参考图进行智能融合。
  - **自研上传链路**: 集成前端直连图床技术，确保在各种网络环境下稳定生成。
- **再次修改 (Iterative Refinement)**: 支持对生成的图像进行连续对话式修改。
- **极致美学**: 采用磨砂玻璃拟态 (Glassmorphism) 暗黑风格界面，流畅的微动画交互。

## 🚀 快速启动

### 方法 1：一键启动 (推荐)
直接双击项目目录下的 **`启动应用.bat`** 文件即可自动打开浏览器并启动服务。

### 方法 2：开发者启动
如果你具备 Node.js 环境，可以使用以下命令：
```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev
```

## 🛠️ 技术配置

本项目已预配置好所有生产环境参数：
- **模型端点**: GRSAI Nano Banana Pro 接口
- **核心逻辑**: `src/api/laozhangApi.js` (处理图片压缩、图床上传及 API 调用)
- **图床服务**: ImgBB (通过前端直连模式绕过跨域与后端限制)

## 📄 项目文档

若需深入了解 API 调用细节，请参阅：
- [GRSAI_AI图像生成_API调用说明.md](./GRSAI_AI图像生成_API调用说明.md)
- [ImgBB_API使用说明.md](./ImgBB_API使用说明.md)

---

*Powered by Nano Banana Pro & GRSAI API*
