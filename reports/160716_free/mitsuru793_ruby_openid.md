---
layout: post
title: gem ruby-openidのREADMEを読む
date: 2016-07-14 16:38:02 +0900
author: mitsuru793
tags: [read]
---

# 感想

zshを読んでいた時より、今のやり方のほうが確実に力が付いている気がする。やはり、あれ？と思ったらやり方を変えた方が良いと思う。

今回はOpenIDの仕組みについても書かれているかなと思って読んだが、特に書かれてなかった。Railsでのデバッグ方法とかgemとは直接関係ないことが書かれていた。

mdファイルを自動生成するスクリプトを書いたが、dateだけコミット時に自動で書き換えるhookを作るべきだと感じた。提出が遅れてしまったイベント数とかが割り出せるといいなと思う。

# 学習記録

## README

[openid/ruby-openid: OpenID library for Ruby](https://github.com/openid/ruby-openid)

### 動詞のdocument

> The library code is quite well documented, so don't be squeamish, and look at the library itself if there's anything you don't understand in the examples.

documentは名詞だけでなく他動詞の意味もある。「文章で証明する」という意味だ。

### takes place on

> Discussion regarding the Ruby OpenID library and other JanRain OpenID libraries takes place on the OpenID mailing list.

take placeは起こる、開催されるという意味だ。それはどこで？メーリングリストでだ。だからonを使う。ちなみにSNSの場合はonを使うとLang-8で聞いた。

take the place ofというのもあって、こちらは代理をするという意味だ。

### check out

> Also check out the openid channel on the freenode IRC network.

このcheck outは参加するという意味で使われている気がした。ちなみにcheckは自動詞・他動詞の2つの意味がある。

* [「check it out」はどういう意味でしょうか？ ネイティブが説明します。 | 英語 with Luke](http://www.eigowithluke.com/2010/08/check-it-out/)
* [句動詞：check＋副詞・前置詞 - 英語](http://homepage1.nifty.com/Liberty/pv/check.htm)

## example/

[ruby-openid/examples at master · openid/ruby-openid](https://github.com/openid/ruby-openid/tree/master/examples)

### demonstrate use of

> This directory contains several examples that demonstrate use of the OpenID library.

このuseは名詞。use ofで利用、使用という意味。実際のやり方を見せてくれるサンプルという具合かな。

### 形容詞は動詞の目的語になるのか

> Make sure you have properly installed the library before running the examples.

sureは「確信して」という形容詞。確信を作るという意味で、確認するということですね。make/become/get/seem/lookなどのbe動詞形と言われるものなら、形容詞を目的語に取れるそうだ。

* [make sure - 英語 解決済 | 教えて！goo](http://oshiete.goo.ne.jp/qa/4021497.html)

### start in ~ into ~

> These examples are a great place to start in integrating OpenID into your application.

inはstartする場所、intoは方向を示しているのでは？つまりintegrating OpenID中でyour applicationに向かってstartすると。inをfromにしていないのは、動作がintegrating OpenIDの中に留まると想定されているかと。

* [英語・「～の中へ」の in と into の区別 : なるほどの素](http://blog.livedoor.jp/veritedesu/archives/1951372.html)
* [前置詞「into」の意味とイメージ！「in」との違い！！ | 飽きっぽい人のための長続き英会話　　～初心者スピーキング上達法～](http://nagatuduki-eikaiwa.com/9779.html)

### from when

> The relevant code to work from when writing your Rails OpenID Relying Party is:

whenはat witchを前に持ってきたもの。at whichはat the timeを変換したもの。これは関係副詞と言われる。「ちょいデブ親父の英文法」によると関係副詞=前置詞+関係代名詞らしいが、前置詞+関係副詞はどうなるのだろう？whenは名詞節をつくっているということなら、fromの目的語でいいのかな。

知恵袋に関係副詞節は形容詞節になり、名詞節や副詞節にはならないとのこと。となるとfromの目的語はThe relevant codeなのかな？けど文法上の理由がわからない。

* [関係副詞　基礎からの英語学習](http://www.englishcafe.jp/english3rd/day68.html)
* [英文法「関係副詞」](http://choidebu.com/bunpou/kankeihukushi.htm)
* [関係副詞how〜は名詞節です。ではwhen、where、whyは何節ですか? - 品詞に... - Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q1194779016)

## examples/rails_openid

[ruby-openid/examples/rails_openid at master · openid/ruby-openid](https://github.com/openid/ruby-openid/tree/master/examples/rails_openid)

### due to

> These two layers are bundled in a single package due to their heavy interdependence.

due toは2語以上で成り立つ前置詞、群前置詞だ。群前置詞にはbecause ofもある。because単体では接続詞なのでSVが続くが、because ofは前置詞なので名詞が続く。SVを続ける必要はない。どちらも原因を示すが、due toの方がフォーマルで残念な理由を述べる時に使う。because ofの方はくだけた感じ。

ポジティブなことならthanks toを使うと良い。

* [due to と because of って違うの？大学受験やTOEICでも頻出の群前置詞｜ 英語学習ボックス](http://eigo-box.jp/grammar/due-to/)
* [due toの意味と使い方 ー because ofよりフォーマルな英語表現を身に付けよう | 英語 with Luke](http://www.eigowithluke.com/2014/11/due-to/)

### much more

> This is unlike the relationship between the Active Record and Action Pack that is much more separate.

much moreはmoreよりもっとさらにを表す。2倍でmoreなら、5倍をmuch moreといった具合だ。fasterなど末尾にerがつくものには、muchは使わない。expensiveといった形容詞にい使う。

上記のseparateは動詞ではなく形容詞として使われている。「全く別のアクションパック」という意味だ。

* [much moreとmoreの違いは？much more の意味と使い方 | 初心者英会話ステーション](http://ajieigo.com/2062.html)
* [much more + 不可算名詞：例文で覚える英文法](http://eigozuki.com/html/reibun/hikaku-much-more.shtml)

### break out of

> This means that you can break out of execution at any point in the code, investigate and change the model, and then, resume execution!

break out ofは脱出するという意味。コードの各ポイントから処理を抜けるという意味かと。

### investigate, examine, inspectの違い

> This means that you can break out of execution at any point in the code, investigate and change the model, and then, resume execution!

調査対象はthe model。原因や真実を調べるという意味でinvestigateは使われる。これはデバッガーの話で、モデルのバグを調べるのでinvestigateが使われる。

> you can examine how your runtime objects actually work:

runtime objectsが実際にどう動いているかを調べる。このように現状や人・ものを注意深く見るという意味でexamineは使われる。

>  You can inspect domain models, change values, and save to the database.

コンソールでドメインモデルを調べるという話です。バグを調べたり観察という意味ではなく、検査や診断という意味で使われます。とりあえずドメインモデルを調べれるよということです。


* [「調査する」の違い： investigate, look into, survey, inspect, examine, , , etc - 英語論文・レポート・メールの書き方 - 使える英語表現・フレーズ集 -](http://blog012.ooenoohji.com/entry/difference-investigate-look-into-survey-inspect-examine)
* [調査する；　inspect, investigate, research, survey　どれだ？：日本語と英語をつなぐ](http://s.webry.info/sp/je.at.webry.info/201204/article_1.html)

## examples/active_record_openid_store/

[ruby-openid/examples/active_record_openid_store at master · openid/ruby-openid](https://github.com/openid/ruby-openid/tree/master/examples/active_record_openid_store)

### 和訳

> A store is required by an OpenID server and optionally by the consumer to store associations, nonces, and auth key information across requests and processes.

> If rails is distributed across several machines, they must must all have access to the same OpenID store data, so the FilesystemStore won't do.

## 単語

* underlying
* underlie
* comprehensive
* suite
* transparently
* squeamish
* hesitate
* demonstrate
* properly
* relevant
* dumb
* primarily
* persist
* incoming
* entitle
* embellish
* interdependence
* unlike
* separate
* handy
* investigate
* resume
* credential
* descend
* nonce
* association
* distribute
* have access to
