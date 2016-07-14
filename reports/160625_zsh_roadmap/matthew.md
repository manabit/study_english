---
layout: post
title: zsh roadmapを読む
date: 2016-06-27 02:23:00 +0900
author: matthew
tags: [read]
---

# Zsh Roadmap

わかりやすい英語だった。英語的にはあなり得るものがなかったけれど、`zsh` 方面でずっと欲しかったものを知ることができたのでとても満足。

## replace-string

コマンドライン上の文字列を置換できるファンクション。カーソルキーでの移動が結構だるいので、この機能は助かる。

```
autoload -U replace-string
zle -N replace-string
bindkey "^[r" replace-string
```
