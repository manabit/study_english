---
layout: post
title: OpenIDとOAuthの違いをStackOverflowで調べる
date: 2016-07-20 20:16:00 +0900
author: mitsuru793
tags: [read]
---

[What's the difference between OpenID and OAuth? - Stack Overflow](http://stackoverflow.com/questions/1087031/whats-the-difference-between-openid-and-oauth?answertab=votes#tab-top)

# 感想

全部を読んだわけではない。votesが高い順から読んでいった。英文を読んでペーストしてから、まとめて調べていたがそうすると前後の内容を忘れてしまっている。長くなりそうなときは、前から一文ずつ和訳していくと確実性がある。しかし、その必要が無いぐらいにさっと読めるようになりたい。和訳を書いていくと精読ができるので、英語を読む感覚を考えることができる。

## OpenIDとOAuthの違い

OpenIDは認証、つまりユーザーが自分自身であることを証明するために使う。OAuthは認可、つまりユーザーのデータ、リソースへのアクセス権を得るために使う。OAuthのアクセス権としてアクセストークンが使われる。OpenIDはディスカバリーがあるので、前もってプロパイダーを決めたり、ハードコーディングする必要はないが、OAuthだとディスカバリーがないのでその必要がある。ユーザーはOAuthだと、サイト側前もって決めたプロパイダーしか使えないが、OpenIDならユーザーが使用するプロパイダーを決めることが出来る。

# 学習記録

## so thatの4つの用法

このsoは「そのように・とても」という副詞だ。副詞の時は3つ、さらに接続詞の時に1つ、合計4つの用法がある。前者は目的、程度・結果、様態。後者は単なる結果。

* [けれども今回はカンマ（,）がある。soとthatが隣り合っていて、一見すると「目的のso that」のようだが](http://eigo-box.jp/grammar/so-that/)
* [so that構文　「3分で分かる」３つの意味・使い方｜受験のミカタ](http://juken-mikata.net/how-to/english/so-that.html)

### 目的

目的を表すso thatのsoは副詞だ。「そのように」という意味だ。前の文の目的を表している。「そのように」とはどのように？ということで、soの後にthatが続き目的が述べられる。

この時that節では助動詞のmay, will, canが形式的に使われる。形式的なのでこの助動詞は訳す必要はない。助動詞を伴うのは、「〜するために」という目的を表現すると未来っぽいからだ。

このthat節は副詞節だ。名詞節ではない。理由は副詞のsoと一緒に使うから。この時、soが省略されることもある。thatで目的だけ表すのだ。thatが副詞節の理由はsoと一緒だからと述べたが、前文がSVだからというのもある。SVと、文が完成しているなら、後ろに続くのは修飾語Mだ。修飾語になる品詞は、形容詞と副詞だけ。副詞節なので、thatは直前の目的語ではなく動詞を修飾している。名詞を修飾するのは基本、関係詞節だけ。

目的のso thatを不定詞に置き換えると、in order to / so as toになる。どちらも目的を表している。

### 程度・結果

so tall that S Vのように、soの後に形容詞が続く場合、このsoは「そのように」という意味ではなく、「それくらい・とても」という程度を表す副詞になる。それくらい高いと言われて、それとはどれなのだろう？それを表すためにthat節を使うのだ。

程度・結果のso thatを不定詞で書き換えると、tall enougth to / so tall as toになる。

目的のso thatも、程度・結果のso thatのthat節は副詞節だ。だが、修飾先が違う。前者は動詞だが、後者は形容詞だ。

### 様態

soとthatの間に形容詞ではなく、過去分詞が置かれたら、それは様態を表す。このsoは目的の時と同じで、「そのように」を表す。そのようにとはどのように？それをthat節で述べている。ここは程度・結果と同じ考え方だ。

### 単なる結果

so thatの直前にカンマが置かれる場合だ。これは目的のso thatみたいに動詞にはかけない。前の文を踏まえて述べているのだ。これは非制限用法だと同じだと思う。口語ではthatは省略されることがある。するとsoは等位接続詞のようになる。


## see over

> I can see over OpenID is that you have to implement it on a per-site basis.

see overは見まわる・調べるという意味。群動詞の一つ。

## 関係代名詞

関係とは先行詞とwhoなどの代名詞を関係づけることから、代名詞はwhoなどが名詞として働いていることから、そう呼ばれている。go to the cityのように「自動詞+前置詞」の場合はgo thereとthereに置き換えることができ、このthereをwhereにして前に持ってくる。この時whereを先行詞を説明するだけでなく、副詞としての働きも持つため関係副詞と呼ばれる。

* [Amazon.co.jp： 総合英語Forest 6th edition: 石黒 昭博: 本](https://www.amazon.co.jp/%E7%B7%8F%E5%90%88%E8%8B%B1%E8%AA%9EForest-6th-%E7%9F%B3%E9%BB%92-%E6%98%AD%E5%8D%9A/dp/4342010402?ie=UTF8&ref_=cm_cr_arp_d_product_top)

### 先行詞とは？

先行詞とは関係代名詞によって説明される名詞のこと。

### wahtは先行詞がない

whatに「〜すること（もの）」という意味を表す。なので先行詞が必要ない。続く関係詞節はこのwhat自体を説明しているのだ。

## 和訳

### よくわからないもの

> The term federated is critical here because the whole point of OpenID is that any provider can be used (with the exception of white-lists).

ここでは連合という用語が重要です。なぜならOpenIDの全てのポイントとはプロパイダーが使われることだからです。

because以降がわからない。

> In OAuth the user authorizes access to their protected resources and in OpenID, to their identity. But that's all they share.

OAuthではユーザーはリソースへのアクセスを許可し、OpenIDでは識別子へのアクセスを許可する。これらは全て共有している。

2文目のBut~がよくわからない。

> But if you have authorized twitter to take actions on your behalf, that implies you are the person who you say you are - so it combines both?

でもtwitterに代理アクションを許可したら、それはあなたが貴方自身であると言っている。これは両方を束ねる？

> In OAuth we can restrict what information is flowing from identity provider (facebook) to service provider(stackoverflow).

関係代名詞節は名詞が欠けていない。information which isじゃいけないのだろうか？

> i.e. One shows their passport at the airport to authenticate (or prove) the person's who's name is on the ticket they are using is them.

who's以降がよくわからない。

> Use OpenID if your users are neckbeards that run their own OpenID providers because they "don't want anyone else owning their identity".

neckbeardsの意味がわからない。

### 訳せたもの

> OpenID is about authentication (ie. proving who you are), OAuth is about authorisation (ie. to grant access to functionality/data/etc.. without having to deal with the original authentication).

OpenIDは誰かを証明する認証で、OAuthは本来の認証なしで、データへのアクセスを許可してもらうもの。

> OAuth could be used in external partner sites to allow access to protected data without them having to re-authenticate a user.

OAuthはユーザを再認証することなくデータへのアクセス許可をするために、外部のパートナーサイトで使うことが出来る。

> OpenID was created for federated authentication, that is, letting a third-party authenticate your users for you, by using accounts they already have.

OpenIDは連合認証のために作られました。サードパーティーに所持しているユーザーアカウントを使って認証してもらいます。

> You don't need to pre-choose or negotiate a deal with the providers to allow users to use any other account they have.

他のアカウントを使うことユーザーに許可するために、プロパイダーと交渉したり、前もって選択する必要はありません。

> OAuth was created to remove the need for users to share their passwords with third-party applications.

OAuthは、サードパーティ製のアプリケーションにパスワードを渡す必要を、ユーザーから無くすために作られました。

>  It actually started as a way to solve an OpenID problem: if you support OpenID on your site, you can't use HTTP Basic credentials (username and password) to provide an API because the users don't have a password on your site.

(OAuth)はOpenIDの問題を解決する方法としてスタートしました。OpenIDに対応しているサイトでは、HTTP Basic認証をAPIを提供するために使うことができません。なぜならユーザーがそのサイトのパスワードを持っていないからです。

> The problem is with this separation of OpenID for authentication and OAuth for authorization is that both protocols can accomplish many of the same things.

問題は、認証のためのOpenIDと、許可のためのOAuthは分かれていますが、たくさんの同じ部分があることです。

> They each provide a different set of features which are desired by different implementations but essentially, they are pretty interchangeable.

これらは実装が違うため、違う内容を提供することが望まれていましたが、基本的に同じ機能を持っているので交換することが可能です。

>  At their core, both protocols are an assertion verification method (OpenID is limited to the 'this is who I am' assertion, while OAuth provides an 'access token' that can be exchanged for any supported assertion via an API).

根底としては、両方のプロトコルはアサーションの検証メソッドです。（OpenIDは自分が誰かを調べるアサーションに限定され、OAuthはAPIをとして対応しているアサーションと交換できるアクセストークンを提供するだけです。）

> Both protocols provide a way for a site to redirect a user somewhere else and come back with a verifiable assertion.

両方のプロトコルは、ユーザーを他の場所にリダイレクトして、証明できるアサーションと一緒に戻ってくる方法を、サイトのために提供します。

> OpenID provides an identity assertion while OAuth is more generic in the form of an access token which can then be used to "ask the OAuth provider questions".

OpenIDは識別子のアサーションを提供する一方、OAuthはプロパイダを尋ねるのに使われるアクセストークン形式の中で一般的。

> the most important feature of OpenID is its discovery process.

OpenIDで一番重要な項目はディスカバリーだ。

> OpenID does not require hard coding each the providers you want to use ahead of time.

OpenIDは前もって使いたいプロパイダをハードコーディングする必要はない。

> Using discovery, the user can choose any third-party provider they want to authenticate.

ディスカバリーを使えば、ユーザーは認証に使いたいサードパーティのプロパイダを選択することができる。

> This discovery feature has also caused most of OpenID's problems because the way it is implemented is by using HTTP URIs as identifiers which most web users just don't get.

ディスカバリーはOpenIDの一番の問題だ。この方法はウェブユーザが持っていない識別子であるHTTP URIを使って実装されているからだ。

> Other features OpenID has is its support for ad-hoc client registration using a DH exchange, immediate mode for optimized end-user experience, and a way to verify assertions without making another round-trip to the provider.

OpenIDはDH交換を使ってad-hocクライアント登録をサポートしている。即時モードはエンドユーザーの体験を最適化する。他のプロパイダを往復する必要なく、アサーションを検証する方法にも対応している。

> the most important feature of OAuth is the access token which provides a long lasting method of making additional requests.

OAuthで一番重要な項目はアクセストークンだ。これは追加リクエストを長い間、作り続ける方式だ。

> Unlike OpenID, OAuth does not end with authentication but provides an access token to gain access to additional resources provided by the same third-party service.

OpenIDと違い、OAuthは認証だけでは終わりません。同じサードパーティ製のプロパイダから提供される追加リソースへのアクセス権を取得するために、アクセストークンを提供します。

> However, since OAuth does not support discovery, it requires pre-selecting and hard-coding the providers you decide to use.

しかし、OAuthはディスカバリーに対応していないので、使いたいプロパイダをハードコーディングするか、前もって選択しておく必要があります。

> A user visiting your site cannot use any identifier, only those pre-selected by you.

サイトに訪問したユーザーは、いくつかの識別子は使えません。前もってあなたが選択したもののみです。

> Also, OAuth does not have a concept of identity so using it for login means either adding a custom parameter (as done by Twitter) or making another API call to get the currently "logged in" user.

OAuthはログインするための識別子という概念も持ち合わせていない。そのためTwitterのようにカスタムパラメーターを使うか、他のAPIを使って現在ログインしているユーザーを取得することになる。

> The two protocols share a common architecture in using redirection to obtain user authorization.

この2つのプロトコルは、ユーザの許可を得るために使うリダイレクトの中では、同じアーキテクチャを共有している。

> Each protocol has a different way of calculating a signature used to verify the authenticity of the request or response, and each has different registration requirements.

リクエストやレスポンスの認証を検証するのに使う署名を計算する方法は、それぞれ違う。登録に必要なものは異なっている。

> Thank you, I was having a lot of trouble with the words 'Federated' and 'discovery' in this context and the answer perfectly clears it up.

ありがとう、Federatedとdiscoveryで詰まっていたけど、回答のおかげで完全に理解できたよ。

> A good answer, but I'm slightly confused with "The exception of white-lists". Do you white list exclusions?

良い回答ですが、"ホワイトリストの例外"がで混乱しています。ホワイトリスト除外とは何ですか？

> OAuth does not end with authentication but provides an access token to gain access to additional resources provided by the same third-party service. Not exactly. From rfc6749:

OAuthは認証で終わらず、サードパーティのリソースへのアクセスできるようになるアクセストークンを提供します。確実ではありません。rfc6749を参照。

> The authorization server may be the same server as the resource server or a separate entity. A single authorization server may issue access tokens accepted by multiple resource servers.

認可サーバはリソースサーバや分離エンティティと同じサーバかもしれない。シングル認可サーバは様々なリソースサーバに対応しているアクセストークンを発行します。

> OpenID is (mainly) for identification/authentication, so that stackoverflow.com knows that I own chris.boyle.name (or wherever) and therefore that I am probably the same person who owned chris.boyle.name yesterday and earned some reputation points.

OpenIDは識別と認証がメインだ。stackoverflow.comが、私がchris.boyle.nameを持っていることを知っているなら、昨日chris.boyle.comを所持していた人と私がおそらく同じであることと判断する。こうして信頼度を稼ぐ。

> OAuth is designed for authorization to take actions on your behalf, so that stackoverflow.com (or wherever) can ask permission to, say, Tweet on your behalf automatically, without knowing your Twitter password.

OAuthは代理にアクションするための認証用に設計された。だからstackoverflow.comは、代わりにパスワードなしで自動的にツイートできるかを尋ねることができる。

> It sounds like with oauth, the 3rd party site would get a token which it could use to perform actions on the oauth provider's site (say, tweet on your behalf), but getting the user's identity (username) isn't built in to the protocol so providers have to add that as a custom resource.

OAuthと一緒は、サードパーティのサイトがOAuthプロパイダーのサイト上のアクションを行うために使うトークンをゲットするみたいだ。ユーザの識別子を得ることは、そのプロトコルに組み込まれていない。だからプロパイダーはカスタムリソースとしてそれ（トークン？）を追加する必要がある。

> Is'nt that the case that Stack Overflow or other websites that belong to stackoverflow like serverfault use OAuth for new user signup using google or facebook and OpenID for signup using other website of their domain like serverfault or askubuntu.

Stack Overflowやそれに属するserverfaultが、OAuthを新規ユーザーがgoogleやfacebookで登録するのに使ったり、OpenIDをseverfaultやaskubuntuのような他のサイトのドメインを使って登録するために使う場合ではない。

> In OpenID we simply give a certificate symbolizing the person as legal and give access to whole database.

OpenIDでは、正当な人を表した証明書と、データベース全体へのアクセス権をシンプルに渡します。

> Since stackoverflow or askubuntu belong to same domain they can exchange certificates with full access to user databases.

stackoverflowやaskubuntuは同じドメインに属しているので、ユーザーのデータベースへフルアクセスできる証明書を交換することが出来ます。

> Shouldn't there be one more step in the OAuth example where the android app uses the valet key to communicate with google to find the users identity?

OAuthの例には、Androidアプリがユーザー識別子を見つけるためにグーグルとvalet keyで通信するようなステップは無いの？

> I think the missing step should be more generic. I.e. it's not so much about identity as it is about data that can be provided via API. I.e. your Google photos or your G-Mail emails that android app could use for whatever purposes. Of course, identity could be accessible via API.

もっと一般的なステップがないのはミスだと思う。APIを通してデータを提供する識別子は十分ではない。Androidアプリで色々なことに使われるGoogle photosやG-mailとかね。もちろんAPIを通して識別子にアクセスすることは可能だよ。

> Used for delegated authorization only -- meaning you are authorizing a third-party service access to use personal data, without giving out a password. Also OAuth "sessions" generally live longer than user sessions. Meaning that OAuth is designed to allow authorization

OAuth:認可を委任するだけのために使われます。これが意味することは、サードパーティのサービスに個人データへのアクセス権を、パスワードを与えずに認可するということです。またOAuthセッションは一般に、ユーザーセッションより長いです。これが意味することは、OAuthは権限を許可するためにデザインされているということです。

> i.e. Flickr uses OAuth to allow third-party services to post and edit a persons picture on their behalf, without them having to give out their flicker username and password.

FlickrはOAuthを使って、外のサービスに投稿や人物写真の編集などを代わりに行えるようにしています。この時、Flickrのusernameとpasswordを教える必要はありません。

> Used to authenticate single sign-on identity. All OpenID is supposed to do is allow an OpenID provider to prove that you say you are. However many sites use identity authentication to provide authorization (however the two can be separated out)

OpenID: シングルサインオンの識別子を証明するために使います。すべてのOpenIDはOpenIDプロパイダーに貴方自身であることを証明することが可能です。しかしたくさんのサイトは、認可を提供するために認証IDを使っています。この2つは分けることが可能です。

> Use OAuth if your users might just want to login with Facebook, or Twitter.

OAuthはFacebookやTwitterでログインしたい時に使う。

## 単語

### 記事

* authentication
* authorisation
* comparison
* downside
* ensure
* confusion
* eliminate
* federate
* negotiate
* separation
* accomplish
* interchangeable
* immediate
* optimize
* gain
* signature
* verify
* authenticity
* slightly
* exclusions
* issue
* generic
* behalf
* imply
* combine
* serverfault
* restrict
* flowing
* service
* certificate
* symbolize
* legal
* notarize
* referral
* valet

### その他

* state
* genuine
* definite
* allegedly
* assault
* platonic
* imitation
* sincere
* arrangement
* firm
* proof
* confident
* noticeable
* involve
* preparation
* suitable
* consequence
* discipline
* occasion
* strict
* qualification
