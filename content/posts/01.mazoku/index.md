+++
title = "まぞくアドバンス"
date = "2021-09-30"
description = "GBAで動くゲームを作りたい"
categories = [
    "log"
]
tags = [
    "PixelArt",
    "GBA"
]

+++



<!--more-->

### 概要 

当時はまちカドまぞくにドはまりしていたので、二次創作のゲームを作成してました。

現在ペンディング中ですが、気が向いたら完成させたいね。

### エミュレータ上での動作
表示バグだらけですが。

<div>
<iframe width="560" height="315" src="https://www.youtube.com/embed/kzuw1l1QM2M?si=SHZjvHkMWn-cBR84" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

### 音楽再生
MIDIシーケンサーで打ち込みをぽちぽち打ち込み、MOD Trackerで再生できるようコンバートする。

divkitProのsampleを参考にmaxmodライブラリを用いて音楽の再生まで確認。

mod形式とは言えサイズは大きいので、省サイズ方法について検討中。

GBA

<div>
<blockquote class="twitter-tweet" data-media-max-width="560"><p lang="ja" dir="ltr">音楽センス皆無なのでドラム打ちも音源も適当 <a href="https://t.co/6i4cTiRKn3">pic.twitter.com/6i4cTiRKn3</a></p>&mdash; ひら (@hira_65536) <a href="https://twitter.com/hira_65536/status/1614998079941545985?ref_src=twsrc%5Etfw">January 16, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>

DS
<div>
<blockquote class="twitter-tweet" data-media-max-width="560"><p lang="ja" dir="ltr">DSの方が音ちゃんと出てる <a href="https://t.co/lINK6XweZD">pic.twitter.com/lINK6XweZD</a></p>&mdash; ひら (@hira_65536) <a href="https://twitter.com/hira_65536/status/1614998571602051074?ref_src=twsrc%5Etfw">January 16, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>

### カセットに作成途中のソフトを書き込み実機動作

Writerは以下を購入。

[GBxCart RW (Gameboy/GBC/GBA Cart Reader, Writer & Flasher)](https://shop.insidegadgets.com/product/gbxcart-rw/)

動作確認の様子。元の動画データ紛失してしまったので、がびがび...

<div>
<iframe width="560" height="315" src="https://www.youtube.com/embed/zrR7Nnhh8-w?si=_4erTZ_CpGNRJgJR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>