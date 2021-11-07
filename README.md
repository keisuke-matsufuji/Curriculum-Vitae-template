
# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|松藤 圭祐 (Matsufuji Keisuke)|
|Living|福岡県福岡市|
|Qiita|https://qiita.com/mtfuji_ksk|
|Blog|https://www.mtfujiksukblog.com/|


## スキル
### 言語 / フレームワーク / ライブラリ
- PHP
  - PHP(5.6・7.3)
  - Laravel(6.5)
    - WebAPI開発経験
    - Eloquentを用いてのCRUD実装・マイグレーション経験
    - Laravel タスクスケジュールの機能を用いたバッチ処理実装経験
    - PHPUnitを用いたテストコード実装・単体テスト実装
  - Zend Framework2
    - MVCパターンでの実装経験
- Python(3.8)
  - SQLAlchemyを用いてのCRUD実装
  - (個人開発)AWSLambda関数の実装・AWSCloudWatchを使用したバッチ処理実装経験
  - 負荷試験ツールLocustを用いたWebAPIのテストシナリオ実装
- JavaScript
  - jQuery
- TypeScript
  - Vue.js(2.6)
    - vue-class-component/vue-property-decorator記法の実装経験
    - Vuetify
      - マテリアルデザインを踏襲した実装。モック作成を通してデザイン作成経験あり
    - vue-router/Vuex
      - Vuex/vue-routerを使用した画面遷移・状態管理
  - Nuxt.js(2.15)
    - composition-api記法の実装経験
    - (個人開発)nuxt/contentを使用した技術ブログの作成
  - yarn
  - npm
- Java(8系)
  - JSP
- Swift

### DB / ミドルウェア
- Oracle(11g)
- PostgreSQL(14.0～)
- MySQL(5.7～)
- Redis
- MongoDB
- DynamoDB

### ツール / OS / 他
- Git / GitHub / GitLab / GitHub Actions
- Docker
- docker-compose
- Windows / macOS / Linux
- Visual Studio Code
- SourceTree
- XCode
- AWS(個人開発)
  - Lambda
  - DynamoDB
  - IAM
  - CloudWatch
  - Amplify
- Serverless Flamework(個人開発)
  - AWS Lambdaと組み合わせたCI/CD環境構築


## 【自己PR】強み / これから伸ばしたいこと / 興味があるもの
### 強み
- Laravel / Vue.jsを用いた、SPAの開発経験
  - フロントエンドの実装
  - WebAPI(バックエンド)の実装
- フロントエンド・サーバーサイドを一貫した開発経験
  - WebAPIへのリクエスト/レスポンスを明確にした上で、フロントの実装を行うので、仕様の考慮漏れに早い段階で気づくことができました。
- WebAPIのパフォーマンスを考慮した実装。
  - 主にDBへのアクセス・SQLについてのパフォーマンスを考慮した実装を行うことができます。
  - 既に作られた機能に対して、SQLのパフォーマンスチューニングやNoSQLを用いるなど、必要な要素を提案・導入することが得意です。
- 業務要件から仕様に落とし込むこと、また、システムの各機能の仕様理解・キャッチアップ
- 機能実装に必要な工数の想定
  - リリース期日優先のタスクについては、タスクの細分化を行い、切り出した作業を他のメンバーに割り振ったり、優先度が低い箇所については二次開発で対応可能かどうか、提案をするなど、柔軟な対応を行うことができます。
- 本番障害の調査と原因分析・改修までの対応。原因と思われる箇所にあたりをつける。
  - 障害の内容から、どの処理に問題がありそうか、というイメージを手早く描くことは得意です。

### これから伸ばしたいこと
- パフォーマンス改善の経験をもっと積み、知見を深める(特に、バックエンドの処理・SQLのパフォーマンス改善)
- 静的型付け言語を用いたバックエンド実装
- Vue.jsなどのJavaScriptフレームワークを用いたフロントエンド実装の経験を深める
- AWSなどのパブリッククラウドを使用した開発業務経験
  - 実務経験はありませんが、AWS Lambda + Cloud Watchを用いたアプリケーションの構築を個人開発で行いました。

### やったことはないが興味があるもの
- CI/CD環境の構築などの、SRE領域の業務に興味があります。  
個人開発でGithub ActironsとAWS Lambdaを用いたCI環境の構築を行ったので、実際に業務で使用できるところまで体系的に知識を学びたいです。

## 職務経歴

### 2019.07 - 現在 : 株式会社BTM

職務：Webアプリケーションエンジニア  
業態：SES / 受託開発

#### 学習塾向けアプリケーション開発(SES)(2021.4 - 現在)
1 学習塾 進捗管理アプリケーション(2021.4 - 現在)
- 規模：4名～10名
- 担当：フロント・サーバーサイド
- 業務：基本設計・詳細設計・開発・テスト
- 技術：PHP(7.3) / Laravel(6.5) / Python(3.8) / TypeScript / Vue.js(2.6)
- 詳細
  - 自社の学習塾で使用する進捗管理アプリケーションの新規開発・機能追加プロジェクト。
  - プロジェクト参画時はチケット化されたバグタスクの改修。
  - 参画後2か月後以降は、リーダーがまとめた業務要件をもとに機能仕様の整理・設計から参画。設計した仕様をもとにバックエンド(WebAPI) / フロントエンド(SPA)を一気通貫して実装しています  
  開発と並行してフロントの共通機能のコンポーネント化といったリファクタも行いました。
  - アジャイル型開発を採用していたため、仕様決定=>実装=>テスト・リリースのサイクルで継続的に開発を行っています。
  - 短納期・仕様変更が頻繁に起こる機能についても担当しました。
  リリース日優先・人員は増やせない制約があったため、
  リリース機能のタスクの細分化・優先度の整理・優先度が低い部分については二次リリースとして後出しをできないかとリーダーに提案したことで、最低限必要な機能が担保された状態で、リリース日に間に合わせることができました。
  - マスタデータの登録作業について、Python製の登録スクリプトの整備と登録作業の平準化を行い、開発チームの作業工数を削減しました。
  - 経験が浅いメンバーが参画してきた際には、積極的に技術指導（実装方法の説明・機能の仕様についての説明）を行いました。
  - 改修・リリースの頻度が多く、デグレの発生が頻出していたため、テスト仕様書の平準化および、今までのデグレ発生個所の分析と対応方法の周知を行いました。
  - 一部機能についてはプロジェクトリーダーに代わってタスクの切り出し・作業の割り振り・仕様の理解・説明を行いました。


2 生徒・保護者向けアプリケーション(2021.6 - 2021.9)
- 担当：フロント・サーバーサイド
- 業務：開発・テスト
- 技術：PHP(5.6) / ZendFramework2 / JavaScript / jQuery
- 詳細
  - 生徒・保護者向けアプリケーションのアンケート機能追加案件。
  管理者が設定したアンケートを生徒・保護者が回答する機能。
  - モック作成 / フロント(JavaScript/jQuery) / サーバサイドを包括して実装しています。 


3 学習塾 進捗管理アプリケーション パフォーマンス改善(2021.3 - 2021.9)
- 担当：フロント・サーバーサイド
- 業務：要件定義・設計・実装・テスト
- 技術：PHP(7.3) / Laravel(6.5) / TypeScript / Vue.js(2.6)
- 詳細
  - Oracleを別システムと共用で使用していたためOracleからPostgreSQLへ移行しました。移行することでソースコード上でSQLを記述している箇所に関して、互換性がない個所の調査・適切な文法への改修を行いました。
  - SQLを変更したファイルを対象とした、PHPUnitを用いたテストコードの作成を行いました。
  - システム内で、ユーザが参照する頻度が高い機能（以下、該当機能）についてのキャッシュ機構の要件定義・設計・実装を行いました。キャッシュ機構には、キャッシュクライアントの導入・キャッシュの自動更新機能が含まれます。
  - キャッシュクライアントには、レスポンスの高さが求められていた、かつ、データの永続化は必要がない（1日経過するとキャッシュは削除してよい）という要件から、インメモリ型のNoSQLであるRedisを採用しました。
  - 該当機能は外部システムのデータを参照しており、テータの変更を検知する必要があったため、キャッシュの自動更新機能の実装が必要でした。キャッシュの自動更新機能については、PostgreSQLのトリガとPL/SQLで記述したトリガファンクション、Laravelのバッチ処理を使用しています。
  - Webサーバーへの負荷分散を目的とし、ロードバランサーが導入されました。それに伴い、増設したWebサーバへのRedisのレプリケーション設定作業を行いました。
  - 負荷試験の実施を負荷試験ツールLocustを用いて行いました。テストシナリオをPythonにより記述しました。
  - DB移行後の、SQLパフォーマンスチューニングを行いました。実行計画の実施・ボトルネックの特定と原因の解消(適切なindex設定・テーブル結合の見直しなど)をすることで、最大20秒程かかっていたクエリを3秒程度まで短縮することに成功しました。


4 生徒・保護者向けアプリケーション(2021.1 - 2021.3)
- 担当：iOS
- 業務：開発・テスト・AppStoreへのリリース
- 技術：Swift
- 詳細
  - 生徒・保護者向けのiOSアプリの機能改修。TestFlightへのリリースやAppStoreへのリリースまで担当しました。


#### 出版社向けCMS開発(受託開発)(2020.2 - 2020.3)
- 担当：基本設計書作成
- 業務：基本設計書作成
- 技術：Java / JSP
- 詳細
  - 有償のCMS(HeartCore)で製造された出版社向けのサイトのリバース設計を行うプロジェクト
  - 設計書が作成されていない状態から、既存ソース(JSP)の処理を解析し、基本設計書の作成を行いました。


#### 飲食チェーン店向けCMS開発(受託開発)(20219.11 - 2020.1)
- 担当：フロント・サーバーサイド
- 業務：実装・テスト
- 技術：Java / JSP / jQuery
- 詳細
  - 有償のCMS(HeartCore)を用いて、飲食チェーン店向けのコーポレートサイトを作成するプロジェクト
  - CMSの標準機能を用いて画面の実装と内部処理の実装、標準機能で実装できない箇所については、JSP / jQueryでバックエンドとフロントの実装を行いました。

#### 空調機器メーカー向けアプリ開発(受託開発)(20219.7 - 2020.10)
- 担当：フロント・サーバーサイド
- 業務：バグ改修 / テスト
- 技術：TypeScript / Angular
- 詳細
  - 空調機器メーカー向けのシステム開発プロジェクト。
  - 機能テストの実施と、チケット化されたバグの改修を行いました。


### 2017.4 - 2019.6: 株式会社モード・プランニング・ジャパン

職務: 人材紹介 コンサルタント

#### 職務内容
- 人材紹介会社のコンサルタントとして、人材を採用したい企業に対して、仕事を探している求職者をマッチングさせる業務を行っていました。
- 採用企業・求職者それぞれからヒアリングを行い、双方にとってよい採用となるよう、要望の可視化や調整業務を行いました。
- 上記の経験から、現職のプロジェクトでも、調整などを行うことに関してはあまり抵抗なく行うことができます。

## 課外活動
### 個人開発
- [FX自動売買](https://github.com/keisuke-matsufuji/fx_by_oanda)
  - 技術要素
    - Python
    - AWS
      - Lambda
      - DynamoDB
      - IAM
      - CloudWatch
    - Serverless Flamework
    - GitHub Actions
    - Docker
  - OANDA社から提供されているAPIを使用し、指定通貨ペアのローソク足価格データ取得・新規注文処理・ポジションの決済処理を自動で行うアプリ。
  - AWS Lambdaの関数をPythonで記述し、Cloud Watchで定期実行します。
  - GitHub ActionsとServerless Flameworkを用いて、AWS Lambdaへの自動デプロイ環境(CI/CD環境)を構築しました。

- [技術ブログ](https://www.mtfujiksukblog.com/)
  - 技術要素
    - Nuxt.js
    - Vuetiry
    - Nuxt-Content
    - Docker
    - AWS
      - Amplify Console
      - Route53
    - Github
- Nuxt.jsのプラグインであるNuxt-Contentを使用して、個人ブログの作成を行いました。
- 開発環境構築はDocker/docker-composeで行いました。
- 記事をマークダウンで作成し、静的ファイルで吐き出す仕組みにしています。
- お名前.comで取得したドメインを使用し、AWS Amplifyでホスティングしています。
- ドメインについては、Route53で管理しています。
- AWS Amplify Consoleを使用し、Githubのブランチへのマージをトリガーに自動デプロイするCI環境の構築を行いました。masterブランチとdevelopブランチそれぞれにトリガーを設定しているので、developブランチで動作確認（ステージング環境）を行えるようにしました。