# Baithicuoikyjava
🚀 I. GIỚI THIỆU DỰ ÁN
"Snake Game Classic" là một dự án lập trình ứng dụng dựa trên nền tảng Java Swing, nhằm tái hiện lại trò chơi huyền thoại với những cải tiến về mặt kỹ thuật và trải nghiệm người dùng. Dự án tập trung vào việc áp dụng các nguyên lý lập trình hướng đối tượng (OOP) và mô hình MVC để tạo ra một cấu trúc mã nguồn sạch và dễ mở rộng.







II.## 👥 Thông tin nhóm (Team Members)

| STT | Họ và Tên | Mã Sinh Viên | Vai trò / Nhiệm vụ | Link GitHub Cá Nhân |
|-----|-----------|--------------|---------------------|----------------------|
| 1 |Lê Hồng Gia Huy (Nhóm trưởng) | 3120225065 | Code Controller, Code Model, Xử lý Thuật toán, Main | https://github.com/giahuylehong398-glitch |
| 2 | Trần Văn Tài | 3120225133 | Xử lý File I/O, Main, test, Báo cáo |https://github.com/tvt2007cute-debug  |
| 3 | Nguyễn Công  | 3120225023 | Vẽ Giao diện (View), KeyListener, Đồ họa |https://github.com/congdanhhh2006767-tech  |

✨ III. CÁC TÍNH NĂNG NỔI BẬT

1.Giao diện hiện đại: Sử dụng đồ họa lưới caro, màu sắc Gradient mang lại cảm giác dễ nhìn và chuyên nghiệp.

2.Hệ thống vật cản (Obstacles): Các tảng đá xuất hiện ngẫu nhiên giúp tăng độ khó và tính thử thách cho trò chơi.

3.Âm thanh tương tác: Tích hợp âm thanh khi ăn mồi và khi kết thúc trò chơi bằng kỹ thuật đa luồng (Multithreading).

4.Lưu trữ Kỷ lục: Sử dụng File I/O để ghi lại điểm số cao nhất (High Score) vào file highscore.txt.




🛠 IV. CÔNG NGHỆ & KỸ THUẬT SỬ DỤNG

Kiến trúc MVC: Chia dự án thành 3 phần chính (Model - dữ liệu, View - hiển thị, Controller - điều khiển) để quản lý code hiệu quả.

Xử lý Đồ họa: Sử dụng thư viện Java Swing và Graphics2D để vẽ các đối tượng chuyển động mượt mà.

Xử lý Ngoại lệ: Tự định nghĩa lớp HoangYenNhiException để quản lý các lỗi đặc thù trong quá trình vận hành game.



📝 V. GIẢI THÍCH MÃ NGUỒN CHI TIẾT

1. Cơ chế di chuyển (Logic "Thêm đầu, xóa đuôi")
Hệ thống sử dụng một danh sách ArrayList<Point>. Khi rắn di chuyển, một tọa độ mới được thêm vào đầu danh sách. Nếu rắn không ăn mồi, phần tử cuối cùng của danh sách sẽ bị xóa, tạo cảm giác rắn đang bò.

2. Xử lý va chạm (Collision Detection)
Hàm checkCollision() trong GameController liên tục kiểm tra tọa độ đầu rắn với:
Biên của màn hình (Tường).
Các đốt thân của chính con rắn.
Tọa độ của các tảng đá (Vật cản).

3. Xử lý Âm thanh Đa luồng
Để âm thanh không gây đứng hình (lag) cho game, lớp SoundManager khởi chạy mỗi âm thanh trên một Thread riêng biệt, giúp âm thanh và hình ảnh hoạt động song song.



🏁 VI. KẾT LUẬN
Dự án đã hoàn thành đầy đủ các yêu cầu về kỹ thuật và mỹ thuật. Thông qua bài tập lớn này, nhóm đã nắm vững cách vận dụng OOP, cách quản lý tài nguyên trong Java và rèn luyện kỹ năng làm việc nhóm hiệu quả.
