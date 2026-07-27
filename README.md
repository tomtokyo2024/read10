# read10

音読（朗読練習）の反復回数をブラウザのマイクでカウントする、ビルド不要の単一 HTML 静的ページです。

> ⚠️ マイク（getUserMedia）を使うため、**HTTPS またはlocalhost** でアクセスする必要があります。`file://` で直接開いても動作しません。

## ローカルプレビュー

```bash
python3 -m http.server 8000
```

その後ブラウザで `http://localhost:8000` を開いてください。
