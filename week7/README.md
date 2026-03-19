1. Giới thiệu
Project này thực hiện bài toán phân loại ảnh thời trang sử dụng bộ dữ liệu Fashion-MNIST với thư viện PyTorch.
Mục tiêu:
Xây dựng mô hình Neural Network
Huấn luyện và đánh giá độ chính xác
Hiển thị kết quả training (loss & accuracy)
2. Dataset
Dataset: Fashion-MNIST
Gồm:
60,000 ảnh train
10,000 ảnh test
Mỗi ảnh:
Kích thước: 28x28 pixels
Grayscale (1 kênh)
Các lớp (10 classes):
T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot
3. Cài đặt môi trường
Chạy lệnh sau để cài thư viện:
pip install torchtorchvision matplotlib
4. Quy trình thc hiện
4.1 Load dữ liệu
Sử dụng torchvision.datasets.FashionMNIST để tải dữ liệu:
Dữ liệu được lưu vào thư mục ./data
Tách thành:
tr_images
tr_targets
4.2 Trực quan hóa dữ liệu
Hiển thị ảnh theo từng class
Mỗi class gồm nhiều ảnh mẫu
Giúp hiểu dataset trước khi train
4.3 Xây dựng Dataset tùy chỉnh
Tạo class:
class FMNISTDataset(Dataset):
Chức năng:
Chuyển ảnh về dạng vector (28x28 → 784)
Chuẩn hóa dữ liệu
Trả về (x, y)
4.4 DataLoade
DataLoader(batch_size=32, shuffle=True)
Dùng để:
Chia batch
Trộn dữ liệu
4.5 Xây dựng mô hình
Sử dụng Neural Network đơn giản:
nn.Sequential
    nn.Linear(784, 1000),    nn.ReLU(),
   nn.Linear(1000, 10)
)
Output:
10 lớp (softmax qua CrossEntropyLoss)
4.6 Hàm mất mát & tối ưu
Loss: CrossEntropyLoss
Optimizer:
SGD (ban đầu)
Adam (cải tiến)
🔹 4.7 Training
Số epoch: 5
Mỗi batch:
Forward
Tính loss
Backward
Update weights
4.8 Đánh giá độ chính xác
Hàm:
accuracy()
So sánh:
predicted label vs true label
 4.9 Vẽ biểu đồ
Hiển thị:
Training Loss
Training Accuracy
5. Kết quả
Model học được qua nhiều epoch
Accuracy tăng dần theo thời gian
Loss giảm dần
Cho thấy mô hình hoạt động hiệu quả
6. Công nghệ sử dụng
Python
PyTorch
Torchvision
Matplotlib
NumPy
7. Hướng phát triển
Tăng số epoch → cải thiện accuracy
Dùng CNN thay vì ANN
Thêm validation/test set
Tuning hyperparameters
