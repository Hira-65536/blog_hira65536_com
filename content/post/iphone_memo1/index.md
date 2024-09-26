+++
author = "hira65536"
title = "iPhone壊したときのアカウント移行"
date = "2021-09-30"
description = "二度あることは三度あると言うので、備忘録として。"
categories = [
    "memo"
]
tags = [
    "iPhone",
]

+++

### LINE

- 前提としてパスワードと電話番号が変わっていないこと。
- 電話番号が変わっていないならば、下記ページ記載の手順に沿ってできる。
  - https://help.line.me/line/?contentId=50000951&lang=ja

- **ただし、二段階認証を前端末で有効にしていないといけないらしい。**
  - 二段階認証を設定していなかった場合は、おとなしくLINEヘルプセンターに問い合わせる。
  - 私は夜の19時頃に問い合わせて、次の朝10時くらいには返答きてログインできるようになった。

### Mobile Suica

- 公式のやり方は以下らしい。(以前のスマホがある前提。)
  - https://apfaq.mobilesuica.com/faq/show/1537?site_domain=default
- Appleアカウントにログインできている場合は、新端末から旧端末の情報を削除可能
  - 新端末から「設定」を開く。
  - 左サイドバーの「Apple ID,i Cloud,メディアと購入」の項目を開く。
  - 旧端末のiPhoneを選択
  - デバイス情報画面のApple Pay項目から、「カードを削除」を選択して旧端末からSuicaの情報を削除する。

- そのあとは新端末側でMobile Suicaアプリをインストール、引継ぎの手順で復帰可能。

### その他困ったこと

- Google Authenticator等の認証アプリなど
  - 二段階認証設定する際のバックアップコードは絶対取っておく。
    - Discord, Github, Misskey io etc...
- やり取りが多い相手の場合は、LINE以外の通信手段を確保しておく

