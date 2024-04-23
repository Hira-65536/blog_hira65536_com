+++
author = "hira65536"
title = "まぞくアドバンス"
date = "2021-09-30"
description = "GBAで動くゲームを作ってみたかった。"
categories = [
    "log"
]
tags = [
    "PixelArt",
    "GBA"
]

+++

GBAで動くゲームを作れるとネットで情報を見たので、気になって色々遊んでいたときのまとめ。

### 概要 

当時はまちカドまぞくにドはまりしていたので、二次創作のゲームを作成してました。

現在ペンディング中ですが、気が向いたら完成させる予定。

### エミュレータ上での動作
表示バグだらけですが。

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/kzuw1l1QM2M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### 音楽再生
MIDIシーケンサーで打ち込みをぽちぽち打ち込み、MOD Trackerで再生できるようコンバートする。

divkitProのsampleを参考にmaxmodライブラリを用いて音楽の再生が成功！

mod形式とは言えサイズは大きいので、省サイズ方法について検討中。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">音楽センス皆無なのでドラム打ちも音源も適当 <a href="https://t.co/6i4cTiRKn3">pic.twitter.com/6i4cTiRKn3</a></p>&mdash; ひら (@hira_65536) <a href="https://twitter.com/hira_65536/status/1614998079941545985?ref_src=twsrc%5Etfw">January 16, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### カセットに作成途中のソフトを書き込み実機動作

https://x.com/hira_65536/status/1442804603590901761