# ML Office

**Bộ công cụ văn phòng và dạy học dành cho giáo viên.** Soạn văn bản, làm bảng tính, tạo bài trình chiếu và chuẩn bị tài liệu giảng dạy trong một ứng dụng.

Các công cụ Office được sử dụng miễn phí, không giới hạn thời gian. Tính năng AI sử dụng gói **ML +** hoặc **ML Ultra** riêng.

## Tải ML Office 0.3.2

| Hệ điều hành | Tải xuống |
| --- | --- |
| Windows 10/11 · 64-bit | [Bộ cài EXE](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-Setup-0.3.2-win-x64.exe) |
| Mac Apple Silicon · M1 trở lên · macOS 14+ | [Bộ cài DMG](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-0.3.2-mac-arm64.dmg) |
| Mac Intel · macOS 12+ | [Bộ cài DMG](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-0.3.2-mac-Intel.dmg) · [ZIP](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-0.3.2-mac-Intel.zip) |
| Linux · x86_64 · bản thử nghiệm | [AppImage](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-0.3.2-linux-x86_64.AppImage) |

[Xem bản phát hành](https://github.com/tranbao209/ml-office-releases/releases/tag/v0.3.2) · [Mã kiểm tra SHA-256](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/SHA256SUMS.txt)

## Làm được gì?

- **Văn bản, bảng tính, trình chiếu:** tạo, mở và chỉnh sửa DOCX, XLSX, PPTX; làm việc với nhiều tài liệu trong các tab.
- **PDF và OCR:** xử lý PDF, trích xuất chữ từ tài liệu hoặc ảnh scan tiếng Việt, tiếng Anh và xuất Word để biên tập tiếp.
- **Thời khóa biểu:** nhập Excel hoặc ảnh, nhận dạng chữ cục bộ, gộp lịch sáng/chiều, lọc theo giáo viên và sửa/xóa tiết.
- **Soạn bài và đề kiểm tra:** quản lý ngân hàng câu hỏi, trộn đề, xuất Word, tạo phiếu bài tập Toán và tổ chức trò chơi học tập.
- **Trợ lý AI:** hỏi đáp, tóm tắt, dịch, viết lại và hỗ trợ soạn tài liệu theo nội dung bạn cung cấp.

## Cài đặt

**Windows:** chạy tệp EXE và làm theo hướng dẫn.

**macOS:** mở DMG, kéo **ML office** vào **Applications**, rồi mở ứng dụng từ đó. Nếu macOS chặn lần mở đầu, vào **System Settings → Privacy & Security → Open Anyway** sau khi đã xác nhận tệp tải từ trang phát hành này. Bộ cài Mac chưa được Apple notarize; bộ cài Windows chưa ký Authenticode.

**Linux:** tải AppImage, mở Terminal tại thư mục chứa tệp rồi chạy:

```bash
chmod +x ML-Office-0.3.2-linux-x86_64.AppImage
./ML-Office-0.3.2-linux-x86_64.AppImage
```

Bản Linux cần môi trường desktop x86_64 có GTK3, NSS, ALSA, X11/GBM; glibc từ 2.34 và libstdc++ có GLIBCXX_3.4.29 trở lên. Gói đã được kiểm tra cấu trúc và checksum; **chưa kiểm thử chạy thực tế trên Linux**.

## Dữ liệu và AI

Tệp Office và OCR được xử lý trên máy. Chức năng AI cần Internet; nội dung bạn gửi cho AI được chuyển đến dịch vụ tương ứng. Hãy kiểm tra kết quả AI trước khi sử dụng trong tài liệu hoặc giảng dạy.

## Thành phần mã nguồn mở

ML Office sử dụng các thành phần từ Libera Suite, Euro-Office/ONLYOFFICE và các thư viện khác. Thông tin ghi công, giấy phép và nguồn converter được đóng gói cùng ứng dụng trong `resources/payload/licenses` (Linux/Windows) hoặc `Resources/payload/licenses` (macOS); xem thêm `THIRD_PARTY_NOTICES.md` đi kèm bộ cài.

Kho này dùng để giới thiệu và phân phối bộ cài ML Office.
