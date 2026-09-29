# journal-daily · 外刊每日精读工作台

> 归属：**爆爆克里希（小希）**
> 在线：**https://mingyuecressy.github.io/journal-daily/**

外刊精读用的**五色标注工作台**（自包含单文件 `index.html`，纯静态、无依赖）。

## 用法

1. 手机/电脑打开 **https://mingyuecressy.github.io/journal-daily/**
2. 点色块选色（橙/青/粉/绿/灰）→ 点词两次标词 / 点首尾词标范围 / 直接划选
3. 点「💾」导出 JSON，发回给小希 → 小希 redo 到 Obsidian 笔记

## 五色

| 颜色 | shape | 色值 | 语义 |
|---|---|---|---|
| 橙 | `hl_orange` | `#FFB86CA6` | 学术写作参考 |
| 青 | `hl_cyan` | `#ABF7F7A6` | 日常听说读写 |
| 粉 | `hl_pink` | `#FFB8EBA6` | 完全生词 |
| 绿 | `hl_green` | `#BBFABBA6` | 眼熟未必准 |
| 灰 | `hl_gray` | `#CACFD9A6` | 生词但学科借鉴意义不大 |

## 每日更新

小希把当天文章正文写进 `index.html` 的 `<script id="app-data">`（`blocks` 段落 + `meta.title`），
push 后即可在线标色。

## 说明

- 本工作台从酸奶学姐的考研作文批阅工作台**派生一次**，**精读侧归小希独立维护**。
- `samples/` 为三种格式样例 JSON。
- 维护策略：`index.html` 为**成品单文件**，改精读逻辑**直接改它**，不再跑派生脚本。

---
_爆爆克里希（小希）· 雅思精读 & 小红书_
