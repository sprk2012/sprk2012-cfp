# My talk title: Ruby code runtime optimizations in JRuby
# タイトル: JRubyにおけるRubyコード実行性能最適化

My talk description:

JRuby team continue improving its runtime in approximately yearly major release cycles, to make it more compatible with CRuby, to get more benefits from Java, and to run it more effectively on JVM.  Especially for runtime efficiency, JRuby team did several optimizations in its runtime to execute Ruby code more quickly utilizing features of the JVM.

This talk will provide brief summary of past runtime optimizations in JRuby first, then it will introduce the following two optimizations that are actively being developed now.
- Optimization of dynamic method dispatch with help from InvokeDynamic in Java SE 7
- Changing execution model by introducing new internal representation: IR


発表概要:

JRubyは、CRubyとの互換性向上、Java資産のより良い活用、JVM上での効率的な動作をめざし、概ね年一回のメジャーリリースのたびに改善を行ってきています。特に効率的な動作のためには、JVMの性能を最大限に活かし、より高速にRubyコードを実行できるよう、最適化のための様々な試みを行ってきました。

本発表ではまず、これまでにJRuby処理系に行われてきた最適化の概要を紹介したのち、現在積極的に開発を行っている最適化の試みとして、以下の2つの手法を紹介します。
- Java SE 7 InvokeDynamic対応による、動的メソッドディスパッチの高速化
- 新たな内部表現であるIR導入による、実行モデルの変更

## Presentation information

- Preferred presentation day: no preference
- Presentation language: English / Japanese

## My name: Thomas E. Enebo, Hiroshi Nakamura
## 名前: トーマス エネボ, 中村浩士

## My affiliation: JRuby, Red Hat(Thomas) / Appirio(Hiroshi)
## 所属: JRuby RedHat(Thomas) / 株式会社アピリオ(Hiroshi)

My bio:

Thomas Enebo is the co-lead of the JRuby project and an employee of Red Hat.  He has been a practitioner of Java since the heady days of the HotJava browser, and he has been happily using Ruby since 2001.  Thomas has spoken at numerous Java and Ruby conferences, co-authored "Using JRuby", and was awarded the "Rock Star" award at JavaOne.  When Thomas is not working he enjoys biking, anime, and drinking a decent IPA.

Hiroshi Nakamura (NaHi) has 14 years of experience with custom software development, mainly focusing on network security.  He is a comitter of CRuby and JRuby, and has been involved with number of OSS development for more than 10 years (HTTPClient, soap4r, etc.)


プロフィール:

トーマス エネボはJRubyプロジェクトのリーダーの一人であり、Red Hatの社員です。彼はHotJavaブラウザーの全盛期以来のJava専門家ですが、2001年からはRubyも好んで利用しています。また数々のJavaおよびRubyカンファレンスで講演を行い、"Using JRuby"を共著し、JavaOneにて"Rock Star"賞を受賞しました。仕事以外では自転車、アニメ、優れたIPAを楽しんでいます。

中村浩士（なひ）はネットワークセキュリティーにフォーカスしたシステム開発で14年の経験を持ち、現在は株式会社アピリオでテクニカルアーキテクトの職に就いています。CRubyとJRubyのコミッタであり、10年以上に渡り、数々のオープンソースソフトウェア開発に関わっています（HTTPClient、soap4r等）。


- [Thomas's website](http://blog.enebo.com/)
- [Hiroshi's website](http://www.google.com/profiles/nakahiro) 

- [Thomas's twitter](https://twitter.com/tom_enebo)
- [Hiroshi's twitter](https://twitter.com/nahi)

- [Thomas's past talk slides](http://jrubykaigi.org/2010/downloads/JRubyKaigi2010.pdf)
- [Hiroshi's past talk slides](http://slidesha.re/JavaOneJpInvokeDynamic)

- [Thomas's past talk video](http://vimeo.com/26537473) He has talked at RubyKaigi Tokyo 3 times, RubyWorld once, RubyBusinessCommons 3 times. Many US/EU presentations.
- [Hiroshi's past talk video](http://www.youtube.com/watch?v=-7nrXrvGzaE)
