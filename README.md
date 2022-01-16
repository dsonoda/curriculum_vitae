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
AWS (IoT Core / IoT Greengrass / IoT Events / IoT Device Management / CloudWatch / S3 / Glue / Timestream / Grafana / Lambda / SNS / CodeCommit /  CodePipeline / CloudFormation / ECR) | Git | Docker | Python | Jira | Backlog

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

### サーバレス翻訳アプリケーションのリプレイス開発・及び保守運用フローの整備（2021年4月〜2021年9月）
- プロジェクト概要  
社内業務用のサーバレス翻訳アプリケーションの技術的負債を解消するため、システムを全面的にリプレイス開発した。  
このアプリは、実用だけでなく社内技術者のWeb・クラウド技術教育を兼ねて開発されたものであった。そのため技術的知見の不足によるエラーが多発しており、原因追求も困難な状態だった。社内業務に支障がでており、早急な技術的負債の解消と安定運用に向けた取り組みが求められていた。

- プロジェクトの規模  
PO: 2名、PM: 1名、開発: 1名

- プロジェクトで利用した技術、ツール  
AWS (IoT Core / IoT Greengrass / IoT Events / IoT Device Management / CloudWatch / S3 / Glue / Timestream / Grafana / Lambda / SNS / CodeCommit /  CodePipeline / CloudFormation / ECR) | Git | Docker | Python | Jira | Backlog

- 担当業務
  - サーバレスAPI（AWS Lambda）の技術的負債の解消  
問題の原因調査を行い、改善提案とリプレイス開発を実施。  
処理内のtry節が大きいことによって例外が握り潰されておりエラー発生原因の特定を困難にしていたため、意味のある単位で処理をモジュール化し、try節の担当範囲を適切に絞り込むことによってエラーハンドリングを改善。加えて、外部連携処理をMock化することでテストコードの責任範囲を限定化した。これらの改善によって、問題の早期発見と解決が可能となり、エラー発生率を1/20に抑えることに成功。  
また、LambdaのバージョンにLambda環境変数が紐づく仕様により、システムリリース時に環境変数の手動設定ミスが多発していた。Lambda環境変数で管理していた値をSSMパラメータストアに移し、処理内で取得できるエイリアス名から環境別の値を自動取得するように改善。これにより、リリース時のヒューマンエラー発生リスクを大幅に削減した。

  - サーバレスAPI（AWS Lambda）のパフォーマンス改善  
顧客の要望により翻訳テキストの文字数拡張が必要となった。処理内ではGCP翻訳APIを使用しているが、その仕様を大幅に超える文字数であった。仮にテキスト分割してGCP翻訳APIを直列実行してもAmazon API Gatewayの30秒タイムアウト制限を超過するリスクがあったため、Lambdaのメモリ増加に伴う料金上昇とタイムアウト発生リスクを比較検討した上で、メモリ増設+GCP翻訳API実行処理の並列化を提案、実装。これによって、サーバレスAPIのタイムアウト発生を極力抑えつつ、レスポンスタイムを1/2以下に削減することに成功した。

  - アプリケーションコードのCI/CD化  
サーバレスシステムの静的コンテンツがバージョン管理されておらず手動リリース体制となっていた。問題の原因調査を困難にしている一因であったため、AWSのCode系サービスでバージョン管理するように変更。加えて、プルリクエスト機能によりリリースコードの管理責任範囲を明確化した。また、Code系サービスのCI/CD機能によってリリース作業を自動化し、問題発生時のロールバックを容易にすることによってリリース作業のリスク削減を実現した。

  - サーバレスシステムのインフラコード化  
AWSのインフラリソースが管理されておらず、手動でのリソースの変更履歴がトレース出来ない状態であった。これではインシデント発生時の原因特定が困難となることに加え、リソース構築の再現性に関する社内クラウド技術資産の蓄積につながらない。これを解決する手段として、サーバレスリソースのコード化を提案した。  
構成管理ツールは、インフラコード化の入門者でも運用管理を可能にして欲しいという顧客の要望により、AWSコンソールからテンプレート単位で手動更新可能なAWS CloudFormationを採択。また、サーバレス関連リソースの構築は、CloudFormationの拡張であるAWS SAM(Serverless Application Model)を採択した。  
APIのアクセス制限IPアドレスやSSMパラメータストアの更新など、顧客の運用ユースケース別にリソースのライフサイクルを考え、CloudFormationテンプレートを適切にスタック分割。AWSサポートエンジニアからインフラコードの構成に問題ないことを確認した上で、運用プランを顧客に提案した。

  - 技術教育
顧客は社内のCCoE（Cloud Center of Excellence）を目指す部署であり、Webアプリケーションやクラウド技術についてはまだ発展途上であった。そのため、一般的なソフトウェア開発のベストプラクティスやクラウドを利用したCI/CDについて、業務とは別に技術教育を実施し、部署全体の技術力向上に貢献した。
