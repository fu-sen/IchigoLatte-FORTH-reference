## IchigoLatte FORTH リファレンス一覧

IchigoLatte FORTH で使用できる命令を一覧しています。

Download ZIP でファイル一覧をダウンロードできます。\
GitHub・Git を使っている場合は Clone を使っても良いでしょう。

RAW で参照した場合、またファイルをダウンロードした場合\
.txt ファイルは文字コード UTF-8、改行コード CR+LF になります。\
Windows ではメモ帳を使用する事が可能です。

* イチゴジャム レシピ (公開元) https://15jamrecipe.jimdofree.com/

[IchigoLatte](http://ichigolatte.shizentai.jp/) は [株式会社ナチュラルスタイル](https://na-s.jp/) の登録商標です。

### FORTH について

FORTH はスタックという概念を持つ言語です。

スタックは積む場合、右へ追加されていき、\
一番右が一番最初に得られる値になります。\
これを「スタック 1 つ目」と表記しています。\
3 4 5 となる場合、最初に得られる スタック 1 つ目 は 5 となります。

数値 は **その値 をスタックへ積む** という意味になります。
