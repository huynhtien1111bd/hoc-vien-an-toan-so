# Hướng dẫn sử dụng — Học viện An toàn số CVA

## 1. Dành cho học sinh
1. Mở website và chọn **Bắt đầu hành trình**.
2. Có thể nhập biệt danh hoặc mã do giáo viên cấp; không nhập dữ liệu nhạy cảm.
3. Chọn một trong 5 trạm.
4. Đọc tình huống, chọn đáp án, bấm **Kiểm tra đáp án** để xem phản hồi giải thích.
5. Bấm **Câu tiếp theo** đến khi hoàn thành trạm.
6. Xem điểm và huy hiệu; có thể luyện tập lại.

## 2. Dành cho giáo viên
- Mở mục **Góc giáo viên** > **Mở bảng điều khiển**.
- Xem điểm theo trạm và tỉ lệ trả lời đúng ước tính dựa trên kết quả đã lưu ở thiết bị.
- Chọn **Xuất CSV** để tải dữ liệu dạng bảng.
- Có thể dùng CSV để mở bằng Excel, nhưng cần lưu ý đây chỉ là dữ liệu trên trình duyệt hiện tại.

## 3. Tùy chỉnh
- Nội dung câu hỏi nằm trong mảng `questions` ở cuối tệp `index.html`.
- Thông tin tên trạm, mô tả và huy hiệu nằm trong mảng `stations`.
- Sao lưu bản gốc trước khi chỉnh sửa. Sau khi chỉnh sửa, kiểm tra lại cả đáp án đúng và giải thích.

## 4. Đưa lên GitHub Pages
1. Tạo repository mới.
2. Tải `index.html` lên thư mục gốc.
3. Mở **Settings > Pages**.
4. Chọn nguồn triển khai từ branch chính và thư mục root.
5. Chờ GitHub xuất bản; dùng URL do GitHub cung cấp.
6. Thử URL trong cửa sổ riêng tư và trên điện thoại.

## 5. Kiểm thử tối thiểu
- Mỗi trạm mở đúng 4 câu hỏi.
- Đáp án đúng và sai đều hiển thị phản hồi.
- Điểm mỗi câu đúng là 5; tối đa 20 điểm/trạm.
- Điểm cao nhất và huy hiệu được cập nhật.
- Tải CSV được và mở được bằng Excel.
- Làm mới trang không làm mất tiến độ đã lưu trên cùng trình duyệt.
- Nếu dùng nhiều thiết bị, không giả định dữ liệu sẽ tự đồng bộ.

## 6. Quyền riêng tư và an toàn
- Sản phẩm không yêu cầu đăng nhập tài khoản.
- Tránh nhập tên đầy đủ nếu không cần; ưu tiên biệt danh/mã.
- Không nhập mật khẩu, OTP, số điện thoại, địa chỉ, thông tin sức khỏe hoặc dữ liệu nhạy cảm.
- Không dùng ảnh hoặc kết quả định danh học sinh trong báo cáo nếu chưa đáp ứng yêu cầu về sự đồng ý và bảo vệ dữ liệu.
- Trước khi triển khai toàn trường, nhà trường cần xem xét việc thu thập dữ liệu, quyền truy cập và quy trình lưu trữ.


## Góc bóc tách lừa đảo số (bản 2.0)
- Có 10 tình huống mô phỏng dành cho học sinh THCS: quà game giả, giả danh hỗ trợ tài khoản, trúng thưởng phải đóng phí, tin nhắn giao hàng giả, giả danh giáo viên, tài khoản bạn bè nhờ vay tiền, vật phẩm game/vé giá rẻ, nhiệm vụ nhận tiền, giả giọng người thân bằng AI và link bình chọn giả.
- Có ô tìm kiếm và bộ lọc theo nhóm tình huống.
- Mỗi tình huống gồm dấu hiệu đáng ngờ, cách xử lý an toàn và câu hỏi kiểm tra nhanh có phản hồi.
- Tình huống là mô phỏng; không có link độc hại hoặc hướng dẫn thực hiện lừa đảo.


## Nội dung trang chủ phiên bản 2.1
- Thông điệp chính: **“Đừng chỉ lướt Internet. Hãy làm chủ thế giới số!”**
- Giới thiệu mục tiêu học qua tình huống, nhấn mạnh bảo vệ dữ liệu, nhận diện lừa đảo, kiểm chứng thông tin và sử dụng AI có trách nhiệm.
- Nút truy cập nhanh đến hành trình học tập và khu vực tình huống lừa đảo số.


## Cập nhật phiên bản 2.2
Trang chủ đã rút gọn nội dung để tăng tính trực quan: thông điệp chính, ba điểm nhấn và hai nút hành động. Các nội dung hướng dẫn chi tiết vẫn nằm trong các khu vực chức năng của webapp.


## Cập nhật phiên bản 2.3
Giao diện trang chủ căn giữa, có logo khiên CVA, minh họa vector, nhãn gợi tò mò và hiệu ứng chuyển sắc ở tiêu đề. Trên điện thoại, các thành phần tự co giãn; người dùng bật chế độ giảm chuyển động sẽ không thấy hiệu ứng động.


## Phiên bản 2.4 — dùng chung cho nhiều trường
Tên hiển thị đã đổi thành **Học viện An toàn số**; logo là biểu tượng khiên số trung tính, không gắn với tên viết tắt của một trường cụ thể.


## Rà soát chất lượng phiên bản 2.5
- Tỉ lệ đúng ở bảng giáo viên được tính theo các trạm đã hoàn thành.
- Khuyến nghị học sinh dùng biệt danh, không nhập họ tên thật hoặc thông tin nhạy cảm.
- CSV chỉ xuất dữ liệu của trình duyệt hiện tại; cần thu thập và quản lý tệp theo quy định của nhà trường nếu dùng trong lớp.
- Tình huống lừa đảo là mô phỏng; học sinh không được thử làm theo các yêu cầu đáng ngờ ngoài đời thật.
