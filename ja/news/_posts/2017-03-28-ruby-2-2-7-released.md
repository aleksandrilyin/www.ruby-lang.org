---
layout: news_post
title: "Ruby 2.2.7 リリース"
author: "usa"
translator:
date: 2017-03-28 11:00:00 +0000
lang: ja
---

Ruby 2.2.7 がリリースされました。
これは安定版 2.2 系列の TEENY リリースです。

今回のリリースでは、前回リリースからおよそ 70 件のバグ修正が行われ、安定性のさらなる向上が図られています。
詳しくは、対応する [ChangeLog](https://svn.ruby-lang.org/repos/ruby/tags/v2_2_7/ChangeLog) を参照してください。

今回のリリースをもって、2.2 系列は通常メンテナンスフェーズを終了し、セキュリティメンテナンスフェーズへ移行します。セキュリティメンテナンスフェーズの期間は 1 年間を予定しており、この間は重大なセキュリティ上の問題への対応のみが行われます。セキュリティメンテナンスフェーズ期間の満了をもって、2.2 系列の公式サポートは終了します。
現在、2.2 系列を利用しているユーザーの皆さんは、なるべく早く、2.4 系列等のより新しいバージョン系列の Ruby への移行を検討されるよう、お勧めします。

※ただし、今回のリリースにおいて何らかの重大な互換性問題が発見された場合は、これに対応するためのリリースが行われる可能性はあります。

## ダウンロード

* [https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.tar.bz2](https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.tar.bz2)

      SIZE:   13381078 bytes
      SHA1:   0b5b79f55a1e7a7c2f6600e75167c1b9cc435042
      SHA256: 80486c5991783185afeceeb315060a3dafc3889a2912e145b1a8457d7b005c5b
      SHA512: 83756cd1c91516962b83961e0de59d858618f7ed3e9795f930aab4f199d47a95ed8f867d8aa9b51d508be26d9babf2140117c88241168bac41e6ef702cfadf20

* [https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.tar.gz](https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.tar.gz)

      SIZE:   16678101 bytes
      SHA1:   dc819c4810b009f282f3b794f61f0db313f03b19
      SHA256: 374184c6c5bbc88fb7bad422368d4053a236fb6587f0eff76146dcba57f93da5
      SHA512: 056f4b59afdd5e7697e96e64f0c0308392d9dce386abfdb101a2260d1d906877c55ae135cb86a1598a778ca7beb39424ad38bce0deb860981a10e8f5d48bf359

* [https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.tar.xz](https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.tar.xz)

      SIZE:   10507528 bytes
      SHA1:   8b811b08c1ba790949fa67c6856c9b3ba3f12691
      SHA256: 234c8aee6543da9efd67008e6e7ee740d41ed57a52e797f65043c3b5ec3bcb53
      SHA512: 21bebec6d0972f4e6f2988f471c58520e32096e43a61d627eb2210df283a6fd6d0fc49da9063f2d086f3d489f13e948462a6f084f9e931b4fde6102f490cc225

* [https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.zip](https://cache.ruby-lang.org/pub/ruby/2.2/ruby-2.2.7.zip)

      SIZE:   18519665 bytes
      SHA1:   5214c5b4c0c64b6af1d77c2d9ff890481e7e4e01
      SHA256: db3852d3f23b5eab2b9862ff01c16486eb5700cd7cb5a78234254fd8a330e183
      SHA512: 3bb978c510ecb9f962c4613124fffd64e1348d1fa2779218727c1c7c8ff3cbcf88ff0232acb815f3363af67e9f5ce546ca84990ee95269f9512270830daa588a

## リリースコメント

リリースに協力してくれた皆様に感謝します。

このリリースを含む Ruby 2.2 系列の保守は、[一般財団法人 Ruby アソシエーション](http://www.ruby.or.jp/)の Ruby 安定版保守委託事業に基いています。
