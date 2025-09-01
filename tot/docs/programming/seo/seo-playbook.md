---
sidebar_position: 30
title: SEO運用プレイブック
description: totハンドブック（Docusaurus/WordPress）のSEO基本設計・記事作成チェックリスト・今後の改善計画をまとめた内部向けガイド
slug: /programming/seo
sidebar_label: SEOプレイブック
tags: [SEO, Docusaurus, WordPress, コンテンツ設計]
keywords:
  - Docusaurus SEO
  - 大学 サークル SEO
  - メタデータ 設計
  - サイト構造 設計
  - ハンドブック SEO
---

# SEO運用プレイブック（tot）

> **対象**：Docusaurus のハンドブック／WordPress「Web編集版」  
> **目的**：新入生にも伝わる**読みやすさ**と、検索に拾われる**技術的土台**を両立。  
> **現状**：基本のメタデータは整備済み。構造化データや運用チェックの自動化は**これから強化**。

---

## 1. まず大事な考え方（tot流）

1. **読者優先**：新入生・外部の学生が読んで役立つ内容を最優先。  
2. **情報の一貫性**：同じ内容は**1か所に正本**を置き、他はリンクで参照。  
3. **最小英字スラッグ**：URLは英小文字＋ハイフン（`/production/interview` など）で**壊れにくく**。  
4. **公開/非公開の切り分け**：名簿や個人情報は**非公開**（Governance）。公開は**要約のみ**。

---

## 2. 記事のフロントマター（テンプレ）

各記事は**タイトル／説明／slug／タグ／キーワード**を入れる。  
日本語SEOでは、**タイトル28–35字／説明80–120字**を目安に簡潔に。

```md
---
sidebar_position: 1
title: 〇〇のやり方（学内向け完全ガイド）
description: 新入生でも迷わない〇〇の基本手順。よくある失敗例とチェックリスト付き。
slug: /path/to/page
sidebar_label: 〇〇ガイド
tags: [サークル運営, 〇〇]
keywords: [芝浦工業大学, サークル, 〇〇, 手順, チェックリスト]
---
