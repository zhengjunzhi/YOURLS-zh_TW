# YOURLS-zh_TW
YOURLS 縮址服務台灣中文語言套件

開源專案的語言套件維護很少有持續維護的，YOURLS 找的到的台灣中文語言套件，已經多年沒有維護，加上缺漏新版本字串譯文， 因此依據台灣用語及資訊本地化業界譯文樣式規範，重譯一份最新版譯文，且會與我其他 WordPress 外掛/佈景主題台灣中文語言套件一樣，持續維護下去。

請注意，這是全新翻譯版本，遵照本地化業界台灣中文譯文樣式重新翻譯，若有任何疑問、譯文錯誤或需要修改的地方，請與我聯絡。 

YOURLS 官方本地化詳細資料：

https://github.com/YOURLS/YOURLS/wiki/YOURLS-in-your-language

## 安裝方式

1. 下載 `zh_TW.po` 及 `zh_TW.mo`。如果沒有需要自行修改譯文的需求，下載 `zh_TW.mo` 檔案即可。
2. 開啟自建 YOURLS 服務網站 `user` 目錄中的 `config.php`，然後編輯或新增以下常式：
    - `define( 'YOURLS_LANG', 'zh_TW' );`
3. 將 `zh_TW.mo` 檔案上傳至 `user/languages` 目錄。

## 使用授權

使用與 YOURLS 專案相同的 MIT 授權。
