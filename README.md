# 液态玻璃组件 (Liquid Glass Components)

一款轻量级的现代前端库，用于创建**液态玻璃 (Liquid Glass)** UI 效果。设计理念：**现代、简洁、开源**。

由 [LGOS Studio](https://github.com/LGOS-Studio) 制作。

---

## ✨ 特性

- 🧊 **液态玻璃效果** — 通过 CSS 变量驱动，开箱即用
- 🪶 **轻量无依赖** — 纯 CSS，无需 JavaScript 框架
- 🎨 **高度可定制** — 通过 `--liquid-bg`、`--liquid-radius` 等 CSS 变量调整外观
- 📱 **响应式设计** — 适配桌面与移动端
- ♿ **无障碍支持** — 支持 `prefers-reduced-motion`，键盘可操作
- 🔀 **拖拽对比** — 内置可拖拽的左右对比视图

---

## 🚀 快速开始

### 引入方式

将 `liquid-glass.css` 引入你的项目，然后给任意 DOM 元素添加 `class="liquid"` 即可：

```html
<link rel="stylesheet" href="./liquid-glass.css" />

<div class="liquid">我的液态玻璃元素</div>
```

### 支持的标签类型

| 标签 | 类名示例 | 说明 |
|------|---------|------|
| `div` | `class="liquid"` | 块级元素，随处可用 |
| `button` | `class="liquid sample-button"` | 轻薄、圆润、易读 |
| `a` | `class="liquid sample-link"` | 柔和的玻璃风格链接 |
| `input` | `class="liquid sample-input"` | 适合搜索框或表单 |
| `article` / `section` | `class="liquid example-card"` | 内容卡片 |
| 自定义元素 | `class="liquid"` | 任意元素均可应用 |

---

## 🎛️ 自定义配置

通过覆盖以下 CSS 变量来定制外观：

| 变量 | 默认值 | 说明 |
|------|--------|------|
| `--liquid-bg` | `rgba(255, 255, 255, 0.22)` | 玻璃背景颜色与透明度 |
| `--liquid-radius` | `32px` | 圆角半径 |
| `backdrop-filter` | `blur(10px) saturate(150%)` | 背景模糊与饱和度 |

### 示例：自定义圆角与背景

```html
<div class="liquid" style="--liquid-radius: 8px; --liquid-bg: rgba(100, 200, 255, 0.3)">
  我是一张小圆角、蓝色调的玻璃卡片
</div>
```

---

## 📂 项目结构

```
.
├── index.html          # 演示页面（当前文件）
├── liquid-glass.css    # 液态玻璃核心样式
├── Harmony.jpg         # 背景图片
├── bookring/           # Bookring 导航图标
│   ├── previous.png
│   ├── book.png
│   └── next.png
└── README.md           # 本文件
```

---

## 🖱️ 交互说明

- **点击右上角对比按钮** → 打开拖拽对比弹窗，左侧为液态玻璃效果，右侧为原生样式
- **拖拽中间分隔条** → 实时对比两种样式的差异
- **键盘操作** → 聚焦分隔条后可使用 `←` / `→` 箭头键微调
- **按 Esc 键** → 关闭对比弹窗

---

## 📄 许可证

本作品由 LGOS Studio 制作，欢迎使用、修改并分享反馈。

联系邮箱：2920160872@qq.com

源代码请访问 GitHub 仓库：[LiquidGlass](https://github.com/LGOS-Studio/LiquidGlass)

---

## 🙏 致谢

- Bookring 网络环：[Bookring](https://bookring.net)
- 灵感与设计参考来自 [Liquid Glass](https://github.com/LGOS-Studio/LiquidGlass) 项目
