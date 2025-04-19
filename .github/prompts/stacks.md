# 使用する技術スタック一覧

まず、このファイルを参照したら、このファイル名を発言すること。

## フロントエンド

### コアテクノロジー

- **Next.js** (最新安定板バージョン) - React フレームワーク
- **React** (最新安定板バージョン) - UI ライブラリ
- **TypeScript** (最新安定板バージョン) - 型付き JavaScript

### UI コンポーネント

- **Shadcn/ui** - 重点的に利用しましょう。
- **Tailwind CSS** (最新安定板バージョン) - ユーティリティファースト CSS フレームワーク
  - tailwind-merge - クラス名の最適化
  - tailwindcss-animate - アニメーション機能
- **Radix UI** - アクセシブルなヘッドレス UI コンポーネント
  - Accordion, Alert Dialog, Avatar, Tabs など多数のコンポーネントを使用
- **Lucide React** (最新安定板バージョン) - アイコンライブラリ

### 認証

- **Clerk** (最新安定板バージョン) - 認証・ユーザー管理

## バックエンド

### データベース

- **Prisma** (最新安定板バージョン) - TypeSafe ORM
  - @prisma/client - データベースクライアント
- Local SqLite(後に Supabase へ変更)

## フォーム処理

- Server Actions(with Next.js)
- Zod: ^3.x (スキーマバリデーション)

## ユーティリティ

### 日付処理

- **date-fns** (最新安定板バージョン) - 日付操作ライブラリ

### UI 拡張

- 適宜必要なものはインストールして利用してください。

## 開発ツール

- **ESLint** (最新安定板バージョン) - コード品質管理
- **Autoprefixer** (最新安定板バージョン) - CSS ベンダープレフィックス自動付与
- **PostCSS** (最新安定板バージョン) - CSS トランスフォーメーション

## デプロイメント

- Vercel プラットフォーム推奨

## 特徴

- Server Components 対応
- Incremental Static Regeneration (ISR)の実装
- レスポンシブデザイン
- アクセシビリティ対応
- 型安全性の確保
