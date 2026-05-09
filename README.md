# PAINT SPLATTER — 紹介サイト

iPhone アプリ「**PAINT SPLATTER**」のランディングページおよび関連ページを静的 HTML で公開するためのリポジトリです。

## 構成

| ファイル | 説明 |
|----------|------|
| `index.html` | アプリ紹介（ヒーロー、プレイ動画、訴求ブロック） |
| `support.html` | サポート・お問い合わせ |
| `privacy.html` | プライバシーポリシー |
| `promo.mp4` | 紹介ページ用プロモーション動画（`index.html` から参照） |
| `screenshot1.jpg` など | スクリーンショット画像（必要に応じて HTML に組み込み可） |

## ローカルでの確認

ブラウザで `index.html` を直接開いても表示できます。相対パスで動画を読み込むため、ファイルはこのディレクトリ構成のまま置いてください。

任意で簡易サーバーを使う場合の例:

```bash
cd /path/to/PAINTSPLATTER_LP
python3 -m http.server 8080
```

ブラウザで `http://localhost:8080/` を開きます。

## お問い合わせ（サイト記載と同一）

- **Email:** [support@corevista.jp](mailto:support@corevista.jp)

## ライセンス

アプリおよび本サイトの著作権は運営者に帰属します。第三者による無断転載は禁止します。
