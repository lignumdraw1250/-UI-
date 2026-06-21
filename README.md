# SOLACEON — Archive of a Soul · 灵魂档案馆

> *"Every frame holds a truth the eye cannot hold still."*

个人作品集网站，以**重返未来：1999**美学为灵感，融合英伦电影风格与时间氛围系统。

## ✨ 特性

- 🎨 **重返未来：1999 配色** — 午夜海军蓝 × 古董金 × 星穹紫 × 岁月青
- 🌅 **时间氛围系统** — 根据当地时间自动切换 清晨/正午/晚霞/黑夜 四套动态模糊背景
- 🎬 **电影感视觉** — 胶片颗粒、动态粒子、暗角、投影光束、液态玻璃卡片
- 🇬🇧 **英伦风格** — IM Fell English + Playfair Display 衬线字体，Art Deco 装饰元素
- 🖱️ **自定义游标** — 发光星辰游标 + 鼠标环境光追踪
- 📜 **全屏叙事翻页** — 5屏全页滚动 + MG换帧动画 + 3D视差卡片
- 🎯 **详情Overlay** — 学科/作品详情弹层，顶部进度线动画 + 交错内容浮现
- 📱 **响应式适配** — 桌面/平板/移动端自适应

## 🚀 部署

### GitHub Pages (推荐)

1. Fork 或 Push 本仓库到 GitHub
2. 进入仓库 **Settings → Pages**
3. Source 选择 `main` 分支，根目录 `/ (root)`
4. 保存，等待部署完成
5. 访问 `https://<你的用户名>.github.io/<仓库名>/`

### 自定义域名

1. 在项目根目录添加 `CNAME` 文件（内容为你的域名）
2. DNS 添加 CNAME 记录指向 `<用户名>.github.io`
3. Settings → Pages → Custom domain 填入域名

### 本地预览

```bash
# 任意静态服务器均可
npx serve .
# 或
python -m http.server 8080
```

## 📁 项目结构

```
.
├── index.html    # 主页面（CSS + JS 内嵌）
├── README.md     # 项目说明
└── .gitignore    # Git 忽略规则
```

## 🎨 设计参考

- **重返未来：1999** (Reverse: 1999) — 配色灵感
- **Awwwards SOTD** — 交互模式
- **Apple/Stripe** — 卡片展开动画
- **英伦博物馆美学** — 排版与装饰

## 🛠️ 技术栈

- 纯 HTML/CSS/JS，零框架依赖
- CSS 自定义属性 (Design Tokens)
- Canvas 2D (胶片颗粒 + 粒子系统)
- Backdrop Filter (液态玻璃效果)
- CSS 3D Transform (视差倾斜)

## 📷 个性化

将 `index.html` 中以 `https://images.unsplash.com/` 开头的图片链接替换为你自己的图片。搜索注释 `📷` 可快速定位所有图片位置。

## 📝 License

MIT © 2025 Solaceon
