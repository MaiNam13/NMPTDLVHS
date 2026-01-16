## 2. Công nghệ sử dụng

* **Ngôn ngữ:** Python 3
* **Thư viện chính:**

  * `pandas`
  * `numpy`
* **Định dạng dữ liệu:** CSV
* **Môi trường:** Jupyter Notebook (`.ipynb`)

---

## 3. Nội dung chính của bài LAB

Notebook bao gồm các nội dung xử lý dữ liệu sau:

### 3.1 Đọc và khám phá dữ liệu

* Đọc dữ liệu từ file `dulieuxettuyendaihoc.csv`
* Thiết lập cột `STT` làm chỉ mục (index)
* Hiển thị và kiểm tra dữ liệu ban đầu

### 3.2 Phân loại biến

* **Biến định tính:** GT, DT, KV, KT,…
* **Biến định lượng:** Các cột điểm môn học (T1–T6, L1–L6, …) và điểm đại học (DH1, DH2, DH3)

### 3.3 Xử lý dữ liệu thiếu (Missing Data)

* Biến định tính:

  * Thay thế giá trị thiếu bằng `0`
* Biến định lượng:

  * Thống kê số lượng giá trị thiếu
  * Thay thế giá trị thiếu bằng **giá trị trung bình (Mean)** của từng biến
* Áp dụng lần lượt cho toàn bộ các cột điểm môn học và điểm đại học

### 3.4 Biến đổi và làm sạch dữ liệu

* Đảm bảo các cột điểm ở dạng số (numeric)
* Kiểm tra lại dữ liệu sau khi hiệu chỉnh
* Dữ liệu sau xử lý không còn giá trị thiếu

### 3.5 Lưu dữ liệu sau xử lý

* Xuất dữ liệu đã được làm sạch ra file CSV mới
* Sẵn sàng cho các bước phân tích hoặc mô hình hóa tiếp theo

---

## 4. Kết quả đạt được

* Dữ liệu được làm sạch hoàn toàn
* Không còn giá trị thiếu trong các cột điểm
* Dữ liệu được chuẩn hóa và nhất quán
* File CSV đầu ra có thể dùng cho:

  * Thống kê mô tả
  * Phân tích dữ liệu
  * Xây dựng mô hình học máy (ở các LAB sau)

---

## 5. Ý nghĩa của bài LAB

* Giúp sinh viên hiểu rõ:

  * Cách đọc và xử lý dữ liệu thực tế
  * Tầm quan trọng của việc xử lý dữ liệu thiếu
  * Các bước tiền xử lý dữ liệu trong khoa học dữ liệu
* Là nền tảng cho các bài LAB và đồ án phân tích dữ liệu tiếp theo

---

## 6. Ghi chú

* Notebook phục vụ **mục đích học tập**
* Dữ liệu sử dụng mang tính minh họa cho bài toán xét tuyển đại học

