# Zsh Roadmap

わかりやすい英語だった。英語的にはあなり得るものがなかったけれど、`zsh` 方面でずっと欲しかったものを知ることができたのでとても満足。

## replace-string

コマンドライン上の文字列を置換できるファンクション。カーソルキーでの移動が結構だるいので、この機能は助かる。

```
autoload -U replace-string
zle -N replace-string
bindkey "^[r" replace-string
```
