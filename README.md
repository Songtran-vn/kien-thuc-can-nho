# Kiến Thức Cần Nhớ

Ứng dụng tĩnh, không cần cơ sở dữ liệu. Dữ liệu được lưu trong `localStorage` của trình duyệt trên từng thiết bị.

## Chức năng

- Ghi kiến thức bằng bàn phím hoặc micro tiếng Việt.
- Sắp xếp ngày cần ôn gần nhất lên đầu.
- Lọc riêng kiến thức cần ôn, đã ôn xong hoặc xem tất cả.
- Khi đánh dấu đã ôn, tự đặt lần ôn tiếp theo sau 30 ngày.
- Đến ngày hẹn, kiến thức tự quay lại danh sách cần ôn.

## Đưa lên GitHub và Vercel

1. Giải nén file ZIP và tải toàn bộ tệp lên một repository GitHub.
2. Vào Vercel, chọn **Add New → Project** và kết nối repository đó.
3. Giữ nguyên thiết lập mặc định, sau đó chọn **Deploy**.

Không cần khai báo biến môi trường, tài khoản hoặc cơ sở dữ liệu.
