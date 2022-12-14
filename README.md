# 職務経歴書

#### 2022年12月現在

## スキルレベル

|     |              | 業務経歴 |    独学 | レベル(1-5) | レベル説明                     |
|-----|--------------|-----:|------:|---------:|---------------------------|
| 言語等 | Java8        |   4年 |       |        5 | 指導ができる                    |
|     | Java11       |   2年 |       |        5 | 指導ができる                    |
|     | JavaScript   |   4年 |       |        4 | 調べながら、進められる               |
|     | Shell        |   4年 |       |        4 | 調べながら、進められる               |
|     | VBA          |   4年 |       |        4 | 調べながら、進められる               |
|     | Kotlin       |      |    2年 |        4 | 調べながら、進められる               |
|     | TypeScript   |      |    2年 |        4 | 調べながら、進められる               |
|     | Swift3       |      |  0.5年 |        3 | 調べながら、進められる               |
|     | Python       |      |  0.5年 |        3 | 調べながら、進められる               |
|     | Rust         |      | 0.25年 |        3 | 調べながら、進められる               |
|     |              |      |       |          |                           |
| FW等 | Spring MVC   |   4年 |       |        5 | 指導できる                     |
|     | Spring Boot  |   2年 |       |        5 | 指導できる                     |
|     | Spring Batch |   2年 |       |        4 | 調べながら、進められる               |
|     | MyBatis      |   6年 |       |        5 | 指導できる                     |
|     | React        |      |    2年 |        4 | 調べながら、進められる               |
|     | GraphQL      |      |  0.2年 |        4 | 調べながら、進められる               |
|     | Next.js      |      |  0.2年 |        4 | 調べながら、進められる               |
|     | PostGraphile |      |  0.2年 |        3 | 調べながら、進められる               |
|     |              |      |       |          |                           |
| OS等 | RedHut       |   4年 |       |        2 | 調べながら、進められる、提案できるレベルではない  |
|     | AWS          |   2年 |       |        2 | 調べながら、進められるが、提案できるレベルではない |
|     |              |      |       |          |                           |
| DB等 | PostgreSQL   |   6年 |       |        5 | クエリ作成、チューニング可能            |
|     | MySQL5.7     |   2年 |       |        5 | クエリ作成、チューニング可能            |
|     | Oracle       | 0.5年 |       |        1 | さわりのみ                     |
|     |              |      |       |          |                           |
| その他 | SubVersion   |   4年 |       |        3 | 操作できる、軽い指導なら可能            |
|     | BitBucket    |   2年 |       |        3 | 操作できる、軽い指導なら可能            |
|     | Docker       |   1年 |       |        4 | 自身で構築が可能。調べながら進められる。      |
|     | GitHub       |      |    3年 |        3 | 操作できる、軽い指導なら可能            |
|     |              |      |       |          |                           |

## 業務経歴

### 1. （副）SaaS 開発 2022年11月〜現在

1. システム概要
    1. 非公開
2. 規模
    1. フロント: 4人体制、バックエンド: 4人体制、マネジメント等: 1名
3. 担当領域
    1. フロント
    2. データ設計
4. 要素技術
    1. サーバ：Golang
    2. フロント：Next.js
    3. DB：PostgreSQL、PostGraphile
    4. AWS: lambda、Amplify、ECS

### 2. （本）宅配業者経理支援システム 2021年2月〜現在

1. システム概要
    1. 注文を元に、加盟店への支払金額、請求金額を集計し、加盟店へ通知、ファイル発行するシステムです。
    2. 注文履歴ファイル、支払通知書・請求書のPDFファイル、全銀ファイル等のファイルを出力する機能を備えています。
2. 規模
    1. バッチ: 6人体制、フロント、API、BFF: 1人体制
    2. インフラ: 3人体制、マネジメント等: 3人体制、企画: 3人体制
3. 担当領域
    1. 設計からテスト（バッチ : マネジメント : フロント等 : その他 = 50 : 49 : 1 : 0）
    2. 顧客とのヒアリング
    3. メンバへの技術のレクチャ、勉強会の提案、設計壁打ち
    4. 3人規模のチームリード
4. 要素技術
    1. サーバ：Java11(Spring Boot、Spring Batch、Jasper Report、GraphQL、MyBatis)、CleanArchitecture、DDD
    2. フロント：Next.js
    3. DB：MySQL5.7、PostgreSQL、Oracle
    4. AWS: ECS、StepFunctions、CloudWatch、S3

### 3. （副）商品売上管理システム 2022年3月〜2022年8月

1. システム概要
    1. 商品の売上を記録するシステムです。購入された商品の登録、更新、削除、検索、PDF出力機能を備えています。
2. 規模
    1. 5人月: 1人体制
3. 担当領域
    1. 全て
4. 要素技術
    1. サーバ：Kotlin(Spring Boot、Jasper Report、MyBatis)、CleanArchitecture、DDD
    2. フロント：TypeScript(React)
    3. DB：MySQL5.7
    4. OS：AWS、Docker

### 4. （本）人工衛星観測支援システム 2016年10月〜2021年1月

1. システム概要
    1. エンドユーザが指定した地点の観測データを提供するシステムです。
    2. 人工衛星が観測したデータを受領し、処理解析します。
    3. マスタデータの登録、更新、検索
    4. 観測データの受注、シミュレート、提供
    5. 各種ファイル出力
2. 規模
    1. 2000人月（ピーク時60人）
3. 担当領域
    1. 設計、実装、SW結合テスト、結合テスト（1年）
    2. 開発リーダ（3.5年）、ピーク時8名のBPの管理者
4. 要素技術
    1. サーバ：Java8(Spring mvc、MyBatis)
    2. フロント：JavaScript(Jquery)、JSP
    3. DB：PostgreSQL
    4. OS：RedHut

## 自己PR

### 2016年に新卒で

今の会社へ入社しました。
大学時代はプログラミングを一切することなく、半年にも及ぶ会社の研修で習いました。
実際に上記 観測支援案件に配属されるも、業務だけでは理解することができませんでした。

そこで、自宅学習を通じて、休日問わず、小さいものから大きなものまでを作っては、壊しを繰り返したことで、
プログラミングの魅力に取り込まれるようになりました。
その成果もあり、実装、レビュー、開発・テックリードまでできるようになりました。

気づけば、この案件での、解決できない要件・課題は一つもありませんでした。
正直、やればできる( DIY )で、プログラミングは余裕だと思っていました。

### 案件が代わり、

上記 経理支援案件に参画することになりました。
この案件では、衝撃の連続でした。

#### 1. レイヤードアーキテクチャとかクリーンアーキテクチャとか、ドメイン駆動設計とか

    前案件では、ビジネスロジックなんて概念がありませんでした。
    JSP -> Controller -> Service -> Mapperの流れでデータを移すだけ。

#### 2. ドキュメントが成果物にない

    前案件では、設計書と実装とがほぼ同じものでなければなりませんでした。
    Word、Excelで書かれている資料が大量にあり、修正・レビューコストは計り知れないものです。
    顧客からの指摘で、資料を書き直しになることもありました。

#### 3. テストが自動化されている。

    前案件は、手作業でテストを実施し、エビデンス パシャパシャ。
    単体テストなんてものはなく、SW結合テストを人力で。
    Spring のバージョンアップでSW結合テストを半年かけてやり直したとか。。。

#### 4. フロントとバックエンドが別れている。

    前案件は、Spring MVCでモデルにデータ詰め込んで、ビュー返して。。。

前案件で学んだことは、決して無駄ではないでしょうが、全否定をされた気分になりました。
顧客が求めている以上、それに対応する必要はありますが、あまりにも差がありすぎです。

キリがないので

### この案件での学びは

```
動くシステムを作ったとしても、設計、データモデルを間違えると、
改修不可な状態に陥り、それが負債と化し、自分達の首を閉め続けることになる。
```

です。
今思えば、前案件では負債だらけです。
今は保守フェーズだと思いますが、首が閉まってないといいですが。

この学びを定着させるには、だいぶ時間を要しましたが、更にプログラミングに興味を持つことになりました。
やればできる( DIY )でシステムを作るのではなく、ちゃんとした設計のもと、
システム開発をするようになった **転機**となりました。

自宅学習を通じて、過去に作成したプログラムのリファクタリングを教材に、復習に復習を重ねました。

- MavenからGradleへ変更
- JSP × Javaだったものを、 React × Kotlin の構成に変更
- テスト可能な構成へ変更
- さらに、Next.js × GraphQL の構成に変更

というような全面的な見直しを行いましたが、ほぼ作り直しになりました。
それもそのはず、ビジネスロジックの使い回しが一切できない構成になっていたからです。

自身の負の遺産の恐ろしさを痛感しました。
今後も、新要素の獲得と同時進行で、負債返上は続きます。
