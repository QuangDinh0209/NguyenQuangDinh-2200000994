# DỰ ÁN: TỪ DỮ LIỆU ĐẾN PHÂN TÍCH VỚI PYTHON
   - **Họ và tên:** Nguyễn Quang Định
   - **MSSV:** 2200000994
   - **Lớp:** 23DTH2A.GHEP02

   ## Trả lời câu hỏi thu hoạch
   - **Câu 1:** Trong UTF-8, các ký tự ASCII thông dụng như chữ cái tiếng Anh không dấu thường chiếm 1 byte. Nhiều ký tự tiếng Việt có dấu cần 2 hoặc 3 byte để biểu diễn. Vì vậy, hai chuỗi có cùng số ký tự vẫn có thể có số byte khác nhau.
   - **Câu 2:** CSV lưu dữ liệu dạng bảng gồm hàng và cột, dễ mở bằng bảng tính và phù hợp với dữ liệu phẳng. JSON lưu dữ liệu dưới dạng đối tượng và mảng, hỗ trợ cấu trúc lồng nhau. Vì vậy, dữ liệu phân cấp hoặc nested thường phù hợp với JSON hơn.
   - **Câu 3:** Notepad thường hiển thị các ký tự khó đọc hoặc ký hiệu lạ. Nguyên nhân là file ảnh PNG/JPEG là dữ liệu nhị phân theo định dạng riêng, không phải văn bản thuần được mã hóa để con người đọc trực tiếp.
   - **Câu 4:** `data/raw/` giữ dữ liệu nguồn ban đầu để có thể kiểm tra và tái lập quy trình; `data/processed/` chứa dữ liệu đã làm sạch hoặc lọc, tránh ghi đè dữ liệu gốc. `.gitignore` giúp loại bỏ file tạm, cache, môi trường ảo và thông tin cấu hình nhạy cảm khỏi Git, làm repository gọn và an toàn hơn.

   - **Câu 5:** Với bộ dữ liệu mẫu gồm 5 sinh viên, GPA trung bình là **3.56/4.0**, cao nhất **3.9** (Vu Hai Yen), thấp nhất **3.1** (Le Van C). Đây là nhận xét dựa trên dữ liệu mẫu đi kèm dự án.