Tiếp tục từ bài đa hình 2, hãy bổ sung code cần thiết để xây dựng một bản đồ họa (Java Swing) mô phỏng chuyển động của các hình vẽ:

- Xem demo tại [đây](https://www.youtube.com/watch?v=RfG2hQN3zfM)
![](https://bqcuong.github.io/uetoop/DaHinh3/dahinh3.png)
- Tham khảo thêm bài hướng dẫn đồ họa Java trong danh sách bài tập
- Các hình vẽ nên được thêm thuộc tính tốc độ (velocity) để mô tả tốc độ di chuyển
- Lớp **Layer** nên thừa kế từ lớp **JPanel**, override phương thức _paintComponent()_ để sử dụng đối tượng **Graphics** từ thư viện Java2D
- Mỗi lớp con thuộc lớp **Shape** nên có phương thức _move()_ để tự mô phỏng di chuyển, phương thức _draw()_ với tham số là đối tượng **Graphics** để có thể "tự vẽ". Nếu làm theo cách này, bạn sẽ tiết kiệm được nhiều code, và code sẽ "elegant" hơn rất nhiều (đây là ví dụ cụ thể về việc áp dụng tính đa hình).
- Cài đặt chức năng thêm hình bằng các phím tắt (`c` thêm hình tròn, `r` thêm hình chữ nhật,...). Những hình này sẽ được sinh với các thông tin tọa độ, kích thước, màu sắc ngẫu nhiên (realtime).
- Cài đặt các chức năng xóa hình tròn, xóa các hình trùng nhau (realtime)
- Cài đặt hệ thống nhận diện va chạm (các hình va chạm vào khung cửa sổ, va chạm lẫn nhau)
- Tự cài đặt các ý tưởng mới mình thích...
