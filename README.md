# Tom's Film Lab for Windows — リリース / Releases

**Tom's Film Lab** は、スキャンしたフィルムネガを反転・編集するためのアプリです。
このリポジトリは **Windows 版**の配布用ビルド（バイナリ）を置く場所で、ソースコードは非公開で管理しています。

➡️ **[最新版をダウンロード（Download latest）](../../releases/latest)**

> **ベータ版です。** Mac 版の移植版で、まだ一部の機能が未実装・未確認です。
> 大切な写真は念のためバックアップを取ってからお使いください。
> Mac 版は [toms-film-lab-releases](https://github.com/phototomoro-stack/toms-film-lab-releases) で配布しています。

## 更新履歴 (Changelog)

各バージョンの変更点です。過去の全リリースは [Releases](../../releases) を参照してください。

<!-- CHANGELOG:START -->
### 0.0.1-beta

Windows 版の最初のベータ版です。
<!-- CHANGELOG:END -->

## 動作環境

- Windows 10 / 11（64bit）
- 対応形式：JPEG / PNG / TIFF（8・16bit）/ RAW

## インストール

1. 最新リリースから `.zip` をダウンロードして解凍します。
2. フォルダを好きな場所（例：ドキュメント）に置きます。
3. `tfl-app.exe` をダブルクリックして起動します。

インストーラーはありません。削除するときはフォルダごと消してください。
設定とプリセットは `%APPDATA%\TomsFilmLab` に保存されます。

## 初回起動の注意（重要）

このビルドはコード署名をしていないため、初回起動時に Microsoft Defender SmartScreen が
「**Windows によって PC が保護されました**」と表示します。**一度だけ**次の操作で起動してください。

1. 表示された画面の「**詳細情報**」を押す。
2. 下に出る「**実行**」ボタンを押す。

## Mac 版との互換性

編集内容は Mac 版と同じ形式のサイドカー（`*.tfl.json`）に保存されるので、
同じ写真を Mac 版と Windows 版の両方で開いて編集を続けられます。

## アップデート

Windows 版には自動アップデートがまだありません。新しいバージョンはこのリポジトリの
[Releases](../../releases) で公開します（右上の **Watch → Custom → Releases** で通知を受け取れます）。

---

## English (summary)

**Tom's Film Lab** is an app for inverting and editing scanned film negatives.
This repo hosts **Windows** release binaries only; the source is kept private.
This is a **beta**: a port of the macOS app, and some features are not implemented or verified yet.

**Install:** download the `.zip` from the [latest release](../../releases/latest), unzip it anywhere,
and run `tfl-app.exe`. There is no installer; delete the folder to uninstall.

**First launch:** the build is not code-signed, so SmartScreen shows "Windows protected your PC".
Click **More info → Run anyway** (once).

Edits are saved as sidecars (`*.tfl.json`) in the same format as the macOS app.
The macOS app is distributed at [toms-film-lab-releases](https://github.com/phototomoro-stack/toms-film-lab-releases).
