# ominiauth gemのREADMEを読む

## 感想

一見知ってるような文法でも、もう一度調べ直すことで収穫があった。少しでも気になったら熟考してみるのが一番力についている。調べた後にもう一度通して読んでみると、読みやすさが違う。

### 読んだきっかけ

Qiitaなどでこのgemの使い方の解説をみたが、OAuth自体をよく知らない。何が出来るかはわかっても安全性で不安になったので、まずは使用Gemの概要から読んでみようと思ったのがきっかけだ。

## 学習記録

### as ~ asの品詞

> It was created to be powerful, flexible, and do as little as possible.

1つの目のasは副詞だ。無くしても文が成り立つからだ。2つ目のasは接続詞だ。SVの構造が隠れている。今回の場合だとpossibleの後にdoがあるのか？

このasの使い方は原級比較というもので、2つのasの間に原級が入る。原級とは、形容詞・副詞が比較級や最上級になる前の形である。動詞でいう原型だ。

今回だと出来る限りしないという意味だ。設定が少ないgemということだ。

* [as ～ asは比較の基礎！2つの「as」の大きな違い｜ 英語学習ボックス](http://eigo-box.jp/grammar/comparison-3/)
* [受験生に知っておいてほしい接続詞asの5つの意味まとめ｜ 英語学習ボックス](http://eigo-box.jp/grammar/as/)
* [「as much as」と「as little as」の表現、使用例を名言で学ぶ！ | おもしろいんぐりっしゅ](http://nekocacao.com/as-much-as-expression/)

### everything from A to Z

> OmniAuth strategies have been created for everything from Facebook to LDAP.

A to Zだと片っ端からという意味になる。このことから推測するに、FacebookとLDAPではなく、FacebookからLDAPまで様々に対応という意味だと思われる。

### 前置詞のvia

> One strategy, called Developer, is included with OmniAuth and provides a completely insecure, non-production-usable strategy that directly prompts a user for authentication information and then passes it straight through.

名詞だと半導体技術のvia holeを指す。今回は前置詞として使われているので、「〜を経由して」という意味になる。

### 文頭にBecauseは使えない

> Because OmniAuth is built for multi-provider authentication, I may want to leave room to run multiple strategies.

英語は新しい情報は後半に持ってくる性質がある。そのため既に知っている理由なら文頭にはSinceを使って述べる。新しい情報なら後半にbecauseを使って述べる。becauseは接続詞だから文頭に置けないというのを見たが、Sinceも接続詞であった。

だが、実際には文頭にBecauseが使われるいるのを見かける。

* [Becauseを行頭に使うのは文法的にはどうなのか - 英語は勉強ではなく国際交流で学ぶ](http://manabu-eigo.com/because-beginning-sentence)
* [「初心者編 becauseの誤った使い方」　ライティング術シリーズ：英会話初心者からの大逆転](http://www.toeics.com/writing/129essaybeginner-because.html)
* [becauseとsinceの意味・違いと使い方 / 英語 by ほりぃ |マナペディア|](http://manapedia.jp/text/477)

### look to A for

> You should look to the documentation for each provider you use for specific initialization requirements.

このforはlook forではなく、Aにかかるforだと思う。なので原因・理由の意味ではなく、対象を示しているかと。for以降はドキュメントに書かれている内容だと思いました。

* [Amazon.co.jp： 総合英語Forest 6th edition: 石黒 昭博: 本](https://www.amazon.co.jp/%E7%B7%8F%E5%90%88%E8%8B%B1%E8%AA%9EForest-6th-%E7%9F%B3%E9%BB%92-%E6%98%AD%E5%8D%9A/dp/4342010402?ie=UTF8&ref_=cm_cr_arp_d_product_top)

### into

> It is designed to be a black box that you can send your application's users into when you need authentication and then get information back.

* [Amazon.co.jp： 総合英語Forest 6th edition: 石黒 昭博: 本](https://www.amazon.co.jp/%E7%B7%8F%E5%90%88%E8%8B%B1%E8%AA%9EForest-6th-%E7%9F%B3%E9%BB%92-%E6%98%AD%E5%8D%9A/dp/4342010402?ie=UTF8&ref_=cm_cr_arp_d_product_top)

intoは「の中へ」、ontoは「の上へ」が基本的な意味。intoはa black boxを指していると思う。

### as much ~ as

> This hash contains as much information about the user as OmniAuth was able to glean from the utilized strategy.

"as much information"のasは前置詞、muchは形容詞。"as much"で「等しい」という意味。"as much ~ as"で「~と同じ量の」という意味。

wasの主語はOmniAuth。1つの文には動詞は1つだから、beenではないのでwasは過去分詞ではない。となると関係代名詞が省略されているのかと思った。ただ、2個目のasがOmniAuthにかかっているわけではないのなら、この文はasの後ろにピリオドを付け割れただけで、2文になっているともとれる。しかし、2文だと何と等しいユーザー情報かわからない。だから1文だろう。

ユーザー情報と同じ量である、OmniAuthが利用できるstrategyから集めたものをHashに含んでいるということだろうか？始めはユーザー情報を含んでいるのかと解釈した。結局よくわからない。

### whatever

> You should set up an endpoint in your application that matches to the callback URL and then performs whatever steps are necessary for your application.

whateverは複合関係詞だ。関係代名詞や関係副詞にeverが付いているのが特徴。「〜するもなは何でも」とう意味の名詞節を作る。

* [Amazon.co.jp： 総合英語Forest 6th edition: 石黒 昭博: 本](https://www.amazon.co.jp/%E7%B7%8F%E5%90%88%E8%8B%B1%E8%AA%9EForest-6th-%E7%9F%B3%E9%BB%92-%E6%98%AD%E5%8D%9A/dp/4342010402?ie=UTF8&ref_=cm_cr_arp_d_product_top)

### might

> And I might then have a SessionsController with code that looks something like this:

mightはmayの過去形ですが、会話では過去の意味としては使われない。どちらも可能性の意味を持っており、mightはmayより可能性が低い。控えめ。そしてmayにはcanの意味はあるが、mightにはない。だからハッキリと可能性の意味を示すならmightを使うと良い。上記にcanの意味はないとすぐわかるのだ。

* [Mayの２つの意味とMightとの使い方け方。mightが過去形は誤解！ | 初心者英会話ステーション](http://ajieigo.com/464.html)

### of what

> For an in-depth description of what the authentication hash might contain, see the Auth Hash Schema wiki page.

このwhatは名詞節を作っているので、前置詞であるofの後ろに来てもおかしくはない。このwhatはcontainの目的語だ。「認証のhashが含んでいるはずのものの詳細が知りたいなら、wikiを見て」と言っている。

* ["of what"の使い方を教えてください。... - 英語 | Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q1248746637)
* [・He was born in what is now Germany.・At the celebration... - Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q1012521430)

### beyondとbehind

> Note that OmniAuth does not perform any actions beyond setting some environment information on the callback request.

behindはfrontの対義語です。これらは基準値から前と後ろという位置を表している。しかしbehindに前後のニュアンスは含まれておらず、基準から超えた向こう側という距離を表している。またbehindだと隠れているというように取ることも出来る。

"beyond setting"とは設定する前ではなく、設定後という意味だと思う。call backリクエスト上で環境設定した後は、OmniAuthは何もしないということか。

* [behindとbeyondの違い - 英語 締切済 | 教えて！goo](http://oshiete.goo.ne.jp/qa/3399163.html)

### be up to

> It is entirely up to you how you want to implement the particulars of your application's authentication flow.

be up toは〜次第を表している。"you ~"次第ということだ。

* [be up toの意味を教えてください、お願いします... - 英語 | Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q1252714007)

### how

> It is entirely up to you how you want to implement the particulars of your application's authentication flow.

when/where/why/howは関係副詞である。"at the time"を"at witch"のように前置詞+whichで置き換えることができるなら、"at witch"をwhenにして前に持ってくることができる。howの場合は、先行詞はthe wayだが、the way howとは使われず、howかthe wayのみ。whyの場合は、reasonのみを先行詞にとる。

"up to you"であなた次第。それはどうのようにかをhowで示している。"up to you / how you ~"と区切ると分かりやすい。と思ったが、"how ~"は意味上の主語とも取れる。「どう実装するかはあなた次第」と。[似たような文がこちらにありました。](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q10101144440)やはり強調構文だと思います。how~が長い名詞節だから後ろに置いているのですね。

* [関係副詞　基礎からの英語学習](http://www.englishcafe.jp/english3rd/day68.html)
* [英文の構造についてIt entirely is up to you which one you ... - Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q10101144440)

### 和訳

> OmniAuth was intentionally built not to automatically associate with a User model or make assumptions about how many authentication methods you might want to use or what you might want to do with the data once a user has authenticated.

"built not to"はassociateとmakeの2つに結びついている。orが等位接続詞だからだ。"about how many ~"からがよくわからない。

### 単語

* standardize
* strategy
* insecure
* via
* disparate
* leverage
* individually
* usable
* extremely
* intentionally
* assumptions
* incredibly
* glean
* utilize
* beyond
* particulars
* maintain
* adhere
* violation
* specifically
* precision
