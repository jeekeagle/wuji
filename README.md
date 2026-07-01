# 无记

> 记录，而获得自己。

导航页 · landing page for [jeekeagle](https://github.com/jeekeagle) 的所有子站。

## 子站

- [openwalk.top](https://openwalk.top) — 随笔

## 部署

仓库：`jeekeagle/wuji`
访问：<https://jeekeagle.github.io/wuji>

GitHub Pages 设置：
1. Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` / `/ (root)`
4. Save

## 本地预览

```bash
# 任选其一
python3 -m http.server 8000
# 或
npx serve .
```

## 新增子站

编辑 `index.html`，在 `<nav class="links">` 内增加 `<a>` 即可。

```html
<a href="https://example.com" target="_blank" rel="noopener">
  <span class="label">板块名</span>
  <span class="arrow" aria-hidden="true">→</span>
</a>
```

## 设计

- 背景：`#f7f5f0`（米白）
- 主文：`#1a1a1a`（墨黑）
- 强调：`#8b1a1a`（朱砂，用于"记"字）
- 字体：Noto Serif SC + Cormorant Garamond
