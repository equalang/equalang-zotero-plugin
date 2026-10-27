# Equalang Zotero 번역 플러그인

[![Release](https://img.shields.io/github/v/release/equalang/equalang-zotero-plugin)](https://github.com/equalang/equalang-zotero-plugin/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/equalang/equalang-zotero-plugin/total)](https://github.com/equalang/equalang-zotero-plugin/releases)
[![Zotero](https://img.shields.io/badge/Zotero-7%20%7C%208%20%7C%209%20%7C%2010-CC2936)](https://www.zotero.org)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-555555)](#자주-묻는-질문)

[English](../README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · **한국어** · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Italiano](README.it.md) · [Русский](README.ru.md) · [Polski](README.pl.md) · [Türkçe](README.tr.md) · [Tiếng Việt](README.vi.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md) · [हिन्दी](README.hi.md) · [العربية](README.ar.md)

[최신 버전 다운로드](https://github.com/equalang/equalang-zotero-plugin/releases/latest) · [공식 웹사이트](https://equalang.com/ko/extension/zotero?utm_source=github) · [가격](https://equalang.com/ko/pricing?utm_source=github) · [변경 내역](../CHANGELOG.md)

> **키워드:** Zotero 번역 플러그인, Zotero PDF 번역, 문헌 번역, 논문 번역, 서식 유지 PDF 번역, 대역 대조, 선택 텍스트 번역, Word 번역, PPT 번역, Excel 번역, 학술 번역, zotero plugin, zotero translate, pdf translator

**클릭 한 번으로 번역, 나란히 대조.** Equalang의 Zotero 플러그인은 PDF 등 다양한 문서 번역과 선택 텍스트 번역을 지원합니다. 첨부 파일을 마우스 오른쪽 버튼으로 클릭하면 논문 전체를 바로 번역할 수 있으며, 번역본은 기존 서식을 유지한 채 원본 항목의 첨부 파일로 추가됩니다. 리더에서 텍스트를 선택하면 번역과 단어 뜻이 팝업창에 바로 표시됩니다.

![왼쪽은 원문, 오른쪽은 번역본. 단어를 선택하면 팝업창에 뜻이 바로 표시됩니다](../images/reader-bilingual.png)

## 기능

- **문서 번역**: PDF, Word, PowerPoint, Excel 첨부 파일을 마우스 오른쪽 버튼으로 클릭하면 바로 번역됩니다. 번역본은 기존 서식을 유지한 채 원본 항목의 첨부 파일로 추가되며, PDF는 대조본으로도 생성하여 원문과 번역본을 좌우로 대조하며 읽을 수 있습니다.
- **선택 텍스트 번역**: 리더에서 텍스트를 선택하면 번역이 팝업창에 바로 표시됩니다. 단어를 선택하면 사전 의미, 발음 기호, 예문도 함께 제공됩니다.
- **백그라운드 번역**: 언제든지 Zotero를 종료할 수 있습니다. 완료되지 않은 작업은 다음 실행 시 이어서 진행되며, 번역본은 그대로 원본 항목 아래에 추가됩니다.
- **웹사이트와 크레딧 공유**: 문서 번역을 시작하기 전에 예상 크레딧과 현재 잔액이 표시되며, 취소된 작업은 크레딧이 차감되지 않습니다.

## 설치

1. **플러그인 파일 다운로드**: [Releases 페이지](https://github.com/equalang/equalang-zotero-plugin/releases/latest)로 이동하여 최신 버전의 `equalang.xpi` 파일을 다운로드합니다(압축을 풀 필요는 없습니다).
2. **Zotero 플러그인 관리 열기**: Zotero 메뉴에서 '도구 → Plugins'를 선택합니다.
3. **파일에서 설치**: 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 'Install Plugin From File…'을 선택한 뒤, 방금 다운로드한 파일을 선택합니다. 파일을 이 플러그인 창으로 직접 드래그해도 됩니다.
4. **Equalang 로그인**: 설치가 완료되면 시작 창이 열립니다. '로그인 / 가입'을 클릭하고 브라우저에서 로그인을 완료하세요. 새 계정에는 크레딧이 무료로 제공됩니다.

이후 플러그인은 Zotero와 함께 자동으로 업데이트되며, '도구 → Plugins'의 톱니바퀴 메뉴에서 수동으로 업데이트를 확인할 수도 있습니다.

## 사용 방법

- **문서 번역**: 항목이나 첨부 파일에서 마우스 오른쪽 버튼을 클릭하고 'Equalang으로 문서 번역…'을 선택한 뒤, 대상 언어와 예상 크레딧을 확인하고 시작합니다. 진행 상황은 오른쪽의 'Equalang' 창에 표시되며, '도구 → Equalang → 번역 작업…'에서도 확인할 수 있습니다.

  ![오른쪽 클릭 메뉴의 Equalang 번역](../images/context-menu.png)

- **좌우 대조 읽기**: 대조본을 열고 리더에서 '보기 → Spreads → Odd'를 선택하면 원문과 번역본이 좌우로 나란히 정렬됩니다.
- **선택 텍스트 번역**: 리더에서 텍스트를 선택하기만 하면 됩니다. 설정에서 먼저 '번역' 버튼이 표시되도록 변경하여 클릭한 후 번역할 수도 있습니다.
- **설정**: '도구 → Equalang → 설정…'에서 번역할 언어, PDF 대역 대조 여부(대역 대조 또는 번역본만), 번역본 저장 위치, 번역 완료 후 번역본 열기 여부, PDF 내 수식 서식 최적화 여부(크레딧이 추가 차감됨)를 설정할 수 있습니다.

## 자주 묻는 질문

**어떤 Zotero 버전과 운영체제를 지원하나요?**

Zotero 7, 8, 9, 10을 지원하며, Windows와 macOS에서 모두 사용할 수 있습니다.

**요금은 어떻게 부과되나요?**

플러그인은 무료로 설치할 수 있습니다. 번역은 Equalang 웹사이트와 동일한 크레딧 잔액을 공유하며, [웹사이트 가격](https://equalang.com/ko/pricing?utm_source=github)에 따라 크레딧이 차감됩니다. 문서 번역을 시작하기 전에 예상 크레딧과 현재 잔액이 표시되며, 취소된 작업은 크레딧이 차감되지 않습니다. 새 계정에는 크레딧이 무료로 제공됩니다.

**번역된 파일은 어디에 저장되나요?**

문서 번역 파일은 기본적으로 원본 항목의 첨부 파일로 저장되어 Zotero와 함께 동기화됩니다. 설정에서 컴퓨터의 특정 폴더에 저장한 후 원본 항목에 링크하도록 변경할 수도 있습니다('내 라이브러리'에만 해당).

## 링크

- [Equalang 공식 웹사이트](https://equalang.com/ko?utm_source=github) · [Zotero 플러그인 페이지](https://equalang.com/ko/extension/zotero?utm_source=github) · [가격](https://equalang.com/ko/pricing?utm_source=github) · [개인정보 처리방침](https://equalang.com/ko/legal/privacy?utm_source=github) · [서비스 이용약관](https://equalang.com/ko/legal/terms?utm_source=github)
- [Equalang 브라우저 확장 프로그램](https://equalang.com/ko/extension?utm_source=github): 웹페이지, 동영상 자막, 만화 번역
- 문의 사항: <support@equalang.com>

이 저장소에서는 플러그인 설치 파일([Releases](https://github.com/equalang/equalang-zotero-plugin/releases) 참조)과 변경 내역을 배포합니다.
