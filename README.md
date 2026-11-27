# ML office

**Bộ công cụ văn phòng, trợ lý AI và không gian dạy học trong cùng một ứng dụng.**

ML office giúp bạn soạn văn bản, làm việc với bảng tính, chuẩn bị bài trình chiếu, chuyển PDF/ảnh scan thành văn bản và xây dựng học liệu. Với giáo viên, ứng dụng kết nối ngân hàng câu hỏi, công cụ tạo đề và trò chơi để tái sử dụng nội dung cho nhiều hoạt động trên lớp.

Tài liệu và dữ liệu dạy học được lưu trên máy. Các chức năng AI trực tuyến, kho cộng đồng và truy cập nguồn học liệu trên Internet cần kết nối mạng.

## Tải ML office 0.3.2

| Hệ điều hành | Bộ cài |
| --- | --- |
| Windows 10/11 64-bit (x64) | [Tải bộ cài Windows (.exe)](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-Setup-0.3.2-win-x64.exe) |
| Mac Apple Silicon M1, M2, M3, M4… · macOS 14+ | [Tải bộ cài ARM64 (.dmg)](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-0.3.2-mac-arm64.dmg) |
| Mac Intel · macOS 12+ | [Tải bộ cài Intel (.dmg)](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-0.3.2-mac-Intel.dmg) · [ZIP](https://github.com/tranbao209/ml-office-releases/releases/download/v0.3.2/ML-Office-0.3.2-mac-Intel.zip) |

[Xem bản phát hành mới nhất](https://github.com/tranbao209/ml-office-releases/releases/latest) · [Xem thống kê lượt tải](https://api.github.com/repos/tranbao209/ml-office-releases/releases/tags/v0.3.2)

## Cài đặt và mở trên macOS

### 1. Tải và kiểm tra bộ cài

Tải đúng bộ cài ARM64 hoặc Intel từ bảng trên. Nếu tải bằng trình duyệt, tệp thường nằm trong thư mục `Downloads`.

Có thể kiểm tra tệp tải về bằng Terminal:

```bash
shasum -a 256 ~/Downloads/ML-Office-0.3.2-mac-arm64.dmg
```

Đối chiếu mã SHA-256 hiển thị với mã của `ML-Office-0.3.2-mac-arm64.dmg` trong mục [Lượt tải và kiểm tra bộ cài](#lượt-tải-và-kiểm-tra-bộ-cài) bên dưới. Nếu mã không khớp, hãy xóa tệp và tải lại từ link phát hành chính thức. Mã khớp xác nhận tệp giống bản được đăng ở đây; nó không thay thế việc Apple ký và kiểm tra ứng dụng.

### 2. Cài ứng dụng

1. Mở `ML-Office-0.3.2-mac-arm64.dmg` trong Finder.
2. Trong cửa sổ đĩa vừa mở, kéo `ML office` vào `Applications` và đợi sao chép xong.
3. Trong Finder, bấm nút eject cạnh ổ đĩa `ML office 0.3.2` ở thanh bên.
4. Mở Finder > `Applications`, rồi mở `ML office` từ đó. Không chạy ứng dụng trực tiếp bên trong cửa sổ DMG.

### 3. Cho phép mở lần đầu

Ở bản 0.3.2, cả hai gói Mac đều chưa có Developer ID và chưa notarize bởi Apple; gói ARM được ký ad-hoc để chạy mã native. Vì vậy macOS có thể hiện cảnh báo rằng nhà phát triển chưa được xác định. Chỉ tiếp tục nếu bạn tải đúng DMG từ link phát hành chính thức ở trên và đã kiểm tra SHA-256.

Nếu macOS chặn ứng dụng:

1. Đóng cảnh báo bằng `OK` hoặc `Done`.
2. Mở menu Apple > `System Settings` > `Privacy & Security`.
3. Kéo xuống phần `Security`, tìm thông báo về `ML office`, rồi bấm `Open Anyway`.
4. Đọc cảnh báo hiện lại và bấm `Open` để xác nhận. macOS có thể yêu cầu mật khẩu đăng nhập máy.

Sau khi xác nhận, có thể mở `ML office` bình thường từ `Applications` ở những lần sau. Nếu không thấy `Open Anyway`, đừng tắt Gatekeeper hoặc chạy lệnh bỏ qua bảo vệ; hãy tải lại và kiểm tra checksum, hoặc chờ bản phát hành đã được ký và notarize.

macOS hiển thị cảnh báo này vì chưa xác minh được danh tính/chứng thực bảo mật của ứng dụng. Việc chọn `Open Anyway` chỉ cho phép chạy ứng dụng trên máy đó; nó không biến ứng dụng thành đã được Apple xác minh.

## Có gì mới ở bản 0.3.2

- **Office miễn phí không giới hạn:** trạng thái dùng thử hoặc trả phí của AI được hiển thị riêng; quản lý gói và đăng nhập Google tại Hồ sơ.
- **Thời khóa biểu:** chỉ nhập từ Excel hoặc ảnh người dùng; OCR chạy cục bộ. Gộp các sheet và lịch sáng/chiều, lọc giáo viên cả hai buổi và Chủ nhật; sửa/xóa tiết đã nhập. Đã bỏ MiniTest và AI trong màn hình thời khóa biểu.
- **Cài đặt và cập nhật:** giao diện gọn hơn; kiểm tra cập nhật độc lập với gói AI, báo rõ khi chưa kiểm tra được; đặt lại dữ liệu tùy chọn vẫn giữ hồ sơ và bản quyền.
- **Bộ cài riêng:** Windows x64, Mac Intel và Mac Apple Silicon ARM64.

## Công cụ văn phòng và tài liệu

- **Văn bản, bảng tính, trình chiếu:** tạo, mở và chỉnh sửa tệp DOCX, XLSX, PPTX trong không gian làm việc nhiều tab.
- **PDF & OCR:** trích văn bản từ PDF có lớp chữ; nhận dạng tiếng Việt và tiếng Anh từ PDF scan hoặc ảnh JPG, PNG, WebP; rà soát, chỉnh sửa nội dung theo trang và xuất Word để tiếp tục biên tập.
- **Quản lý tài liệu:** xem tài liệu gần đây, đánh dấu yêu thích và tìm lại nội dung đã lưu.

## ML AI — từ nội dung đầu vào đến tài liệu có thể chỉnh sửa

ML AI hỗ trợ hỏi đáp, tóm tắt, dịch thuật, kiểm tra chính tả, viết lại và xây dựng dàn ý theo yêu cầu. Bạn có thể đính kèm tài liệu, yêu cầu AI đọc tài liệu đang mở hoặc tìm nội dung liên quan trong thư viện tài liệu, học liệu và câu hỏi đã lưu trên máy.

Các quy trình tiêu biểu:

- **Đọc hiểu tài liệu:** rút ý chính, giải thích đoạn khó, đặt câu hỏi theo nội dung và tổng hợp thông tin.
- **Soạn và biên tập:** viết nội dung mới, điều chỉnh cách diễn đạt, sửa lỗi chính tả và hỗ trợ dịch song ngữ.
- **Tạo tệp Office:** chuyển nội dung thành Word, bảng tính Excel, bài trình chiếu PowerPoint hoặc Markdown để mở và chỉnh sửa tiếp.
- **Chuẩn bị bài dạy:** gợi ý dàn ý, câu hỏi và sơ đồ tư duy; chuyển nội dung tài liệu thành bài trình chiếu.
- **Tra cứu có nguồn trong chế độ ML +:** tìm bài tham khảo trên Wikipedia kèm liên kết để bạn mở và kiểm tra.
- **ML Ultra:** hỗ trợ hỏi đáp đa lĩnh vực, giải thích/viết mã và tạo ảnh từ mô tả khi dùng chế độ, gói và dịch vụ phù hợp.

ML AI sử dụng dịch vụ trực tuyến và yêu cầu gói **ML +** hoặc **ML Ultra** phù hợp. Nội dung được gửi đến dịch vụ AI khi bạn sử dụng các chức năng đó. Kết quả AI cần được kiểm tra trước khi đưa vào tài liệu, đề kiểm tra hoặc giảng dạy.

### Đọc tài liệu từ ngắn đến nhiều trang

| Loại nội dung | Cách sử dụng |
| --- | --- |
| Văn bản ngắn, ghi chú, bài học | Đính kèm hoặc chọn nội dung để hỏi đáp, tóm tắt, dịch và biên tập. |
| Word, Excel, PowerPoint | Đọc phần văn bản; với Excel có tên trang tính, vị trí ô và giá trị/kết quả công thức đã lưu; với PowerPoint có văn bản theo thứ tự slide. |
| PDF và ảnh scan | Trích chữ hoặc OCR trước khi chuyển nội dung cho AI; hỗ trợ tiếng Việt và tiếng Anh. |
| Tài liệu dài, nhiều chương hoặc dung lượng lớn | Chia thành các phần nhỏ để xử lý lần lượt, sau đó yêu cầu tổng hợp các ý đã xử lý. |

**Giới hạn của bản 0.3.2:** tệp đính kèm tối đa **100 MiB**; PDF/OCR tối đa **200 trang** mỗi lượt xử lý; mỗi lượt AI nhận tối đa **24.000 ký tự văn bản trích xuất**. Đây là các giới hạn khác nhau: một PDF nhập được vẫn có thể quá dài để gửi toàn bộ cho AI trong một lượt. Ứng dụng chưa tự chia tài liệu dài trong luồng đính kèm này.

Khả năng đọc Office chủ yếu dựa trên nội dung văn bản trích xuất, không bảo đảm hiểu đầy đủ mọi hình, biểu đồ hay bố cục. Bản scan mờ, chữ viết tay, ký hiệu và công thức cần được đối chiếu lại. Thời gian xử lý phụ thuộc cấu hình máy, độ phức tạp của tài liệu và dịch vụ AI.

## Công cụ dành cho dạy học

- **Thời khóa biểu:** nhập `.xlsx` hoặc ảnh do bạn chọn, gộp lịch sáng/chiều, xem theo giáo viên và chỉnh sửa/xóa tiết đã nhập.

- **Ngân hàng câu hỏi có sẵn:** **1.927 câu hỏi trong 46 gói** được đóng gói cùng bản cài và nạp vào ngân hàng trên máy khi mở ứng dụng lần đầu. Có thể tìm, lọc theo môn/lớp, chỉnh sửa và dùng lại để soạn đề.
- **Tạo đề kiểm tra:** hỗ trợ năm dạng câu hỏi — một đáp án, nhiều đáp án, đúng/sai, trả lời ngắn và tự luận; lấy câu từ ngân hàng, lập ma trận gọn, chia điểm, trộn mã đề và xuất Word có hoặc không có đáp án.
- **Phiếu bài tập Toán:** sinh phiếu bài tập theo phạm vi đã chọn và xuất Word để chỉnh sửa hoặc in.
- **Trò chơi học tập:** có **72 hoạt động offline** với sáu dạng chơi. Dùng đề đã lưu hoặc câu hỏi trong ngân hàng cho các hoạt động đố vui, lật thẻ, ghép cặp và trả lời ngắn; thư viện còn có dạng sắp xếp và xếp trình tự. Có thể xem trước, chọn lớp và trình chiếu toàn màn hình.
- **SGK & học liệu:** tra cứu theo môn/lớp, mở nguồn đọc và tải những tài liệu nguồn cho phép để đọc offline; bản mẫu được phân biệt với bản đầy đủ.
- **Sao lưu và khôi phục:** xuất bản sao lưu dữ liệu trên máy, khôi phục khi cần và trao đổi các gói câu hỏi.

**Ngân hàng trên máy và kho đề chung là hai nguồn riêng:** 1.927 câu hỏi đi kèm bản cài có thể dùng trên máy; kho đề chung cần Internet và hiển thị các gói đã được công khai trong cộng đồng.

## Lượt tải và kiểm tra bộ cài

Mở [thống kê GitHub của bản 0.3.2](https://api.github.com/repos/tranbao209/ml-office-releases/releases/tags/v0.3.2), tìm tên tệp trong mục `assets` và xem trường `download_count`. Đây là số lượt tải theo tệp, không phải số người dùng duy nhất hay danh sách người tải.

SHA-256 để đối chiếu bộ cài:

```text
c0641594e8e8e2bca07c48b032f48634cf78f48870a4c3f9b8a3dd331a1863cf  ML-Office-0.3.2-mac-arm64.dmg
db074070eb8f41e0e3ee214c8bf339507d7223c4c6550fb64f8dee0646bd0d51  ML-Office-0.3.2-mac-Intel.dmg
829f8522f9c2ae61f6275a70e5fea8d4447e4d2f095585546e996fafedd7baef  ML-Office-0.3.2-mac-Intel.zip
b09b1860232e20d3a2ed65cf06984a9b66a83d0b884cd9ed896a8529bd5a7b44  ML-Office-Setup-0.3.2-win-x64.exe
fc43d40865533864ca60b25b4089a2929bad396f885fa0a5b9c00482ad9edf56  ML-Office-Setup-0.3.2-win-x64.exe.blockmap
```

## Kiểm chứng và giới hạn phát hành

- `npm run build`: exit 0.
- `npm test`: **395/395 đạt**, không lỗi, không bỏ qua.
- Thời khóa biểu đã kiểm tra nhập Excel/ảnh, gộp sheet và sáng/chiều, lọc giáo viên cả hai buổi, sửa/xóa, lựa chọn buổi không rõ và OCR cục bộ; MiniTest và AI không còn trong luồng TKB.
- macOS Intel: DMG/ZIP được kiểm tra checksum, cấu trúc `.app`, app.asar, payload, giấy phép và smoke Office; chưa ký Developer ID/notarize.
- macOS Apple Silicon: DMG hợp lệ, payload ARM64 và framework symlink được kiểm tra; ký ad-hoc, macOS 14+.
- Windows: bộ cài NSIS x64, app Electron và `x2t.exe` là PE32+ x86-64; đã kiểm tra đóng gói 6/6, nhưng chưa chạy native trên Windows 10 và chưa ký Authenticode.



Windows chưa ký Authenticode; Mac Intel chưa ký, Mac ARM ký ad-hoc. Các gói macOS chưa có Developer ID và chưa notarize. Chữ ký ad-hoc phục vụ chạy mã ARM, không xác minh danh tính nhà phát triển và không bảo đảm Gatekeeper tự cho phép bản tải về.

Các tệp nguồn/giấy phép upstream Libera đi kèm gói trong `Resources/payload/licenses` trên macOS hoặc `resources/payload/licenses` trên Windows; provenance của converter ARM nằm tại `payload/bin/darwin-arm64/PROVENANCE.json`.

Kho GitHub này dùng để giới thiệu sản phẩm và phân phối bộ cài ML office. Chỉ giữ bản phát hành chính thức hiện tại 0.3.2.
