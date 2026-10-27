# Plugin dịch Zotero Equalang

[![Release](https://img.shields.io/github/v/release/equalang/equalang-zotero-plugin)](https://github.com/equalang/equalang-zotero-plugin/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/equalang/equalang-zotero-plugin/total)](https://github.com/equalang/equalang-zotero-plugin/releases)
[![Zotero](https://img.shields.io/badge/Zotero-7%20%7C%208%20%7C%209%20%7C%2010-CC2936)](https://www.zotero.org)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-555555)](#câu-hỏi-thường-gặp)

[English](../README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Italiano](README.it.md) · [Русский](README.ru.md) · [Polski](README.pl.md) · [Türkçe](README.tr.md) · **Tiếng Việt** · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md) · [हिन्दी](README.hi.md) · [العربية](README.ar.md)

[Tải bản mới nhất](https://github.com/equalang/equalang-zotero-plugin/releases/latest) · [Trang chủ](https://equalang.com/vi/extension/zotero?utm_source=github) · [Bảng giá](https://equalang.com/vi/pricing?utm_source=github) · [Nhật ký thay đổi](../CHANGELOG.md)

> **Từ khóa:** plugin dịch Zotero, dịch PDF Zotero, dịch tài liệu, dịch bài báo khoa học, dịch PDF giữ nguyên bố cục, đối chiếu song ngữ, dịch văn bản đã chọn, dịch Word, dịch PPT, dịch Excel, dịch học thuật, zotero plugin, zotero translate, pdf translator

**Dịch một cú nhấp, đối chiếu song song.** Plugin Zotero của Equalang hỗ trợ dịch tài liệu PDF cùng nhiều định dạng khác, kèm tính năng dịch văn bản được chọn: chỉ cần nhấp chuột phải vào tệp đính kèm để dịch toàn bộ tài liệu, bản dịch giữ nguyên bố cục ban đầu và được lưu dưới dạng tệp đính kèm của tài liệu gốc; khi chọn văn bản trong trình đọc, bản dịch và giải nghĩa từ sẽ lập tức xuất hiện trong cửa sổ nổi.

![Bên trái là bản gốc, bên phải là bản dịch; khi chọn một từ, giải nghĩa sẽ lập tức xuất hiện trong cửa sổ nổi](../images/reader-bilingual.png)

## Tính năng

- **Dịch tài liệu**: Nhấp chuột phải vào tệp đính kèm PDF, Word, PowerPoint hoặc Excel để dịch. Bản dịch giữ nguyên bố cục ban đầu và được lưu dưới dạng tệp đính kèm của tài liệu gốc; tệp PDF còn có thể tạo bản đối chiếu song ngữ để đọc song song bản gốc và bản dịch ở hai bên.
- **Dịch văn bản đã chọn**: Chọn văn bản trong trình đọc, bản dịch sẽ lập tức xuất hiện trong cửa sổ nổi; khi chọn một từ, hệ thống còn cung cấp giải nghĩa, phiên âm và câu ví dụ.
- **Dịch ngầm**: Bạn có thể thoát Zotero bất kỳ lúc nào, các tác vụ chưa hoàn thành sẽ tiếp tục khi khởi động lại lần sau và bản dịch vẫn được thêm vào dưới tài liệu gốc.
- **Dùng chung điểm với website**: Trước khi dịch tài liệu, hệ thống sẽ hiển thị số điểm dự kiến cùng số dư hiện tại của bạn; các tác vụ bị hủy sẽ không bị trừ điểm.

## Cài đặt

1. **Tải xuống tệp plugin**: Truy cập [trang Releases](https://github.com/equalang/equalang-zotero-plugin/releases/latest), tải xuống tệp `equalang.xpi` phiên bản mới nhất, không cần giải nén.
2. **Mở quản lý plugin của Zotero**: Trong menu Zotero, chọn "Các công cụ → Plugins".
3. **Cài đặt từ tệp**: Nhấp vào biểu tượng bánh răng ở góc trên bên phải, chọn "Install Plugin From File…", rồi chọn tệp bạn vừa tải xuống; bạn cũng có thể kéo trực tiếp tệp vào cửa sổ plugin này.
4. **Đăng nhập Equalang**: Cửa sổ chào mừng sẽ mở ra sau khi cài đặt xong, nhấp vào "Đăng nhập hoặc đăng ký" và hoàn tất đăng nhập trong trình duyệt. Tài khoản mới được tặng điểm.

Sau đó, plugin sẽ tự động cập nhật cùng Zotero; bạn cũng có thể kiểm tra cập nhật thủ công trong menu bánh răng tại "Các công cụ → Plugins".

## Cách sử dụng

- **Dịch tài liệu**: Nhấp chuột phải vào tài liệu hoặc tệp đính kèm, chọn "Dịch bằng Equalang…", xác nhận ngôn ngữ đích cùng số điểm dự kiến rồi bắt đầu. Tiến độ sẽ hiển thị trong mục "Equalang" ở cột bên phải, hoặc bạn có thể xem tại "Các công cụ → Equalang → Tác vụ dịch…".

  ![Menu chuột phải với tính năng dịch Equalang](../images/context-menu.png)

- **Đọc đối chiếu song song**: Mở bản đối chiếu song ngữ, trong trình đọc chọn “Cách xem → Spreads → Odd”, bản gốc và bản dịch sẽ được hiển thị song song hai bên.
- **Dịch văn bản đã chọn**: Chỉ cần chọn văn bản trong trình đọc. Bạn cũng có thể đổi cài đặt sang hiện nút “Dịch” trước, nhấp vào nút mới dịch.
- **Cài đặt**: Tại "Các công cụ → Equalang → Settings…", bạn có thể thiết lập ngôn ngữ dịch sang, tệp PDF là bản đối chiếu song ngữ hay chỉ bản dịch, vị trí lưu bản dịch, có mở bản dịch sau khi hoàn tất hay không, cũng như có tối ưu hóa bố cục công thức trong PDF hay không (sẽ trừ thêm điểm).

## Câu hỏi thường gặp

**Hỗ trợ những phiên bản Zotero và hệ điều hành nào?**

Hỗ trợ Zotero 7, 8, 9 và 10, hoạt động tốt trên cả Windows và macOS.

**Chi phí được tính như thế nào?**

Plugin được cài đặt miễn phí. Quá trình dịch dùng chung số dư điểm với website Equalang và trừ điểm theo [bảng giá trên website](https://equalang.com/vi/pricing?utm_source=github). Trước khi dịch tài liệu, hệ thống sẽ hiển thị số điểm dự kiến cùng số dư hiện tại của bạn; các tác vụ bị hủy sẽ không bị trừ điểm. Tài khoản mới được tặng điểm.

**Tệp bản dịch được lưu ở đâu?**

Tệp bản dịch tài liệu mặc định được đính kèm dưới tài liệu gốc và đồng bộ cùng Zotero; bạn cũng có thể đổi cài đặt để lưu vào một thư mục trên máy tính rồi liên kết với tài liệu gốc (chỉ áp dụng cho "Thư viện của Tôi").

## Liên kết

- [Trang chủ Equalang](https://equalang.com/vi?utm_source=github) · [Trang plugin Zotero](https://equalang.com/vi/extension/zotero?utm_source=github) · [Bảng giá](https://equalang.com/vi/pricing?utm_source=github) · [Chính sách bảo mật](https://equalang.com/vi/legal/privacy?utm_source=github) · [Điều khoản dịch vụ](https://equalang.com/vi/legal/terms?utm_source=github)
- [Tiện ích mở rộng Equalang cho trình duyệt](https://equalang.com/vi/extension?utm_source=github): Dịch trang web, phụ đề video và truyện tranh
- Hỗ trợ / Liên hệ: <support@equalang.com>

Kho lưu trữ này phát hành các gói cài đặt plugin (xem [Releases](https://github.com/equalang/equalang-zotero-plugin/releases)) và nhật ký thay đổi.
