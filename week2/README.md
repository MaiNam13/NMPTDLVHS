## 1. Công nghệ sử dụng

* **Ngôn ngữ:** Python 3
* **Thư viện chính:**

  * `pandas`
  * `numpy`
* **Định dạng dữ liệu:** CSV
* **Môi trường:** Jupyter Notebook (`.ipynb`)

---

## 2. Nội dung chính của bài LAB

Notebook `MaiVanNam_2374802010322_lab2.ipynb` bao gồm các nội dung xử lý dữ liệu sau:

### 2.1 Đọc và khám phá dữ liệu

* Đọc dữ liệu từ file `dulieuxettuyendaihoc.csv`
* Thiết lập cột `STT` làm chỉ mục (index)
* Hiển thị và kiểm tra dữ liệu ban đầu

### 2.2 Phân loại biến

* **Biến định tính:** GT, DT, KV, KT,…
* **Biến định lượng:**

  * Các cột điểm môn học (T1–T6, L1–L6, …)
  * Các cột điểm đại học (DH1, DH2, DH3)

### 2.3 Xử lý dữ liệu thiếu (Missing Data)

* Biến định tính:

  * Thay thế giá trị thiếu bằng `0`
* Biến định lượng:

  * Thống kê số lượng giá trị thiếu
  * Thay thế giá trị thiếu bằng **giá trị trung bình (Mean)** của từng biến

### 2.4 Biến đổi và tạo biến mới

* Tính điểm trung bình môn:

  * `TBM1`, `TBM2`, `TBM3`
* Xếp loại học lực:

  * Y (Yếu), TB (Trung bình), K (Khá), G (Giỏi), XS (Xuất sắc)
* Chuẩn hóa điểm trung bình môn về **thang điểm 0–4**:

  * `US_TBM1`, `US_TBM2`, `US_TBM3`
* Xét tuyển đại học theo **khối thi**

### 2.5 Kiểm tra và làm sạch dữ liệu

* Đảm bảo các cột điểm ở dạng số (numeric)
* Kiểm tra lại dữ liệu sau xử lý
* Dữ

