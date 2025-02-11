# maimyyym works
## personal data

| item    | content                  |
| ------- | ------------------------ |
| Name    | 宮崎 真衣 (Mai Miyazaki) |
| Birth   | 1997.02.09               |
| Live in | 福岡                     |

### Other Info.
- 1型糖尿病（3歳〜）
- AWS re:Invent 2024 **A**ll**B**uilder**W**elcome**G**rant採択

### Account
- [X](https://x.com/maimyyym)
- [Facebook](https://www.facebook.com/profile.php?id=61557484814842)
- [GitHub](https://github.com/maimyyym)
- [note](https://note.com/myfy_29)
- [Zenn](https://zenn.dev/mai_mizz)
- [SpeakerDeck](https://speakerdeck.com/maimyyym)

### Contacts
- Gmail: m.711029 * gmail.com

## my loads
### 大学
- 中村学園大学栄養科学部 2019年卒業
  管理栄養士国家試験 合格

### 職務経歴 - 概要
- 2019年4月〜2023年9月
  - 某化粧品会社に新卒入社。百貨店スタッフとして化粧品・サプリメントの接客販売に従事。
- 2023年3月〜8月
  - 業務委託契約で技術記事の執筆およびNext.jsを用いたフロントエンド開発。
- 2023年10月〜現在
  - 株式会社Fusicに入社。Python, TypeScript, PHPを用いたWebシステム・API開発やAWSインフラ設計構築。

## my thinking & policy
### Interested in / Future
#### AWS
AWSの"building block", "builder"という考え方が好きです。  
AWSサービスを用いたソリューションの設計構築を今後も自身のスキルとして強化したいと考えています。

#### セキュリティ
自分自身が医療テクノロジーの恩恵を受け、その中でセキュリティの壁を感じていました。個人の生体情報や、生体そのものに影響を与える技術はセキュリティ要件が厳しいものです。（例えば、私は[Dexcom](https://www.dexcom.com/ja-JP)という医療機器を使用していますがスマホアプリで血糖値を確認できること、血糖値等の情報がクラウド管理されることは多くの技術的困難を乗り越えたものだと考えています）  
またエンジニアとしても幅広い技術への知見、基礎力、トレンドへのアンテナ、課題解決力が求められるセキュリティという領域にとても魅力を感じています。  

#### クライアントワーク
接客業に携わっていた経験や人々のQOL向上に携わりたいという仕事の軸にも深くマッチするクライアントワークという仕事が好きです。  
さまざまな方と会話し、協働し、私のスキルを提供できればと考えています。

### motivation / policy
#### 穏和と速さ
難しいことではありますが自分の仕事が誰かのやりづらさにならないこと、またチームが穏やかに仕事を進められることを大切にしています。  
そして何より自分の心を穏やかに保ち、スピード感のある仕事をできることが毎日の目標です。  
速さ、効率は特に意識していることで、自分のもとに誰かのタスクや質問をスタックしないことはマイルールの一つとしています。

#### 発信と循環
ブログや登壇などパブリックに向けた発信活動を好んで行なっています。  
日頃の業務で学ぶ技術をアウトプットすることで自身の定着になり、また誰かの手助けにもなり、そして何より自分のスキルアップが次の業務につながります。その循環を大切にしています。

## my work logs
職務経歴の詳細です。
### 大規模データのOpenSearch連携・API開発
#### 概要
数十万規模のデータをリアルタイムに保存・管理・提供するサーバーレスAPIの開発

#### 期間
2024年6月〜現在

#### 役割
2024年6-9月：メインデベロッパー
2024年10月-：PM 兼 デベロッパー

#### 技術スタック
AWS(Amazon OpenSearch Service, AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Kinesis Data Streams, Amazon S3, Amazon SQS)
AWS SAM, Terraform
Python3.12

#### 内容
- BeautifulSoupを利用したスクレイピング、m3u8ファイルの処理等
- OpenSearchクエリ設計・実装
- Lambdaアプリケーションベース構築
- 2〜3人 × 1年超計画 規模をリード・進捗管理等

### 規制要件を踏まえたシステムのAWS基本設計書作成・調査
#### 概要
業界特有の規制があるプロジェクトのAWS設計支援

#### 期間
2024年8-11月

#### 役割
メンバー

#### 技術スタック
AWS

#### 内容
- 基本設計書作成・技術調査（セキュリティ項目）
- ランディングゾーン技術調査

### メッセージ配信管理システムのインフラ構築
#### 概要
複数システムから顧客へ配信するメッセージデータ管理・配信機構の構築

#### 期間
2024年7-10月

#### 役割
インフラ構築担当

#### 技術スタック
AWS(ALB, ECS on Fargate, Aurora, RDS Proxy, SQS, Lambda,　EventBridge, SES, SNS, Chatbot, CodePipeline, CodeBuild, CodeDeploy, EC2, NAT Gateway, Amazon Inspector, SecurityHub, AWS WAF)
Terraform

#### 内容
- LaravelアプリケーションサーバーとしてFargateを採用。
- 複数のバッチ機構にはEventBridgeScheduler, SQS, Lambdaを構築
- デプロイ機構としてCodePipeline
- セキュリティ検知のためInspector, SecurityHubの導入。
- WAF構築

### サーバーレスAPI(Lambda) JavaScript -> TypeScriptリプレイス
#### 概要
CMSバックエンドAPIの機能追加およびリプレイス

#### 期間
2024年4-6月

#### 役割
デベロッパー

#### 技術スタック
AWS(Lambda, API Gateway, S3, DynamoDB)
AWS SAM
TypeScript, Node.js

#### 内容
- JavaScriptで書かれた27種の既存APIをTypeScriptにリプレイス
- 伴ってSDK for JavaScript v2をv3に移行

### Webシステム開発(Laravel)
#### 概要
BtoBtoCのWebアプリケーション開発・初期フェーズ

#### 期間
2024年1-3月

#### 役割
デベロッパー

#### 技術スタック
Laravel, Docker

#### 内容
- MinIOを用いたローカルでのS3環境構築(Docker)
- Laravelを用いたWebアプリケーション機能開発およびBladeテンプレートを用いた画面実装

## Certification
[Credly](https://www.credly.com/users/mai-miyazaki.5bd0582a)

- AWS Certified Cloud Practitioner
- AWS Certified AI Practitioner
- AWS Certified Solutions Architect – Associate
- AWS Certified Developer – Associate
- AWS Certified SysOps Administrator – Associate
- AWS Certified Data Engineer – Associate
- AWS Certified Machine Learning Engineer – Associate
- AWS Certified Solutions Architect – Professional
- AWS Certified DevOps Engineer – Professional
- AWS Certified Advanced Networking – Specialty
- AWS Certified Security – Specialty
- AWS Certified Machine Learning – Specialty
- AWS Certified Data Analytics – Specialty
- AWS Certified Database – Specialty
- AWS Certified SAP on AWS – Specialty
