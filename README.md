# 饭米粒米饭王国

> 饭米粒米饭王国餐厅官方网站，展示菜单、优惠活动与联系方式，移动端优先设计。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-valid-orange.svg)](https://developer.mozilla.org/zh-CN/docs/Glossary/HTML5)
[![Mobile First](https://img.shields.io/badge/Design-Mobile%20First-green.svg)](https://developer.mozilla.org/zh-CN/docs/Web/Progressive_web_apps/Responsive/Mobile_first)

---

## 项目简介

饭米粒米饭王国是一个餐厅官方网站，采用移动端优先的响应式设计，展示餐厅的招牌菜品、优惠活动，并提供一键拨打和导航功能。网站以暖色调（橙色 `#ff6b35`）为主，营造温馨食欲感。

### 核心特性

- **移动端优先设计** — 针对手机浏览优化，适配平板和桌面
- **开场品牌动画** — 精致的 Logo 缩放 + 品牌名渐入动画
- **轮播 Banner** — 自动轮播展示推广内容
- **菜品展示** — 分类展示米饭类和小吃类菜品，含图片、描述、价格
- **一键拨打电话** — 点击电话号码直接拨号
- **一键导航** — 集成高德地图导航
- **美团点餐入口** — 悬浮按钮直达美团外卖
- **波浪分隔线** — SVG 波浪动画分隔不同区域

---

## 技术栈

| 层级 | 技术 |
|------|------|
| 页面结构 | HTML5 |
| 样式 | CSS3（动画、Grid 布局、响应式） |
| 交互 | 原生 JavaScript |
| 部署 | GitHub Pages |

---

## 项目结构

```
Rice-Restaurant/
├── index.html              # 主页面（单文件应用）
├── picture/                # 菜品图片资源
│   ├── logo.jpg            # 餐厅 Logo
│   ├── 招牌咖喱鸡排蛋包饭23.9.jpg
│   ├── 咖喱鸡排蛋包饭23.9.jpg
│   ├── 卤肉饭25.jpg
│   ├── 鸡腿饭25.jpg
│   ├── 香香元宝鸡6.jpg
│   ├── 鸡腿6.jpg
│   ├── 香煎荷包蛋6.jpg
│   └── 脆香薯球8.8.jpg
├── .github/workflows/
│   └── deploy.yml          # GitHub Pages 自动部署
└── .gitignore
```

---

## 菜单内容

### 米饭类

| 菜品 | 价格 | 描述 |
|------|------|------|
| 招牌咖喱鸡排蛋包饭 | ¥23.9 | 秘制咖喱酱搭配金黄鸡排 |
| 咖喱鸡排蛋包饭 | ¥23.9 | 浓郁咖喱香配嫩滑鸡排 |
| 卤肉饭 | ¥25 | 秘制卤汁炖煮五花肉 |
| 鸡腿饭 | ¥25 | 大鸡腿配香米饭 |

### 小吃类

| 菜品 | 价格 | 描述 |
|------|------|------|
| 香香元宝鸡 | ¥6 | 外酥里嫩形似元宝 |
| 鸡腿 | ¥6 | 大鸡腿香嫩多汁 |
| 香煎荷包蛋 | ¥6 | 煎至金黄酥脆边缘 |
| 脆香薯球 | ¥8.8 | 薯泥炸至金黄酥脆 |

---

## 视觉设计

### 配色方案

| 用途 | 色值 |
|------|------|
| 主色调（橙色） | `#ff6b35` |
| 辅助色（浅橙） | `#f7c59f` |
| 背景色（暖白） | `#fff8f0` |
| 强调色（金黄） | `#ffeaa7` |
| 文字色（深棕） | `#8b5a2b` |

### 字体

`"PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Noto Sans SC", sans-serif`

---

## 联系信息

- **电话**：182-0920-3884
- **地址**：阎良区南孙路洛阳坊快递驿站旁
- **营业时间**：10:00 — 22:00（全年无休）
- **外卖**：美团点餐

---

## 快速开始

```bash
# 本地预览
python -m http.server 8000
# 访问 http://localhost:8000
```

部署方式：推送到 GitHub 后，GitHub Actions 会自动部署到 GitHub Pages。

---

## 许可证

本项目基于 MIT 协议开源 — 详见 [LICENSE](LICENSE) 文件。

---

**餐厅**：饭米粒米饭王国 | **口号**：粒粒饱满，口口香浓 | **协议**：MIT
