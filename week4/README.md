LAB 4: Titanic Data Analysis & Survival Prediction
1. Giới thiệu
LAB 4 thực hiện tiền xử lý dữ liệu, khai thác dữ liệu và trực quan hóa dữ liệu hành khách trong thảm họa Titanic nhằm tìm ra các yếu tố ảnh hưởng đến khả năng sống sót của hành khách.
Dữ liệu được làm sạch, xây dựng đặc trưng mới và trực quan hóa để phục vụ việc phân tích và hỗ trợ xây dựng mô hình dự đoán.
2. Công nghệ sử dụng
Các công nghệ và thư viện được sử dụng trong bài:
Python 3
Google Colab / Jupyter Notebook
Pandas – xử lý dữ liệu
NumPy – tính toán số học
Matplotlib – vẽ biểu đồ
Seaborn – trực quan dữ liệu
CSV dataset Titanic
3. Cách hoạt động của chương trình
Quy trình xử lý dữ liệu gồm các bước:
Bước 1: Load dữ liệu
Đọc dữ liệu Titanic từ file CSV vào chương trình.
Bước 2: Data Cleansing
Kiểm tra dữ liệu thiếu
Điền dữ liệu tuổi bị thiếu
Chuẩn hóa giới tính
Xử lý dữ liệu cabin
Xóa dữ liệu dư thừa
Bước 3: Feature Engineering
Tạo thêm các đặc trưng:
AgeGroup
familySize
Alone
namePrefix
typeCabin
Bước 4: EDA – Khai thác dữ liệu
Trực quan các yếu tố ảnh hưởng đến khả năng sống sót:
Giới tính
Hạng vé
Tuổi
Số người đi cùng
Giá vé
Cảng lên tàu
Bước 5: Xuất kết quả
Kết quả được hiển thị qua biểu đồ và bảng dữ liệu để phục vụ phân tích.
4. Kết quả đạt được
Sau khi phân tích dữ liệu, rút ra một số kết luận:
Phụ nữ có tỷ lệ sống sót cao hơn nam giới.
Hành khách hạng 1 có tỷ lệ sống sót cao hơn.
Trẻ em được ưu tiên cứu.
Hành khách đi theo nhóm nhỏ có cơ hội sống cao hơn.
Người mua vé giá cao thường sống sót nhiều hơn.
Các đặc trưng này có thể dùng để xây dựng mô hình dự đoán sống sót.
5. Giao diện web xuất kết quả (nếu có yêu cầu)
Nếu giảng viên yêu cầu giao diện web:
Có thể sử dụng:
Flask hoặc Streamlit để xây dựng giao diện
Người dùng nhập thông tin hành khách
Hệ thống dự đoán khả năng sống sót
Hiển thị kết quả dự đoán trên web
Ví dụ giao diện gồm:
Nhập tuổi
Giới tính
Hạng vé
Giá vé
Số người đi cùng
Sau đó hệ thống trả về:
Passenger survival probability: 72%
6. Kết luận
LAB giúp hiểu rõ quy trình:
Làm sạch dữ liệu
Xây dựng đặc trưng
Khai thác dữ liệu
Trực quan dữ liệu
Chuẩn bị dữ liệu cho Machine Learning
