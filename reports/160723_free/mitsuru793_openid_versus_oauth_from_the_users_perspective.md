---
layout: post
title: OpenIDとOAuthの動きの違いを、ユーザー方面から見てみる。
date: 2016-07-21 04:48:30 +0900
author: mitsuru793
tags: [read]
---

[OpenID versus OAuth from the user’s perspective - cakebaker](http://cakebaker.42dh.com/2008/04/01/openid-versus-oauth-from-the-users-perspective/)

# 感想

動きがシンプルにまとまっているので見返すのに調度良かった。読むのはあまり苦労しなかった。なので読んだ内容をここでアウトプットしてみた。英語以外の勉強になって一石二鳥。

# 内容のまとめ

OpenIDの動き

1. ユーザーが、example.comに自分のアカウントでアクセスしたい。
2. example.comは、ユーザーにOpenIDを求めます。
3. ユーザーは、OpenIDを入力します。
4. example.comは、ユーザーをOpenIDプロパイダにリダイレクトします。
4. ユーザーは、自分自身をOpenIDのプロパイダに証明します。
5. OpenIDプロパイダは、ユーザーをexample.comにリダイレクトします。
6. example.comは、ユーザーが自分のアカウントアクセスできるようにします。

OpenIDはURLのこと。自分のマイページを持っているからそれを入力する。

OAuthの動き

1. example.comのユーザーは、mycontacts.comから自分の連絡帳をインポートしたいです。
2. example.comはユーザーをmycontacts.comにリダイレクトします。
3. ユーザーはmycontacts.comに自分自身であることを証明します。
4. mycontacts.comはユーザーに、example.comに連絡帳へのアクセス権を許可していいか尋ねます。
5. ユーザーは回答を選択します。
6. mycontacts.comは、ユーザーをexample.comに戻します。
7. example.comは、mycontacts.comから連絡帳を取得します。
8. example.comは、ユーザーにインポートが成功したことを知らせます。

OpenIDもOAuthもプロパイダにユーザーをリダイレクトします。この時、ユーザーをリダイレクトするのはサードパーティーのサイトです。ここで自分自身であることをプロパイダに証明します。OAuthの場合は、さらに認可も行います。

# 学習記録

## ask for

> example.com (the “Relying Party” in OpenID lingo) asks the user for his OpenID

forをつけないと、どんなものかを尋ねる。forがつくと「〜を求めて」という意味になり、頂戴と言っている。情報を求めているようなもの。

* [ただのask と　ask for の違い - 英語 解決済 | 教えて！goo](http://oshiete.goo.ne.jp/qa/8543303.html)

## 主格、目的格のof

ofの前の名詞が、自動詞が変化したものなら主格のof、他動詞が変化したものなら目的格のofになる。

* [英語が得意な人は必ず知っている、2つのofの使い方｜ 英語学習ボックス](http://eigo-box.jp/grammar/preposition-1/)

## 知覚動詞 of

> She informed her parents of her safe arrival.
>
> <cite>[informの意味 - 英和辞典 Weblio辞書](http://ejje.weblio.jp/content/inform)</cite>

このofは関係・関連をだろう。前置詞はAとBの関係を表すもの。前置詞が1つあれば、絶対にA, Bが存在する。例え、文面にはなくても。もともとofの語源はoffと同じで、離れるという感覚がある。またofを使うことで「〜のこと」という強調になる場合もある。

* [know of, inform of... などのofの文法上の意味は？ - 英語 解決済 | 教えて！goo](http://oshiete.goo.ne.jp/qa/1430551.html)


## compare to/with

異なるものを比べる場合はtoを、同じグループで本質的に比較する場合はwithを使います。

* [compare toとcompare withの違い【紛らわしい英語】 | ぷらいまりい](http://primaryplus1.com/compare-to-or-compare-with)

## make for

> I see the different and I also see redundancy which does NOT make for a smooth and simple user experience.

## 単語

* cousin
* lingo
* retrieve
* inform
* scenario
* identify
* whereas
* keep apart
* point
* primer
* redundancy
* exclusively
* freak
* mess
* interoperability
* theoretically
