🔹 1. Docker vs Docker Compose \| Tiêu chí \| Docker \| Docker Compose
\| \|------------\|---------\|----------------\| \| Mục đích \| Chạy một
container từ image \| Quản lý nhiều container cùng lúc \| \| Cách dùng
\| docker run ... \| File docker-compose.yml \| \| Tình huống \| Khi chỉ
cần test nhanh 1 app, 1 service \| Khi app phức tạp: web + database +
cache + message queue \|

 Khi nào dùng:

-   Dự án đơn giản → Docker.
-   Dự án nhiều service → Docker Compose.

------------------------------------------------------------------------

🔹 2. Linux vs Unix vs BSD vs macOS (\*nix) \| Tiêu chí \| Unix \| Linux
\| BSD \| macOS \| \|------------\|------\|-------\|-----\|-------\| \|
Nguồn gốc \| Thương mại (Bell Labs) \| Mã nguồn mở (1991) \| Tách từ
Unix (Berkeley) \| Xây dựng từ BSD (Darwin) \| \| Giấy phép \| Đóng \|
GPL \| BSD license (tự do hơn GPL) \| Đóng (của Apple) \| \| Dùng ở
đâu?\| Server lớn (IBM AIX, Solaris) \| Server, desktop, cloud, embedded
\| Router, firewall (FreeBSD, pfSense) \| Máy Mac, iPhone \| \| Ưu điểm
\| Ổn định, bảo mật \| Miễn phí, cộng đồng cực lớn \| Bảo mật cao, ổn
định \| Tích hợp tốt phần cứng Apple \| \| Nhược điểm \| Đắt, ít phổ
biến hiện nay \| Phân mảnh nhiều distro \| Cộng đồng nhỏ hơn Linux \|
Đóng, khó tùy biến \|

 Khi nào dùng:

-   Unix: doanh nghiệp lớn, hệ thống cũ.\
-   Linux: cloud, server, developer, AI, devops.\
-   BSD: cần bảo mật, ổn định (firewall, hệ thống mạng).\
-   macOS: phát triển phần mềm Apple hoặc cần Unix nhưng giao diện thân
    thiện.

------------------------------------------------------------------------

🔹 3. Alpine vs Ubuntu \| Tiêu chí \| Alpine \| Ubuntu \|
\|------------\|--------\|--------\| \| Kích thước image \| \~5MB \|
\~70--120MB \| \| Tốc độ \| Nhanh, nhẹ \| Nặng hơn \| \| Package \| Ít,
khó cài hơn \| Rất nhiều, dễ cài \| \| Tương thích\| Có thể lỗi với app
cần glibc \| Rất tương thích, phổ biến \| \| Dùng trong Docker \| Tối ưu
dung lượng, CI/CD \| Phát triển dễ dàng, cộng đồng lớn \|

 Khi nào dùng:

-   Alpine: khi muốn container nhẹ, build nhanh, tiết kiệm băng thông.\
-   Ubuntu: khi dev, cần dễ dùng, nhiều tài liệu, tránh lỗi tương thích.

------------------------------------------------------------------------

🔹 4. VNC \| Tiêu chí \| VNC \| \|------------\|-----\| \| Khái niệm \|
Remote Desktop (truy cập giao diện máy khác qua mạng) \| \| Ưu điểm \|
Đa nền tảng (Windows, Linux, macOS đều chạy được) \| \| Nhược điểm \|
Chậm hơn SSH (do phải truyền hình ảnh) \| \| Khi nào dùng? \| Khi muốn
thấy GUI (desktop environment) chứ không chỉ dòng lệnh \|
