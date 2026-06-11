# 🌈 舒翔的数学游戏 · Shoofly's Math Games

> 数形结合 · 动手探索 · 轻松理解数学原理
>
> Visual Learning · Hands-on Exploration · Easy Understanding

---

## 这是什么？

一套面向小学高年级学生的**交互式数学可视化课件**，专为发育迟缓、缺乏空间想象力的儿童设计。

每个课件将抽象的数学知识转化为**看得见、摸得着**的视觉呈现，孩子可以动手调节参数，观察图形实时变化，然后挑战由易到难的选择题。

## What is this?

A collection of **interactive math visualizations** for upper elementary students, designed especially for children with developmental delays who struggle with abstract math concepts.

Each module turns abstract math into **visual, hands-on** experiences — tweak a slider, see the result change instantly, then test your understanding with progressive quiz questions.

---

## 🚀 快速开始

**无需安装任何软件**。下载项目后，双击 `index.html` 即可在浏览器中打开目录页，点击课件卡片进入学习。

```
MathGamesForKids/
├── index.html          ← 总目录（点这里开始！）
├── 比例尺/             ← ✅ 比例尺课件
│   └── index.html
├── 分数的认识/          ← 🔜 开发中...
├── ...                 ← 更多课件陆续上线
└── DESIGN.md           ← 开发者设计文档
```

> 💡 在手机、平板、电脑上都能使用 — 界面会自动适配屏幕大小。

## Quick Start

**No installation required.** Just open `index.html` in any modern browser and start exploring.

> 💡 Works on desktop, tablet, and mobile — the interface adapts automatically.

---

## 🎯 已完成的课件

| # | 课件 | 描述 | 难度 |
|---|------|------|------|
| 1 | 🗺️ **比例尺 / Map Scale** | 理解如何将现实世界按比例缩小画到图纸上，必须同时考虑长和宽！ | ⭐⭐⭐ |

## 📋 规划中的课件 (12课)

| # | 课件 | 核心难点 | 难度 |
|---|------|---------|------|
| 2 | 🍕 分数的认识 | 部分与整体的抽象关系 | ⭐⭐ |
| 3 | 🔢 分数运算 | 通分、约分的可视化 | ⭐⭐⭐ |
| 4 | ⭕ 圆与周长面积 | π 的抽象概念 | ⭐⭐⭐ |
| 5 | 📦 面积与体积 | 二维到三维的跨越 | ⭐⭐⭐ |
| 6 | 📐 角度的认识 | 角度大小的直观感知 | ⭐⭐ |
| 7 | 💯 百分数 | 百分比与实际量的对应 | ⭐⭐ |
| 8 | 🌡️ 负数 | 数轴向负方向延伸 | ⭐⭐ |
| 9 | 🎲 立体图形与展开图 | 3D 空间想象力 | ⭐⭐⭐⭐ |
| 10 | ⚖️ 方程入门 | 用字母表示未知数 | ⭐⭐⭐ |
| 11 | 📏 单位换算 | 进率关系易混淆 | ⭐⭐ |
| 12 | 🚗 速度·时间·距离 | 三个变量的关系 | ⭐⭐⭐⭐ |

---

## 🔧 技术栈

- **纯 HTML + CSS + JavaScript** — 零依赖，无需 node、npm 或任何框架
- **Canvas 2D API** — 高性能矢量图形渲染
- **ResizeObserver** — 画布自动适配手机/平板/桌面
- **localStorage** — 语言偏好跨页面保持

详见 [`DESIGN.md`](DESIGN.md) 了解完整架构设计、开发规范和课件策划。

---

## 🌐 中英双语

所有课件支持中文/英文一键切换，语言选择自动记忆。切换方式：
- 目录页和课件页右上角的 `中文` / `English` 按钮
- 通过 URL 参数指定：`?lang=zh` 或 `?lang=en`

---

## 👨‍👩‍👧 适用对象

- 小学四至六年级学生（约 10–13 岁）
- 对数学抽象概念理解困难的儿童
- 需要视觉化辅助教学的特殊教育场景
- 任何想通过互动方式理解数学基础的人

---

## 📄 许可

本项目为个人家庭教育用途。详见 [LICENSE](LICENSE)（如有）。

---

> 🌈 让每个孩子都能看见数学之美 · Every child can see the beauty of math
