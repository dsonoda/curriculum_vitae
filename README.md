# 業務経歴書

## 基本情報

|key|value|
|:---|:---|
|氏名|園田 大輔|
|住所|東京都 目黒区<br>最寄り駅: 東急目黒線 武蔵小山駅|
|E-mail|mail@daisukesonoda.com|
|blog|[Qiita](https://qiita.com/dsonoda)<br>[Zenn](https://zenn.dev/dsonoda)|
|著書|「[AWSエンジニア入門講座―学習ロードマップで体系的に学ぶ](https://www.amazon.co.jp/AWS%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E5%85%A5%E9%96%80%E8%AC%9B%E5%BA%A7%E2%80%95%E2%80%95%E5%AD%A6%E7%BF%92%E3%83%AD%E3%83%BC%E3%83%89%E3%83%9E%E3%83%83%E3%83%97%E3%81%A7%E4%BD%93%E7%B3%BB%E7%9A%84%E3%81%AB%E5%AD%A6%E3%81%B6-CloudTech%E3%83%AD%E3%83%BC%E3%83%89%E3%83%9E%E3%83%83%E3%83%97%E4%BD%9C%E6%88%90%E5%A7%94%E5%93%A1%E4%BC%9A/dp/4297125374/ref=sr_1_1_sspa?keywords=aws+%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2&qid=1642343661&sprefix=aws+enn%2Caps%2C170&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyWlNCMDdNT0laRlROJmVuY3J5cHRlZElkPUEwNTM1NTQ1NVVVNlVPTFhPNlQ1JmVuY3J5cHRlZEFkSWQ9QTNMTVBJM1hCVUVXOTMmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)」共著<br>AWS入門者向け書籍を有志メンバーで共同執筆。担当はCloudFrontとCloudWatchの章。|
|資格| 2021年2月 AWS認定 Solutions Architect Associate 取得<br /> 2021年2月 AWS認定 Cloud Practitioner 取得|

## 概要
- 現在はAWSのクラウドアーキテクチャ設計、クラウドインフラ構成管理、DevOpsをメイン業務としています。
- IoT、機械学習、WebアプリのバックエンドAPI開発、などの広い範囲の開発実績があります。
- 小〜中規模プロジェクトの新規開発フェーズで最もパフォーマンスを発揮します。
- 大企業での開発内製化、及び社員の技術教育の実績があります。
- 小規模自社開発スタートアップにて、初期〜運用フェーズにおける要件定義・設計・実装・検証・デプロイまでの一通りの実務経験があります。
## スキル
- 業務で使用した技術のみを列挙しています。

### クラウド
#### AWS
EC2 | VPC | IAM | Organizations | Cognito | Route53 | Certificate Manager | CloudFront | WAF | ELB | Auto Scaling | IoT Core | IoT Greengrass | IoT Events | IoT Device Management | CodeCommit | CodeBuild | CodeDeploy | CodePipeline | CloudFormation | API Gateway | Lambda | CloudWatch | X-Ray | DynamoDB | RDS(Aurora, PostgreSQL) | Timestream | Redshift | S3 | Athena | Glue | Managed Grafana | SES | SNS | SQS | Systems Manager | ECR | ECS | Fargate | Batch

#### GCP
BigQuery | Storage | IAM | Cloud Translation

### 言語
Python | JavaScript | PHP | SQL | Shell

### フレームワーク
Django | Django REST framework | Flask | CakePHP | Zend Framework | jQuery

### RDB
PostgreSQL | MySQL | SQL Server

### その他ツール
Docker | AWS SAM | Serverless Framework | nginx | gunicorn | Apache | RabbitMQ | LDAP | GitHub | GitLab | CircleCI | DataDog | Jira | Backlog

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

### 産業用加工装置のIoT化、及び遠隔監視アプリケーションの開発（2021年10月〜現在）
- プロジェクト概要  
顧客が開発運用している産業用加工装置は、インシデント発生時におけるサポートが電話対応からの現地出向となっている。エンドユーザからの対応スピード改善要望と人件費削減のため、装置の遠隔監視システムを開発した。  
本プロジェクトでは開発内製化も重要な目標であったため、社内技術者のWeb・クラウドに関する技術教育にも焦点を当てたプロジェクト進行が求められた。

- プロジェクトの規模  
PO: 1名、ステークホルダー: 多数、PM: 3名、装置開発: 顧客側のエンジニア50名、バックエンド開発: 5名

- プロジェクトで利用した技術、ツール  
AWS (IoT Core, IoT Greengrass, IoT Events, IoT Device ManagementAmazon, CloudWatch, S3, Glue, Timestream, Grafana, Lambda, SNS, CodeCommit, CodePipeline, CloudFormation, ECR) | Git | Docker | Python | Jira | Backlog

- 担当業務
  - クラウドサービスの選択  
AWS、Azure、GCPの中から顧客要件に合致するクラウドサービスを調査した。顧客のナレッジ蓄積度、IoT系サービスの充実度、顧客が既に契約しているエンタープライズ向けサポートがあるという理由からAWSを提案、導入。

  - エッジ側アーキテクチャの構築  
エッジ側のIoTクライアントとしてAWS IoT Greengrassを採用。ただし装置はIoT用途を想定して設計されておらず、稼働実績のある装置にGreengrassをインストールすることもできない。加えて装置にはネットワーク接続のインターフェイスがなかった。そのため、データ取得用途で一時的に装置へ接続していたWindows機をネットワーク接続用のゲートウェイ機として流用。当初、GreengrassはLinuxでの動作保証のみであったため、ゲートウェイ機に立てたGreengrass用Dockerコンテナの内部から装置側のAPIを実行するように実装。クラウド側へのデータ送信を確認し、稼働中の装置のIoT化を実現した。

  - 遠隔監視アプリケーションのデモ用サービスの選定  
プロジェクト継続の可否を判断するため、ステークホルダーから装置の遠隔監視アプリケーションのデモを観たいという要望があった。すぐに見栄えのよいアウトプットが用意でき、一時的なアウトプットサービスとして利用できるAmazon Managed Grafanaを提案、導入。

  - 遠隔監視アプリケーションのデモの設計・構築  
クラウド側で受信したデータをIoT Coreのルールエンジン経由で時系列DBであるAmazon Timestreamに登録、Grafanaから参照することで時系列グラフを表示するように実装した。　　
しかし、データの一部がTimestreamに登録されない問題が発生。クラウド側で受信データの欠損は確認できなかったことから、問題発生箇所をTimestreamへのデータ登録過程に絞り込み、登録可/不可のデータの差異に焦点を当てて調査を実施。その結果、Timestreamのデータ登録用フィールド名が公式ドキュメントにも記載されていないキャメルケース形式のみの対応であったことが分かり、データのフィールド名形式を統一。これにより稼働中の装置の遠隔監視アプリケーション構築を実現した。

  - 遠隔監視アプリケーションのパフォーマンス測定  
ステークホルダーへのデモで必要となるため、エッジ側の装置APIのレイテンシー、Grafana表示するまでの処理時間などのパフォーマンス測定を実施した。エッジ側でのデータ取得処理開始からクラウド側でのGrafanaアウトプットまでを1フローとし、Greengrass処理やAWSの各サービス等、各レイヤーで発生する処理時間をAWS Lambda経由でCloudWatch Logsの同一ロググループに出力。その後、CloudWatch Logs Insightsのクエリでフロー単位の処理時間集計を実施し、測定結果の情報をまとめて提出した。　　
問題ないパフォーマンスをデモで提示できたことにより、ステークホルダーからプロジェクトの正式なGoサインを頂くことができた。

  - 技術教育  
開発チームの技術力向上のため、チームの技術教育系タスクを積極的に引き受けた。具体的な教育内容はスクリプトの命名規約やモジュール設計の方針、エラーハンドリングやテスト手法、インフラコードのスタック分割、CI/CDパイプラインの構築方法といった基本的な開発手法であり、必要となった時に開発チームへレクチャーを実施した。また、コードレビューをすべて引き受けることにより、レクチャーした内容を継続的に再教育できる体制を整えた。これにより、進捗の悪いタスクをスプリント完了前にフォローすることが可能となったため、次スプリントへの持ち越しタスク数を半分以下へ減らすことに成功した。
