# A few things I learned from XtAddInput
# XtAddInputから学んだこと。

My talk description
I've written applications using GUI and socket communication techniques for about 20 years.
In good old Xt, XtAddInput() is a primitive to append functionalities of asynchronous communication into GUI.
XtAddInput() calls functions back every time that a file-descriptor you are interested in becomes readable/writable.
Although it makes asynchronous communication easy that passing a non-block file to XtAddInput(),
in fact, there are various traps about that.

I will show you the mechanism of asynchronous communication and the pattern of the problem in Xt, and how I solve the same problem in dRuby.
I will also describe the strategy of Drip that gives you the unordinary viewpoint of the general problem of communication programs.

発表概要 (talk description in Japanese; optional)
GUIとソケット（などの）通信を絡めたアプリケーションを20年ほど書いている。
古き良きXtにおいて、GUIに非同期通信の機能を追加するプリミティブがXtAddInput()である。
XtAddInput()は関心のあるファイル記述子がreadable/writableになるたびにコールバックする。
XtAddInput()にノンブロックモードのファイルを与えることで容易に非同期通信ができるわけだが、実際にはさまざまな罠が待ち受けている。

本発表ではXtでの非同期通信のしくみと問題のパターンを示しつつ、dRubyというライブラリの実装を例にRubyで同じ問題をどのように解いたか、また、こういった通信プログラム一般の問題に斜め上の視点を与えるDripの戦略についても説明する。

最近は再度、モノスレッド、コールバックスタイルのノードなんとか（すみません詳しく知りません）というしくみが流行っているらしいので、若者の話に混ぜてもらいたいです。


- Preferred presentation day: [9/14 | 9/15] (最終日は体力的にあやしいです）
- Presentation language: 日本語

## Masatoshi SEKI
## 関将俊

## tochigi test no kaigi
## とちぎテストの会議

a Ruby committer and an author of several Ruby standard libraries including dRuby, eRuby, and Rinda. He's an expert in object-oriented programming, distributed systems, and eXtreme programming. His favorite Ruby methods are "method_missing" and "inject".
プロフィール (bio in Japanese; optional)

- [My website](https://github.com/seki)
- [My twitter](https://twitter.com/#!/m_seki)
- [Past talk slides](http://www.example.org)
- [Past talk video](http://www.example.org)
