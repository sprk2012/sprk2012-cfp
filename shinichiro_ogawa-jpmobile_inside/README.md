# The inside of jpmobile

Jpmobile is a essential Rails plugin for mobile phones in Japan, including Feature Phone and Smart Phone.
Recently, some features are added; sending emoticon email and decomail, tablet classes.

In this presentaion, I will introduce the inside of jpmobile. The main topics are the followings:

* Cookie and session store manipulation
* Character encoding and emoticon conversion
* sending/receiving emails with emoticon, and decomail
* Considerations about testing

Jpmobileは携帯電話、いわゆるガラケーだけではなく、スマホ対応サイトを製作する上で必須のプラグインです。
最近ではデコメの送信や絵文字メールの送受信、またタブレットクラスが導入され、タブレットにも対応しています。

本発表では、
このjpmobileの内部について、どのように実装され動作しているのかを具体的に紹介します。
クッキーやセッションストアに対する処理や、
文字列・絵文字の変換処理、またメールの送受信に関する処理から、
テストの際に気をつけることまで、
様々な観点からjpmobileを紹介します。

- Preferred presentation day: no preference
- Presentation language: Japanese

## Shin-ichiro OGAWA
## 小川 伸一郎

## Tokyu.rb
## Tokyu.rb

Rails Programmer. jpmobile developer. Ph.D. Physics.
Railsアプリケーション開発者。jpmobileを開発しています。

- [My website](http://stnard.jp)
- [My twitter](https://twitter.com/#!/conceal_rs)
- [Past talk slides](http://www.slideshare.net/rust/, https://speakerdeck.com/u/ogawa)
- [Past talk video](http://www.nicovideo.jp/watch/sm11901698, http://vimeo.com/26540910)
