# ML office

**Bộ công cụ văn phòng, trợ lý AI và không gian dạy học trong cùng một ứng dụng.**

ML office giúp bạn soạn văn bản, làm việc với bảng tính, chuẩn bị bài trình chiếu, chuyển PDF/ảnh scan thành văn bản và xây dựng học liệu. Với giáo viên, ứng dụng kết nối ngân hàng câu hỏi, công cụ tạo đề và trò chơi để tái sử dụng nội dung cho nhiều hoạt động trên lớp.

Tài liệu và dữ liệu dạy học được lưu trên máy. Các chức năng AI trực tuyến, kho cộng đồng và truy cập nguồn học liệu trên Internet cần kết nối mạng.

## Tải ML office 0.2.8

| Hệ điều hành | Bộ cài |
| --- | --- |
| macOS | [Tải ML office 0.2.8 (.dmg)](https://github.com/tranbao209/ml-office-releases/releases/download/v0.2.8/ML.office-0.2.8.dmg) |
| Windows | [Tải ML office 0.2.8 (.exe)](https://github.com/tranbao209/ml-office-releases/releases/download/v0.2.8/ML-Office-Setup-0.2.8.exe) |

[Xem bản phát hành mới nhất](https://github.com/tranbao209/ml-office-releases/releases/latest) · [Xem thống kê lượt tải](https://api.github.com/repos/tranbao209/ml-office-releases/releases/tags/v0.2.8)

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

**Giới hạn của bản 0.2.8:** tệp đính kèm tối đa **100 MiB**; PDF/OCR tối đa **200 trang** mỗi lượt xử lý; mỗi lượt AI nhận tối đa **24.000 ký tự văn bản trích xuất**. Đây là các giới hạn khác nhau: một PDF nhập được vẫn có thể quá dài để gửi toàn bộ cho AI trong một lượt. Ứng dụng chưa tự chia tài liệu dài trong luồng đính kèm này.

Khả năng đọc Office chủ yếu dựa trên nội dung văn bản trích xuất, không bảo đảm hiểu đầy đủ mọi hình, biểu đồ hay bố cục. Bản scan mờ, chữ viết tay, ký hiệu và công thức cần được đối chiếu lại. Thời gian xử lý phụ thuộc cấu hình máy, độ phức tạp của tài liệu và dịch vụ AI.

## Công cụ dành cho dạy học

- **Ngân hàng câu hỏi có sẵn:** **1.927 câu hỏi trong 46 gói** được đóng gói cùng bản cài và nạp vào ngân hàng trên máy khi mở ứng dụng lần đầu. Có thể tìm, lọc theo môn/lớp, chỉnh sửa và dùng lại để soạn đề.
- **Tạo đề kiểm tra:** hỗ trợ năm dạng câu hỏi — một đáp án, nhiều đáp án, đúng/sai, trả lời ngắn và tự luận; lấy câu từ ngân hàng, lập ma trận gọn, chia điểm, trộn mã đề và xuất Word có hoặc không có đáp án.
- **Phiếu bài tập Toán:** sinh phiếu bài tập theo phạm vi đã chọn và xuất Word để chỉnh sửa hoặc in.
- **Trò chơi học tập:** có **72 hoạt động offline** với sáu dạng chơi. Dùng đề đã lưu hoặc câu hỏi trong ngân hàng cho các hoạt động đố vui, lật thẻ, ghép cặp và trả lời ngắn; thư viện còn có dạng sắp xếp và xếp trình tự. Có thể xem trước, chọn lớp và trình chiếu toàn màn hình.
- **SGK & học liệu:** tra cứu theo môn/lớp, mở nguồn đọc và tải những tài liệu nguồn cho phép để đọc offline; bản mẫu được phân biệt với bản đầy đủ.
- **Sao lưu và khôi phục:** xuất bản sao lưu dữ liệu trên máy, khôi phục khi cần và trao đổi các gói câu hỏi.

**Ngân hàng trên máy và kho đề chung là hai nguồn riêng:** 1.927 câu hỏi đi kèm bản cài có thể dùng trên máy; kho đề chung cần Internet và hiển thị các gói đã được công khai trong cộng đồng.

## Lượt tải và kiểm tra bộ cài

Mở [thống kê GitHub của bản 0.2.8](https://api.github.com/repos/tranbao209/ml-office-releases/releases/tags/v0.2.8), tìm tên tệp trong mục `assets` và xem trường `download_count`. Đây là số lượt tải theo tệp, không phải số người dùng duy nhất hay danh sách người tải.

SHA-256 để đối chiếu bộ cài:

```text
76cbc9a16ac96afd48c4bf7fed445f34eec264529a259a45381f124219f7a632  ML.office-0.2.8.dmg
43a9da3a3fa73b812299959b42cbc68126e1e1d662647aeeba0219cbec660585  ML-Office-Setup-0.2.8.exe
```

Kho GitHub này dùng để giới thiệu sản phẩm và phân phối bộ cài ML office.
