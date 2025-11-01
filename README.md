# 🛍️ 优购臻选 · 现代化电商网页

> 一个由 **HTML + TailwindCSS + Font Awesome + JavaScript** 构建的响应式购物商城网页，展示了完整的电商首页布局与交互特效。

---

## 🌐 在线预览

> 🚀 [点击查看演示页面（建议部署到 GitHub Pages）](https://your-github-username.github.io/yougou-mall)

---

## 📸 页面展示

| 首页展示 | 商品分类 | 热销商品 |
|-----------|-----------|-----------|
| ![首页预览](https://picsum.photos/400/250?random=1) | ![分类菜单](https://picsum.photos/400/250?random=2) | ![商品展示](https://picsum.photos/400/250?random=3) |

---

## ✨ 功能亮点

- 🧭 **响应式布局**：适配 PC、平板、移动端，体验流畅。  
- 🌗 **暗色模式切换**：一键切换暗色 / 亮色主题。  
- 🔍 **搜索框与热词滚动**：支持动态搜索提示动画。  
- 🛒 **购物车与分类导航**：带下拉动画与交互反馈。  
- 💡 **TailwindCSS 动画增强**：使用自定义动画（如淡入、滑入、弹跳、滚动等）。  
- 📦 **组件化结构**：可扩展的商品分类与推荐模块。  
- 🎨 **美观 UI**：灵感源于京东/天猫风格，采用圆角卡片与渐变背景。  

---

## 🧰 技术栈

| 前端技术 | 说明 |
|-----------|------|
| **HTML5** | 语义化结构，SEO 优化 |
| **Tailwind CSS 3.x** | 原子化样式 + 自定义主题色 |
| **Font Awesome 6.x** | 图标系统支持 |
| **JavaScript (Vanilla)** | 动画与交互逻辑 |
| **CSS 动画 + 过渡效果** | 自定义 hover / scroll / fadeIn 动效 |

---

## 📁 项目结构

```
yougou-mall/
│
├── index.html                 # 主页面
├── css/
│   ├── index.css
│   ├── 商城弹窗.css
│   ├── 购物车弹窗.css
│   ├── 搜索框热词切换.css
│   ├── 左侧滚轴广告.css
│   └── dark-mode.css
│
├── assets/
│   └── font-awesome/          # 图标字体库
│
├── images/                    # 页面图片素材
│   ├── iPhone.jpg
│   ├── huawei.jpg
│   ├── jd.gif
│   └── ...
│
└── js/
    └── main.js                # 可自定义交互脚本（如轮播图逻辑）
```

---

## 🚀 本地运行

```bash
# 克隆项目
git clone https://github.com/your-github-username/yougou-mall.git

# 进入项目目录
cd yougou-mall

# 使用 VSCode 或任意编辑器打开，然后用 Live Server 运行
```

或者直接双击 `index.html` 用浏览器打开即可。

---

## 🧩 功能模块说明

| 模块 | 描述 |
|------|------|
| 顶部导航栏 | 包含搜索框、购物车、用户中心等功能入口 |
| 分类侧边栏 | 多层级商品分类，支持鼠标悬停展示子分类 |
| 商品展示区 | 热销、新品、限时秒杀等多个板块 |
| 推荐区域 | “为你推荐”、“进口好物”等个性化推荐内容 |
| 动态特效 | 滚动热词、轮播图、限时秒杀倒计时等 |

---

## 🎨 自定义主题

`index.html` 中通过 Tailwind 的配置块可修改主题色：

```js
colors: {
  primary: '#E1251B', // 主色（红）
  secondary: '#165DFF', // 辅色（蓝）
  dark: '#333333',
  light: '#F5F5F5',
}
```

可替换为品牌色或你自己的配色方案。

---

## 📄 作者信息

- **作者**：monster（`zou0113`）
- **项目名称**：优购臻选购物商城
- **版本**：v1.0
- **许可证**：MIT License
- **关键词**：电商、购物网站、Tailwind、商城模板、HTML5

---

## 💡 部署到 GitHub Pages

1. 提交项目到 GitHub 仓库  
2. 打开仓库 → Settings → Pages  
3. Branch 选择 `main` + `/ (root)`  
4. 保存后即可通过链接访问网站  

---

## 🏷️ 鸣谢

感谢以下技术与素材支持：

- [Tailwind CSS](https://tailwindcss.com/)  
- [Font Awesome](https://fontawesome.com/)  
- [Picsum Photos](https://picsum.photos/)（图片占位符）  

---

> 🧠 如果你想扩展该项目，可将其改造成 **Vue 3 + Vite 前端商城系统** 或 **SpringBoot 后端接口电商项目**。
