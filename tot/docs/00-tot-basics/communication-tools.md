---
sidebar_position: 2
title: コミュニケーションとツール
description: 連絡はメイン＝Discord、サブ＝LINE。外部連絡はメール。導入ツール（Zoom/Drive/GitHub/WordPress/Bitwarden）に加え、誌面制作は Adobe Illustrator と Photoshop を使用する方針を明記。
slug: /tot-basics/tools
sidebar_label: コミュニケーションとツール
tags: [基本情報, ツール, Discord, LINE, Illustrator, Photoshop, 連絡]
keywords:
  - サークル 連絡 ルール
  - Discord 使い分け
  - 学生団体 ツール
  - Illustrator Photoshop 初心者
  - 芝浦工業大学 tot
  - 新入生向けガイド
---

# コミュニケーションとツール

> **TL;DR**  
> - 公式連絡・議論・アーカイブ＝**Discord（メイン）**  
> - 速報／小規模連絡＝**LINEグループ（サブ）**  
> - 学外向け／正式な依頼＝**メール（info@tot-ch.com）**  
> - 会議＝**Zoom**、共有＝**Google Drive**、Wiki＝**Docusaurus**  
> - **誌面制作は Adobe Illustrator（レイアウト）＋ Photoshop（画像加工）** を使用

---

## 1. 使い分けポリシー

| 種別 | 使う場所 | 用途 | 備考 |
|---|---|---|---|
| 日常の連絡・議論 | **Discord** | 企画相談／進捗共有／定例会の案内とログ | 公式アーカイブ。スレッド活用・検索可能 |
| 速報・少人数連絡 | **LINEグループ** | 当日集合／遅刻・欠席連絡／緊急連絡 | 補助的運用。決定事項はDiscordへ要約転載 |
| 学外とのやり取り | **メール** | 取材依頼・大学窓口・企業対応 | 署名・文面テンプレを使用 |
| オンライン会議 | **Zoom** | 週次の[オンライン定例会](/docs/tot-basics/online-regular-meeting) 等 | 招待URLはDiscordに掲示 |
| ドキュメント共有 | **Google Drive** | 企画書・画像・会計PDF | フォルダ規約に従って命名 |
| 原稿／Wiki | **GitHub / Docusaurus** | 記事原稿・手順書・ハンドブック | 公開可能な知見はここへ |
| 内部メモ | **Growi（試験運用）** | 非公開の下書き | 最終判断は翌3月に実施 |
| パスワード | **Bitwarden** | アカウント・秘密情報の管理 | [パスワード管理ポリシー](/docs/governance/security/passwords) |

> 個人情報・パスワード・口座番号などは**公開Wikiに書かない**（[個人情報と公開範囲]。

---

## 2. Discord の使い方（最短）

1. 招待リンクから参加 → ニックネームを「学年-氏名」に変更（例：B1-山田）。  
2. ルールにリアクション → ロール付与。  
3. 通知は **「@mentionsのみ」** に設定（おすすめ）。  
4. 投稿は**スレッド**を使い、タイトルに用件（例：`[白熱教室] 取材候補の相談`）。  
5. 決定事項は**最初のメッセージを編集して要約**（ピン留め）。

**チャンネル例**
- `#定例会`（Zoom URL／議事メモ）  
- `#進捗共有`（今日やる／やった）  
- `#取材` `#編集` `#校閲` など制作別  
- `#obog-contact`（OB・OG交流。通知は控えめ）

> 卒業時は**キックせず**「OB・OGロール」へ。詳しくは[OB・OG](/docs/club-obog)。

---

## 3. LINE グループ（サブ運用）

- 当日連絡・緊急時の**通話**に便利。  
- ただし**意思決定や議事**は残らない → **Discordへ要約転載**がルール。  
- 交代時は管理者を更新し、古い招待リンクは失効。

---

## 4. 外部とのやり取り（メール）

- アドレス：**info@tot-ch.com**（代表または広報が送信）  
- 依頼や回答は**テンプレ**から：  
  - 取材依頼 → [アポ取りメールのテンプレ](/docs/production/interview-mail-template)  
  - 大学・銀行向け → [団体規約](/docs/governance/constitution)

---

## 5. アクセス申請フロー

- **新入部員**：Discord参加 → オンボーディングフォーム → Drive/GitHub権限付与  
- **役職就任**（会計・Webなど）：Bitwardenボルト昇格＋2FA確認  
- **退会/役職交代**：権限剥奪 → **パスワード即日ローテ**  
  - 詳細：[権限の付与・剥奪](/docs/governance/security/access-lifecycle)

---

## 6. 制作ツール（誌面づくり）

> tot の誌面制作は **Adobe Illustrator（＝いられ）** と **Adobe Photoshop（＝フォトショ）** が基本です。

**役割分担の目安**
- **Illustrator**：ページレイアウト／文字組／トンボ・塗り足し設定／入稿用PDF書き出し  
- **Photoshop**：写真のRAW現像・色調補正・切り抜き・リサイズ（画像は**リンク配置**）

**最低限の初期設定（覚えておけばOK）**
- ドキュメント：仕上がりサイズ（例：A5/A4）、**塗り足し3mm**、**CMYK**（印刷用）  
- フォント：配布可のフォントを使用（Adobe Fonts 推奨）。**勝手に増やさない**  
- 画像：**解像度 300dpi** 以上、リンクは `images/` フォルダに整理  
- 書き出し：プリセット「**PDF/X-1a** or 印刷所推奨設定」、**オーバープリント**誤設定に注意

**データ運用**
- 保存場所：`Google Drive > 制作 > 20XX_○号 > ai/ psd/ images/ pdf/`  
- 命名規則：`p01_cover.ai` / `p12_feature1.ai` / `img_2025-05-10_撮影者名.jpg`  
- 共有：入稿直前は **「パッケージ」** でフォント/リンクを束ねて提出  
- 学内共有版は PDF の**軽量書き出し**も用意すると便利


---

## 7. 導入ツール一覧（2025）

| 区分 | ツール | 主な用途 | 管理 |
|---|---|---|---|
| コミュニケーション | Discord / LINE | 連絡・議論／緊急連絡 | 代表・運用 |
| 会議 | Zoom | 定例会・取材オンライン | 代表 |
| 共同編集 | Google Drive | 企画書・画像・会計PDF | 各担当 |
| 原稿/サイト | GitHub / Docusaurus / WordPress | ハンドブック／Web編集版 | Web担当 |
| **デザイン** | **Adobe Illustrator / Photoshop** | 誌面レイアウト・画像加工 | 編集担当 |
| パスワード | Bitwarden | 秘密情報の保管・共有 | 代表＋会計 |
| 内部メモ | Growi（試用） | 非公開の下書き | 運用 |

> 追加・廃止は「運営会議」で決定し、ここを更新すること。

---

## 8. マナーと小技

- 質問は**結論先出し**＋**補足**（読み手の時間を節約）  
- スクショは**1枚＝1論点**、後から見つけやすいタイトルを付ける  
- 迷ったら**Discordメイン**に投げる → 価値があると判断したらWikiへ要約転載

---

## 9. よくある質問

**Q. いられとフォトショ、どちらから触ればいい？**  
A. まずは**Photoshopで写真を整える→Illustratorでレイアウト**の順が基本。テンプレを配布します。

**Q. 家のPCにAdobeがない**  
A. 大学アカウントの利用可否を確認。不可なら部内の共有PCや体験版期間を活用し、最終書き出しだけ担当者に依頼でも可。

**Q. Web用の画像は？**  
A. sRGBで書き出し、長辺 1600px 目安。誌面用PSDはそのまま流用せず、**別書き出し**に。

---

### 関連ページ
- [オンライン定例会](/docs/tot-basics/online-regular-meeting)  
- [対面会](/docs/tot-basics/face-to-face-meeting)  
- [Wikiの運用方針](/docs/wiki)  
- [パスワード管理ポリシー](/docs/governance/security/passwords)
