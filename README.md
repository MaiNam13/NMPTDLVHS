Mục đích

Chương trình được xây dựng nhằm xử lý và phân tích dữ liệu xét tuyển đại học từ file CSV bằng Python.
Kết quả sau xử lý dùng để đánh giá học lực và xác định kết quả trúng tuyển của thí sinh.

Công nghệ sử dụng

Python 3

Pandas

Dữ liệu đầu vào/đầu ra: CSV

Chức năng chính

Đọc dữ liệu từ file dulieuxettuyendaihoc.csv

Phân biệt dữ liệu định tính và định lượng

Xử lý dữ liệu thiếu:

Biến định tính → điền giá trị mặc định

Biến định lượng → điền giá trị trung bình

Tính điểm trung bình môn cho 3 giai đoạn học tập

Phân loại học lực theo mức điểm

Chuẩn hóa điểm về thang 0–4

Xét tuyển đại học theo từng khối thi

Lưu dữ liệu sau xử lý ra file mới

Kết quả đạt được

Dữ liệu sạch, không còn giá trị thiếu

Tạo thêm các cột phục vụ phân tích:

Điểm trung bình môn (TBM1, TBM2, TBM3)

Xếp loại học lực (XL1, XL2, XL3)

Điểm chuẩn hóa (US_TBM1, US_TBM2, US_TBM3)

Kết quả xét tuyển (KQXT)

File kết quả:

processed_dulieuxettuyendaihoc.csv
