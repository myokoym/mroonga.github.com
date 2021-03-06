---
layout: post.ja
title: 「隔週連載groonga 第7回　[実録] MySQL向け全文検索エンジン「Tritonn」から「mroonga」への移行ガイド（2）」公開
description: gihyo.jpさんで公開された記事「隔週連載groonga 第7回　[実録] MySQL向け全文検索エンジン「Tritonn」から「mroonga」への移行ガイド（2）」の紹介
---
## 「隔週連載groonga 第7回　[実録] MySQL向け全文検索エンジン「Tritonn」から「mroonga」への移行ガイド（2）」公開

2013-06-18に [gihyo.jp](http://gihyo.jp/) さんで
[Tritonn](http://qwik.jp/tritonn/)
からmroongaへの移行事例を紹介した記事が公開されました。 [隔週連載groonga 第6回　[実録]
MySQL向け全文検索エンジン「Tritonn」から「mroonga」への移行ガイド（1）](http://gihyo.jp/dev/clip/01/groonga/0006)
です。

実際に [@yoshi_ken](https://twitter.com/yoshi_ken)
さんが実施した事例を元に以下のトピックを解説してくれているので、とても実践的になっています。

-   Tritonnとmroongaそれぞれの紹介と移行時の要注意点
-   現在利用できる日本語全文検索ソリューションの比較
-   ストレージエンジンをMyISAMからmroongaへ移行する際に気をつけたいAuto
    Incrementの挙動の違い

今回紹介するのは、その続編である [隔週連載groonga 第7回　[実録]
MySQL向け全文検索エンジン「Tritonn」から「mroonga」への移行ガイド（2）](http://gihyo.jp/dev/clip/01/groonga/0007)
です。

第7回では、Tritonnからmroongaへの移行はもちろんのこと、既存のMySQL
5.0を用いたMaster-Slave構成のレプリケーションにMySQL
5.6を追加し、最小ダウンタイムで段階的移行をする手順を詳しく解説しています。

現在Tritonnを使用しているみなさんの、mroongaにどうやって段階的に移行をすすめていけばいいんだろう?
という疑問に対する一つの答えとして参考になるのではないかと思います。

該当記事では次号の予告もすでにされています。移行プロジェクトの集大成となる記事になりそうです。続きが楽しみですね!

また、この「隔週連載groonga」ではgroonga/mroonga/rroonga/...の利用事例を募集しています。利用事例を記事として紹介してもいいよ、という方は
[募集要項](http://sourceforge.jp/projects/groonga/lists/archive/dev/2013-February/001186.html)
を参考にご連絡ください！お待ちしています！

現在、あと1件利用事例が控えているので、7月中はこの連載は続けられそうです。8月以降も続けるために、みなさんのご協力をお願いします。
:-)
