# Atsusics Apps

https://apps.atsusics.jp

Atsusics のアプリに関する公開ページをホストするリポジトリです。GitHub Pages + カスタムドメイン `apps.atsusics.jp` で公開しています。

## 内容

- **プライバシーポリシー** — 各アプリのプライバシーポリシー（日本語・英語）
- **app-ads.txt** — 広告ネットワーク認証ファイル
- **利用規約** — サブスクリプション等の利用規約（今後追加予定）
- **LP** — アプリのランディングページ（今後追加予定）

## 構成

```
/
├── CNAME                  # カスタムドメイン設定
├── app-ads.txt            # 広告認証
├── style.css              # 共通スタイル
├── index.html             # トップページ
├── 1m-clean/              # 1分掃除
├── dorodango/             # どろだんご育成
├── fire-idle/             # FIREへの道
├── garlic-breath-meter/   # にんにく息
├── oriro/                 # 降りろ
├── shotlix/               # Shotlix
└── station-mission/       # 駅ミッション
```

## DNS 設定

`apps.atsusics.jp` の DNS に以下のいずれかを設定してください：

- **CNAME レコード**: `apps.atsusics.jp` → `atsusics.github.io`
