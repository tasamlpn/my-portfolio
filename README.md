# 自己紹介Webサイト

## 使い方（ローカルで表示）

このフォルダで以下を実行します。

```bash
python3 -m http.server 5173
```

ブラウザで `http://localhost:5173` を開くと表示されます。

## 差し替えるところ

- **GitHubリンク**: `index.html` の「連絡先 > GitHub」を自分のURLに変更
- **メール**: `index.html` の `mailto:` と表示メールアドレスを自分のものに変更

## ファイル構成

- `index.html`: ページ本体
- `styles.css`: デザイン（レスポンシブ対応）

