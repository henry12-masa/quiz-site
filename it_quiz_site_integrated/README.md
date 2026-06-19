# IT資格クイズ統合サイト

## 内容

- 9資格対応
- 各資格180問
- 合計1,620問
- ランダム50問出題
- 重複なし
- 4択
- 解説付き
- HTML / CSS / JavaScriptのみ

## 収録資格

- Juniper JNCIA-Junos
- Palo Alto PCCET
- Fortinet FCA
- Nutanix NCA
- UiPath Certified Professional
- Microsoft Power Platform PL-900
- Microsoft Dynamics 365 Fundamentals
- Alibaba Cloud Certification
- Tencent Cloud Practitioner

## ファイル構成

```text
index.html
style.css
script.js
data/
  registry.js
  各資格のJSファイル
```

## 問題データの追加方法

1. `data/新しい資格.js` を作成
2. `window.quizData["資格ID"] = { ... }` の形式で登録
3. `data/registry.js` に資格情報を追加
4. `index.html` に `<script src="data/新しい資格.js"></script>` を追加

## 公開方法

GitHub Pages、Cloudflare Pages、Netlify、Vercelにそのままアップロードできます。
