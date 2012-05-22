# Tofu - A fast, flexible and highly scalable system for delivering image assets

Image delivery can often be a source of concern when developing web services. For example, 
when prototyping new features, you usually need to try many different layouts, with various 
different sizes of thumbnails. How can you easily and quickly generate these?

Tofu is system that generates images on the fly, at high scale, and can be used in a rails app 
through a simple but versatile ruby interface. Tofu fetches original images from Amazon S3, then 
delivers them after resizing and/or cropping as needed via an Apache module.

Tofu was extracted from Cookpad.com, where we deliver 50 million images per day on production. As 
a result of on-the-fly thumbnail generation, we have enabled to develop prototypes extremely rapidly.

ウェブサービスの開発において、画像配信は悩ましい問題です。
例えば、新機能のプロトタイピングでは、様々なレイアウトを試す必要があり、
そのたびに様々な大きさのサムネイル画像が欲しくなる場合があります。

Tofu は Apache module として実装された画像配信システムで、
Ruby インタフェースによりRailsアプリケーション等から簡単に利用できます。
Tofu は Amazon S3 に保存された画像を高速にリサイズやクロップを行い、配信します。

Tofu はクックパッドで利用されており、1日あたり5,000万枚の画像を配信しています。
クックパッドでは画像の動的配信を採用したことにより、飛躍的に開発効率を向上させることができました。

本プレゼンテーションではTofuの利用方法およびクックパッドにおける活用事例を紹介します。

なお、プレゼンテーションまでには、Tofuをオープンソースソフトウェアとして公開する予定です。

- Preferred presentation day: no preference
- Presentation language: Japanese

## Issei Naruta (@mirakui)

## Cookpad Inc.

An Infrastructure engineer at Cookpad.com in Tokyo, Japan

- [My website](http://d.hatena.ne.jp/mirakui)
- [My twitter](https://twitter.com/#!/mirakui)
- [Past talk slides](http://www.slideshare.net/mirakui)
