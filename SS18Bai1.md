# Bài 1 : Sự cố không truy cập được hệ thống quản trị

##  Xác định Input (Tên miền) / Output (IP address) và mô tả sơ đồ luồng dữ liệu của DNS.

### 1: Input và  Output

- Input: tên miền phong-dieu-phoi.grenlog.vn nhưng thiếu một chữ e 

- Output Địa chỉ IP của máy chủ tương ứng với tên miền.

### 2: Sơ đề lường dữ liệu của DNS

- Nhập tên miền 

- Kiểm tra bộ nhớ đệm

- Kiểm tra IP 
  (Nếu có thì trả về địa chi IP còn không có thì trả về lỗi)

 ## Quy trình kiểm tra mã trạng thái HTTP Status Code để xác nhận xem yêu cầu đã chạm tới máy chủ hay chưa.

 Bước 1: Bật F12
 
 Bước 2: Chọn mục Network và tải lại trang
 
 Bước 3: Quan sát cột Status để kiểm tra bảng trạng thái

## Giả định Nam sửa đúng tên miền nhưng vẫn nhận mã **404 Not Found**, hệ thống đang gặp vấn đề gì?

Đúng tên miền nhưng vẫn bị 404 vì không tìm thấy trang