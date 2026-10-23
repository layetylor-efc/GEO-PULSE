# GEO-PULSE

スマートフォン対応のインタラクティブ・アート「GEO-PULSE」。

## GitHub Pages 公開準備

- エントリーポイント: `index.html`（リポジトリ直下）
- 配信方式: 静的 HTML / CSS / JavaScript（ビルド不要）
- ブランチ: `main`
- 公開元フォルダ: `/(root)`
- `.nojekyll` でJekyll処理を無効化

### サイトを公開するには（ユーザーによる最終承認後）
1. リポジトリの **Settings → Pages** を開く。
2. **Build and deployment → Source** で **Deploy from a branch** を選択。
3. **Branch** で **main** / **/(root)** を選択し **Save**。
4. 公開が完了したら `https://layetylor-efc.github.io/GEO-PULSE/` で確認。

設定画面: https://github.com/layetylor-efc/GEO-PULSE/settings/pages

### 品質確認
- [ ] Android Chrome / iOS Safari の表示・タップ・ドラッグ
- [ ] アニメーション停止／再開・軽量化
- [ ] 下部カウンター行が画面に収まるか
- [ ] バッジ・レベル・コイン・整列動作
- [ ] コンフィグ・Top操作
- [ ] ブラウザ最新版、HTTPS/証明書とMixed Content
- [ ] APIキー／個人情報／内部メモの不在とGit履歴の確認
- [ ] 公開するリンクと非公式表記が適切か

## 構成
```text
GEO-PULSE/
├── index.html       # 既存サイトの静的HTML
├── .nojekyll        # Jekyll無効化
└── README.md        # 公開手順と品質チェック
```

## 注意
公開されるHTML・JavaScriptおよびリポジトリの履歴は、外部から閲覧できます。秘密情報は記載しないでください。
