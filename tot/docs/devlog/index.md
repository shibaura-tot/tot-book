---
title: 開発日記の使い方（運用ルールとテンプレ）
slug: /devlog/guide
sidebar_position: 0
---

# 開発日記の使い方

:::info 目的
単なる作業ログではなく、**意思決定の記録**を残す。  
「何をやったか」よりも「**なぜそうしたか／どんな代替案があり何を捨てたか**」を未来の自分と後輩に伝える。
:::

## 対象（何を書く？）

- コンテンツ構造変更（sidebar、slug、カテゴリ設計）
- ビルド/CI とデプロイの不具合・修正（Broken links、Duplicate routes 等）
- 執筆規約・SEO方針・アクセシビリティ方針の更新
- インフラ変更（Vercel/Cloudflare/DNS など）
- 大きめの編集ガイドラインの合意（見出しレベル、警告ブロックの使い方）

> 「1コミットでは伝わらない背景」をここで残す。

## ファイル命名と場所

- 置き場所: `docs/devlog/`
- ファイル名: `YYYY-MM-DD-topic.mdx`  
  例）`2025-09-06-routing-fix.mdx`
- タイムゾーンは JST（UTC+9）で統一

## フロントマター（雛形）

```md
---
title: "YYYY/MM/DD｜トピックの要約"
description: "変更点と採用理由を一行で"
tags: ["devlog","build"]   # 例: build, content, infra, seo, a11y, governance
draft: false               # 下書きは true
---
