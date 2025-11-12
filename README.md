# 🎭 Witty Word Finder

Claude AIを使った、皮肉なユーモア付き英語学習アプリ

![Witty Word Finder](https://img.shields.io/badge/Powered%20by-Claude%20AI-5A67D8)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ 機能

- 📖 詳細な単語解説（品詞、定義、語源）
- 💬 皮肉なユーモア付き例文
- 🎨 AI生成イラスト
- ⭐ お気に入り機能
- 📜 検索履歴
- 🎲 ランダム単語

## 🚀 ワンクリックデプロイ

### 1️⃣ バックエンドをデプロイ（Railway）

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/J5JLbP)

1. クリックして Railway にログイン
2. "Deploy Now" をクリック
3. 環境変数を入力:
   - `ANTHROPIC_API_KEY`: [こちら](https://console.anthropic.com/)でAPIキーを取得
4. デプロイ完了後、Settings で **URL をコピー**

### 2️⃣ フロントエンドをデプロイ（Vercel）

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/あなたのユーザー名/witty-word-finder-template&env=VITE_API_URL&project-name=witty-word-finder&repository-name=witty-word-finder)

1. クリックして Vercel にログイン
2. リポジトリをインポート
3. Root Directory を `frontend` に設定
4. 環境変数を入力:
   - `VITE_API_URL`: Railway の URL（ステップ1でコピーしたもの）
5. "Deploy" をクリック
6. 完成！🎉

## 💻 ローカル開発
```bash
# リポジトリをクローン
git clone https://github.com/あなたのユーザー名/witty-word-finder-template.git
cd witty-word-finder-template

# バックエンド
cd backend
npm install
echo "ANTHROPIC_API_KEY=your-key" > .env
npm start

# フロントエンド（別のターミナル）
cd frontend
npm install
echo "VITE_API_URL=http://localhost:3001" > .env.local
npm run dev
```

## 📝 必要なもの

- [Anthropic API キー](https://console.anthropic.com/) - Claude API用
- [GitHub アカウント](https://github.com) - デプロイ用
- [Railway アカウント](https://railway.app) - バックエンドホスティング
- [Vercel アカウント](https://vercel.com) - フロントエンドホスティング

## 💰 コスト

- Railway: 月 $5 の無料クレジット
- Vercel: 無料（Hobbyプラン）
- Claude API: 従量課金（1検索 約 $0.03-0.05）

**合計**: 月 $5-10 程度

## 📚 技術スタック

### フロントエンド
- React 19
- TypeScript
- Vite
- Tailwind CSS

### バックエンド
- Node.js
- Express
- Claude API (Sonnet 4)

## 🤝 コントリビューション

プルリクエスト大歓迎！

## 📄 ライセンス

MIT License

## 🙏 謝辞

Powered by [Anthropic Claude](https://www.anthropic.com/)
