# 業務経歴書

## 基本情報

|key|value|
|:---|:---|
|氏名|園田 大輔|
|住所|東京都 目黒区<br>最寄り駅: 東急目黒線 武蔵小山駅|
|E-mail|mail@daisukesonoda.com|
|blog|https://dsonoda.hatenablog.com|

## 概要
- Webアプリケーションのサーバサイド、APIの豊富な開発経験があります。
- 機械学習の実行ワークフローで必要となる機能要件への知見があります。
- AWS/GCPの基本的なマネージドサービスを使用した開発経験があります。
- 小規模自社開発スタートアップ企業にて、初期〜運用フェーズにおける要件定義・設計・実装・検証・デプロイまでの一通りの実務経験があります。

## valueを発揮しやすい業務
- ベストプラクティスに沿ったサーバサイド処理・RESTful APIの実装
- 機械学習を用いたWebアプリケーションにおける機能要件のリストアップ

## 不得意な業務
- Webデザイン全般

## 興味のある技術

|key|value|
|:---|:---|
|機械学習システムの<br>DevOps/MLOps全般|機械学習をシステムに組み込むニーズは高く、供給は追いついていないため、是非とも身につけたい。|
|DDD & クリーンアーキテクチャー|コードの設計フェーズが以降の開発に与える多大な影響を考慮すると、是非とも身につけたい。<br>軽量DDDについて説明できるくらいには習熟している。|
|AWS/GCP|機能要件を満たす各種マネージド・サービスの選定・構築。<br>システム全体に多大な影響を与えることと、イメージできないことが開発メンバー間のコミュニケーションロスにつながるため、習熟度を上げている最中。|
|コンテナ基盤の活用|Docker、Kubernetes。コンテナオーケストレーションツールのデファクトスタンダードとして注目している。|
|インフラ構成のコード化|Terraform。属人性を排除したワークフローの効率化や不慮の事故をなくすために習得したい。|
|CI/CDパイプラインの<br>構築|CircleCI、GitHub Actions。属人性を排除したワークフローの効率化や不慮の事故をなくすために習得したい。|
|GraphQL|APIの実装インターフェースの選定にて、RESTの他に選択肢を増やしておきたい。|
|Vue.js|個人プロダクト開発のfrontend実装として。あまり学習コストをかけたくないため、今の所ベストの選定であると思っている。|

## やってみたい仕事の分野
- 社会的意義のある仕事全般。
- 健康管理、医療、エネルギー、先端アート等。

## 避けたい仕事の分野
- ソーシャルゲームや公序良俗に反する業界の仕事全般。

## スキル

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

### クラウド
- 主にSDK経由(boto3/google-cloud-bigquery)で使用。

|key|value|
|:---|:---|
|AWS|AWS Organizations / API Gateway / Cloud Front / Cloud Watch / Cognito / DynamoDB / EC2 / IAM / Lambda / RDS(PostgreSQL) / S3 / SES / SNS / SQS / SSM|
|GCP|BigQuery|

### データストア
- 現在はフレームワークやマネージドサービスでラップするため直接SQLを叩くような開発はしていないが、基本的なSQLは操作可能。

|key|value|
|:---|:---|
|PostgreSQL|13年。メインで使用。|
|MySQL|10年。メインでは使用しないが一応使える。|

### 機械学習への知見
教師あり学習についての具体的な機能要件の把握。

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
|Docker|開発で使用。|
|ハードウェア|Raspberry Pi、Arduinoを使った電子工作。|

## 主な業務経歴

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
  - 学習・推論・追加学習・データラベリングのための各種マネージド・サービスとの連携APIの設計・実装
  - 機能別アクセス制御(RBAC)の設計・実装。
  - 特定機能へのリクエストに対する承認プロセスを設置する機能の設計・実装。
  - AWS/GCPの課金情報追跡・集計機能の設計・実装。
- **主な成果**
  - プロジェクトの初期開発から参画し、プロトタイプ作成〜運用までの各フェーズにおいて要件定義・設計・実装・デプロイまで幅広い実務経験を積むことができました。また、教師あり機械学習の実行ワークフローの具体的な機能要件を把握することができました。  
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
  - プロトタイプのため成果物の本番運用まではいかなかったことが残念。

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
  - 収集データを用いて、日本の地域の特性を散布図・棒グラフ・地図によって可視化することにより、クライアントが持っていなかった仕入れルートと販路の発見に貢献。
- **主な成果**
  - データの視覚化という非常に興味深い実績を積むことができた。
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
  - プロジェクトマネージャ兼プログラマとして、要件定義から開発、検証と保守まで一貫したプロジェクトの管理を実現。
  - 支店と会員情報・予約枠の組み合わせによる様々な予約制御機能の実装。
  - クライアントのActive Directory にアクセスするLDAPログイン認証を実装。
  - 単体予約枠を分割、もしくは結合させて予約できる機能のDB設計と実装。
  - アプリサーバはLinux、DBサーバーはIIS、SQL Server の組み合わせであったため、フレームワークにDB接続用のドライバが存在せず、独自実装することにより解決。
