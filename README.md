# 職務経歴書

## 基本情報

| key | value |
| --- | --- |
| Name | 小澤 誠二郎（Seijiro Ozawa） |
| GitHub | [ozw-sei](https://github.com/ozw-sei) |
| 経験 | 2014年からエンジニア（インターン・アルバイトを含めると2011年から） |
| 現在 | アニメ・マンガ領域のITスタートアップ（データエンジニア、バックエンド） |

土台は 3D、ネイティブ（家庭用ゲーム・iOS・Android・Unity）、GUI、画像処理。そこから Web・サーバーサイド・データへと幅を広げ、最近はバックエンドとデータ基盤の経験が最も厚くなっています。

副業では、開発／AIシステムの活用／メンターのお手伝いができます（土日・平日夜、フルリモート）。

## スキル

- Go（主力）
  - gRPC / Protocol Buffers、sqlc、GraphQL
- TypeScript
  - React、Next.js、Three.js / react-three-fiber
- Python
- データ
  - Cloud Spanner、PostgreSQL（RLS）、MySQL、MongoDB
  - BigQuery、dbt、DuckDB / DuckDB-Wasm、Parquet
- クラウド・IaC
  - Google Cloud（Cloud Run、Pub/Sub、Cloud SQL、GCS）
  - AWS（ECS / Fargate、Lambda、DynamoDB、Kinesis）
  - Terraform、GitHub Actions
- AI
  - Vertex AI（Gemini）、Google ADK、MCP、OpenAI API、Stable Diffusion
  - AI エージェントを使った開発（Claude Code、Codex）
- 3D・グラフィックス
  - WebGL、Unity（C#）、ARKit、Photon、Blender、openFrameworks、Arduino
- 過去に使用
  - C++、Scala、Swift、PHP、Java

## 職務経歴

### 2025/02 - 現在: アニメ・マンガ領域のITスタートアップ

2025年2月に業務委託で参画し、2026年5月から正社員（データエンジニア）・バックエンド責任者。企業向けAIマーケティング支援サービスのバックエンドを、設計から本番運用までほぼ一人で担当しています。

- AI エージェント前提の開発基盤：AGENTS.md と 17 種の静的検査・CI を整備し、約3か月で従量課金・企業ごとのデータ管理・LINE 連携などを本番リリース
- AI機能の従量課金基盤：冪等キーと追記専用の台帳で二重計上を防止。専用DBへ無停止で移行
- PostgreSQL の RLS による契約企業ごとのデータ分離（gRPC API 12本）
- AI日次レポート生成ジョブを 6時間15分 → 約6分 に短縮
- ブラウザ内集計（Parquet + DuckDB-Wasm）で BigQuery の都度クエリを不要に
- 海外向けアニメ情報サイトの検索改善 R&D（OpenSearch、NDCG@5 約 +48%）、ファンコミュニティの開発
- コードレビュー 190 件超（2026年5月以降）

技術：Go、TypeScript（Next.js）、Python、Cloud Run、Pub/Sub、Cloud Spanner、PostgreSQL、BigQuery、dbt、DuckDB、Terraform、Vertex AI、MCP

### 2018/12 - 現在: 業務委託（個人事業主）

- 2026/02 - 2026/04 銀行向けシステム企業：認証・認可基盤（Auth0、Cedar）と、Outbox + Kinesis による証跡ログ基盤（Go、AWS）
- 2024/10 - 2025/05 飲食店向けPOS企業：モバイルオーダーと電話注文受付ツールのバックエンド（Go、MySQL、sqlc、CQRS）
- 2023/05 - 2024/06 ニュース配信系IT企業：災害・交通情報を配信する外販 API（Go、Python、GraphQL、Pub/Sub、PostgreSQL）
- 2023/04 - 2024/11 建設テック企業：360° 画像・図面・Revit を同期する施工管理システムのフロントエンド（Next.js、Three.js、WebGL）
- 2023/02 - 現在（不定期） 教育系コンテンツ企業：小学生向け学習 Web ゲーム（TypeScript、WebGL、WebSocket）
- 2022/09 - 2023/08 ファッション×AI企業：EC サイト開発と画像生成 AI サービス（Go、Next.js、Stable Diffusion、OpenAI API）
- 2021/11 - 2022/08 ニュース配信系IT企業：Push 通知基盤を Go で内製化し、約600万件を1分未満で配信
- 2021 AR開発スタートアップ：Unity・Photon による 3D の AR 対戦ゲーム（ARKit）
- 2020/01 - 2021/08 AIチャットボット企業：チャットボットの Web 開発と技術リード、デジタルサイネージ・展示作品（Unity、openFrameworks、C++、Arduino）
- 2018/12 - 2019/06 モバイルゲーム会社：Unity の 3D リアルタイム対戦ゲーム

### 2014/04 - 2018/12: 会社員

- 2017/10 - 2018/12 マンガアプリ運営会社：iOS・サーバー・Web をフルスタックに担当（Swift、Scala、React）
- 2015/08 - 2017/09 ゲーム・アプリ開発会社：アニメ IP の Unity ソーシャルゲーム（リリース後リーダー）、VR・WebGL の研究開発
- 2014/04 - 2015/04 マーケティング系IT企業：写真共有サービスのサーバーと iOS アプリ（Scala、Swift）

## 保有資格

- CGエンジニア検定 エキスパート
- 画像処理エンジニア検定 エキスパート
- 普通自動車運転免許
