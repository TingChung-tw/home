# Ting Chung — GitHub Pages + Jekyll Starter

## 上線（5 步）
1) 建立 repo：`USERNAME.github.io`（把 USERNAME 換成你的 GitHub 帳號）。
2) 下載本 ZIP、解壓縮，把**全部檔案**上傳到該 repo。
3) 到 Settings → Pages → Build and deployment → Source 選 **GitHub Actions**。
4) 等 1–2 分鐘，開 `https://USERNAME.github.io` 看網站。
5) 改 `_config.yml` 的 `url`（把 USERNAME 換成你的帳號）→ commit 即可。

## 發新文章（站內長文）
```
---
layout: single
title: "文章標題"
date: 2025-08-11
categories: [defense-technology]
tags: [tag1, tag2]
---
你的內容（Markdown）
```

## 外部連結文（LinkedIn / Island Insight）
```
---
layout: single
title: "外部文章標題"
date: 2025-08-11
link: "https://外部連結"
categories: [economy-industry-policy]
tags: [LinkedIn]
---
一句摘要（可選）
```

## 連結牆（/links）
在 `_links/` 新增 `.md`：
```
---
title: "連結標題"
url: "https://外部連結"
topic: "Defense & Technology"
---
一句話說明。
```

## 分類 slug（請用以下四個）
- defense-technology
- institutions-politics
- economy-industry-policy
- commentary-perspectives
