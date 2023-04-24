+++
author = "hira65536"
title = "MazokuAdvance"
date = "2021-09-30"
description = "GBAで動くゲームを作ってみたかった。"
categories = [
    "Software",
    "GBA"
]
tags = [
    "PixelArt",
    "retro"
]
+++

## GBA開発
GBAで動くゲームを作れるとネットで情報を見たので、気になって色々遊んでいたときのまとめ。
<br>当時はまちカドまぞくにドはまりしていたので、二次創作のゲームを作成しようとしてました。
<br>気が向いたら、完成させるかも。

### エミュレータ上での動作
表示バグだらけですが。

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/kzuw1l1QM2M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### 音楽再生
MIDIシーケンサーで打ち込みをぽちぽち打ち込み、MOD Trackerで再生できるようコンバートする。
divkitProのsampleを参考にmaxmodライブラリを用いて音楽の再生が成功！

mod形式とは言えサイズは大きいので、省サイズ方法について検討中。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">音楽センス皆無なのでドラム打ちも音源も適当 <a href="https://t.co/6i4cTiRKn3">pic.twitter.com/6i4cTiRKn3</a></p>&mdash; ひら (@hira_65536) <a href="https://twitter.com/hira_65536/status/1614998079941545985?ref_src=twsrc%5Etfw">January 16, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### GBxCart RWによる、カセットに作成途中のソフトを書きこみテスト！

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">Writerが届いたので、GBAカートリッジに書き込んで自作ゲームが起動できるようになった <a href="https://t.co/p14Piqhb2h">pic.twitter.com/p14Piqhb2h</a></p>&mdash; ひら (@hira_65536) <a href="https://twitter.com/hira_65536/status/1442804603590901761?ref_src=twsrc%5Etfw">September 28, 2021</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></blockquote>
<br><br>


### マルチブートによる動作テスト

<br>
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">思い描いていたゲームの形はできたので、GBA実機で遊んでる動画<br><br>バグ取りとかエフェクトとか調整とかはこれから <a href="https://t.co/8TV9tX2EF9">pic.twitter.com/8TV9tX2EF9</a></p>&mdash; れーひら (@hira_65536) <a href="https://twitter.com/hira_65536/status/1388849255700262917?ref_src=twsrc%5Etfw">May 2, 2021</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></blockquote><br><br>
