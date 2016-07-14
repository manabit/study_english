---
layout: post
title: zsh miscを読む
date: 2016-07-10 04:02:00 +0900
author: mitsuru793
tags: [read]
---

# 感想

zshmiscのPRECOMMAND MODIFIERSだけを読んだ。今回は読む量は少ないが、抜き取った文章から連想的に気になったことを調べた。最初はzshmiscは読む気になれなかったが、最初に各文章から小さな疑問をリストアップしていくことで、徐々に面白くなっていった。文法本を読むでは知識が身につかないので、実際に読む流れの中で関連付けて覚えていきたい。そうすれば、文法が感覚となるだろう。

1つの文章を何度か読み直して、英語のまま直感的・感覚的に理解するように努めた。日本語だと飛ばしながらもニュアンスを感じ取ることができるが、英語だとわからないから飛ばしてしまうので力がつかないままになってしまっている。必要な情報を抜き取れれば目的は果たせるが、英語の勉強ということで基礎を重視した形で取り組もうと思う。だから、文量より掘り下げることを重視する。

# vimでのメモの取り方

tmuxで左右のペーンにvimとmanを表示して読んでいる。tmuxでmanをコピペして、vimに貼り付ける形だ。単語リストは最後に書いている。これはGキーですぐにファイル終端に移動できるためだ。単語リストはリンクは貼っていない。markdownが見づらくなるのと、1つの辞書サイトに固定されてしまうためだ。私は自作の関数でカーソル下の単語をもとに、ブラウザから[Collins](http://www.collinsdictionary.com/dictionary/english)で検索をするショートカットを設定している。これなら、ほかのサイトにも対応可能だ。

# 文

## may beとmaybeの違い

> A simple command may be preceded by a precommand modifier, which will  alter  how  the command is interpreted.

文法的に言えば品詞が違う。"may be"は助動詞+be動詞であり、"maybe"は副詞である。意味的には、2つとも似たような意味であるが、mayに「〜してもよい」という意味もある。ここが使い分けの必要がありそうだ。ただし、同じ意味でもニュアンス、程度の差はあるだろう。

* [「Maybe」 と「May be」 の違いはなんですか？同... - 英語 | Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q1235951267)
* [助動詞|mayとmaybeの違い|中学英語|定期テスト対策サイト](http://teikitest.benesse.co.jp/chu/english/english/c00283.html)

## how S Vとは？

> A simple command may be preceded by a precommand modifier, which will  alter  how  the command is interpreted.

"how S V"は言い換えると"the way S V"にあたる。このはhowは名詞節を作っている。名詞節を作るhowには"how M S V"もある。

* [how S V=the way S Vについて - how S Vは（どの... - 英語 | Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q1367180473)


## A of B whichだとA,Bどちらにwhichがかかるのか？

> These modifiers are shell builtin commands with the exception of nocorrect which is a reserved word.

文脈によると思う。ただ、今回のはうまく訳せなかった。

"of which"となっている場合は、whoseと同等になっている。また、whoseは人以外にも使えることに注意。

* [英語 "of which,in which" 関係代名詞と前置詞の関係　 / 英語 by ほりぃ |マナペディア|](http://manapedia.jp/text/435)

## prepended toのtoの理由

> The command is executed with a `-' prepended to its argv[0] string.

prependは先頭に追加するという意味。jQueryのメソッドにもある。addには他動詞と自動詞の2つの意味があるが、prependは他動のみ。例え、自動があったとしても、今回は受動態なので他動として使われていることがわかる。

前置きはこれぐらいで、このtoは前置詞。理由は後ろに動詞ではなく、名詞節が来ているから。動詞だったら不定詞である。

## take to beの意味

> The command word is taken to be the name of a builtin command,  rather  than  a shell function or external command.

[アルク](http://eow.alc.co.jp/search?q=take+to+be)には"take ~ to be"で「〜を...と思う」とある。おそらく今回のは、command wordがthe name of a buildin commandとして扱われる、解釈されるという意味だと思う。

## rather thanの意味

> The command word is taken to be the name of a builtin command,  rather  than  a shell function or external command.

"A rather than B"は「AよりもB」という意味かと思ったが、そうではなかった。「BよりもむしろA」、「BではなくA」という意味だ。BもAより少ないが含まれているという意味ではなさそうだ。今回の場合だと、コマンドの単語はビルトインコマンドの単語として解釈されるとある。これは「シェル関数や外部コマンドよりも優先度が高い」という意味ではなく、「シェル関数や外部コマンドではなく、ビルトインコマンドとして」という意味だろう。「シェル関数や外部コマンドとして勘違いしているかもしれないが、そうではない」と警告をしている。

* [A rather than B：例文で覚える英文法](http://eigozuki.com/html/reibun/hikaku-rather-than.shtml)

## similarとfamiliarの違い

> With the -v flag,  command is similar to whence and with -V, it is equivalent to whence -v.

similarとは似ている、familiarよく知っているという意味だ。

## togeterとwithを一緒に使えるのか？

> The following command together with any arguments is run in place of  the  current  process,  rather  than  as a sub-process.

使えると思う。togeterは副詞でwithは前置詞だ。"with together"ではなく、"together with"なので前置詞の前に副詞が来ている。ただし、前置詞の後ろに名詞が来るというのは例外もある。

今回のtogetherはwithを強調していて、"together with"で前置詞のような働きをしている。

## norの使いドコロ

> The shell does not invoke  TRAPEXIT,  nor  does  it  source  zlogout files.

"neither A nor B"とneitherと一緒に使われる。「AもBも...ない」という両方とも含まない表現だ。この場合は、続くbe動詞はAではなくBに合わせる。A, Bの品詞は合わせておいたほうが綺麗。Aが名詞ならBも名詞という風に。

今回はneitherとは使われていない。nor単体だ。これは2つ目の否定文をつなぐ使い方だ。"nor does"でnorはdoesを否定している。このように使えることと一緒に次のことも覚えると良い。

A or BでBが動詞ならorでもnorで使えるが、Bが動詞でない場合はorしか使えない。だから前述のようなnorで動詞を否定という使い方ができると思う。

* [「nor」の使い方と意味、そして「neither … nor」の使い方 | 英語 with Luke](http://www.eigowithluke.com/2010/11/nor/)

## inではなくonを使う理由

> Spelling  correction  is not done on any of the words.

onは名詞ではなく、動詞の後に来ている。これを踏まえて調べた。Forestにonの「動作の対象」として例があった。

> He is concentrating on his experiment.
> 彼は実験に集中している。

場所に関するonは上下ではなく、接触を表す。上記は「動作の対象」を「動作する場所」とも解釈できる気がした。そうすると、"done on any of the words"のonはこの例と同じ使われ方だと思う。

inは劇場のような立体の中を表す。時の場合は期間内を表す。どちらも何かの中を表してる。"is not done"の動作対象は"any of the words"の中という見方も出来るため、inが使われてもいいように思えた。しかし、Forestには場所のinは、「一番具体的かつ基本的なイメージ」とある。"any of the words"はanyが使われているので、具体的ではないということかもしれない。と思ったら、"in any case"という「どのような場合でも」という熟語があった。

Forestによると"in case"のinは接続詞らしい。なので上記の"in any case"は検討違いだった。しかし、"in any ~"という記述をgoogle検索で調べると使っている人はいた。

また、[inは境界線を意識するが、onは意識しない](http://english4.jugem.jp/?eid=33)という情報もあった。onが接触というイメージがより具体的になってきたが、今回のinではなくonを使う理由はハッキリとはわからなかった。理由というより感覚を知る、感覚に近づくために調べた。

* [Amazon.co.jp： 総合英語Forest 6th edition: 石黒 昭博: 本](https://www.amazon.co.jp/%E7%B7%8F%E5%90%88%E8%8B%B1%E8%AA%9EForest-6th-%E7%9F%B3%E9%BB%92-%E6%98%AD%E5%8D%9A/dp/4342010402?ie=UTF8&ref_=cm_cr_arp_d_product_top)
* [in on at の違い | よねの英語文法解説 ーネイティブ感覚の世界一わかりやすい文法ー](http://english4.jugem.jp/?eid=33)

## onではなくinを使う理由

> It has no effect in non-interactive shells.

"non-interactive shells"はモードという捉え方もできる。「またこのシェルの中では〜」という表現のイメージが持てたため、inの使う感覚は分かりやすい。

## 接続詞？のas

> This must appear before any other precommand modifier, as it is  interpreted  immediately, before  any parsing is done.

接続詞には等位接続詞と従属接続詞がある。このasはおそらく後者だ。as以降がSVという文になっているので接続詞と判断した。従位接続詞はそこだけでは言いたいことが伝わらない。なので"as ~"を読むだけではわからない内容ということから従位接続詞だと思う。等位接続詞の場合もそこを見るだけじゃ分からないので、文脈での判断になるかもしれない。

と思ったが等位接続詞と従属接続詞、両方に使える接続詞はないかもしれない。だとすると接続詞を見ただけで種類は決まる。

+ [受験生に知っておいてほしい接続詞asの5つの意味まとめ｜ 英語学習ボックス](http://eigo-box.jp/grammar/as/)

# 単語

* precede
* suppress
* whence
* compatibility
* prepend
