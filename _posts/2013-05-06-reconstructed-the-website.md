---
layout: post
title: "ウェブサイトの再構築"
date: 2013-05-06 05:32
comments: true
categories:
- meta
---

日記の類の執筆実績を積み上げられないことに実績のある私ですが、長らく死んでたウェブサイトを [GitHub Pages](http://pages.github.com/) + [Octopress](http://octopress.org/) で構築しなおしてみました。
最近 GitHub 上にウェブサイトを構築するのが流行ってるのかは知らないですが、便利そうだったので。

<!-- more -->

どうも記事の執筆が WYSIWYG 寄りというか変に複雑なので一般的なブログ エンジンを使うのがしっくり来ず、ならば Wiki かということで Pukiwiki クローンに手を伸ばしてみましたが、
記事のバージョン管理のシステムがいい加減で (というか全体的に古臭い)、その後 [Gollum](https://github.com/gollum/gollum) という Git ベースの Wiki エンジンを試してもみたものの、
どうも上手く動かないというところで飽き、適当に GitHub にリポジトリを立てて記事をぶち撒けるようにしてみたのですが、当然、クソ面倒だったので飽きた次第。

さらに、ウェブサイトをホストするにあたって、サーバを構築しないといけないという流れにしていたところ、すっかりサーバ弄りに飽きてしまった (or 時間が取れなかった) ので、結果的に放置してしまったという事情もあり、
この度の構成により GitHub に全部お任せすることができ、不安定要素を排除することができました (独自ドメインで blog をホストする手段は他にもあったけど)。

GitHub Pages だとちゃんと blog 然としたサイトを作ってくれて、かつ、単独のページも難なく作れ、一方で記事も markdown で書けるので執筆も楽々だし、Git 上にも当然に乗ってくれるので、きっと快適なはず。
シンタックス ハイライト絡みで困ることも無さそうだし、ようやくこの構成で腰を落ち着けることができるのではと考えています。

## TODO

* デザインの調整
    * サイトのテーマは [これ](https://github.com/wallace/justin-kelly-theme) を入れてみたのですが、日本語文章を前提としていないので、色々手直しが必要。
* 古い記事を持ってくる
    * 以前書いた記事で有用そうなものを手直ししてこちらに持ってくる。
* 継続的に何か書く
    * たぶんこの構成が (GitHub が死なない限り) 終の棲家になるはずなので、心置きなく書けるはず…