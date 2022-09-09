# 業務経歴書

## 基本情報

|key|value|
|:---|:---|
|氏名|園田 大輔|
|住所|東京都 目黒区<br>最寄り駅: 東急目黒線 武蔵小山駅|
|E-mail|[mail@daisukesonoda.com](<mailto:mail@daisukesonoda.com>)|
|SNS|Twitter: [@d5onoda](https://twitter.com/d5onoda)<br>LinkedIn: [dsonoda](https://www.linkedin.com/in/dsonoda/)<br>Facebook: [Daisuke Sonoda](https://www.facebook.com/daisuke.sonoda.758)|
|blog|[Qiita](https://qiita.com/dsonoda)<br>[Zenn](https://zenn.dev/dsonoda)|
|著書|「[AWSエンジニア入門講座―学習ロードマップで体系的に学ぶ](https://www.amazon.co.jp/AWS%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E5%85%A5%E9%96%80%E8%AC%9B%E5%BA%A7%E2%80%95%E2%80%95%E5%AD%A6%E7%BF%92%E3%83%AD%E3%83%BC%E3%83%89%E3%83%9E%E3%83%83%E3%83%97%E3%81%A7%E4%BD%93%E7%B3%BB%E7%9A%84%E3%81%AB%E5%AD%A6%E3%81%B6-CloudTech%E3%83%AD%E3%83%BC%E3%83%89%E3%83%9E%E3%83%83%E3%83%97%E4%BD%9C%E6%88%90%E5%A7%94%E5%93%A1%E4%BC%9A/dp/4297125374/ref=sr_1_1_sspa?keywords=aws+%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2&qid=1642343661&sprefix=aws+enn%2Caps%2C170&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyWlNCMDdNT0laRlROJmVuY3J5cHRlZElkPUEwNTM1NTQ1NVVVNlVPTFhPNlQ1JmVuY3J5cHRlZEFkSWQ9QTNMTVBJM1hCVUVXOTMmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)」共著<br>AWS入門者向け書籍を有志メンバーで共同執筆。担当はCloudFrontとCloudWatchの章。|
|資格| 2021年2月 AWS認定 Solutions Architect Associate 取得<br /> 2021年2月 AWS認定 Cloud Practitioner 取得|

## 概要
- 現在はAWSのクラウドアーキテクチャ設計、クラウドインフラ構成管理、MLOps、DevOpsをメイン業務としています。
- IoT、機械学習、WebアプリのバックエンドAPI開発、などの広い範囲の開発実績があります。
- 小〜中規模プロジェクトの新規開発フェーズで最もパフォーマンスを発揮します。
- 大企業での開発内製化、及び社員の技術教育の実績があります。
- 小規模自社開発スタートアップにて、初期〜運用フェーズにおける要件定義・設計・実装・検証・デプロイまでの一通りの実務経験があります。
- お仕事に関するお問い合わせは、SNSのDM等でお気軽にどうぞ。

## スキル
- 業務で使用した技術のみを列挙しています。

### クラウド
#### AWS
VPC | EC2 | IAM | Lambda | Batch | ECR | ECS | Fargate | S3 | EFS | RDS | Timestream | DynamoDB | CloudFront | Route 53 | API Gateway | CodeCommit | CodeArtifact | CodeBuild | CodeDeploy | CodePipeline | Cloud9 | CloudShell | X-Ray | Organizations | CloudWatch | Auto Scaling | ELB | CloudFormation | Config | Systems Manager | Trusted Advisor | Well-Architected Tool | Health Dashboard | Grafana | CloudTrail | SageMaker | Lookout for Metrics | Athena | Redshift | EMR | Kinesis | QuickSight | Glue | Cognito | Secrets Manager | IAM Identity Center(AWS SSO) | ACM | WAF & Shield | Cost Explorer | Step Functions | EventBridge | SNS | SQS | SES | WorkSpaces | IoT Core | IoT Device Management | IoT Events | IoT Greengrass | IoT SiteWise

#### GCP
BigQuery | Storage | IAM | Cloud Translation

### 言語
Python | JavaScript | PHP | SQL | Shell

### フレームワーク
Django | Django REST framework | Flask | CakePHP | Zend Framework | jQuery

### RDB
PostgreSQL | MySQL | SQL Server

### その他ツール
Docker | AWS SAM | Serverless Framework | Terraform | AWS CDK | nginx | gunicorn | Apache | RabbitMQ | LDAP | GitHub | GitLab | CircleCI | DataDog | Jira | Backlog

### ハードウェア
Raspberry Pi | Arduino

### 機械学習
教師あり学習についての具体的な機能要件の把握。

- 機械学習実行ワークフローにおける実行担当者の責任範囲の切り分けと整理。
- 大容量の訓練用データファイルをS3にアップロードする手法。
- データの前処理。
- 特定条件で抽出したデータレコードへのラベリング（教師データの生成）。
- 教師あり学習による学習済みモデルの生成。
- 推論とその結果出力。
- 追加学習。
- 学習で必要な特徴量と訓練データカラムの紐付け。

## 主な業務経歴

### AI研究部門に向けたクラウド利用アドバイザー、及びMLOps業務（2022年4月〜現在）
- プロジェクト概要  
顧客のAI研究部門では、MLパイプライン構築やスクリプト、コンテナイメージのバージョン管理をすべて手動で実施しており、処理時間短縮とリソース管理効率改善が課題となっていた。  
インフラとバージョン管理をクラウドのマネージドサービスに置き換え、チームがビジネス価値を生み出すモデル開発のみに注力できるように、AWS SageMaker Studioを使用したMLOps統合開発環境への移行をサポートした。

- プロジェクトの規模  
研究部: 4名、PL: 1名、開発・アドバイザー: 1名

- プロジェクトで利用した技術、ツール  
AWS(SageMaker(Studio, Pipeline, Processing, Training, Experiments, 各種Inference) / ECR / S3 / CodeCommit / CodeBuild / IAM / CloudFormation) | Docker | Git | AWS CLI

- 発揮したバリュー
  - 顧客要望のヒアリング  
  - 既存MLスクリプトの切り分け（AWSマネージドへの移行可 or 移行不可）  
  - 技術選定  
  - クラウド設計  
  - クラウドリソースのIaC化  
  - 社内技術者への技術教育  

- 担当業務
  - 技術選定  
他部門におけるAWS利用実績とその評判の高さから、顧客はAWSを利用したML開発に興味を持っていた。そのため、クラウドはAWS、サービスはML統合開発環境をサポートしているSageMaker Studioを採択、クラウドに不慣れな顧客の技術選択をサポートした。

  - 既存スクリプト分析とAWSマネージドへの切り分け、移行  
顧客のエンジニアからMLの知見のサポートを受けつつ、SageMaker Studioに移行予定の既存MLスクリプトを分析。顧客に代わってAWSサービスにマネージド可能なもの・不可なものを切り分けた。具体的には、中間生成物の入出力先をS3に変更。前処理・学習・モデル評価の各処理を再利用可能な単位に切り分け、SageMakerのカスタムコンテナで実行可能となるように変更。SageMaker Pipelineを用いて、前処理・学習・モデル評価のコンテナを順次起動できるように整備した。これにより、顧客はビジネスロジック（前処理・学習・モデル評価）のみに集中可能となった。また、処理の負荷別にコンテナ実行インスタンスのスペックをスケールさせることによって、8時間以上かかっていた一連の処理実行時間を2〜3時間程度に短縮し、利用料金の節約も可能となった。  
現在は、SageMaker PipelinesとExperimentsの連携によって、一連の処理フローとそのパラメータ推移を「実験」という単位で管理できるように整備中。

  - 開発環境の権限の整備  
顧客のAWS開発フローをヒアリングして必要なAWS IAMの権限周りを整備。具体的には、特定の責任（ペイメント管理等）を持つユーザーが必要な時のみ必要な情報にアクセスできるようにIAMスイッチロール機能を構築。誤操作発生リスクを特定シーンに限定することで、顧客のより安全なAWSリソース運用管理の実現に貢献した。

  - 開発環境構築のIaC化  
他部門でも簡単に同一のMLOps統合開発環境を構築可能となる運用体制にしたいという要望を受け、リソース管理方法を整備した。AWSコンソールのUIは不定期に変更されるため、画面キャプチャを用いた作業手順は不採用とした。代わりに、再現性の観点から開発インフラ構築をCloudFormationテンプレートで管理して実行手順を整備。インフラコードはリソースのライフサイクルを考慮してML・IAM権限・ユーザー情報の3種に分け、スタックを分割して管理できるようにした。  
これにより、顧客のスムーズな開発環境の移行とインフラの再現が可能となった。

  - 顧客のMLエンジニアへのAWS技術教育  
顧客による中長期的なAWSの安定利用を実現するため、顧客のエンジニアに向けたAWS技術のレクチャーを実施中。具体的には、SageMakerと連携して使うS3やECR、Code系サービスやGitOps、AWS IAMといったサービスや技術に対して、AWS公式やGitHubにあるハンズオンを顧客のレベルにカスタマイズして実施。レクチャーでは、予め用意しておいた詳細なアーキテクチャ図や概念図を用いて、顧客が視覚的にAWSの使い方を理解できるように工夫することで、AWSで発生する問題を顧客自身が解決できるようになるための体制作りに貢献中。

### 社内システムのクラウドセキュリティ改善計画立案（2022年4月〜2022年9月）
- プロジェクト概要  
AWS利用の増大と用途の多様化に伴い、顧客のシステムでは膨大な数のセキュリティアラームが発生していた。インシデント発生予防と監視運用体制の確立が急務となったため、開発メンバーとして調査とKPIの設定、及びセキュリティ改善計画の作成と提案を実施した。  

- プロジェクトの規模  
計画承認者:情報セキュリティ部門、PO: 3名、開発: 3名、運用: 数100名、アドバイザー: AWS技術サポート数名  

- プロジェクトで利用した技術、ツール  
AWS (Well-Architected Framework / Trusted Advisor / Organizations(OU, SCP) / IAM / EC2(EBS, Security Group, ELB, Snapshot) / S3 / RDS(Snapshot) / CloudFront / Route 53 / Auto Scaling / Lambda / CloudWatch)  

- 発揮したバリュー
  - 顧客へのヒアリング  
  - 問題の整理、目標設定と提案  
  - 実施計画の作成  
  - 技術選定  
  - アラーム集計処理の実装  

- 担当業務
  - 現状の問題の把握  
顧客へのヒアリングにより、オンプレからAWS移行時にユーザー責任となるセキュリティ領域が増大しているにも関わらず、組織としてのクラウド利用ガイドラインが存在しないことから、各アカウント管理者のセキュリティレベルに依存したシステムが構築されていることがわかった。  
また、定量的に現状を把握するため、Trusted Advisorの組織ビュー情報を使い、アカウント別のセキュリティアラーム項目とその出力数を集計した。これによって、100以上存在する各アカウント上のシステムのセキュリティレベルにはバラツキがあること、古いリソースの利用によるアラーム発生がある程度の割合で存在していること、特定のセキュリティアラームが一部のアカウントに集中していることなど、戦略立案に必要な情報を把握することができた。

  - 戦略立案  
組織全体でクラウドセキュリティのレベルを上げるため、クラウド利用ガイドラインの作成方法を模索した。AWSにはWell-Architectedのセキュリティの柱に対応したベストプラクティスが存在するため、それに準拠することでゼロからガイドラインを作らずにセキュリティを高めることが可能である。ベストプラクティスは数が多いため「全アカウントへの適用可能性」「既存システムへの影響範囲の低さ」「現状体制での運用可能性」という選択軸を設け、ベストプラクティスの取り捨て選択を実施することを提案。しかしベストプラクティスの数の多さ、選択軸に該当しないベストプラクティスの存在、それによる選択軸そのものの選択の困難化、KPI達成期間内の現実的な実施可能性がチーム内で考慮された結果、この戦略案は不採用となった。  
Trusted Advisorがセキュリティの専門家による基本的なベストプラクティスを提案するためのAWSの公式ツールであること、セキュリティアラームを出力している項目と数をすでに集計で把握していること、セキュリティ項目が限られており選択軸を設定して優先順位をつけることが可能であることから、Trusted Advisorを利用し、セキュリティ項目別の施策を実施してくことを検討し、これを提案。顧客を説得できる現実的な戦略案として採択された。

  - 戦術立案  
Trusted Advisorの各セキュリティ項目ごとに具体的な実施計画を立ててKPIを設定。各施策の優先順位付けに客観的な説得力を持たせるため、CVSS(共通脆弱性評価システム)のスコア値を採択。これをもとに、セキュリティ施策の実行計画（マイルストーン）を作成した。これにより、施策実施スケジュールと予算獲得のための道筋をたてることが可能となった。

### 産業用加工装置のIoT化、及び遠隔監視アプリケーションの開発（2021年10月〜2022年3月）
- プロジェクト概要  
インシデント発生時における対応スピード改善と経費削減のため、運用している産業用加工装置の遠隔監視システムを開発した。また、開発内製化のため社内技術者へクラウド技術教育を実施した。  

- プロジェクトの規模  
PO: 1名、ステークホルダー: 多数、PM: 3名、装置開発: 顧客側のエンジニア50名、バックエンド開発: 5名  

- プロジェクトで利用した技術、ツール  
AWS (IoT Core / IoT Greengrass / IoT Events / IoT Device Management / CloudWatch / S3 / Glue / Timestream / Grafana / Lambda / SNS / CodeCommit /  CodePipeline / CloudFormation / ECR) | Git | Docker | Python | Jira | Backlog  

- 発揮したバリュー
  - 顧客要望のヒアリングと要件定義  
  - 技術選定  
  - クラウド設計  
  - コード開発とテスト  
  - CI/CDパイプラインの構築  
  - クラウドリソースのIaC化  
  - 社内技術者への技術教育  

- 担当業務
  - クラウドサービスの選定  
要件に合致するクラウドサービスを調査した。ナレッジ蓄積度、IoT系サービスの充実度、エンタープライズ向けサポートを既存契約しているという理由からAWSを提案、導入した。  

  - エッジ側アーキテクチャの構築  
IoTクライアントとしてAWS IoT Greengrassを採用。装置はIoT用途を想定して設計されていなかったため、データ取得用途で接続しているWindows機をゲートウェイ機として流用。Windows OS固有の機能制限リスクを回避するため無償利用できるHyper-VでUbuntuの仮想環境を構築。Greengrassをインストールして装置のIoT化を実現した。  

  - 遠隔監視アプリケーションのプロトタイプ構築  
ステークホルダーの要望によりプロトタイプを構築した。短期間で見栄えの良いアウトプットが構築可能なこと、SQLで細かい出力調整が可能なことからAmazon Managed Grafanaを提案、導入。グラフ表示用データ格納先としては、必要最小限の時系列データを格納できることと、データ保存期間を細かく調整できることからAmazon Timestreamを選択。  
開発中にデータの一部がTimestreamに登録されない問題が発生したが、クラウド側で受信データの欠損が確認できなかったことから問題発生箇所をTimestreamへの登録過程に絞り込み、登録可/不可データの差異に焦点を当てて調査を実施。結果的にTimestreamのテーブルフィールド名形式が公式ドキュメントに未記載のキャメルケース形式のみ対応であったことが分かり、形式を統一することによって解決。プロトタイプ構築を実現した。  

  - 装置ログファイルのアップロード機能構築  
エラー発生原因を装置の出力ログファイルから直接解析したいという要望により、数百MBのログファイルをクラウドに定期アップロードする機能を実装した。AWS IoT Core管理のクラウド連携証明書を利用できること、大容量ファイルをストリーミングアップロードできることからGreengrass StreamManagerを採択。また、クラウド側からアップロード実行間隔をコントロールできるようにAWS CloudWatch EventsとLambdaでPublisherを構築、IoT Coreのトピック経由でSubscribeして定期実行するように実装した。  

  - リソースのIaC化とCI/CDパイプラインの構築  
AWSリソースをCloudFormationでテンプレート化。デバイスの追加・削除といったIoT固有の運用ユースケースに沿って適切にスタック分割し、CDパイプラインを構築してリソース管理を整備した。またGreengrassやLambda等のコードをAWSのCode系サービスでGitフロー管理化し、デプロイブランチごとにCI/CDパイプラインを構築した。  

  - 技術教育  
現状の開発チームの技術力ではプロジェクトの進捗が遅れる可能性が共有されていたため、チームの技術教育系タスクを積極的に引き受けた。  
具体的な教育内容はスクリプトの命名規約やモジュール設計の方針、エラーハンドリングやテスト手法、インフラコードのスタック分割、CI/CDパイプラインの構築方法といった基本的な開発手法であり、必要となった時に開発チームへレクチャーを実施した。また、コードレビューをすべて引き受けることにより、レクチャーした内容を継続的に再教育できる体制を整えた。これにより、進捗の悪いタスクをスプリント完了前にフォローすることが可能となったため、次スプリントへの持ち越しタスク数を半分以下へ減らすことに成功した。  

### サーバレス翻訳アプリケーションのリプレイス開発・及び保守運用フローの整備（2021年4月〜2021年9月）
- プロジェクト概要  
業務用のサーバレス翻訳アプリケーションの技術的負債を洗い出し、全面的にリプレイス開発を実施した。  
このアプリは実用だけでなく社内技術者のクラウド技術教育を兼ねて開発されたものだが、技術的知見の不足によるエラーが多発している状態であった。原因追求も困難な状態だっため社内業務に支障がでており、早急な技術的負債の解消と安定運用手法の整備が求められていた。  

- プロジェクトの規模  
PO: 2名、PM: 1名、開発: 1名  

- プロジェクトで利用した技術、ツール  
AWS (IAM / CodeCommit / CodeBuild / CodeDeploy / CodePipeline / CloudFormation / Lambda / API Gateway / CloudWatch / ECR / Systems Manager / CloudFront / S3 / WAF) | GCP (IAM / Storage / Cloud Translation) | AWS SAM | Serverless Framework | Git | Docker | Python | Jira | Backlog  

- 発揮したバリュー
  - 技術的負債の洗い出し
  - 保守運用のためのルール整備
  - 安定運用のためのパフォーマンス・チューニング
  - クラウド設計
  - コード開発とテスト
  - CI/CDパイプラインの構築
  - クラウドリソースのIaC化
  - 社内技術者への技術教育

- 担当業務
  - 技術的負債の解消  
問題の原因調査と改善提案後、リプレイス開発を実施。  
具体的には、処理のモジュール化とtry節の範囲限定化によってエラーハンドリングを改善、開発手法をTDD化。これによって問題の早期発見と解決が可能となり、エラー発生率を1/20に抑えることに成功。  
また、Lambda環境変数で管理していた値をSSMパラメータストアに移し、処理内で取得できるエイリアス名から環境別の値を自動取得するように改善。  

  - 改修と処理のパフォーマンス・チューニング  
要望により、処理内で使用している翻訳APIの文字数制限を大幅に超える拡張の改修を実施。  
直列実行ではAPI Gatewayの30秒タイムアウト制限を超過するリスクがあったため、翻訳API実行処理の並列化を提案、実装。同時にLambdaのメモリ使用量増加に伴う料金上昇と処理時間の組み合わせパターンを提示し、最適なパターンを顧客に選択して頂いた。これによって、サーバレスAPIのタイムアウト発生リスクを抑え、現実的な料金でレスポンスタイムを1/2以下に削減することに成功した。  

  - リソースのIaC化とCI/CDパイプラインの構築  
静的コンテンツとLambdaコードをAWSのCode系サービスでバージョン管理するように変更し、CI/CDパイプラインを構築してリリース作業を自動化した。  
また、AWSリソースをCloudFormationでコード化。サーバレスリソースに関してはCloudFormationの拡張であるAWS SAMを使用した。IPアドレスによるアクセス制限やSSMパラメータストアの更新など、顧客の運用ユースケース別にリソースのライフサイクルを考え、CloudFormationテンプレートを適切にスタック分割。AWSサポートエンジニアからインフラコードの構成に問題ないことを確認した上で、運用プランを顧客に提案した。  

  - 技術教育  
顧客は社内のCCoE（Cloud Center of Excellence）を目指す部署であり、Webアプリケーションやクラウド技術についてはまだ発展途上であった。そのため、一般的なソフトウェア開発のベストプラクティスやクラウドを利用したCI/CDについて、業務とは別に技術教育を実施し、部署全体の技術力向上に貢献した。  

### 家庭用据え置きゲーム機のバックエンド機能の開発・パフォーマンス測定・動作検証（2020年11月〜2021年3月）
- プロジェクト概要  
家庭用据え置きゲーム機のバックエンド機能の開発・パフォーマンス測定・動作検証。

- プロジェクトの規模  
世界的な規模で展開。開発者 日本: 約1000名、 USA: 約200名。  
所属チーム: マネージャ 7名、テックリード 2名、Ops 2名、エンジニア 11名。

- プロジェクトで利用した技術、ツール  
AWS (ECS / ECR / Batch / Athena / S3 / Lambda / DynamoDB / EC2 / SNS / SQS / ALB / Auto Scaling / CloudWatch, その他) | Docker | Datadog | GitHub | その他社内独自のCI/CDツール

- 担当業務
  - オンライン対戦時のチームプレイセッション管理機能の機能修正、パフォーマンス測定、動作検証  
APIのバリデーション処理の修正・検証。  
DBアクセス時のパフォーマンス調査と改善修正、検証。  
処理キューの送受信時のパフォーマンス調査と改善修正、検証。  
デモ実機を使用しての動作検証。  

  - ユーザの行動履歴情報をもとに画面出力するサジェスチョン・トロフィー情報抑制のための調査・修正・動作検証  
APIの処理の修正・検証。  
DBキャッシュの時刻関連処理修正・動作検証。  

### 機械学習実行Webアプリケーションの開発（2018年6月〜2020年9月）
- プロジェクト概要  
教師あり機械学習によるデータ分析・予測を実行するためのWebアプリケーションを開発した。  

- プロジェクトの規模
PO: 1名、営業: 3名、CTO: 1名、開発: 5〜8名  

- プロジェクトで利用した技術、ツール  
AWS (API Gateway / Cost Explorer / CloudWatch / DynamoDB / Lambda / EC2 / ECS / ECR / IAM / Lambda / RDS(PostgreSQL) / S3 / SNS / Systems Manager) | GCP (BigQuery) | Git | GitHub | Docker | Python

- 発揮したバリュー
  - 顧客要望のヒアリングと要件定義
  - 技術選定
  - クラウド設計
  - APIコード開発とテスト

- 担当業務
  - プロトタイプの開発  
プロジェクトの初期フェーズから参画し、クラウド基盤にAWS、フレームワークにDjangoとDjango Rest Frameworkを使用してWebアプリケーションのプロトタイプを開発した。  
具体的には、ユーザー管理とデータのアップロード、AIエンジニアが作成した教師あり学習モデルの管理機能といった基本機能に加え、学習モデルとデータの特徴量紐付け画面を構築。POのプロダクトイメージを固め、要件定義を開始するための叩き台として本格的な開発が始まる前まで活用された。  

  - 機械学習ワークフローの要件定義  
モデル開発・学習データの用意・データの管理・学習・推論といった機械学習のワークフローをすべて自動化することは現実的ではないため、エンドユーザとシステムのどちらに各ワークフローを担保させるのかを顧客と調整し、要件を整理。モデル開発はAIエンジニア、学習データの用意は顧客、それ以外はシステムが担当するといった責任範囲を明確に定義。これにより、プロトタイプ開発時よりもスムーズに後続の開発作業を進めることが可能となった。  

  - アカウント管理機能の設計・実装  
エンドユーザには、アプリケーションが要求するデータのセキュリティレベル別に複数の権限を割り当てる必要があった。Djangoフレームワークのデフォルト機能ではカバーできない複雑な権限分けが必要となったため、ロールベースアクセス制御の論文を読んで概念をキャッチアップし、これを実装。  

  - 大容量データの分割アップロード機能の実装  
GB単位の学習データファイルアップロード機能が必要となったため、Amazon S3マルチパートアップロードAPIを実行するバックエンドAPIをFrontendエンジニアと協力して実装。バックエンド側にのみAWSの認証情報を保持し、アプリケーションのログイン認証を経てからでないとS3へのアップロードAPIの実行ができないようにセキュリティを担保した上で機能実装を行い、これを実現した。  

  - 推論実行バックエンドAPIの実装  
エンドユーザが入力した条件に基づいて推論結果のグラフ表示をする必要があったため、顧客とFrontendエンジニア、Frontendエンジニアと自分との間に、表示条件とグラフ表示用APIを連携させるための処理インターフェイスの綿密な認識合わせを行い、これを実装した。  

### 不動産情報、及び物件のレコメンドエンジンを持つWebアプリケーション（2017年10月〜2018年5月）
- プロジェクト概要  
不動産物件サイトと、アクセスユーザーに不動産情報をレコメンド表示するシステムのプロトタイプ開発。

- プロジェクトの規模  
プロジェクトマネージャ 1名、開発者 2名

- プロジェクトで利用した技術、ツール  
Python | Django | scikit-learn | JavaScript | jQuery | Bootstrap | HTML5 | CSS | PostgreSQL | AWS(EC2) | Ansible

- 担当業務
  - 要件定義、機能設計、実装、検証。
  - 管理者(クライアント)によるサイトの広告管理機能の実装。
  - 会員(不動産オーナー)管理機能の実装。
  - 不動産物件管理機能の実装。
  - cookieに紐付けたユーザーの行動追跡データを蓄積し、機械学習によるレコメンド情報の選出により、会員登録なしでアクセスユーザーにレコメンド情報を表示させる機能の実現。
  - 機械学習用のデータがなかったため、ユーザーの行動確率分布設定に基づいてサイト内行動追跡データを擬似的に生成する機能を実装し、これを解決。
  - Ansibleによるデプロイ構成管理設定。

### データ分析による医療製品販売サポートのためのWebアプリケーション（2017年6月〜2018年7月）
- プロジェクト概要  
医療品業者の営業・販売支援のためのデータ分析ツールのプロトタイプをWebアプリケーションとして開発。

- プロジェクトの規模  
プロジェクトマネージャ 1名、開発者 2名

- プロジェクトで利用した技術、ツール  
Python | Django | JavaScript | jQuery | D3.js | Bootstrap | HTML5 | CSS | PostgreSQL | AWS(EC2) | Ansible

- 担当業務
  - 要件定義、機能設計、実装、検証。
  - Webスクレイピングで既存サイトから分析用データを収集、保存。
  - 収集データを用いて、日本の地域の特性を散布図・棒グラフ・地図によって可視化することにより、クライアントが持っていなかった仕入れルートと販路の発見に貢献。

### 新卒採用のためのWeb予約申し込みシステム開発（2017年4月〜2018年4月）
- プロジェクト概要  
クライアントが使用していたSalesforceの予約管理システムと連携し、エンドユーザ(新卒予定の学生)が面談予約を行うためのWebアプリケーションを新規開発。

- プロジェクトの規模  
PM 1名、開発者 3名

- プロジェクトで利用した技術、ツール  
PHP5.x | ZendFramework | PostgreSQL | JavaScript | jQuery | AWS(EC2)

- 担当業務
  - プロジェクト管理、要件定義、設計、開発、検証、保守。
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証と保守まで一貫したプロジェクトの管理を実現。
  - 段階リリースのためのスケジュール提案、Salesforceと予約システムの相互連携のための仕様調整を実施。
  - 予約枠情報・学生情報・予約情報の連携API開発。
  - Salesforce連携機能の開発事例の実績を会社に追加することへの貢献。

### クレジットカード会社の特典表示制御機能開発（2016年4月〜2016年5月）
- プロジェクト概要  
某大手クレジット会社のサイトの会員特典データ・広告表示を制御する機能を開発。

- プロジェクトの規模  
PL 1名、開発者 2名

- プロジェクトで利用した技術、ツール  
JavaScript | jQuery

- 担当業務
  - プロジェクト管理、設計、開発、検証。
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証と保守まで一貫したプロジェクトの管理を実現。
  - 会員特典・広告表示の制御判定、出力処理の実装。
  - OS・端末別の検証ケースの洗い出し、検証。
  - 既存システムのサーバーサイドへの影響を最小限に抑えるというクライアントの要望を、すべてクライアントサイド(JavaScript)で実装することで実現。
  - JavaScriptのベテラン経験者がいない中で、Promiss等の必要となる技術をすばやくキャッチアップして開発。

### アパレル物流の在庫管理用パッケージングシステムのAPI開発（2015年11月〜2016年2月）
- プロジェクト概要  
アパレルの製造から出荷を管理する既存システムのうち各プロセス間のデータ連携処理を、ファイル出力連携からAPI連携に改修。

- プロジェクトの規模  
PM 1名、開発者 3名

- プロジェクトで利用した技術、ツール  
PHP5.x | PostgreSQL | JavaScript

- 担当業務
  - プロジェクト管理、開発、検証。
  - クライアントとの要件定義、仕様調整。
  - 既存システムの調査・報告と改善案の提案。
  - API処理の設計、ドキュメント化、実装。
  - 単体テスト、結合テストの実施。
  - 既存システムに連携機能のドキュメントが存在しなかったため、仕様をソースコードから調査して改修箇所を選定。実際の運用フェーズでの作業とのすり合わせを実施し、具体的な実装案をクライアントに提案。
  - それまで問題となっていた連携出力ファイル内のデータ欠損やファイルロックによる処理の遅延が、提案したAPIと新設したトランザクションデータ管理により解決。

### 会議室のWeb予約システム（2014年11月〜2015年5月）
- プロジェクト概要  
某大手の商品販促セミナー会議室の会員制Web予約システムを開発。

- プロジェクトの規模  
PM 1名、開発者 5名

- プロジェクトで利用した技術、ツール  
PHP5.x | ZendFramework | SQL Server | JavaScript | jQuery | AWS(EC2) | IIS(DBサーバ) | LDAP

- 担当業務
  - プロジェクト管理、要件定義、設計、開発、検証、保守。
  - クライアントとの要件定義、仕様調整。
  - 支店と会員情報・予約枠の組み合わせによる様々な予約制御機能の実装。
  - クライアントのActive Directory にアクセスするLDAPログイン認証を実装。
  - 単体予約枠を分割、もしくは結合させて予約できる機能のDB設計と実装。
  - 運用マニュアル作成のドキュメント化。
  - 単体テスト、結合テストの実施。
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証、保守まで一貫したプロジェクトの管理を実現。
  - アプリサーバはLinux、DBサーバーはIIS、SQL Server の組み合わせであったため、フレームワークにDB接続用のドライバが存在せず、独自実装することにより解決。
  - 「予約枠の分割・結合機能」はASP予約システムパッケージの基本設計では実現できなかったため、システムを再設計することにより実現。

### スポーツジムのWeb予約システム（2013年9月〜2013年10月）
- プロジェクト概要  
都内のスポーツジムの設備とレッスンのWeb予約システムの開発。

- プロジェクトの規模  
開発者 4名

- プロジェクトで利用した技術、ツール  
PHP5.x | Zendframework | JavaScript | PostgreSQL

- 担当業務
  - プロジェクト管理、要件定義、設計、開発、検証、保守。
  - クライアントとの要件定義、仕様調整。
  - 支店と会員の種類による複数の予約枠管理機能増設の実装。
  - 支店と会員情報・予約枠の組み合わせによる様々な予約制御機能の実装。
  - 支店と会員情報・予約枠の組み合わせによる抽選機能とリスク対策のための
  - ログ出力・メール通知機能の実装。
  - 運用マニュアル作成のドキュメント化。
  - 単体テスト、結合テストの実施。
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証、保守まで一貫したプロジェクトの管理を実現。
  - それまで手作業で実施されていた各予約枠の抽選プロセスをすべて自動化することにより、システム運用の大幅な人的リソース削減を実現。
  - 多大な負荷がかかる抽選処理において、不慮の原因による不整合データの発生と問題の拡散を防ぐため、ログ出力とメール通知をクライアントに提案、リスクの削減を実現。

### 車載ナビのシミュレーションサイト開発（2013年1月〜2013年7月）
- プロジェクト概要  
車載ナビシステムのシミュレーション体験をエンドユーザに提供するためのシステム開発。

- プロジェクトの規模  
開発者 3名、デザイナー 1名

- プロジェクトで利用した技術、ツール  
PHP5.x | JavaScript | jQuery | PostgreSQL

- 担当業務
  - 要件定義、開発、検証
  - クライアントとの要件定義、仕様調整。
  - Google Map APIの調査、必要なAPIのリストアップとインターフェース・DB設計。
  - 会員情報管理機能、管理機能、コンテンツ情報管理機能の開発。
  - frontendのコンテンツ操作処理の実装。
  - Google Map APIを使ったリッチコンテンツの開発実績を追加。
  - 複雑なAPIの仕様をまとめ、チーム開発のスピードアップに貢献。

### 旅の思い出共有サイトの開発（2011年12月〜2012年11月）
- プロジェクト概要  
初の自社開発サービスである旅の思い出共有サイト “Travel Reco” CMSの開発。

- プロジェクトの規模  
開発者 10〜15名、デザイナー 2名

- プロジェクトで利用した技術、ツール  
PHP5.x | Zendframework | JavaScript | jQuery | PostgreSQL

- 担当業務
  - 要件定義、開発、検証、運用。
  - 必要な要件のリストアップ。
  - DB・機能設計。
  - 開発ドキュメントの整理。
  - 会員情報管理機能、コンテンツ情報管理機能の開発。
  - ファイルアップロード機能の開発。
  - Twitter、Facebookへのコメント共有機能の開発。
  - 初の自社開発サービスであり、スクラッチ開発であったため、それまで使用していたZendFrameworkではなく、トレンドであったCakePHPフレームワークをメリット・デメリットとともに提案（結果的には却下される）。
  - SNS連携機能の開発実績を追加。

### 某大手カップヌードル施設の見学予約システム開発（2011年4月〜2011年10月）
- プロジェクト概要  
某大手の施設サイトの見学予約システムの開発。自社フレームワークである予約システムのカスタマイズ。

- プロジェクトの規模  
開発者 7名

- プロジェクトで利用した技術、ツール  
PHP5.x | Zendframework | JavaScript | jQuery | PostgreSQL

- 担当業務
  - 要件定義、開発、検証。
  - 要件定義、機能開発。
  - DB・機能設計。
  - 検証。
  - 期間イベントによって予約枠の幅や予約人数が動的に変化するなど、非常に要件が複雑なシステムであったため、要件定義にかなり時間をかけるように提案。チーム間の進捗のズレとコミュニケーションロスを最小限に抑えるようにスケジュールを徹底。

### 某脱毛サロン予約システムの開発（2009年5月〜2009年7月）
- プロジェクト概要  
某大手のサロン施設サイトの予約システムの開発。自社フレームワークである予約システムのカスタマイズ。

- プロジェクトの規模  
PM 1名、開発者 5名

- プロジェクトで利用した技術、ツール  
PHP5.x | Zendframework | JavaScript | jQuery | PostgreSQL

- 担当業務
  - 要件定義、開発、検証。
  - 要件定義、機能開発。
  - DB・機能設計。
  - 会員管理機能・管理側機能の開発。
  - 検証。
  - 夏のキャンペーンに間に合わせるためにかなり開発スピードを上げなければならなかった案件。

### 大手ロードサービス会員向けコンテンツサイトシステム（2008年12月〜2009年4月）
- プロジェクト概要  
ロードサービスの会員向けコンテンツ情報共有サービスの開発。

- プロジェクトの規模  
開発者 4名

- プロジェクトで利用した技術、ツール  
PHP5.x | JavaScript | jQuery | PostgreSQL

- 担当業務
  - 要件定義、開発、検証。
  - 会員情報管理機能の実装。
  - 会員区分別のコンテンツ出し分け処理の実装。
  - 会員からの取り合わせフォームの実装。
  - frontendの簡単なコンテンツ表示切り替え処理をjQueryで実装。
  - 単体テスト、結合テストの実施。
  - プロジェクトリーダーとして、顧客・デザイナーと要件定義・仕様調整を担当。
  - プログラマとして、サーバサイドの開発・検証までを担当。
