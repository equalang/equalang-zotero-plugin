# 意扣 Zotero 翻譯外掛程式

[![Release](https://img.shields.io/github/v/release/equalang/equalang-zotero-plugin)](https://github.com/equalang/equalang-zotero-plugin/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/equalang/equalang-zotero-plugin/total)](https://github.com/equalang/equalang-zotero-plugin/releases)
[![Zotero](https://img.shields.io/badge/Zotero-7%20%7C%208%20%7C%209%20%7C%2010-CC2936)](https://www.zotero.org)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-555555)](#常見問題)

[English](../README.md) · [简体中文](README.zh-CN.md) · **繁體中文** · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Italiano](README.it.md) · [Русский](README.ru.md) · [Polski](README.pl.md) · [Türkçe](README.tr.md) · [Tiếng Việt](README.vi.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md) · [हिन्दी](README.hi.md) · [العربية](README.ar.md)

[下載最新版](https://github.com/equalang/equalang-zotero-plugin/releases/latest) · [官網](https://equalang.com/zh-TW/extension/zotero?utm_source=github) · [價格](https://equalang.com/zh-TW/pricing?utm_source=github) · [更新紀錄](../CHANGELOG.md)

> **關鍵字：** Zotero 翻譯外掛、Zotero PDF 翻譯、文獻翻譯、論文翻譯、PDF 翻譯保留排版、雙語對照、劃詞翻譯、Word 翻譯、PPT 翻譯、Excel 翻譯、學術翻譯、zotero plugin、zotero translate、pdf translator

**一鍵翻譯，雙螢幕對照。** 意扣（Equalang）的 Zotero 外掛程式，支援 PDF 等文件翻譯以及劃詞翻譯：在附件按右鍵就能翻譯整篇文獻，譯文保留原始排版，作為附件放在原文獻下方；在閱讀器中選取文字，譯文和釋義馬上出現在浮動視窗中。

![左邊原文、右邊譯文；選取單字，釋義馬上出現在浮動視窗中](../images/reader-bilingual.png)

## 功能

- **文件翻譯**：在 PDF、Word、PowerPoint 或 Excel 附件上按右鍵即可翻譯。譯文保留原始排版，作為附件放在原文獻下方；PDF 還能產生雙語對照版，原文與譯文左右對照著讀。
- **劃詞翻譯**：在閱讀器中選取文字，譯文馬上出現在浮動視窗中；選取單字時還會顯示釋義、音標與例句。
- **背景翻譯**：可以隨時結束 Zotero，未完成的任務會在下次啟動時繼續，譯文仍會新增至原文獻下方。
- **與網站共用點數**：文件翻譯開始前會顯示預計消耗的點數與目前餘額，取消的任務不扣點數。

## 安裝

1. **下載外掛程式檔案**：前往 [Releases 頁面](https://github.com/equalang/equalang-zotero-plugin/releases/latest)，下載最新版本的 `equalang.xpi`，不需要解壓縮。
2. **開啟 Zotero 的附加元件管理**：在 Zotero 的功能表選取「工具 → 附加元件」。
3. **從檔案安裝**：點選右上角的齒輪圖示，選取「Install Plugin From File…」，然後選取剛下載的檔案；也可以直接把檔案拖進這個附加元件視窗。
4. **登入意扣**：安裝完成後會開啟歡迎視窗，點選「登入或註冊」，在瀏覽器中完成登入。新帳號註冊即贈送點數。

之後外掛程式會隨 Zotero 自動更新，也可以在「工具 → 附加元件」的齒輪選單中手動檢查更新。

## 使用

- **翻譯文件**：在文獻或附件上按右鍵，選取「用意扣翻譯文件…」，確認目標語言與預計消耗點數後開始。進度會顯示在右側的「意扣」欄位中，也可以在「工具 → 意扣 → 翻譯任務…」中查看。

  ![右鍵選單中的意扣翻譯](../images/context-menu.png)

- **左右對照閱讀**：開啟雙語對照版，在閱讀器中選擇「檢視 → 延展 → Odd」，原文與譯文即可左右並排。
- **劃詞翻譯**：在閱讀器中選取文字即可。也可以在設定中改為先顯示「翻譯」按鈕，點選後再翻譯。
- **設定**：在「工具 → 意扣 → 設定…」中，可以設定要翻譯成哪種語言、PDF 要雙語對照還是僅譯文、譯文儲存在哪裡、翻譯完成後是否開啟譯文，以及是否最佳化 PDF 中的公式排版（會扣除較多點數）。

## 常見問題

**支援哪些 Zotero 版本與作業系統？**

支援 Zotero 7、8、9 與 10，在 Windows 和 macOS 上皆可使用。

**如何計費？**

外掛程式可免費安裝。翻譯與意扣網站共用點數餘額，依照[網站的價格](https://equalang.com/zh-TW/pricing?utm_source=github)扣除點數。文件翻譯開始前會顯示預計消耗的點數與目前餘額，取消的任務不扣點數。新帳號註冊即贈送點數。

**譯文檔案儲存在哪裡？**

文件翻譯的譯文檔案預設會作為附件附加在原文獻下方，隨 Zotero 同步；也可以在設定中改為儲存至電腦上的資料夾，再連結至原文獻（僅限「我的文獻庫」）。

## 連結

- [意扣官網](https://equalang.com/zh-TW?utm_source=github) · [Zotero 外掛程式頁面](https://equalang.com/zh-TW/extension/zotero?utm_source=github) · [價格](https://equalang.com/zh-TW/pricing?utm_source=github) · [隱私權政策](https://equalang.com/zh-TW/legal/privacy?utm_source=github) · [服務條款](https://equalang.com/zh-TW/legal/terms?utm_source=github)
- [意扣瀏覽器擴充功能](https://equalang.com/zh-TW/extension?utm_source=github)：網頁、影片字幕與漫畫翻譯
- 有問題：<support@equalang.com>

本存放庫發布外掛程式的安裝檔（見 [Releases](https://github.com/equalang/equalang-zotero-plugin/releases)）與更新紀錄。
