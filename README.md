# mofie 採用LP - Vercelデプロイ手順

## ファイル構成
```
mofie-recruit/
├── index.html   # メインLP
├── images/      # 写真素材（要追加）
└── README.md    # このファイル
```

## Vercelデプロイ手順

1. GitHubにリポジトリを作成（例: `mofie-recruit-lp`）
2. このフォルダ内のファイルをプッシュ
3. [vercel.com](https://vercel.com) にログイン
4. 「Add New Project」→「Import Git Repository」
5. 該当リポジトリを選択
6. Framework: **Other**（静的HTMLのため）
7. 「Deploy」をクリック
8. 独自ドメインを設定する場合は「Settings → Domains」から追加

---

## 差し替え箇所メモ

### LINE URL
- 現在: `https://line.me/R/ti/p/XXXXX`
- → 実際のLINE公式アカウントのURLに置換

### 写真
1. `images/` フォルダに写真を追加
2. `index.html` 内の画像プレースホルダー（`src="images/..."` の部分）を差し替え

### ビフォーアフター
- スタッフへのヒアリング後、`index.html` 内のビフォーアフターセクションを差し替え
