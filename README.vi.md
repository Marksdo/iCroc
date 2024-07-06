# README.md
- [English](README.md)
- [Deutsch](README.de.md)
- [Spanish](README.es.md)
- [Finnish](README.fi.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [Indonesian](README.id.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)
- [Norwegian](README.nb.md)
- [Dutch](README.nl.md)
- [Polish](README.pl.md)
- [Portuguese](README.pt.md)
- [Swedish](README.sv.md)
- [ภาษาไทย](README.th.md)
- [Turkish](README.tr.md)
- [Ukrainian](README.uk.md)
- [Vietnamese](README.vi.md)

# iCroc - Ứng dụng dòng lệnh Croc cho iOS và macOS

Tải về [phiên bản mới nhất từ App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- Hoàn toàn thiết kế lại giao diện và logic hoạt động của ứng dụng.
- Nâng cấp phiên bản croc nhúng lên v10.0.8.
- Thêm tính năng hỗ trợ Handoff cho iOS và macOS.
- Hỗ trợ nhiều ngôn ngữ hơn.

V1.1
---
- Thiết kế lại biểu tượng ứng dụng.
- Sửa lỗi và cải thiện hiệu suất.

V1.0
---
croc là một công cụ cho phép hai máy tính đơn giản và an toàn chuyển đổi tập tin và thư mục. Theo tôi biết, croc là công cụ truyền tệp dòng lệnh duy nhất có thể làm tất cả các điều sau:

- Cho phép hai máy tính chuyển đổi dữ liệu (sử dụng mạng trung gian)
- Cung cấp mã hóa điểm-điểm (sử dụng PAKE)
- Dễ dàng chuyển đổi giữa các nền tảng (Windows, Linux, Mac)
- Cho phép chuyển đổi nhiều tập tin
- Cho phép tiếp tục chuyển đổi sau khi bị gián đoạn
- Không cần máy chủ cục bộ hoặc chuyển tiếp cổng
- Ưu tiên sử dụng ipv6 với fallback ipv4
- Có thể sử dụng proxy như tor

Ứng dụng dòng lệnh này được dựa trên ứng dụng dòng lệnh có sẵn tại đây:

https://github.com/schollz/croc

## macOS kích hoạt iCroc trong Cài đặt
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 Gửi nhanh tập tin với iCroc
- Chọn tập tin trong Finder sau đó sử dụng "mở với iCroc".
- Trong Finder chọn tập tin và nhấn ⌘+C để sao chép, sau đó mở iCroc và nhấn ⌘+V để gửi tập tin.
- Kéo tập tin vào iCroc.

# ⚡ Handoff
- Cả thiết bị iOS và macOS đều cài đặt ứng dụng iCroc.
- Bật tính năng Handoff trên iOS và macOS.
- Khi người gửi tạo mã, iCroc trên thiết bị khác sẽ tự động nhận mã.

# 🔮 Tiếp tục tác vụ bị gián đoạn
- Người gửi gửi lại tập tin và người nhận sử dụng định dạng mã mới@mã cũ, ví dụ: 4161-mambo-young-baby@7611-south-concept-satire.
- Người gửi gửi lại tập tin sử dụng mã thông báo tùy chỉnh làm mã cũ.

# 💾 Thư mục nhận tùy chỉnh
- Thư mục nhận sẽ được lưu vào ~/Downloads/'${code-phrase}'.
- Sử dụng '@tên_thư_mục' sẽ lưu vào ~/Downloads/tên_thư_mục, ví dụ: 8443-siren-mayor-origin@mypics.
- Sử dụng cùng thư mục đích sẽ tự động tiếp tục tác vụ chuyển đổi bị gián đoạn.