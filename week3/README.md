1. Tổng quan bài thực hành
Trong bài Lab 3, sinh viên sẽ thực hành các kỹ thuật cơ bản để làm sạch dữ liệu y khoa, với bộ dữ liệu mô phỏng thông tin về tuổi, cân nặng, giới tính và nhịp tim của bệnh nhân.
Mục tiêu của bài thực hành:
Hiểu rõ các lỗi thường gặp trong dữ liệu thô.
Biết cách sử dụng Pandas và NumPy để phát hiện và xử lý các lỗi này.
Tạo ra một tập dữ liệu sạch, sẵn sàng cho các bước phân tích tiếp theo.
Dữ liệu đầu vào được cung cấp dưới dạng file CSV dung lượng nhỏ, phù hợp cho việc quan sát toàn bộ cấu trúc và thực hành từng bước xử lý.
2. Đối tượng và cấu trúc dữ liệu
Bộ dữ liệu mô tả thông tin của nhiều cá nhân khác nhau, với các thuộc tính chính:
Age – Tuổi của bệnh nhân
Weight – Cân nặng
Sex – Giới tính
Heart Rates – Nhịp tim đo tại nhiều thời điểm khác nhau
3. Yêu cầu môi trường (Technical Requirements)
Để thực hiện bài Lab, sinh viên cần chuẩn bị:
Ngôn ngữ lập trình: Python
Thư viện sử dụng:
pandas – xử lý và làm sạch dữ liệu
numpy – hỗ trợ tính toán số học
4. Danh sách các vấn đề cần xử lý
Trong quá trình làm sạch dữ liệu, sinh viên sẽ lần lượt giải quyết 8 lỗi phổ biến thường gặp trong dữ liệu thực tế:
Thiếu hàng tiêu đề (Missing header)
File CSV không có dòng tên cột, cần gán lại header phù hợp.
Nhiều biến nằm trong cùng một cột
Dữ liệu chưa ở dạng tidy data, cần tách thành nhiều cột hợp lý.
Đơn vị đo không thống nhất
Một cột chứa nhiều đơn vị khác nhau (ví dụ: kg và lbs), cần chuẩn hóa về một đơn vị.
Dòng trống (Empty rows)
Xóa hoặc xử lý các hàng hoàn toàn rỗng.
Dòng trùng lặp (Duplicate rows)
Phát hiện và loại bỏ các bản ghi bị lặp.
Ký tự không phải ASCII
Xử lý lỗi mã hóa do dữ liệu chứa ký tự đặc biệt.
Giá trị bị thiếu (Missing values)
Phát hiện và điền giá trị hoặc loại bỏ các ô chứa NaN/null.
Tiêu đề cột thực chất là giá trị
Trường hợp tên cột không phải là tên biến mà là một giá trị của biến, cần chuyển đổi lại cấu trúc dữ liệu.
5. Kết quả mong đợi
Sau khi hoàn thành bài Lab, sinh viên sẽ thu được:
Một file dữ liệu đã được làm sạch.
Cấu trúc dữ liệu rõ ràng, thống nhất đơn vị đo.
Không còn dòng trống, dòng trùng lặp, hay lỗi mã hóa.
Sẵn sàng cho các bước phân tích và trực quan hóa dữ liệu ở các bài tiếp theo.
