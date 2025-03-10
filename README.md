# Quarkus Microservice Template

## 概要
Gradle と PostgreSQL を使用した Quarkus ベースのマイクロサービス テンプレート。Docker を活用した迅速な開発とデプロイメントを想定し、パフォーマンスとスケーラビリティのベストプラクティスを組み込んでいます。

## 特徴
- **Quarkus**: 軽量で高速な Java フレームワーク
- **Gradle**: 柔軟なビルド管理
- **PostgreSQL**: 信頼性の高いデータベース
- **Docker**: 簡単なコンテナ化
- **REST API**: シンプルな API 設計

## セットアップ

### 1. リポジトリのクローン
```sh
git clone https://github.com/morihoumatu/quarkus-microservice-template.git
cd quarkus-microservice-template
```

### 2. 必要な環境の準備
- **Java 17+** をインストール
- **Gradle** をインストール
- **Docker & Docker Compose** をインストール

### 4. アプリケーションの起動
```sh
./gradlew quarkusDev
```

## API エンドポイント
| メソッド | エンドポイント | 説明 |
|----------|--------------|------|
| GET      | /hello  | 最初のエンドポイント |
