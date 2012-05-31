# Distributed RSpec
# 分散 RSpec

I will introduce a library for distributed execution your spec files.
This library has two strategies in order to distribute spec files.
One divides spec files into some groups and distributes them.
The other distributes every code example following the producer-consumer way.

I will also describe the usage of the library in COOKPAD.
COOKPAD develops large Rails applications including about 800 models.
I will demonstrate the effectiveness of the library by showing the time saved by a COOKPAD CI job by using this library.

スペックファイルを分散実行するためのライブラリを紹介する。
このライブラリは、スペックファイルの分配方法を2つ持っている。
ひとつは、スペックファイルを幾つかのグループへ分割し、それらのグループを分配する。
もうひとつは、Producer-Consumer パターンの方法に従って、コード例毎に分配する。

更に、このライブラリをクックパッド株式会社での使用例を述べる。
クックパッドは、約800のモデルを持つ巨大な Rails アプリケーションを幾つか開発している。
クックパッドの CI ジョブが消費する時間がこのライブラリによって減少したことを示すことで、
このライブラリの有効性を説明する。

- Preferred presentation day: no preference
- Presentation language: Japanese with slides written in English

## Kenta Murata
## 村田賢太

## COOKPAD Inc. && Asakusa.rb && Ruby Sapporo
## クックパッド株式会社 && Asakusa.rb && Ruby 札幌

Kenta Murata is an Engineer at COOKPAD in Tokyo, Japan. He is also a Ruby committer maintaining the bigdecimal library and OS X support.

村田賢太。クックパッド株式会社のソフトウェアエンジニア。CRuby のコミッタであり、bigdecimal ライブラリのメンテナンスと OS X プラットフォームサポートを担当している。

- [My website](http://mrkn.jp)
- [My twitter](https://twitter.com/#!/mrkn)
- [My speakerdeck](http://speakerdeck.com/u/mrkn)
- [My Slideshare](http://slideshare.net/mrkn)
- [My talk video in RailsConf2012](http://www.confreaks.com/videos/909-railsconf2012-chanko-how-cookpad-safely-releases-multiple-feature-prototypes-in-production-for-test-segments-of-their-15-million-engaged-users)
- [My talk video in RubyConf2011](http://www.confreaks.com/videos/698-rubyconf2011-float-is-legacy)
