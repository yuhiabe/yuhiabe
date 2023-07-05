# スキルシート: 阿部 友陽

| カテゴリ    | 詳細 |
| ----------- | ----------- |
| **氏名**      | 阿部 友陽       |
| **性別**      | 男性        |
| **年齢**      | 25         |
| **学歴**      | 弘前大学理工学部自然エネルギー学科 |
| **所在地**    | 北海道札幌市 |
| **最寄駅**    | 北海道札幌市 地下鉄東豊線 |
| **資格**      | AWS認定CLF(2020/8)<br>AWS認定SAA(2021/1)<br>AWS認定SOA（2021/7）<br>ITパスポート(2019/4) |
| **認定資格URL**| [Credly](https://www.credly.com/users/yuhi-abe) |

## 技術スキル

| カテゴリ         | 技術スタック |
| ---------------- | ------------- |
| **プログラミング言語** | PHP, ★Python, JavaScript |
| **フレームワーク** | Django(Python), ★Flask(Python), FastAPI(Python), Vue(JavaScript), Materialize(CSS) |
| **仮想環境** | Docker |
| **DB** | MySQL, PostgreSQL, RDS, Aurora, DynamoDB |
| **AWS** | EC2, VPC, ELB, Auto Scaling, S3, Route53, ACM, Lambda, Api Gateway, SQS, SNS, Chatbot, ECS, Secrets Manager, Amplify, ElasticSearch, EventBridge, ECS Fargate, SDK(boto3), Cloud9 |
| **AWS セキュリティ系サービス** | WAF, Trusted Adviser, CloudTrail, Config, GuardDuty, Security Hub, Well Architected Tool, AWS SSO, Organization, Macie, KMS |
| **CDN** | AWS Cloudfront, Vercel |
| **CI/CD** | AWS CodeCommit, CodeBuild, CodeDeploy, CodePipeline, Github Actions, Gitlab CI |
| **IaC** | Terraform, Terraform Cloud, AWS CloudFormation |
| **Serverless IaC** | Serverless Framework, AWS SAM |
| **認証系サービス** | AWS Cognito, Auth0 |
| **監視系サービス** | Datadog, AWS CloudWatch, AWS X-Ray |
| **IoT系サービス** | AWS IoT core, AWS TimeStream, AWS Kinesis Video Streams, AWS Kinesis Data Firehose |
| **バージョン管理サービス** | Gitlab, Github, AWS CodeCommit |
| **その他サービス** | Selenium, Selenium Grid, Swagger, Let's Encrypt, Adminer, Wafcharm, StatusPage(Atlassian), Cloudcraft, Localstack, Azure AD |
| **業務ツール** | Backlog, Slack |
| **その他API** | Twitter, Google, Spotify, CloudSign, LINE Notify |

## 職務経歴

| NO. | 企業名 | 期間 | 契約・雇用形態 | 担当職種 | 事業内容・業務内容 |
| --- | ------ | ---- | ------------ | ------- | -------------- |
| 1 | [株式会社エコモット](https://www.ecomott.co.jp/) | 2020年4月 - 2021年12月 | 正社員 | フロントエンド, バックエンド、インフラ | IoTインテグレーション事業 |
| 2 | 個人事業主 | 2021年12月 - 現在 | 個人事業主 | バックエンド、インフラ, SRE | Webアプリ開発 |

## 自己PR

主に、SRE業務を行っています。  
日頃から継続的にレガシーなサーバOSやミドルウェア、言語ランタイム、アーキテクチャを刷新していくことや、  
ユーザーが安心して利用できるセキュリティを確保すること、サービス規模拡大に比例してサーバのコストが増えないようにコストの適正化することを意識しています。

フロントエンドからバックエンド、クラウドインフラ(AWS)を経験していることや新しい技術・ツールに抵抗ないことが強みです。  
自動化やパフォーマンス改善を行い、作業効率を上げることやアプリケーションの品質を向上させることが好きです。  
宜しくお願い致します。  

---

## 案件詳細

### 期間: 2021-12-01 - 現在

### 不動産契約システムのインフラ構築・新規開発

**≪システム構成≫**
- フロントエンド: Nuxt.js, Vue.js
- バックエンド: python, mysql, django, flask, fastapi
- インフラ: AWS

**≪担当業務≫**
- バックエンドREST API開発
- インフラ構築・運用

**≪コメント≫**  
主にインフラ構築とバックエンドAPI開発や、DevOpsの業務、商用リリース作業やテナントの導入作業などの運用保守作業を担当してました。

マルチテナントのアプリケーション開発やシングルテナントのアプリケーション運用を経験することができ、  
また、ECSベースのアプリケーション開発、サーバレスアプリケーション開発、運用ツールの理解を深めることができました。

事業責任者、PM、PL、開発チーム、試験チーム、導入チームからの問い合わせ対応や調整作業をはじめ、取引先に大手企業が多く、  
クライアントから要求されるセキュリティチェックシートの回答対応や非機能要件のすり合わせ対応などを通して、インフラの知識を深めることができました。

**≪担当業務詳細≫**
- インフラ
  - インフラアーキテクチャ図作成(Draw.io, Cloudcraft)
  - インフラ構築（AWS）
  - Terraform インフラコード化(IaC)
  - Terraform インフラ既存リソースのリバースエンジニアリング、import連携(IaC)
  - Terraform 開発と運用効率の改善（tfenv, tfsec, tflint, docsなど導入）
  - Terraform Cloud インフラのCI/CD構築
  - TerraformとAWS Providerのバージョンアップ対応
  - Severless Framework サーバレスアプリケーションのインフラコード化(IaC)
  - Github Actions CI/CD構築(バックエンド, フロントエンド, サーバレスアプリケーション)
  - AWS Codepipeline CI/CD構築
  - AWS スイッチロールの導入
  - AWS Organizations、AWS SSOの導入
  - AWS マルチAZ対応による可用性向上
  - AWS 各種セキュリティサービスの導入(SecurityHub, GuardDuty, Inspector)
  - AWS CloudFront HTTPセキュリティヘッダの追加
  - AWS S3ライフサイクルでの不要コスト削減
  - AWS 分散負荷テスト実施
  - AWS SES, SNS, SQS, Lambdaを利用したバウンスメール対策
  - AWS EventBridge schedulerを利用したメンテナンスページ設定
  - AWS Cognito 認証基盤構築、IdP連携（AzureAD）
  - AWS X-Ray マイクロサービスアプリケーションの分析導入
  - AWS RDSなどのインスタンスタイプ世代更新（性能パフォーマンス、コスト削減）
  - AWS Timestreamによるアプリ操作ログ収集
  - AWS StepFunctions による非同期化処理構築
  - AWS 各種ツール(Github Actions, Terraform Cloud)における認証方法をOIDCへ変更
  - AWS Savings plan リザーブドインスタンスによるコスト削減対応
  - Datadog Log/Monitor/Dashboard, Slack通知の導入
  - Datadog Metric Stream導入
  - Datadog Synthetics Monitoring導入（外形監視）
  - Datadog APM導入（パフォーマンス改善調査、障害調査）
  - Datadog RUM導入（ブラウザパフォーマンス改善調査、障害調査）
  - Auth0 認証基盤構築
  - StatusPage ステータスページ導入・設定
  - Wafcharm WAF自動化運用とセキュリティ対策導入
  - GitlabからGithubへのバージョン管理ツール移行(CI/CD込)
  - クライアントの基幹システムとの連携対応
  - クライアント提出用のセキュリティチェックシート、非機能要件シートの対応
  - インシデント調査・対応
  - SLI/SLO の策定

- バックエンド
  - SwaggerによるバックエンドAPI設計・仕様書作成
  - Flaskを用いてのREST API開発
  - 外部サービス連携処理の開発(cloudsign)
  - AWSサービス連携処理の開発(AWS Cognito, SES, S3, StepFunctions)
  - ログ設計、ログ出力処理の開発
  - 各種ミドルウェア(Webサーバ, APサーバ)のチューニング
  - Linter(Flake8,Mypy), Formatter(Black, Isort)の導入
  - Dockerイメージサイズのチューニング
  - Localstack導入によるローカルでAWSエミューレーション環境構築
  - MySQL 5 -> 8系バージョンアップ対応
  - 複数環境の運用におけるgit flow整理

---

### 期間: 2022-02-01 - 2022-06-01

### クラウド経営システムの既存インフラ調査・インフラ設計

---

### 期間: 2021-09-01 - 2021-11-30 (3ヶ月)

### IoTデータコレクトプラットフォームサービス機能追加、保守開発

**≪担当業務≫**
- バックエンド 詳細設計と実装、テスト

**≪担当業務詳細≫**
- バックエンド:
  - PHP, FuelPHP, Smartyによるバックエンドシステムの改修
  - 管理者用ツール 作成
  - DB テーブル定義、追加
  - サイトリニューアル対応
  - ヘルプページ作成

- インフラ:
  - DockerによるFTPサーバの検証環境構築
  - FTPサーバのFTPS対応
  - SVNによるバージョン管理

**≪コメント≫**  
ER図やインフラ構成図などのドキュメントがない既存システムの改修はとても大変でした。Linuxを触れる機会が多く、実務レベルのインフラ知識を得ることができました。

属人化によるブラックボックス、レガシーシステムに依存した業務や作業手順などが存在しており、後から参画する開発メンバーの工数がかかり、  
開発のスピード感が落ち、工数や精神的にも逼迫した状態になっていたので、クラウドサービスなど上手に活用してそういった弊害を無くしたいという気持ちが強くなりました。  

管理者用ツールについては検索、ソート、ページネーション、SQLインジェクション対策、XSS対策など基本的な機能の実装することでコーディングやアルゴリズムの知識を深めることができました。

---

### 期間: 2021-07-01 - 2021-08-31

### 開発系インターンシップの企画・実施

**≪担当業務≫**
- 1週間行われる開発系インターンシップの企画・実施

**≪担当業務詳細≫**
- インフラ:
  - AWS アカウント作成時の運用面でのベストプラクティス適用
  - AWS IoT Core、ElasticSearchを利用したデータのリアルタイム可視化
  - AWS Kinesis Firehose StreamsとS3を利用したデータレイク作成
  - AWS Kinesis Data Streams、Lambda、DynamoDBを利用したアプリケーション用DB作成
  - AWS Secrets Managerによるシークレット管理
  - Google API 利用

**≪コメント≫**  
専門用語やサービスの理解を深めてもらうために、わかりやすい説明資料や構築手順書を用意することは大変でしたが、  
アウトプットする良い機会になり、とても勉強になりました。  
さらに、簡単なIoT基盤構築を通して、データの収集から見える化まで一貫して学ぶことができました。  
また、リーダーを務めることで、タスク管理や他部署との調整など管理職が行っている業務の一部を体験することができました。

---

### 期間: 2020/08/01 - 2021-08-31

### カメラ映像を管理するアプリケーションの開発・運用

**≪システム構成≫**
- フロントエンド: Vue.js
- バックエンド: Python, PostgreSQL
- インフラ: AWS

**≪担当業務≫**
- フロントエンド開発
- バックエンド開発
- インフラ
- 運用・保守

**≪担当業務詳細≫**
- フロント:
  - Vue.js基盤構築、開発
  - hls.jsストリーミング再生機能実装
  - 多言語対応
  - ヘルプページ作成
  - シナリオ・クロスブラウザテスト仕様書兼結果報告書作成
  - Selenium・Selenium-grid WebUIテスト自動化

- バックエンド:
  - Swagger Rest API設計
  - AWS API Gateway・Lambda(Python3.8)でのAPI開発
  - ネットワークカメラ操作・制御機能実装
  - 外部連携用APIの作成・Bearer認証導入
  - ER図作成・テーブル定義などのDB設計

- インフラ:
  - Docker・docker-composeによる開発環境構築
  - AWS CodeシリーズによるフロントエンドのCI/CD構築
  - AWS SAMによるサーバレスアーキテクチャの構築・コード化
  - AWS CodeシリーズによるSAMのCI/CD構築
  - AWS CloudFormationによるインフラの構築・コード化
  - RTSPストリーミングサーバーの構築
  - 新規機能追加のためのクラウド費用見積

- デバイス:
  - ネットワークカメラ検証・接続
  - AWS IoT Coreを利用したネットワークカメラ接続・デバイス管理
  - AWS Kinesis Video Streamsを用いたカメラ動画取得機能実装

**≪コメント≫**  
フロントからインフラまでモダンな技術を使用してシステム開発を行っていました。  
また、カメラを扱うことで、データがクラウドに送られ、ウェブ上で映像が再生されるまで体系的に学ぶことができました。  
機能追加案件ではPLも経験することができました。

社内でAWS勉強会など開くこともありました。  
事業部の方針として[技術ブログ](https://www.ecomottblog.com/?p=8038)を書く機会が多かったです。

---

### 期間: 2021/8 - 2021/8

### イベント出展(環境広場さっぽろ)用のクイズアプリ開発

---

### 期間: 2020/7 - 2020/7

### インフラ構築、DB移行（社内研修）

---

### 期間: 2020/4 - 2020/6

### 従業員情報管理システムの開発（社外研修）

