# 英語勉強会

[![Join the chat at https://gitter.im/mitsuru793/study_english](https://badges.gitter.im/mitsuru793/study_english.svg)](https://gitter.im/mitsuru793/study_english?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# 参加の仕方

`report/`にテーマごとにディレクトリがあります。ない場合は作成してください。そこに`自分のGithub.username.md`というmarkdownを置いて下さい。何を書くかは決めていませんが、例を挙げておきます。

* 気になった文章
* 気になった単語
* 読んだ感想（英語について、技術について）

リポートを書かずに、取り組んだことだけを表す場合は、空の`md`ファイルを置いて下さい。自分の名前の`md`ファイルがあれば取り組んだことになります。

# 各テーマの履歴

history.ymlにまとめてあります。

## 題材候補

[trelloに興味あるテーマをまとめています](https://trello.com/b/owyxuJsx/-)

# 記述フォーマット

jekyllで管理するためにYaml Front Matterを付けて下さい。プロパティは下記の通りです。

```yaml
---
layout: post
title: zsh roadmapを読む
date: 2016-06-28 10:03:00 +0900
author: mitsuru793
tags: [read]
---
```

現在時刻の挿入は`.vimrc`に下記を記述すると、ノーマルモード時にF6で入力できるようになります。

`nmap <F6> <ESC>i<C-R>=strftime("%Y-%m-%d %H:%M:%S +0900")<CR>`
