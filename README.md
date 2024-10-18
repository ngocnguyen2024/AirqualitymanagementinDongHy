# Quản Lý Chất Lượng Không Khí Huyện Đồng Hỷ

## Giới Thiệu
Dự án này nhằm xây dựng một hệ thống quản lý chất lượng không khí cho huyện Đồng Hỷ. Hệ thống cho phép người dùng theo dõi chất lượng không khí theo thời gian thực, cung cấp các cảnh báo về ô nhiễm, và phân tích các bài viết liên quan đến vấn đề này.

## Tính Năng
- **Đăng ký và Đăng nhập**: Người dùng có thể tạo tài khoản và đăng nhập để truy cập các chức năng của hệ thống.
- **Theo dõi Chất lượng Không khí**: Hiển thị các chỉ số chất lượng không khí (AQI, PM2.5, PM10, CO2, NOx, SO2, O3) từ các trạm quan trắc và API.
- **Biểu đồ**: Hiển thị biểu đồ để minh họa dữ liệu chất lượng không khí.
- **Cảnh báo ô nhiễm**: Gửi cảnh báo khi chất lượng không khí vượt quá ngưỡng cho phép.
- **Bài viết Phân tích**: Cung cấp các bài viết phân tích về chất lượng không khí và tác động của ô nhiễm.

## Công Nghệ Sử Dụng
- **HTML/CSS**: Để xây dựng giao diện người dùng.
- **JavaScript**: Để thực hiện các chức năng động và tương tác.
- **Chart.js**: Thư viện để hiển thị biểu đồ chất lượng không khí.
- **API AQICN**: Để lấy dữ liệu chất lượng không khí từ các trạm quan trắc.

## Cấu Trúc Thư Mục
AirqualytInDongHy/ │ ├── index.html # Tệp chính của ứng dụng ├── styles.css # Tệp CSS để định dạng giao diện ├── scripts.js # Tệp JavaScript chứa mã lệnh ├── README.md # Tệp này └── images/ # Thư mục chứa hình ảnh nền và các hình ảnh khác └── background.jpg # Hình nền cho trang web


## Cài Đặt
1. **Clone Repository**:
   ```bash
   git clone https://github.com/ngocnguyen2024/AirqualytInDongHy.git
   cd AirqualytInDongHy
