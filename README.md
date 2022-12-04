
# wellnote_memo

## インストールしておくもの
- google chrome
-- https://www.google.com/intl/ja_jp/chrome/
-- または https://portableapps.com/apps/internet/google_chrome_portable (ポータブル版)
- python
-- https://www.python.org/downloads/

## 手順

### chrome での作業
chrome にて、tampermonkey の導入
- https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo

tampermonkey に js を入れる
- wellnote.js

chrome で wellnote を開く
- https://wellnote.jp/

[get_json] ボタンをクリック

スクロールが止まったら、[save_json] ボタンをクリック

"wellnote_log.json" というファイルがダウンロードされる

### python での作業
"wellnote_log.json" を以下のファイルと同じフォルダに置く
- wellnote.py

コマンドプロンプトを開く

以下のコマンドを打ち込む
- py wellnote.py

完了！

