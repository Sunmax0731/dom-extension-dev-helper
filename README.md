# DOM・拡張開発支援

dom-extension-dev-helper は Chrome拡張開発者、Web QA担当者 向けの closed alpha プロダクトです。DOMセレクタ、要素の役割、イベント仮説、修正アクションを記録して検証する。

## Source

- PICKUP Rank: 43
- Domain / Idea No: ChromeExtension / 10
- Repository: dom-extension-dev-helper
- 主な公開先: Chrome Web Store
- created_idea: `D:/AI/ChromeExtension/created_idea_010_dom-extension-dev-helper`
- 同梱ZIP: `D:/AI/ChromeExtension/created_idea_010_dom-extension-dev-helper/idea_010_dom-extension-dev-helper.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- extension/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/dom-extension-dev-helper-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

