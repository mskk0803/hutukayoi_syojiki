# hutukayoi_syojiki
二日酔い正直申告のソース

■アプリ名

二日酔い正直申告

■サービス概要

飲酒量を記録し、二日酔いになってしまった日は正直にその飲酒量と二日酔いになった旨を申告するアプリです。自信の飲酒量が純アルコール量（と、各種酒に相当する杯数）で表示され、どれくらい飲むと二日酔いになるか可視化することができます。

■ このサービスへの思い・作りたい理由
「翌日予定があるのに、つい楽しくなって飲みすぎてしまった…」

学生時代に飲酒を覚えた私は、飲み会があるたびにそう思っていました。

「だけど、辛い二日酔いにならない程度に、お酒を最大限楽しみたい！」

できるだけ簡単に記録ができ、記録するだけでどれくらい飲んだら二日酔いになるか分かれば、自分でセーブできるようになるはず。

お酒に対する飲みたい気持ちが作りたいと思った理由です。

■ ユーザー層について

- 20歳以上
    - お酒は20歳からなので
- 酒をよくたしなみ、二日酔いになりやすい、または二日酔いになりやすい量を把握したい方
    - 酒をよく飲んで、翌日に支障が出ないようにする飲酒量を知りたい方向けに作りたいと思ったから
- 既存の記録アプリでの記録が長続きしなかった方
    - できるだけ簡単に記録とアプリへのアクセスができるようにしています

■サービスの利用イメージ

ユーザーは、飲み会の開始前と飲み会の翌朝にLINE上にて通知をうけます。

飲み会の最中は、飲んだアルコールの種類を杯数とともに登録できます。

飲み会の翌朝に、昨日の飲み会で二日酔いになったかの通知を受けます。

二日酔いになった際は、二日酔いになったことを登録すると、これまでの二日酔いの記録から大体純アルコール相当で何gか、またアルコール飲料の種類だと何杯分に相当するかを知ることができます。

これにより、ユーザーは自分がどのくらいの飲酒量で二日酔いになるのか特定しやすくなり、二日酔いの予防に繋がります。

■ ユーザーの獲得について
- Xでの拡散（RUNTEQの方々にまずはご利用いただき、口コミで増やしていく）

■ サービスの差別化ポイント・推しポイント

類似サービス

- 二日酔いチェッカー　byあぶらみくん

二日酔いチェッカーは純アルコール量で何時間アルコールが体内にあるのかを通知してくれますが、二日酔い正直申告は、自分自身の感覚で「じぶんが二日酔いかどうか」を知ることができます。また、二日酔いチェッカーは飲み会用のアプリでお楽しみ要素が強いですが、二日酔い正直申告は健康促進のためのアプリのため、遊び要素は入っていません。

■ 機能候補

MVP段階

- 飲酒量の登録、編集、更新、削除機能
- 飲み会予定の登録、編集、更新、削除機能
- 二日酔いの登録、編集、更新、削除機能
- 二日酔いになるアルコール量の表示、通知機能

本リリース

- LINE連携
    - LINEから飲酒量の登録、編集、更新、削除ができる機能
    - LINEから飲み会予定の登録、編集、更新、削除機能ができる機能
    - LINEから二日酔いの登録、編集、更新、削除機能ができる機能
    - LINEによる二日酔いになるアルコール量を通知してくれる機能

■ 機能の実装方針予定
https://lineapiusecase.com/ja/lineapi.html

- LINE MessageAPIかLINE ミニアプリを使用予定