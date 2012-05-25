# My talk title
# DCI and the application builds our mental models

## My talk description

(I'd like to be going to improve and push this by 'the judgement day' )

[DCI(Data, Context and Interaction)](http://en.wikipedia.org/wiki/Data,_Context,_and_Interaction) is a "paradigm" in object-oriented application design. DCI is getting popular in some object-oriented proponent Rubyists these days. In this talk, we'll discuss:

- Why object-oriented proponent Rubyist mention DCI?
- What's DCI and DCI is complementary to MVC framework -- Ruby on Rails.
- (So far)How to avoid 'Too fat to be a model' and/or 'Fat Controller' in Rails App using DCI.
- Case Study

After this talk you'll stand the starting point to improve the design of your application more clear and concise.

- Preferred presentation day: no preference
- Presentation language: Japanese

## 発表概要 (talk description in Japanese; optional)

[DCI(Data, Context and Interaction)](http://en.wikipedia.org/wiki/Data,_Context,_and_Interaction)はオブジェクト指向アプリケーションに対する「パラダイム」のひとつです。随分大きく出ましたね。DCIは設計手法やデザインパターン以上の存在、すなわち我々プログラマはオブジェクト指向アプリケーションの認識の枠組みであるとDCIの提唱者(Trygve Reenskaug)とDCIのエヴァンジェリスト(James O.Coplien)は言っています。ちなみに、DCIの提唱者であるReenskaug氏はMVCの提唱者でもあり、彼らによればDCIはMVCアーキテクチャを補完するものであるとのことです。その意味ではDCIはアーキテクチャと呼べるかもしれません。

そんなDCIが近頃、OO厨系Rubyistの関心を集めています(例:["Objects on Rails"](http://objectsonrails.com/),["Clean Ruby"](http://clean-ruby.com/))。なぜでしょうか？  その背景には、MVCアーキテクチャを具現化したフレームワークであるRuby on RailsによるWebアプリケーションが初期構築から時を経るとともに保守しづらくなっている状況が背景にあるのではないかと講演者は考えています。"Skinny Controller, Fat Model"の教えに従った結果、太りすぎてモデルとしてやっていけないモデル(Too Fat to be a model)や、取り散らかったpartialやHelper、肥大化するApplicationController……。

こんにち本番稼動しているRailsアプリケーションに手を入れる際に、「こうであって欲しい」というあなたの予断、期待、思考の枠組み(マインドセット)を裏切られたことはありませんか？ いっそ全て捨ててやり直せたら……と思いながらも日々、目の前で動いているアプリケーションに手を入れていませんか？ 本番稼動してからそれなりに日も経ち、ユーザーに対して価値を提供し続けているので、納得いかないコードの塊なってるけれども、現実問題としては捨てられない……講演者にも多数心当たるアプリケーションがあります。テストだってそれなりに書いてるのに！ なぜだ！

Ruby on Railsは、最も成功したMVCアーキテクチャによるWebアプリケーションフレームワークです。ですが、だからといってRuby on Railsで構築すればアプリケーションの成功——ユーザーとプログラマの双方にとって幸福な結果——が約束されるわけではありません。DCIアーキテクチャは、Ruby on Railsに足りない部分、つまり「あなたの」アプリケーションをどう捉えるべきかという考え方を支援します。

ただし残念ながらDCIにはまだ、MVCにとってのRuby on Railsのようなソリューションは存在していません。ですが、それでもやはりDCIの考えかたからは「あなたの」アプリケーションのコードをもっと読みやすく、見通しよくするためのヒントを多く学ぶことができます。

本発表は、講演者が携わっているWebアプリケーションプロダクトでの実践例を踏まえ、Ruby on Railsを使ったWebアプリケーションの構築にあたって、どのようにDCIを活用できるかを皆さんにお伝えします。

## My name (required)

Kakutani Shintaro

## お名前 (name in Japanese; optional)

角谷 信太郎

## My affiliation (required)

Ruby no Kai(Japan Ruby Group) || Eiwa System Management, Inc.

## 所属 (name in Japanese; optional)

一般社団法人日本Rubyの会 || (株)永和システムマネジメント

## My bio (required)

Kakutani Shintaro is a just another strong Ruby proponent, working for Eiwa System Management,Inc as 'community manager', a board member of Nihon Ruby-no-kai(Japan Ruby Group) and a core member of Asakusa.rb.

He is one of the organizers of RubyKaigi since 2006. the founder of Regional RubyKaigi. He have translated some english technical book into japanese: "Agile Samurai"(co-supervisor), "Agile Estimating and Planning"(co-translator), "Practices of an Agile Developer"(co-supervisor) and a few other books.

## プロフィール (bio in Japanese; optional)

ただのRuby厨。(株)永和システムマネジメント サービスプロバイディング事業部コミュニティマネージャ。一般社団法人日本Rubyの会理事。自称Asakusa.rb幹部。

2006年から日本Ruby会議の運営に携わり、地域Ruby会議プロジェクトを開始した。著作は『アジャイルサムライ』(共同監訳)や『アジャイルな見積りと計画づくり』(共同翻訳)、『アジャイルプラクティス』(共同監訳)他、技術書の翻訳書が多数。

- [website](http://www.kakutani.com)
- [@kakutani](https://twitter.com/#!/kakutani)
- Past talk slides: [Speaker Deck](http://speakerdeck.com/u/kakutani), [SlideShare](http://www.slideshare.net/kakutani)
- [Past talk video](http://rubykaigi.org/2011/en/schedule/details/17M09)
