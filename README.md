# PCB Robocon-DCN ME V1.0

Mục tiêu của mã nguồn này là xây dựng bộ mạch tiêu chuẩn cho Robocon các năm, làm nền tảng để phát triển. Bộ mạch được đúc kết kinh nghiệm từ năm 2018, và trải qua các năm vẫn ổn định để hoạt động. Trong bộ mạch tiêu chuẩn này sẽ chia làm ba thành phần chính có trên robot: bộ điều khiển trung tâm là vi điều khiển STM32F407, bộ kích 16 van điều khiển và bộ đọc tín hiệu 16 cảm biến qua opto cách ly quang. Mục đích của việc chia các module riêng lẻ nhằm tăng tính thẩm mỹ khi lắp đặt trên robot cũng như dễ dàng bố trí và thay thế các board mạch khi cần thiết.

## Công việc giải quyết
- [X] Main robot chạy trên vi điều khiển STM32F407;
- [X] Mạch Input đọc tín hiệu cảm biết cách ly quang;
- [X] Mạch điều khiển van qua ULN2803 có cách ly quang.

## Thành viên đóng góp chính
1. [Mai Duy Quang (K12)](https://www.facebook.com/mdq198)
2. [Nguyễn Văn Đăng (K11)](https://www.facebook.com/profile.php?id=100006243600874)
3. [Nguyễn Hữu Tuấn (K11)](https://www.facebook.com/tuannguyen.999999)
5. [Vũ Công Thành (K10)](https://sites.google.com/view/vuthanhcdt/home)
6. [Lê Đức Thuận (K10)](https://www.facebook.com/thuan.ld97)
7. [Các thành viên HaIBot Lab](https://sites.google.com/view/haibot-lab/)

Các thông tin được cập nhật theo từng năm với mong muốn tạo ra các nền tảng để tiếp lửa cho khóa sau, do vậy khi sử dụng vui lòng trích dẫn các thông tin này và phát triển theo từng năm. Không chia sẻ các thông tin này với bất kỳ ai khác ngoài đội Robocon DCN-ME 

Người biên soạn:  [Vũ Công Thành (K10)](https://sites.google.com/view/vuthanhcdt/home)

Ngày cập nhật: 04/04/2023
