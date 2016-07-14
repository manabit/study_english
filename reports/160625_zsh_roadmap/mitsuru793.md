---
layout: post
title: zsh roadmapを読む
date: 2016-06-28 10:03:00 +0900
author: mitsuru793
tags: [read]
---

# 感想

よくわからない部分が多かった。読むの詰まるからもっとスラスラ読みたい。zshのマニュアルはかなりの量なので、これを通して英語アレルギーを克服したい。Lang-8など、外国人との会話での英語はアレルギーはなくなってきたと思うが、技術英語だと別なものな感じがした。

* コマンドラインについて知りたいならzshzleを、環境変数について知りたいならzshparamを読むと良い。
* historyファイルの読み書きはインタラクティブシェルからのみ。スクリプトから機能しない。
* `~/.abook/addressbook`からメールアドレスを補完する。

# 文

## NAME

> informal introduction to the zsh manual The Zsh Manual, like the shell itself, is large and often complicated.

* "the zsh manual The Zsh Manual,"はピリオドのつけ忘れ？文は繋がっているのか？
* "like the shell itself"は直訳はできるけど、マニュアルがシェルみたいとはよくわからない。

> This section of the manual provides some > pointers to areas of the shell that are likely to be of particular interest to new > users, and indicates where in the rest of the manual the documentation is to be found.

* 末尾の"is to be found"は見つかった残りのドキュメントという意味なのかな？ニュアンスがわからない。

## WHEN THE SHELL STARTS

> If no personal initialization files exist for the current user, a function is run to help you change some of the most common settings.

* "help you change some~"のchangeの前には関係代名詞の省略があるのかな？
* "If~"は訳せるが、カンマ以降が訳せない。

> The function is designed to be self-explanatory.

* ガイドみたいなのが出るということ？

# INTERACTIVE USE

> Note in particular that for combining characters to be handled the option COMBINING_CHARS needs to be set.

* 主語は"the option COMBINING_CHARS"なのだろうか？構造がわからないため訳しづらい。

> Note in particular that for combining characters to be handled the option COMBINING_CHARS needs to be set.

* ここからがうまく訳せない。

# Competion
> Anything that can be written in or glued together with zsh can be the source of what the line editor offers as possible completions.

* 主語は"together with zsh"までかな？そして動詞は"can be"になるのか？構造と意味がちょっとわからない。
* "source of what"って何だろう？

> (named after the builtin command that serves as its complete and only user interface),

* 完成後、ユーザーインターフェースだけに提供された後？意味がよくわからない。

> it is therefore to be preferred.

* ??

> configuring what the line editor considers a word when moving or deleting by word

* "considers"とか"what"がわからない。

# 単語

* complicate
* likely
* explanatory
* substantially
* explicitly
* retain
* transparently
* degree
* variable
* organize
* facility
* composed
* by means of
* cover
* aspect
* acquaint
* qualify
* encounter
