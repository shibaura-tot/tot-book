# tot-book 📖

芝浦工業大学の学生団体「tot編集部」の知識やノウハウを集約するための公式ハンドブックです。このプロジェクトは [Docusaurus](https://docusaurus.io/) を使って構築されています。

## 🎯 このハンドブックの目的

- **知識の共有:** 部員が持つ専門知識、活動のノウハウ、TIPSなどを一箇所に集約し、誰でも閲覧できるようにします。
- **新入部員向け教育:** 新しく参加したメンバーが、団体の活動内容や必要なスキルを効率的に学べるための教材を提供します。
- **活動の透明化:** 私たちの活動内容や技術的な取り組みを外部に公開し、団体のプレゼンスを高めます。

## ✨ 主な特徴

- **Docusaurusベース:** モダンで高速なドキュメントサイトを簡単に構築できます。
- **全文検索:** [Algolia DocSearch](https://docsearch.algolia.com/) の導入により、膨大な情報の中からでも必要な情報を瞬時に見つけ出すことを目指します。
- **Markdown記述:** 誰でも簡単にページの作成や編集に参加できます。
- **オープンソース:** このハンドブックはオープンソースであり、誰でも改善提案が可能です。

## 🚀 開発環境のセットアップ

このハンドブックを自分のPCで動かして、編集に参加することができます。

**環境構築の詳しい手順や発生しうる問題については、[GitHub Wiki](https://github.com/shibaura-tot/tot-book/wiki)にまとめていますので、そちらを参考にしてください。**



### 1. 必要なツールのインストール

まず、開発に必要なツールをPCにインストールします。

- **VS Code:** コードエディタです。
    - [公式サイト](https://code.visualstudio.com/)からダウンロードしてインストールしてください。
- **Git:** GitHubからソースコードをダウンロードするために必要です。
    - [公式サイト](https://git-scm.com/downloads)からダウンロードしてインストールしてください。
- **Node.js:** Docusaurusを動かすための実行環境です。
    - [公式サイト](https://nodejs.org/)から**LTS版**（推奨版）をダウンロードしてインストールしてください。
- **Typora (推奨):** シンプルで使いやすいMarkdownエディタです。VS Codeでも編集できますが、文章作成に集中したい場合におすすめです。
    - [公式サイト](https://typora.io/)からダウンロードできます。
- **GitHubクライアント (推奨):** Gitのコマンドライン操作に慣れていない方は、GUI（グラフィカル・ユーザー・インターフェース）ツールを使うと便利です。
    - **初心者向け:** [GitHub Desktop](https://desktop.github.com/)
    - **中〜上級者向け:** [Fork](https://git-fork.com/)



---
### 2. プロジェクトの準備と起動

必要なツールをインストールしたら、VS Codeのターミナル（またはGitHubクライアント）で以下の手順を実行します。

1.  **リポジトリをクローン**
    ```bash
    git clone https://github.com/shibaura-tot/tot-book
    ```

2.  **フォルダに移動**
    ```bash
    cd tot-book
    cd tot
    ```

3.  **依存関係をインストール**
    ```bash
    npm install
    ```

4.  **開発サーバーを起動**
    ```bash
    npm start
    ```
    ブラウザで `http://localhost:3000` を開くと、サイトが表示されます。

## 🙌 貢献方法

誤字脱字の修正、新しいページの追加、改善案など、どんな貢献も歓迎します！

 **具体的な修正案や機能追加については、気軽にIssueを立てるか、プルリクエストを送ってください。** 

**まだ固まっていないアイデアの提案や質問、雑談などは、[Discussions](https://github.com/shibaura-tot/tot-book/discussions)をご活用ください。** 

詳しくは `CONTRIBUTING.md`も参照してください。 

本プロジェクトへの貢献にあたっては、私たちの [行動規範](CODE_OF_CONDUCT.md) を尊重してください。

## 🤝 関連リンク

- [芝浦工業大学 tot編集部公式サイト](https://tot-ch.com/)
- [芝浦工業大学 tot編集部X(旧Twitter)](https://x.com/tot_editors)
- [芝浦工業大学 tot編集部Instagram](https://www.instagram.com/tot_shibaura/)
- [Docusaurus公式サイト](https://docusaurus.io/)
