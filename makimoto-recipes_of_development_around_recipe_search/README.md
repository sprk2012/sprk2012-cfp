# Recipes of Development around Recipe Search
# レシピ検索開発のレシピ

"Search" is ranked as one of most important factors in large-scale web services.
At COOKPAD, recipe search is also important, and we continue improving recipe search system for people searching for recipes to cook.

We switched COOKPAD's search backend from MySQL/Tritonn to Apache Solr in 2010.
This renovation brought us more powerful functions and seeds of novel services.
However, development with new search backend is required extremely-different techniques from those of ordinary web development.

In this presentation, we propose pragmatic methods to solve this problem.
There are two viewpoints:

1. How to build new search system in a large-scale web service.
2. How to make it possible to do more challenging service developments around search for ruby/rails engineers (unfamiliar with search techniques).


大規模ウェブサービスにおいて検索は重要な要素に位置付けられる。
月間1500万人が利用するクックパッドにおいても同様であり、日々レシピを探すユーザの要望に答えるレシピ検索システムの開発を続けている。

クックパッドは2010年に MySQL/Tritonn から Apache Solr にレシピ検索バックエンドの大規模な刷新を行ない、それによってサービス開発におけるより多様なチャレンジが可能となった。
しかし、一般的な RDBMS を用いた Ruby on Rails での開発とは異なるノウハウが必要なために対応できる技術者が限られ、そこがボトルネックとなり開発速度が停滞するという問題があった。

本発表では、「いかにして大規模サービス上で検索機能を構築するか」、そして「いかににして (検索を専門としない) 技術者が検索を扱ったサービス開発を積極的に行なえるようにするか」という2つの観点で、大規模ウェブサービスにおける検索機能の開発について実践的な方法を紹介する。

- Preferred presentation day: no preference
- Presentation language: Japanese (slides in English)

## Shimpei Makimoto
## 牧本 慎平

## COOKPAD Inc.
## クックパッド株式会社

Shimpei Makimoto is a software engineer.
He is responsible for search service infrastructures at COOKPAD Inc., Tokyo, Japan.
He loves sushi, autumn, glitch and coding.

牧本慎平。1983年熊本生まれ。ソフトウェアエンジニア。クックパッド株式会社技術部に属し、検索の基盤技術に責任を負う。
寿司と秋とグリッチとコードを書くことを愛す。

- [My blog] (http://makimoto.hatenablog.com)
- [My twitter] (https://twitter.com/makimoto)
- [My GitHub] (https://github.com/makimoto)
