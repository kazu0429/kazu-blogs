---
title: "First Blog"
date: 2024-01-23
summary: About self introduction and this blog
tags: ["memo"]
cover:
  image: images/opengraph-image.png
  hiddenInList: true
draft: false
---

# ブログを始めてみました🚀

...といっても特に書くことないんですけどね。

## なんのために
正直自分のブログサイトを作ってみたいと思ったのが一番です。作ることが目的になってる良くないパターン。
年始に初めてZennの記事を書いたのですが、技術系の記事ってハードルがすごく高く感じているところがあり、見て欲しいんだけど見られたくないみたいなジレンマでした。
そういう意味でも、自分のメモ帳かつ誰でも見れるみたいな気軽な場所を作りたいと思い、このブログサイト制作に至りました。

---

## このサイトについて
このサイトは[{{< inTextImg url="https://raw.githubusercontent.com/gohugoio/hugoDocs/master/static/img/hugo-logo.png" height="15" >}}](https://gohugo.io/)というGo言語で作られたWebフレームワークで構築しています。テーマは[PeparMod](https://github.com/adityatelange/hugo-PaperMod/)を採用しました。(シンプルでいいなと思ったからです。)

実際はbrewでhugoをインストールし、テーマをgitにsubmissionするだけでできたのでプログラムは一切書いていません。

```
$ brew install hugo
$ hugo new site kazu-blogs
$ cd kazu-blogs
$ git init
$ git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

**公式サイト**
> Hugo is a static site generator written in Go, optimized for speed and designed for flexibility. With its advanced templating system and fast asset pipelines, Hugo renders a complete site in seconds, often less.

公式さんの言っている通り、本当に爆速で作れました。[テーマ](https://themes.gohugo.io/)も様々提供されており、それぞれで柔軟にデザインを変えることができる（はず）のが便利すぎます。

--- 

## これから
技術寄りなことも何かあれば書いていきたいし、何かしらイベントに参加したら感想みたいなのでも書き散らしていきたいですね。
でも半分メモです。