## 基本情報

| key | value |
| --- | --- |
| Web アプリ開発歴 | 4年 (2019.8 ~) |
| 職歴 | 製造業 >> 飲食業 >> 現在 |

## スキルセット

### フロントエンド

- JavaScript
  - TypeScript 5
  - Nuxt.js 2, 3
  - Vue.js 2, 3
  - Vuetify 2, 3
  - Leaflet.js
  - Cesium.js
  - jQuery
- CSS
  - SCSS
  - Tailwind CSS
- HTML

### バックエンド

- PHP
  - Laravel 6.x
  - CakePHP 3.x
- Node.js
  - Express 4.x (TypeScript)
- Python
  - FastAPI

### DB

- MySQL
- Amazon DynamoDB
- PostgreSQL

### その他

- Git
- Docker
  - Docker Compose
- Linux
  - CentOS
  - Ubuntu

## 経歴

### 1. 自治体向け地域情報管理プラットフォーム (2023.7 ~)

- アプリ概要
  - ブラウザで 3D の地形を操作して、地域の避難所や川の水位を確認できるアプリケーション
- 使用技術
  - Vue3, Cesium.js, Pinia, Tailwind CSS, Python (FastAPI), PostgreSQL, SQLAlchemy ..
- 主な担当業務
  - 災害体験モードを実装。
    - JSON のシナリオを元に、実際の災害を想定した水位の上昇や避難案内を通しで自動実行する機能。
  - マップの避難所を選択した時に表示される Cesium の infoBox (iframe) をカスタマイズして、任意の情報を表示。
  - Google Analytics タグを設定して、各種イベントを送信してアクセス解析を可能に。
  - 某自治体向けの、初期表示時 loading 画面を実装。
  - スマホ版の UI を実装。
  - PC/スマホモードの切り替え機能を実装。
  - マップの現在地アイコンの切り替え機能を実装。
  - GitHub Actions で ESLint を実行するワークフローを追加。
  - バックエンドの API 実装。

### 2. ドローン飛行日誌作成アプリのプロトタイプ 新規開発 (2022.4 ~ 2023.6)

※ 「2.」「3.」は同一企業様のプロジェクトとなります。

- アプリ概要
  - ドローンを飛行する際に記録する日誌を簡単に作成できるアプリケーション。
- 使用技術
  - Nuxt3 (Vue3, Composition API, Pinia), Vuetify3, Express, TypeORM, TypeScript, Laravel, MySQL, Docker ..
- 主な担当業務
  - Vue2, Nuxt2 を 3 にバージョンアップ。
  - 各画面の UI やロジックを実装。
  - データ抽出、登録等の API 実装。
  - DB の Migration, Seeder ファイル作成。

### 3. 不動産向けドローン壁面点検アプリ 開発・保守 (2022.7 ~ 2023.4)

※ 「2.」「3.」は同一企業様のプロジェクトとなります。

- アプリ概要
  - ドローンで撮影した壁面の画像を AI、目視で解析して異常を検知し解析後、報告書 (pptx) を出力できるアプリケーション。
- 使用技術
  - Nuxt2 (Vue2, Composition API), Vuetify2, Leaflet.js, Express, TypeORM, OpenAPI, TypeScript, Jest, MySQL, Azure Blob Storage, Azure Queue Storage, Docker ..
- 主な担当業務
  - アップロードする撮影データを非同期で AI 推論にかける仕組みを実装。
  - 撮影画像で確認した壁面の異常箇所に Leaflet.js でマーキングする機能を開発。
  - 撮影画像 (約10MB) に異常がないか目視で解析する際、スムーズに切り替えられるよう基本的には圧縮した画像 (500KB) を表示。詳しく解析が必要と判断した場合に元画像を表示させ、操作性を上げる施策を対応。
  - Jest で全ての API のテストを実装。GitHub Actions のワークフローに組み込み。

### 4. 医学会向け会員管理システム 管理画面・会員マイページ 新規開発 (2021.1 ~ 2022.6)

- アプリ概要
  - 某医学会向けの会員管理システム。
  - 事務局ユーザーが使用する管理画面と、学会の各会員が使用可能なマイページ画面があり。
  - 管理画面では会員一覧のステータスや各支部の情報、メールの送信や資格申請の承認などが可能。
  - マイページでは資格申請や毎月の会費支払い等が可能。
- 使用技術
  - Nuxt2 (Vue2, Options API), Vuetify2, Laravel, Mailgun, MySQL, Amazon DynamoDB, Docker ..
- 主な担当業務
  - ユーザーにメールを一斉に送信する画面、機能を実装。最大3万人の会員へ事前に決めた時刻に一斉送信する仕組みを実装。
  - 会員の所属支部変更申請画面、機能を実装。
  - 複数ある資格の申請 ~ 承認 ~ 資格付与のフローを可能とする画面、機能を実装。全50画面ほど。
  - 会員マイページのレスポンシブ対応。

### 5. コールセンター向けシステム 開発・保守 (2020.8 ~ 2021.12)

- アプリ概要
  - 管理画面
    - ユーザーの架電予約管理や、会員ページの　UI カスタマイズが可能
  - 会員ページ
    - 架電予約や企業への問い合わせメッセージを送信可能
- 使用技術
  - CakePHP3, jQuery, Vue2, CSS, HTML, MySQL ..
- 主な担当業務
  - 会員ページの操作ログ集計結果を確認できる画面を実装
  - 既存不具合の改修
  - 基本設計
  - 詳細設計
  - 機能実装
  - 単体テスト
  - 結合テスト
