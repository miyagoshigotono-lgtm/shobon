# ねこのアクション

理不尽トラップだらけの鬼畜横スクロールアクションゲーム。

## 遊び方

- **スマホ**: 左下の ◀▶ で移動、右下の ▲ でジャンプ
- **PC**: 矢印キー or WASD + スペースorZ でジャンプ

## GitHub Pages への公開手順

1. このリポジトリを GitHub に push する
2. Settings → Pages → Branch: `main` / `/(root)` を選択して Save
3. `https://<ユーザー名>.github.io/<リポジトリ名>/` でアクセス可能

## スマホでホーム画面に追加（PWA）

Safariでアクセス → 共有ボタン →「ホーム画面に追加」  
Chromeでアクセス → アドレスバーのインストールボタン

## ファイル構成

```
.
├── index.html      # ゲーム本体
├── manifest.json   # PWA設定
├── sw.js           # Service Worker（オフライン対応）
└── icons/
    ├── icon-192.png
    ├── icon-512.png
    └── favicon-32.png
```
