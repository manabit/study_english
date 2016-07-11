# TwitterAPI設定画面のSettingタブ

## 感想

Consumer KeyとAccess Tokenの違いを調べるために読み始めた。他の解説記事を頼りにせずとも、本家で解決できるために。結果として、今回のページには該当の内容は書いてなかったが違いは推測できた。

Consumer KeyはアプリのユニークIDで、アプリを識別するもの。Access Tokenは各ユーザーがこれを使ってアプリから自分のアカウントを操作する。Access Tokenはどういう仕組みかはわからない。操作させる許可は、アカウントごとにConsumer Keyを登録しておけば済むのではないのかと思った。

この2つのKeyにはSecret Keyというものがある。これはおそらく各Keyのパスワードみたいなものだと思う。

## attributeの使われ方

> This is used to attribute the source of a tweet and in user-facing authorization screens.

これはattributeのために使われるようだ。attributeは属性という名詞だけでなく、「~に帰する」という他動詞の使われ方もある。今回だと"the source of a tweet"が何かに帰するようだが、toがないので分からない。

## 等位接続詞に見えないand

> This is used to attribute the source of a tweet and in user-facing authorization screens.

位置的に等位接続詞として考えると"and in ~"はattributeの目的語かと思ったが、inで始まるから違う。andの前は名詞なら、andの後も名詞のはずだ。だからこれはattributeより前、"to attribute ~"と対応だと思う。つまり、これはattributeのために使われて、かつ"user-facing ~"で使われるということだ。

## to不定詞の副詞的用法

andで繋がれているtoのために、to不定詞について見ていく。to不定詞はこれから先のことを1つの文に圧縮したものだ。だからこれから先のこと、可能性のあることを示す。しかし、"seem to"の場合は、未来の意味は持たない。今回の場合はtoの前に名詞はなく修飾はしていない。usedの目的を表している。これは副詞的用法だ。

* [副詞と前置詞の違いがよくわかりません。例えば、I looked fo... - Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q1037375330)

## 前置詞にもなるし副詞にもなる

toが副詞となっているのはわかった。これが等位接続詞で繋がっているなら、inも副詞になる。しかし、inは前置詞なのでは？ということで、inの使われ方を見ていく。

"put on", "put off", "put in"など前置詞として使われるon, off, inはこの場合は副詞になる。見分け方としては、putが他動詞だからだ。他動詞は前置詞をながくても目的語を取れる。だから前置詞が必要ない。そのため、これらは前置詞ではなく、副詞として扱われる。今回のinはuseに使われている。useは他動詞だ。だから受動態の書き方ができる。このことから、inは副詞として使われていると推測できる。

ただし、自動詞・他動詞の両方の使われ方をする動詞の場合は、前置詞・副詞の見分け方は少し複雑になる。詳細は下記リンクを参照。

* [Amazon.co.jp： 総合英語Forest 6th edition: 石黒 昭博: 本](https://www.amazon.co.jp/%E7%B7%8F%E5%90%88%E8%8B%B1%E8%AA%9EForest-6th-%E7%9F%B3%E9%BB%92-%E6%98%AD%E5%8D%9A/dp/4342010402?ie=UTF8&ref_=cm_cr_arp_d_product_top)

## カンマに続くwhich

> Your application description, which will be shown in user-facing authorization screens.

カンマがついているので非制限用法。非制限用法では、先行詞が明確になっている場合が多い。この形だと先行詞を修飾しているのではなく、補足的に説明していることに注意。先行詞ではなく、文を説明していることもある。

もし今回にカンマがないとしよう。"Your application description which ~"となると、ユーザーは認証時に見るアプリの説明と意味だが、他のアプリの説明もふくまれるかもしれない。いくつかあるアプリのうち、これらと制限するのがカンマなしの制限用法だ。カンマありの非制限用法だと、対象はすべてになる。制限する必要がないからだ。というようなことが書かれていたが、この文章だと少し通じない気もする。結局、腑に落ちなかった。制限用法自体はわかった。

カンマが付いていたら制限する必要はない。つまりすべてが対象だ。He has a dog which is black.なら黒犬を1匹持っているということで、黒以外の犬がいるかもしれない。ところが、カンマがつくと犬を1匹持っている。そしてその犬は黒色だという意味になり、他に犬がいないことになる。

カンマは口語ではわからないので、whichからは別の文の独立させてAll of themと言い換える。

非制限用法は[こちら](http://www.rondely.com/zakkaya/kuto/comm.htm)が一番分かりやすかった。カンマで囲むのは無視できる部分だ。

* [制限用法と非制限用法　その発展的学習　基礎からの英語学習の発展的学習](http://www.englishcafe.jp/english3rd/ad28.html#1)
* [関係代名詞の継続用法「コンマ + which」の訳し方｜毎日５分英文法解説](http://e-grammar.info/relative/relative_23.html)
* [非制限用法（継続用法）と制限用法（限定用法） - RAVCO](http://www.ravco.jp/cat/view.php?cat_id=4536&PHPSESSID=)

## 名詞のuse

> Your application's publicly accessible home page, where users can go to download, make use of, or find out more information about your application.

"make use of ~"のuseは名詞である。「〜を利用する」という意味だ。

* [英語教えてください。・make use of 〜 (〜を利用する)という熟語... - Yahoo!知恵袋](http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q12142710952)

## 連続するカンマ

> Your application's publicly accessible home page, where users can go to download, make use of, or find out more information about your application.

", where"のカンマは非制限用法だ。そして"download,"までが主語だ。どこまでが非制限用法か分かりづらいので", make use of"とmakeの前にカンマある。そして", or find"のカンマも文の区切りを分かりやすくするためのカンマだろう。makeもfindも主語は同じだ。

* [Amazon.co.jp： 総合英語Forest 6th edition: 石黒 昭博: 本](https://www.amazon.co.jp/%E7%B7%8F%E5%90%88%E8%8B%B1%E8%AA%9EForest-6th-%E7%9F%B3%E9%BB%92-%E6%98%AD%E5%8D%9A/dp/4342010402?ie=UTF8&ref_=cm_cr_arp_d_product_top)
* [英語の句読点 - コンマ](http://www.rondely.com/zakkaya/kuto/comm.htm)

## if any

> The organization or company behind this application, if any.
> The organization or company behind this application's web page, if any.

"if any"は「もしあるなら」という意味。（任意）と書いているようなもの。

## 和訳

> OAuth 1.0a applications should explicitly specify their oauth_callback URL on the request token step, regardless of the value given here.

訳：Callback URLの説明。OAuth1.0aアプリケションは、ここに設定した値に関わらず、リクエストトークンステップ上で、oauthのcallback urlを特定出来ないといけない。

stepがうまく訳せなかった。stepは方法、手段と解釈して和訳上は書かなくてもいいかも。「リクエストトークンで、〜特定できないといけない。」の方が自然かもしれない。

specifyとregardlessは感覚が掴みにくい単語の気がする。

> To restrict your application from using callbacks, leave this field blank.

訳：callbackをアプリケーションで制限するなら、ここは空にしなさい。

## 単語

* explicitly
* specify
* regardless
* restrict
