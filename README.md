# 无记

> 记录，而获得自己。

导航页 · landing page for [jeekeagle](https://github.com/jeekeagle) 的所有子站。

## 子站

- [wuji-blog](https://jeekeagle.github.io/wuji-blog/) — 随笔
- [zero-perspective-hub](https://jeekeagle.github.io/zero-perspective-hub/) — 视角
- [ZeroPark](https://jeekeagle.github.io/ZeroPark/) — 园

## 视觉

中央画框型：一张主图占视觉中心，外围留白，文字退到画面之外。
参考杉本博司 (Hiroshi Sugimoto) 网站的极简编辑型视觉。

主图：`show.jpg`（4032×3024，天空/云/草地/远树）。

字体：
- 英文：`Cormorant Garamond`（编辑型衬线）
- 中文：`Noto Serif SC`

主题：纸（默认，米白）/ 夜（深墨），选择写入 localStorage。

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
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 新增子站

编辑 `index.html`，在 `<nav class="corner-tr">` 内增加 `<a>` 即可。

```html
<a href="https://example.com" target="_blank" rel="noopener">板块名</a>
```

## 更换主图

替换 `show.jpg` 即可，建议横构图 4:3 或 3:2，文件保持同名。

## 设计

- 背景：`#f4f1ea`（米白纸感）
- 主文：`#1a1a1a`（墨黑）
- 强调：`#8b1a1a`（朱砂，用于"记"字）
- 字体：`Cormorant Garamond` + `Noto Serif SC`
- 布局：中央画框 + 四角定位 + 大量留白