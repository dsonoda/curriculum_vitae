# 業務経歴書

## 基本情報

|key|value|
|:---|:---|
|氏名|園田 大輔|
|住所|東京都 目黒区<br>最寄り駅: 東急目黒線 武蔵小山駅|
|E-mail|mail@daisukesonoda.com|
|blog|[Qiita](https://qiita.com/dsonoda)<br>[Zenn](https://zenn.dev/dsonoda)|
|資格| 2021年2月 AWS認定 Solutions Architect Associate 取得<br /> 2021年2月 AWS認定 Cloud Practitioner 取得|

## 概要
- サーバレス・コンテナ基盤・マイクロサービスの開発実績があります。
- Webアプリケーションのサーバサイド、APIの豊富な開発経験があります。
- 機械学習の実行ワークフローで必要となる機能要件への知見があります。
- AWS/GCPの基本的なマネージドサービスを使用した開発経験があります。
- 小規模自社開発スタートアップ企業にて、初期〜運用フェーズにおける要件定義・設計・実装・検証・デプロイまでの一通りの実務経験があります。

## valueを発揮しやすい業務
- Webアプリ・API等の機能開発全般。 
- AWSのマネージドサービスを活用したバックエンド機能開発。 
- 機械学習を用いたWebアプリケーションにおける周辺機能の実装。 

## 興味のある技術
- DevOps全般
  - コンテナ基盤の活用
  - CI/CDパイプライン構築(CircleCI、GitHub Actions、AWS CodePipeline等)
  - インフラのコード化(Terraform、AWS CloudFormation等)
- DDD & クリーンアーキテクチャー

## スキル

### クラウド

|key|value|
|:---|:---|
|AWS|設計全般<br />EC2 / S3 / ELB / Auto Scaling / CloudFront / CloudWatch / X-Ray / IAM / Organizations / API Gateway / Lambda / Cognito / DynamoDB / RDS / SES / SNS / SQS / SSM / Athena / ECS / Fargate / ECR / CodeCommit / CodePipeline / CodeBuild / CodeDeploy / CloudFormation / Lookout for Metrics / Fault Injection Simulator|
|GCP|BigQuery / Storage / IAM / その他API|

### 言語

|key|value|
|:---|:---|
|Python|3年。3.x系によるWebアプリケーション・RESTful APIの開発の経験あり。現在メインで使用している。|
|PHP|11年。5.x系によるWebCMSサービス開発の経験あり。現在はブランクがある。|
|JavaScript|jQueryによるフロントエンドの実装経験あり。現在はブランクがある。|

### フレームワーク

|key|value|
|:---|:---|
|Django|3年。1.x系から3.x系によるWebアプリケーション・RESTful APIの開発経験。|
|Flask|半年。AWS LambdaでのAPI開発経験。|
|Vue.js|個人開発プロダクトで少し触った程度。|
|jQuery|7年。外注のデザインテンプレートを利用したfrontendの開発経験。|
|CakePHP|3年。PHP開発時代にメイン使用。|
|Zend Framework|7年。PHP開発時代にメイン使用。|

### データストア
- 現在はフレームワークやマネージドサービスでラップするため直接SQLを叩くような開発はしていないが、基本的なSQLは操作可能。

|key|value|
|:---|:---|
|PostgreSQL|13年。メインで使用。|
|MySQL|10年。メインでは使用しないが一応使える。|

### 機械学習への知見
教師あり学習についての具体的な機能要件の把握。

- 機械学習実行ワークフローにおける実行担当者の責任範囲の切り分けと整理。
- 大容量の訓練用データファイルをS3にアップロードする手法。
- データの前処理。
- 特定条件で抽出したデータレコードへのラベリング（教師データの生成）。
- 教師あり学習による学習済みモデルの生成。
- 推論とその結果出力。
- 追加学習。
- 学習で必要な特徴量と訓練データカラムの紐付け。

### その他
- バージョン管理・プロジェクト管理は Git / GitHub がメイン。

|key|value|
|:---|:---|
|GitHub|バージョン管理・プロジェクト管理で使用。|
|Docker/docker-compose|開発で使用。|
|ハードウェア|Raspberry Pi、Arduinoを使った電子工作。|

## 主な業務経歴

### サーバレスシステムのリプレイス (2021/4〜現在)
- **プロジェクト概要**
  - 社内サーバレスシステムのリプレイス（設計、開発、運用フローの整備、改善提案）。
- **プロジェクトの規模**
  - PO 2名、PL 1名、開発者2名
- **プロジェクトで利用された技術**
  - アプリケーション: Python3 / Docker / AWS　(Lambda / Cloud9) / GCP　(翻訳API)
  - インフラ: AWS　(API Gateway / ECS / Fargate / ECR / CodeCommit / CodePipeline / CodeBuild / CodeDeploy / CloudWatch / X-Ray / SNS / Route53 / CloudFront / S3 / EC2, その他) / GCP　(IAM / Storage)
  - 構成管理: AWS SAM / CloudFormation
- **担当業務**
  - 既存のサーバレスシステムのリプレイス
    - 問題点の洗い出し。
    - SPAサイトのCI/CDパイプライン構築。
    - サーバレスシステムの機能の再設計・開発・運用フローの整備。
  - 技術指導
    - クライアントの開発チームへのコードレベルの技術指導。
- **主な成果**
  - クライアントの要望に加え、既存システムの再設計と開発、運用フローの再整備を提案、実施。
  - 改善提案の実施によって納品スケジュールの大幅な短縮を実現、所属チームの社内評価の向上に貢献。

### 家庭用据え置きゲーム機のバックエンド機能の開発 (2020/11〜2021/3)
- **プロジェクト概要**
  - 家庭用据え置きゲーム機のバックエンド機能の開発・パフォーマンス測定・動作検証。
- **プロジェクトの規模**
  - 世界的な規模で展開。開発者 日本: 約1000名、 USA: 約200名
  - 所属チーム: マネージャ 7名、テックリード 2名、Ops 2名、エンジニア 11名
- **プロジェクトで利用された技術**
  - Python3 / AWS　(ECS / ECR / Batch / Athena / S3 / Lambda / DynamoDB / EC2 / SNS / SQS / ALB / Auto Scaling / CloudWatch, その他) / Datadog / GitHub / その他社内独自のCI/CDツール
- **担当業務**
  - オンライン対戦時のチームプレイセッション管理機能の機能修正、パフォーマンス測定、動作検証
    - APIのバリデーション処理の修正・検証。
    - DBアクセス時のパフォーマンス調査と改善修正、検証。
    - 処理キューの送受信時のパフォーマンス調査と改善修正、検証。
    - デモ実機を使用しての動作検証。
  - ユーザの行動履歴情報をもとに画面出力するサジェスチョン・トロフィー情報抑制のための調査・修正・動作検証
    - APIの処理の修正・検証。
    - DBキャッシュの時刻関連処理修正・動作検証。

### 機械学習実行Webプラットフォーム(SaaS)の開発 (2018/06〜2020/09)
- **プロジェクト概要**
  - 機械学習によるデータの分析・予測の実行webアプリケーションの開発。
- **プロジェクトの規模**
  - プロダクトオーナー 1名、営業 3名、CTO 1名、開発者 5〜8名
- **プロジェクトで利用された技術**
  - Python3.6 / Django3 / DjangoRestFramework / Angular.js / AWS(AWS Organizations / API Gateway / Cost Explorer / Cloud Front / Cloud Watch / DynamoDB / EC2 / ECS / EMR / IAM / Lambda / RDS(PostgreSQL) / S3 / SageMaker / SES / SNS / SSM) / GCP(BigQuery) / AirFlow / embulk / fluentd / kubernetes / Spinnaker / Docker / boto3 / Google Cloud SDK
- **担当業務**
  - 要件定義、機能設計、実装、検証
- **業務詳細**
  - Webアプリケーションの初期プロトタイプ設計・実装。
  - Luigiによる機械学習(学習・推論・追加学習)実行パイプラインのプロトタイプ設計・実装。
  - アカウント管理機能の設計・実装。
  - S3への大容量データファイルの分割アップロード機能の設計・実装。
  - データセット管理機能の設計・実装。
  - 学習・推論・追加学習・データラベリングのための各種マネージド・サービスとの連携APIの設計・実装。
  - 機能別アクセス制御(RBAC)の設計・実装。
  - 特定機能へのリクエストに対する承認プロセスを設置する機能の設計・実装。
  - AWS/GCPの課金情報追跡・集計機能の設計・実装。
- **主な成果**
  - プロジェクトの初期開発から参画し、プロトタイプ作成〜運用までの各フェーズにおいて要件定義・設計・実装・デプロイまで幅広い実務経験を積む。
  - 教師あり機械学習の実行ワークフローの具体的な機能要件を把握。
  - 注意すべきこととして、開発メンバー間で発生したコミュニケーションロスがプロジェクトに及ぼす影響の大きさとそれを防ぐための措置、インフラへの理解の必要性について実感できたことは大きな収穫です。  
  - 技術的・時間的な理由によりCI/CDとkubernetesを利用した実務経験を積めなかったため、そちらをカバーする技術力を身につける必要性を認識できました。

### 不動産情報、及び物件のレコメンドエンジンを持つWebアプリケーション (2017/10〜2018/05)
- **プロジェクト概要**
  - 不動産物件サイトと、アクセスユーザーに不動産情報をレコメンド表示するシステムのプロトタイプ開発。
- **プロジェクトの規模**
  - プロジェクトマネージャ 1名、開発者 2名
- **プロジェクトで利用された技術**
  - Python3.6 / Django1.x / scikit-learn / JavaScript / jQuery / Bootstrap3.x / HTML5 / CSS / PostgreSQL / AWS(EC2) / Ansible
- **担当業務**
  - 要件定義、機能設計、実装、検証
- **業務詳細**
  - プロジェクトリーダー兼プログラマとして、要件定義、設計、開発、検証を担当。
  - 管理者(クライアント)によるサイトの広告管理機能の実装。
  - 会員(不動産オーナー)管理機能の実装。
  - 不動産物件管理機能の実装。
  - cookieに紐付けたユーザーの行動追跡データを蓄積し、機械学習によるレコメンド情報の選出により、会員登録なしでアクセスユーザーにレコメンド情報を表示させる機能の実現。
  - 機械学習用のデータがなかったため、ユーザーの行動確率分布設定に基づいてサイト内行動追跡データを擬似的に生成する機能を実装し、これを解決。
  - Ansibleによるデプロイ構成管理設定。
- **主な成果**
  - ユーザ行動の疑似データ生成や、scikit-learnによるレコメンドエンジン開発という機械学習システム開発を経験できたことは収穫でした。
  - プロトタイプのため成果物の本番運用まではいかなかったことが残念です。

### データ分析による医療製品販売サポートのためのWebアプリケーション (2017/06〜2017/07)
- **プロジェクト概要**
  - 医療品業者の営業・販売支援のためのデータ分析ツールのプロトタイプをWebアプリケーションとして開発。
- **プロジェクトの規模**
  - プロジェクトマネージャ 1名、開発者 2名
- **プロジェクトで利用された技術**
  - Python3.6 / Django1.x / JavaScript / jQuery / D3.js / Bootstrap3.x / HTML5 / CSS / PostgreSQL / AWS(EC2) / Ansible
- **担当業務**
  - 要件定義、機能設計、実装、検証
- **業務詳細**
  - プロジェクトリーダー兼プログラマとして、要件定義、設計、開発、検証を担当。
  - Webスクレイピングで既存サイトから分析用データを収集、保存。
- **主な成果**
  - データの視覚化という非常に興味深い実績を積む。
  - 収集データを用いて、日本の地域の特性を散布図・棒グラフ・地図によって可視化することにより、クライアントが持っていなかった仕入れルートと販路の発見に貢献。
  - クライアントの評価が高かったことで、成果物としての完成度もかなり高いものができたと自負しています。

### 新卒採用のためのWeb予約申し込みシステム開発 (2017/04〜2018/04)
- **プロジェクト概要**
  - クライアントが使用していたSalesforceの予約管理システムと連携し、エンドユーザ(新卒予定の学生)が面談予約を行うためのWebアプリケーションを新規開発。
- **プロジェクトの規模**
  - PM 1名、開発者 3名
- **プロジェクトで利用された技術**
  - PHP5.x / ZendFramework / PostgreSQL / JavaScript / jQuery / AWS(EC2)
- **担当業務**
  - プロジェクト管理、要件定義、設計、開発、検証、保守
- **業務詳細**
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証と保守まで一貫したプロジェクトの管理を実現。
  - 段階リリースのためのスケジュール提案、Salesforceと予約システムの相互連携のための仕様調整を実施。
  - 予約枠情報・学生情報・予約情報の連携API開発。
  - Salesforce連携機能の開発事例の実績を会社に追加することへの貢献。
- **主な成果**
  - 会社の独自フレームワークと別企業で運用中のSalesforceシステムとの連携という、つじつま合わせが非常に困難な仕様調整をやり遂げるられたことで、調整力に関する自信がつきました。

### クレジットカード会社の特典表示制御機能開発 (2016/04〜2016/05)
- **プロジェクト概要**
  - 某大手クレジット会社のサイトの会員特典データ・広告表示を制御する機能を開発。
- **プロジェクトの規模**
  - PL 1名、開発者 2名
- **プロジェクトで利用された技術**
  - JavaScript / jQuery
- **担当業務**
  - プロジェクト管理、設計、開発、検証
- **業務詳細**
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証と保守まで一貫したプロジェクトの管理を実現。
  - 会員特典・広告表示の制御判定、出力処理の実装。
  - OS・端末別の検証ケースの洗い出し、検証。
  - 既存システムのサーバーサイドへの影響を最小限に抑えるというクライアントの要望を、すべてクライアントサイド(JavaScript)で実装することで実現。
- **主な成果**
  - JavaScriptのベテラン経験者がいない中で、Promiss等の必要となる技術をすばやくキャッチアップしました。
  - チームに具体的な実装のロードマップを提示し、スケジュール管理を徹底して問題なく納品までこぎつけたことにより、マネージャとしての経験と自信をつけることができました。
  - 30近い携帯端末での検証は初めてであり、機種をそろえる事自体が困難であったため、今後はプロジェクト開始時から現実的な数に限定するような調整が必要であると反省しました。

### アパレル物流の在庫管理用パッケージングシステムのAPI開発 (2015/11〜2016/02)
- **プロジェクト概要**
  - アパレルの製造から出荷を管理する既存システムのうち各プロセス間のデータ連携処理を、ファイル出力連携からAPI連携に改修。
- **プロジェクトの規模**
  - PM 1名、開発者 3名
- **プロジェクトで利用された技術**
  - PHP5.x / PostgreSQL / JavaScript
- **担当業務**
  - プロジェクト管理、開発、検証
- **業務詳細**
  - クライアントとの要件定義、仕様調整。
  - 既存システムの調査・報告と改善案の提案。
  - API処理の設計、ドキュメント化、実装。
  - 単体テスト、結合テストの実施。
- **主な成果**
  - 既存システムに連携機能のドキュメントが存在しなかったため、仕様をソースコードから調査して改修箇所を選定。実際の運用フェーズでの作業とのすり合わせを実施し、具体的な実装案をクライアントに提案しました。
  - それまで問題となっていた連携出力ファイル内のデータ欠損やファイルロックによる処理の遅延が、提案したAPIと新設したトランザクションデータ管理により解決しました。

### 会議室のWeb予約システム (2014/11〜2015/05)
- **プロジェクト概要**
  - 某大手の商品販促セミナー会議室の会員制Web予約システムを開発。
- **プロジェクトの規模**
  - PM 1名、開発者 5名
- **プロジェクトで利用された技術**
  - PHP5.x / ZendFramework / SQL Server / JavaScript / jQuery / AWS(EC2) / IIS(DBサーバ) / LDAP
- **担当業務**
  - プロジェクト管理、要件定義、設計、開発、検証、保守
- **業務詳細**
  - クライアントとの要件定義、仕様調整。
  - 支店と会員情報・予約枠の組み合わせによる様々な予約制御機能の実装。
  - クライアントのActive Directory にアクセスするLDAPログイン認証を実装。
  - 単体予約枠を分割、もしくは結合させて予約できる機能のDB設計と実装。
  - 運用マニュアル作成のドキュメント化。
  - 単体テスト、結合テストの実施
- **主な成果**
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証、保守まで一貫したプロジェクトの管理を実現しました。
  - アプリサーバはLinux、DBサーバーはIIS、SQL Server の組み合わせであったため、フレームワークにDB接続用のドライバが存在せず、独自実装することにより解決しました。
  - 「予約枠の分割・結合機能」はASP予約システムパッケージの基本設計では実現できなかったため、システムを再設計することにより実現しました。

### スポーツジムのWeb予約システム (2013/09〜2013/10)
- **プロジェクト概要**
  - 都内のスポーツジムの設備とレッスンのWeb予約システムの開発。。
- **プロジェクトの規模**
  - 開発者 4名
- **プロジェクトで利用された技術**
  - PHP5.x / Zendframework / JavaScript / PostgreSQL
- **担当業務**
  - プロジェクト管理、要件定義、設計、開発、検証、保守
- **業務詳細**
  - クライアントとの要件定義、仕様調整。
  - 支店と会員の種類による複数の予約枠管理機能増設の実装。
  - 支店と会員情報・予約枠の組み合わせによる様々な予約制御機能の実装。
  - 支店と会員情報・予約枠の組み合わせによる抽選機能とリスク対策のための
  - ログ出力・メール通知機能の実装。
  - 運用マニュアル作成のドキュメント化。
  - 単体テスト、結合テストの実施。
- **主な成果**
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証、保守まで一貫したプロジェクトの管理を実現しました。
  - それまで手作業で実施されていた各予約枠の抽選プロセスをすべて自動化することにより、システム運用の大幅な人的リソース削減を実現しました。
  - 多大な負荷がかかる抽選処理において、不慮の原因による不整合データの発生と問題の拡散を防ぐため、ログ出力とメール通知をクライアントに提案、リスクの削減を実現しました。

### 車載ナビのシミュレーションサイト開発 (2013/01〜2013/07)
- **プロジェクト概要**
  - 車載ナビシステムのシミュレーション体験をエンドユーザに提供するためのシステム開発。
- **プロジェクトの規模**
  - 開発者 3名、デザイナー 1名
- **プロジェクトで利用された技術**
  - PHP5.x / JavaScript / jQuery / PostgreSQL
- **担当業務**
  - 要件定義、開発、検証
- **業務詳細**
  - クライアントとの要件定義、仕様調整。
  - Google Map APIの調査、必要なAPIのリストアップとインターフェース・DB設計。
  - 会員情報管理機能、管理機能、コンテンツ情報管理機能の開発。
  - frontendのコンテンツ操作処理の実装。
- **主な成果**
  - Google Map APIを使ったリッチコンテンツの開発実績を追加。
  - 複雑なAPIの仕様をまとめ、チーム開発のスピードアップに貢献。

### 旅の思い出共有サイトの開発 (2011/12〜2012/11)
- **プロジェクト概要**
  - 初の自社開発サービスである旅の思い出共有サイト “Travel Reco” CMSの開発。
- **プロジェクトの規模**
  - 開発者 10〜15名、デザイナー 2名
- **プロジェクトで利用された技術**
  - PHP5.x / Zendframework / JavaScript / jQuery / PostgreSQL
- **担当業務**
  - 要件定義、開発、検証、運用
- **業務詳細**
  - 必要な要件のリストアップ。
  - DB・機能設計。
  - 開発ドキュメントの整理。
  - 会員情報管理機能、コンテンツ情報管理機能の開発。
  - ファイルアップロード機能の開発。
  - Twitter、Facebookへのコメント共有機能の開発。
- **主な成果**
  - 初の自社開発サービスであり、スクラッチ開発であったため、それまで使用していたZendFrameworkではなく、トレンドであったCakePHPフレームワークをメリット・デメリットとともに提案（結果的には却下される）。
  - SNS連携機能の開発実績を追加。
  - 初のBtoC案件であったため、それまでは避けていた運用業務もやらせてもらいました。エンドユーザの反応が刺激的で、開発のモチベーションが非常に高かった案件。

### 某大手カップヌードル施設の見学予約システム開発 (2011/04〜2011/10)
- **プロジェクト概要**
  - 某大手の施設サイトの見学予約システムの開発。自社フレームワークである予約システムのカスタマイズ。
- **プロジェクトの規模**
  - 開発者 7名
- **プロジェクトで利用された技術**
  - PHP5.x / Zendframework / JavaScript / jQuery / PostgreSQL
- **担当業務**
  - 要件定義、開発、検証
- **業務詳細**
  - 要件定義、機能開発。
  - DB・機能設計。
  - 検証。
- **主な成果**
  - 期間イベントによって予約枠の幅や予約人数が動的に変化するなど、非常に要件が複雑なシステムであったため、要件定義にかなり時間をかけるように提案。チーム間の進捗のズレとコミュニケーションロスを最小限に抑えるようにスケジュールを徹底。

### 某脱毛サロン予約システムの開発 (2009/05〜2009/07)
- **プロジェクト概要**
  - 某大手のサロン施設サイトの予約システムの開発。
  - 自社フレームワークである予約システムのカスタマイズ。
- **プロジェクトの規模**
  - PM 1名、開発者 5名
- **プロジェクトで利用された技術**
  - PHP5.x / Zendframework / JavaScript / jQuery / PostgreSQL
- **担当業務**
  - 要件定義、開発、検証
- **業務詳細**
  - 要件定義、機能開発。
  - DB・機能設計。
  - 会員管理機能・管理側機能の開発。
  - 検証。
- **主な成果**
  - 夏のキャンペーンに間に合わせるためにかなり開発スピードを上げなければならなかった案件。

### 大手ロードサービス会員向けコンテンツサイトシステム (2008/12〜2009/04)
- **プロジェクト概要**
  - ロードサービスの会員向けコンテンツ情報共有サービスの開発。
- **プロジェクトの規模**
  - 開発者 4名
- **プロジェクトで利用された技術**
  - PHP5.x / JavaScript / jQuery / PostgreSQL
- **担当業務**
  - 要件定義、開発、検証
- **業務詳細**
  - 会員情報管理機能の実装。
  - 会員区分別のコンテンツ出し分け処理の実装。
  - 会員からの取り合わせフォームの実装。
  - frontendの簡単なコンテンツ表示切り替え処理をjQueryで実装。
  - 単体テスト、結合テストの実施。
- **主な成果**
  - プロジェクトリーダーとして、顧客・デザイナーと要件定義・仕様調整を担当。
  - プログラマとして、サーバサイドの開発・検証までを担当。
