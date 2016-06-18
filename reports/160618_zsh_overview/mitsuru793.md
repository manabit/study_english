# 感想
まだ全部読んでいない。

zshの1ページの最初にどういうメーリングリストがあるかが書いてあった。これを見て、OSSの開発がどういう体系でやりとりされているのかが、なんとなく想像ができた。今のところ詰まる部分はあるが、全体としては読めている。細かい部分でわからないところがあるので、そこを潰したいところ。そうじゃないと、概念を説明された時にわからないから。また、具体的な例題を出されても理解できない可能性がある。

zshのmanを読むこと自体は実用性が高いと感じた。manのどこに何が書いてあるかがすぐ分かれば、ネット調べる時間が大幅に短縮できる。よくオプションと、condition, ファイル修飾子をググってしまっていたので、それらはすぐ引けるようにしたい。

# 文

> The sites marked with (H) may be mirroring ftp.cs.elte.huinstead of the primary site.

(H)とはどういうことだろう？Hから始まる、つまりhttp(s)ということ？

> All submissions to zsh-announce are automatically forwarded to zsh-users.

zsh-announceへ連絡は、自動でzsh-usersに転送される？

## THE ZSH USERGUIDE
> A userguide is currently in preparation

userguideはまだ準備中ということ？

> It is intended to complement the manual, with explanations and hints on issues where the manual can be cabbalistic, hiero-graphic, or downright mystifying (for example, the word `hierographic' does not exist).

* cabbalisticがわからない。whereはissuesをどういう風に修飾しているのだろう？「最初の完全なマニュアルを指している」ということはわかるが、with~がわからない。

> At the time of writing, chapters dealing with startup files and their contents and the new completion system were essentially complete.

スタートアップのファイルと、そのコンテンツと、新しい補完システムのチャプターは基本的に完成している。

## INVOCATION

> The following flags are interpreted by the shell when invoked to determine where the shell will read commands from:

invoked to~がうまく訳せない。

> If any further arguments are given, the first one is assigned to $0, rather than being used as a positional parameter

TODO

> If the option PATH_SCRIPT is set, and the file name does not contain a directory path (i.e. there is no `/' in the name), first the current directory and then the command path given by the variable PATH are searched for the script.

TODO

# 単語

* a host of other features
* resembles
* coordinated
* cabbalistic
* submissions
* preparation
* hieroglyphic
* hieroglyphic
* downright
* mystifying
