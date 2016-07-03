# 感想

スラスラ読めないため文章量が多く感じる。しかし、毎日読んでいるわけではないので、習慣になっていないからとも言える。

わからないところを抜き出しているが、自分で文法を調べて説明する形にした方がしっかり力がつく気がする。読む文章量は減るかもしれないが、確実に力をつける方向の方が安心する。でも、まだ読んだ量が少ないのでどれくらいの効果があるのかもわかっていない。

# 文

## SIMPLE COMMANDS & PIPELINES

> The first word is the command to be executed, and the remaining words, if any, are
 arguments to the command.

* "if any,"は初めて見た。
* "and the remaing words~"がわからない

> If a command name is given, the parameter assignments mod- ify the environment of the command when it is executed.

* 文の意味はわからるが、環境を変えるコマンド名とはどういうことかがわからない。

> A pipeline is either a simple command, or a sequence of two or more simple commands where each command is separated from the next by `|' or `|&'.

* "more simple commands where"とあるが、なぜwhereが使われているのかがわからない。分割される場所ということだと思うか、腑に落ちない。
* "the next"は何のためにあるのだろう？"the following"みたいなもの？それか隣りにある記号のおかげでということだろうか。

> The value of a pipeline is the value of the last command, unless the pipeline is preceded by `!' in which case the value is the logical inverse of the value of the last command.

> Both operators have equal precedence and are left associative.

* `&&`と`||`のことだけど、よくわからなかった。

>  If  it  does  not, the  value of the sublist is that return status, else it is the status returned by the print (almost certainly zero).

* "else"はIfの時に成立するもう一つのことということ？

# 単語

* sequence
* assignment
* interspersed
* prameter assignment
* precede
* inverse
* precedence
* associative
* whatsoever
* imply
