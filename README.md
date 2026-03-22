# daphne-mapper

Wizardry Variants Daphne 用の  
ブラウザベース・ダンジョンマッピング支援ツールです。

## 🔗 公開URL
https://spinel-azure.github.io/dungeon-mapper/

## 🧭 概要
本ツールは、Wizardry Variants Daphne のダンジョン探索時に  
手動でマップを記録・管理するための補助ツールです。

- ブラウザ上で動作（インストール不要）
- PC / スマホ対応
- データはローカル環境で完結（サーバー保存なし）

## 🖱️ 使い方（簡易）
1. 上記URLにアクセス
2. マスをクリックして床・壁・アイコンを配置
3. 必要に応じて修正・上書き

※ 詳細な操作は画面表示に従ってください。

## ⚠️ 注意事項
- 本ツールは **非公式のファンメイドツール** です
- ゲーム本体・運営とは一切関係ありません
- ブラウザのデータ削除を行うと保存内容が消える場合があります
- Wizardry™は（株）ドリコムの商標です

## 🛠️ バージョン
- v2e_patched（現在公開中）

## 📄 ライセンス
本ツールは個人利用向けに公開しています。詳細は LICENSE.md を参照してください。

# dungeon-mapper

A browser-based dungeon mapping support tool  
for **Wizardry Variants Daphne**.

## 🔗 Live Demo
https://spinel-azure.github.io/dungeon-mapper/

## 🧭 Overview
This tool is designed to help players manually record and manage dungeon maps  
while exploring dungeons in *Wizardry Variants Daphne*.

- Runs entirely in the browser (no installation required)
- Works on both PC and mobile devices
- All data is stored locally in your browser (no server-side storage)

## 🖱️ How to Use (Quick Guide)
1. Open the URL above
2. Click on tiles to place floors, walls, and icons
3. Edit or overwrite tiles as needed while exploring

※ For detailed controls, please refer to the on-screen UI.

## ⚠️ Notes
- This is an **unofficial fan-made tool**
- It is not affiliated with or endorsed by the game or its developers
- Clearing your browser data may remove saved maps
- Wizardry™ is a trademark of Drecom Co.,Ltd.

## 🛠️ Version
- v2f_patched

## 📄 License
This tool is provided for personal use only.
See LICENSE.md for the full terms.

<details>
<summary><strong>## 📝 Changelog / 更新履歴（クリックで開く）</strong></summary>
### リポジストリ名およびツール名を変更（2026-03-22)
- Renamed the repository and the tool.

### v2f_patched (2025-12-24)

- 壁描画ツールに「マーク（なし/扉＋）」選択を追加
- 壁線の線種を「実線/点線」切替可能に（点線描画対応）
- 線幅の選択範囲を 2〜10 → 2〜4 に制限

- Added a “Mark (None / Door+)” option to the wall drawing tool
- Added wall line style switching: Solid / Dashed (dashed rendering supported)
- Limited selectable line width from 2–10 to 2–4

---

### v2f (2025-12-23)
- グリッドの下に3行分のテキストボックスを設置  
  最大100文字までメモ書き可能に（印刷 / PNG出力にも反映）  
  Added a 3-line memo box below the grid (up to 100 characters), included in both Print and PNG export.

- セル選択ハイライト（黄色枠）の表示 / 非表示切替ボタンを追加  
  （PC / タブレットで線引き時に視認性を確保）  
  Added a toggle button to show/hide the selected-cell highlight (yellow outline) for better visibility while drawing walls (PC/tablet).

- 切替状態は localStorage に保存（次回起動時も維持）  
  The toggle state is saved to localStorage (persists across sessions).

- 言語切替（日本語 / English）に追従  
  Works with the language switch (日本語 / English).

---

### v2e (2025-12-22)
- 日本語 / 英語の表示切り替え（Languageプルダウン）に対応  
  操作メモの説明文を整理（不要な注記を削除）  
  Added Japanese/English UI switching via a Language dropdown.  
  Cleaned up the Operation Notes text (removed unnecessary notes).

---

### v2d (2025-12-20)
- グリッド下部（X軸）と左側（Y軸）に 0〜26 の座標ラベルを表示  
  タップしたセルの座標（X:00 Y:00）を表示  
  選択中セルを黄色枠でハイライト  
  Added coordinate labels (0–26) on the bottom (X-axis) and left (Y-axis).  
  Displays the tapped cell coordinates (X:00 Y:00).  
  Highlights the selected cell with a yellow outline.

---

### v2c (2025-12-20)
- スマートフォン / タブレットでの塗りつぶし操作に対応  
  Added fill support for mobile and tablet devices.

---

### v2b (2025-12-19)
- 初回公開版  
  Initial public release.


v2b (2025-12-19)
初回公開版
Initial public release.

</details>
