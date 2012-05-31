# Heckle: we break code!

Heckle evaluates the thoroughness of your unit tests. It does this by making modifications to your production code, and seeing if those modifications cause any unit test failures. For example, it will turn ifs into unlesses, and replace strings and numbers with other strings and numbers or nil, or even delete lines of code! If no failures occur when your unit tests are run on the modified production code, then that code isn't being tested enough.

In this talk, I will discuss how Heckle has been useful to me in maintaining a one person Ruby project that's been worked on for three years, has 15K lines of production code, 11K lines of test code, and varying degrees of unit testing.

- Preferred presentation day: no preference
- Presentation language: English, hopefully with Japanese subtitles.

## Andrew Grimm
## アンドリュー グリム

## University of New South Wales.
## ニューサウスウェールズ大学 (UNSW)

Andrew Grimm is a bioinformatician at the University of New South Wales in Sydney, Australia. He came across Ruby while using Rails at his previous job associated with the Encyclopedia of Life, but now specialises in Plain Old Ruby Objects.

He has worked on various projects outside of work. One analyzed why you always end up at "Philosophy" in Wikipedia. Another was a fork of Heckle in which zombies eat your brains unless your unit tests can kill them all. At RubyKaigi 2011 he demonstrated the Small Eigen Collider, which generates random Ruby code that can be run under different implementations of Ruby to check for inconsistencies or bugs.

ニューサウスウェールズ大学(シドニー)のバイオインフォマティクスの研究者。
Encyclopedia of Life関係の仕事でRailsを使ったことをきっかけにRubyと出会い、今はPlain Old Ruby Objectsを専門としている。

これまでに、Wikipediaのリンクを辿っていくと最終的に"Philosophy"のページに
到達するという事象についての分析や、Heckleというテストライブラリのフォークなどを行ってきた。
RubyKaigi 2011では、ランダムなRubyコードを生成することでRubyの様々な処理系におけるバグを見つけるための
Small Eigen Colliderというライブラリについて発表した。

- [My website](https://andrewjgrimm.wordpress.com/)
- [My twitter](https://twitter.com/#!/andrewjgrimm)
- [Past talk slides](http://www.slideshare.net/agrimm)
- [Past talk videos](https://vimeo.com/channels/332579)
- [Past t-shirt](http://www.zazzle.com/small_eigen_collider_japanese_and_english_text_tshirt-235235813665782515)
