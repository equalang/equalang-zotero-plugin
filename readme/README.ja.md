# Equalang Zotero 翻訳プラグイン

[![Release](https://img.shields.io/github/v/release/equalang/equalang-zotero-plugin)](https://github.com/equalang/equalang-zotero-plugin/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/equalang/equalang-zotero-plugin/total)](https://github.com/equalang/equalang-zotero-plugin/releases)
[![Zotero](https://img.shields.io/badge/Zotero-7%20%7C%208%20%7C%209%20%7C%2010-CC2936)](https://www.zotero.org)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-555555)](#よくある質問)

[English](../README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · **日本語** · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Italiano](README.it.md) · [Русский](README.ru.md) · [Polski](README.pl.md) · [Türkçe](README.tr.md) · [Tiếng Việt](README.vi.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md) · [हिन्दी](README.hi.md) · [العربية](README.ar.md)

[最新版をダウンロード](https://github.com/equalang/equalang-zotero-plugin/releases/latest) · [公式サイト](https://equalang.com/ja/extension/zotero?utm_source=github) · [料金](https://equalang.com/ja/pricing?utm_source=github) · [更新履歴](../CHANGELOG.md)

> **キーワード：** Zotero 翻訳プラグイン、Zotero PDF 翻訳、文献翻訳、論文翻訳、レイアウト維持 PDF 翻訳、対訳表示、選択テキスト翻訳、Word 翻訳、PPT 翻訳、Excel 翻訳、学術翻訳、zotero plugin、zotero translate、pdf translator

**ワンクリックで翻訳、並べて対照。** Equalang の Zotero プラグインは、PDF をはじめとするドキュメント翻訳と選択テキストの翻訳に対応しています。添付ファイルを右クリックするだけで文献全体を翻訳でき、元のレイアウトを保ったまま訳文が元の文献の下に添付されます。リーダー内でテキストを選択すると、訳文や語義がすぐにポップアップ表示されます。

![左に原文、右に訳文。単語を選択するとポップアップに語義がすぐに表示されます](../images/reader-bilingual.png)

## 機能

- **ドキュメント翻訳**：PDF、Word、PowerPoint、Excel の添付ファイルを右クリックするだけで翻訳できます。元のレイアウトを保ったまま訳文が元の文献の下に添付され、PDF なら対訳版を生成して原文と訳文を左右に見比べながら読むこともできます。
- **選択テキストの翻訳**：リーダー内でテキストを選択すると、すぐにポップアップに訳文が表示されます。単語を選択した場合は、語義、発音記号、例文も表示されます。
- **バックグラウンド翻訳**：Zotero をいつでも終了できます。未完了のタスクは次回起動時に再開され、訳文は変わらず元の文献の下に追加されます。
- **サイトと共通のクレジット**：ドキュメント翻訳の開始前に予想クレジット数と現在の残高が表示され、キャンセルしたタスクにはクレジットがかかりません。

## インストール

1. **プラグインファイルのダウンロード**：[Releases ページ](https://github.com/equalang/equalang-zotero-plugin/releases/latest)にアクセスし、最新バージョンの `equalang.xpi` をダウンロードします（解凍する必要はありません）。
2. **Zotero のプラグイン管理を開く**：Zotero のメニューで「ツール → プラグイン」を選択します。
3. **ファイルからインストール**：右上の歯車アイコンをクリックし、「Install Plugin From File…」を選択して、ダウンロードしたファイルを指定します。このプラグイン画面にファイルを直接ドラッグしてもかまいません。
4. **Equalang にログイン**：インストール完了後にウェルカム画面が開くので、「ログイン / 登録」をクリックし、ブラウザでログインを完了します。新規アカウントにはクレジットが進呈されます。

以降、プラグインは Zotero とともに自動更新されます。「ツール → プラグイン」の歯車メニューから手動で更新を確認することもできます。

## 使い方

- **ドキュメント翻訳**：文献または添付ファイルを右クリックし、「Equalang でドキュメントを翻訳…」を選択して、翻訳先言語と予想クレジットを確認したうえで開始します。進捗は右側の「Equalang」欄に表示されるほか、「ツール → Equalang → 翻訳タスク…」でも確認できます。

  ![右クリックメニューの Equalang 翻訳](../images/context-menu.png)

- **左右に対照表示して読む**：対訳版を開き、リーダーで「表示 → 見開きページ → 奇数」を選択すると、原文と訳文が左右に並んで表示されます。
- **選択テキストの翻訳**：リーダー内でテキストを選択するだけです。設定で最初に「翻訳」ボタンを表示するように変更し、クリックしてから翻訳させることもできます。
- **設定**：「ツール → Equalang → 設定…」で、翻訳先言語、PDF を対訳にするか訳文のみにするか、訳文の保存先、翻訳完了後に訳文を開くかどうか、PDF 内の数式レイアウトの最適化（追加のクレジットを消費します）などを設定できます。

## よくある質問

**どの Zotero のバージョンと OS に対応していますか？**

Zotero 7、8、9、10 に対応しており、Windows と macOS の両方でご利用いただけます。

**料金体系はどうなっていますか？**

プラグインは無料でインストールできます。翻訳は Equalang のウェブサイトと共通のクレジット残高を使用し、[サイトの料金](https://equalang.com/ja/pricing?utm_source=github)に沿って消費されます。ドキュメント翻訳の開始前に予想クレジット数と現在の残高が表示され、キャンセルしたタスクにはクレジットがかかりません。新規アカウントにはクレジットが進呈されます。

**翻訳されたファイルはどこに保存されますか？**

ドキュメント翻訳の訳文ファイルは、デフォルトで元の文献の添付ファイルとして保存され、Zotero で同期されます。設定で PC 上のフォルダへの保存に切り替え、元の文献にリンクさせることも可能です（「マイライブラリ」のみ）。

## リンク

- [Equalang 公式サイト](https://equalang.com/ja?utm_source=github) · [Zotero プラグインページ](https://equalang.com/ja/extension/zotero?utm_source=github) · [料金](https://equalang.com/ja/pricing?utm_source=github) · [プライバシーポリシー](https://equalang.com/ja/legal/privacy?utm_source=github) · [利用規約](https://equalang.com/ja/legal/terms?utm_source=github)
- [Equalang ブラウザ拡張機能](https://equalang.com/ja/extension?utm_source=github)：Web ページ、動画字幕、マンガの翻訳
- お問い合わせ：<support@equalang.com>

本リポジトリではプラグインのインストーラー（[Releases](https://github.com/equalang/equalang-zotero-plugin/releases) を参照）と更新履歴を公開しています。
