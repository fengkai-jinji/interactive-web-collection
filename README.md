<div align="center">

# ✨ Interactive Web Collection · 交互网页作品集

**四个单文件 HTML 交互特效页 · 浏览器打开即玩 · 无需构建**

`Three.js` · `MediaPipe Hands` · `Canvas Particles` · `Single-file HTML`

</div>

---

## 🌐 在线预览

> 启用 GitHub Pages 后，这里就是作品集主页：**https://fengkai-jinji.github.io/interactive-web-collection/**
> 主页是一个画廊页，点卡片即可进入每个作品。

## 📂 作品列表

| 作品 | 文件 | 简介 |
| --- | --- | --- |
| 🖐️ **3D 粒子手势交互系统** | [`pages/particle-gesture-3d.html`](./pages/particle-gesture-3d.html) | MediaPipe 手势识别 + Three.js 粒子，手势控制星尘聚散，带交互状态监控面板 |
| 🎄 **Grand Luxury Tree** | [`pages/grand-luxury-tree.html`](./pages/grand-luxury-tree.html) | 华丽圣诞树粒子特效，支持上传照片、背景音乐与字幕，开场视频位预留 |
| ❄️ **Lina // THE WORLD IS GENTLE** | [`pages/lina-winter-gentle.html`](./pages/lina-winter-gentle.html) | 冬日温柔版互动页：飘雪、星光与一句句暖心小字 |
| 🌸 **Sakura & Erii // THE WORLD IS GENTLE** | [`pages/sakura-erii-gentle.html`](./pages/sakura-erii-gentle.html) | 绘梨衣主题版：小怪兽与 Sakura 的天空树之约 |

## 🚀 怎么运行

1. **在线**：打开上方的 GitHub Pages 链接（推荐）。
2. **本地**：把任意 `.html` 文件下载下来，用浏览器直接打开即可。
   - 手势交互系统需要**摄像头权限**，请在 `https` 或本地文件环境下允许授权。
   - 页面会从 CDN 加载 Three.js / MediaPipe / 字体，运行时请保持联网。

## 🛠️ 技术说明

- 全部作品均为 **单文件 HTML**（样式与脚本内嵌），无构建步骤、无后端依赖。
- `index.html` 是作品集主页（画廊），各作品放在 `pages/` 目录下，互不影响、可单独打开。
- 圣诞树页的开场视频不绑定任何固定文件：点页面上的 **Add Video** 按钮，可选择任意本地视频作为开场视频播放（视频只在本地浏览器里播放，不会上传到任何服务器），不选则直接欣赏圣诞树主体特效。

## 📌 备注

- Lina 版与绘梨衣版共用同一套交互框架，是两个不同主题的版本（文案与氛围不同），因此并列保留。
- 欢迎 ⭐ Star，玩得开心。

<div align="center">

*THE WORLD IS GENTLE — 世界很温柔，你也是。*

</div>
