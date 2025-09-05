---
sidebar_position: 3
---

# ドメインを変える

GROWIを新しく登録しました。登録するとオリジナルのドメインが作れるそうです。ですが作り方がよくわかりません。
今まで、Valu Domainで作ったドメインを使用してHPを運用していましたが、GROWI上で作成したドメインを使ってHPを運用していきたいです


ChatGPT:
メモリを更新しました
なるほど、ありがとうございます！
現在は Valu Domain で取得した独自ドメインを使って HP を運用していたけど、これからは GROWI のドメイン（または GROWI 上で作成したページ）を使ってサイトを運用していきたい、ということですね。

ここでのポイントは：

✅ GROWIの「ドメインを作れる」という意味
おそらくこれは「◯◯.growi.cloud というサブドメインを取得できる」という意味で、GROWI Cloudの提供元（WESEEK社など）がホスティングする形です。
→ この場合、たとえば mywiki.growi.cloud のようなURLがGROWIのアドレスになります。

✅ 目標：Valu Domain で取得した独自ドメインを使って GROWI を見せたい
この場合、次のような方法が考えられます。

■ 方法1：サブドメインを使う（おすすめ）
たとえば、Valu Domain側で wiki.yourdomain.com を作って、それを mywiki.growi.cloud に向ける方法です。

具体的な手順：
GROWIのURLを確認

例: mywiki.growi.cloud

Valu DomainのDNS設定画面を開く

サブドメイン wiki.yourdomain.com を追加

種類：CNAME

値：mywiki.growi.cloud

GROWIの管理画面で独自ドメインを登録（必要な場合）

管理者画面 → 「システム設定」や「独自ドメイン設定」など

入力例：https://wiki.yourdomain.com

HTTPS対応（SSL証明書）

GROWI Cloud 側が自動でやってくれるか、証明書発行手順が必要な場合もある

■ 方法2：独自ドメイン自体でアクセスできるようにする（Aレコード）
この場合は Valu Domain 側で A レコードを設定し、GROWI を自分のサーバーにホストしている場合に有効です。

ただし、GROWI Cloudを利用している場合は、CNAME経由の設定が基本です。

🔧 要確認：
GROWI Cloudの 管理画面に「独自ドメイン設定」があるか？

GROWIのURL（◯◯.growi.cloud）は発行済み？

Valu DomainのDNS設定画面に入れるか？

よければ、

今使っているGROWIのURL（例：yourteam.growi.cloud）

希望しているドメイン名（例：wiki.yourdomain.com）

を教えてもらえたら、もっとピンポイントでDNS設定の書き方や流れをお手伝いできます！






そもそもできない説出てきました