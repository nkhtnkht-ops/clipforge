# ClipForge

Windows / macOS 向け軽量クリップボードマネージャー。

- クリップボード履歴の自動記録
- Win+Shift+S 連動の範囲スクショ
- カテゴリ別の定型文管理（Clibor CSV 取込対応）
- 画面上端ホバーで一発呼び出し

## サイト
https://nkhtnkht-ops.github.io/clipforge/

## ダウンロード
[Releases](https://github.com/nkhtnkht-ops/clipforge/releases) から Windows 版インストーラーをダウンロード。
Mac 版は [ダウンロードページ](https://nkhtnkht-ops.github.io/clipforge/#download) から Apple Silicon 向け DMG をダウンロード。
未notarizeのため、「開いていません」「検証できません」「壊れている」と表示された場合は Applications へコピー後に次を実行。

```sh
xattr -dr com.apple.quarantine /Applications/ClipForge.app
```

## システム要件
- Windows 10 (1803 以降) / Windows 11、x64、WebView2 ランタイム（標準搭載）
- macOS 12 以降、Apple Silicon

---
© 2026 NK
