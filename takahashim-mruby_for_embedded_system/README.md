# mruby for embedded system

My talk description

mruby, Matz's new lightweight ruby, is suited for embedded system.
But somtimes embbeded system has too limited resources to use mruby.
I'll talk about mruby and how to use it for embedded system.

発表概要 (talk description in Japanese; optional)

mrubyこと軽量Rubyは「家電、携帯電話や自動車など」の「組込みソフトウェア開発に適用できるように
軽量化」(平成２２年度地域イノベーション創出研究開発事業採択テーマ一覧事業概要より)と言われていますが、
実際には組込みソフトウェア環境にもいろいろあるわけで、最近のかなりリッチな環境では普通に動いても、
組込みにありがちな厳しいメモリ環境で実行させるのはなかなか難しいのが現実です。

本発表では、限られた資源しか使えない環境でもmrubyを(なんとか)動かすための
工夫についてお話しします。


……という予定なんですが、今のところまだ動くようにはなっていません……。
ターゲットとしてはRAMが数10KB、FLASHが数100KBくらいの環境を想定しているのですが、現状、

- mrblib(ライブラリのうちRubyで書かれた部分)は削る
- パーサも捨ててvmだけにする
- 正規表現とかその辺もいらなさそうなものは削る
- コンパイルオプションをいじってバイナリを小さくする

くらいの工夫をしても、そもそも現状ではへーきでmallocをばんばん発行するつくりになっている
ので、メモリが足りなくて死んでしまったりします。おそらくはコアのところをいじらないと厳しそうです。

今のところ考えているのが、eLuaとかPyMiteとかを参考に以下のような改造をしてみる予定です。
- Flashに載せる場合にはRAMを使わずFlashのみでいじれるようになんとかする
- メソッドテーブルとインスタンス変数をハッシュじゃなくて別のデータ構造にして省メモリ化

この辺りについて、うまくいくかどうかも合わせて発表したいと思います。

- Preferred presentation day: [no preference, but 9/14 or 9/15 are better]
- Presentation language: [Japanese]

## Masayoshi Takahashi + Yurie Yamane
## 高橋征義、山根ゆりえ

## Ruby no Kai, Tatsu-zine Publishing Inc.
## 日本Rubyの会、株式会社達人出版会

My bio (required)

Masayoshi Tkahashi is an old-timer rubyist since (about) 1997.
The founder and Representative Director of Nihon Ruby no Kai.

- [My website](http://tatsu-zine.com)
- [My twitter](https://twitter.com/#!/takahashim)
- [Past talk slides](http://slideshare.net/takahashim)
- [Past talk video](http://www.example.org)
