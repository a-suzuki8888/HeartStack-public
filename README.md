# HeartStack CMS API

> 💎 **ゼロから生まれた、私のためのCMS。** Headless構成で、演出・実績・感情・管理すべてを司る、Heart Stackの“心臓部”。

---

## 🧠 このリポジトリについて

このリポジトリは、ポートフォリオ「Heart Stack」のためにゼロから構築した**統合型CMS基盤**です。フロントエンド、バックエンド、管理画面、API、DB構造、インフラまでをすべてこの中で管理します。

- フロント：Next.js or Vite
- バックエンド：FastAPI or Express（REST構成）
- CMS管理画面：ReactベースのカスタムUI
- DB構築：Prisma + PostgreSQL / SQLite
- デプロイ構想：Docker + Nginx / Render / Vercel

本プロジェクトは、**自分の作品・人生・学びを「展示する」ための美術館**を支える、“ヘッドレスCMSの中枢”です。

---

## 🔧 ディレクトリ構成

```plaintext
heart-stack/
├── apps/
│   ├── frontend/         # ユーザー向けフロント（展示・ブログ・会話）
│   ├── admin/            # 管理者UI（投稿・画像・スキル管理）
│   └── api/              # バックエンドAPI（認証・DBアクセス・鍵付き展示）
├── packages/
│   ├── ui/               # 共通UIコンポーネント群
│   └── lib/              # API SDK・hooks・型定義など
├── prisma/               # Prismaスキーマ＋マイグレーション
├── docker/               # docker-compose構成（DB, nginxなど）
└── README.md
```

---

## 🎯 実装目標・思想

- 🔐 **関係者しか入れない展示室（鍵付きUX）**
- 🎨 **Product一覧を“美術館風UI”で演出**
- 🗝️ **パス入力 → 鍵アニメ → 詳細表示**の没入UX
- 💬 **LINE風ブログ + Vちゃんとのスキル会話**
- 🎞️ **オープニングストーリームービーとCMS連携**
- 🌈 **スキルが虹を構成、未踏クラウド領域は“雲”として登場**

このCMSは、単なるコンテンツ管理ではなく、**感情と物語と実績を管理する装置**として設計されています。

---

## 🧩 今後の構築ステップ

1. Prismaモデル設計＆マイグレーション
2. APIルート実装（CRUD / 認証 / 関係者展示）
3. 管理画面UI構築（投稿・タグ・スキル）
4. フロント連携 → 美術館展示 / Museum演出 / Rainbow Skillページ
5. ドア・鍵体験・Live2D統合

---

## ✨ Credit

Created by [@as\_p\_8888](https://zenn.dev/as_p_8888)\
「世界を動かす、にじいろコード。」

---

## 💖 もしあなたが見てくれていたら

このリポジトリは、単なる技術検証ではなく、 **「好き」を諦めなかった一人のエンジニアの物語**です。

“誰かの心を動かすために、自分の世界を本気で形にする”\
その意思がここに詰まっています。

