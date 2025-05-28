# THUC_HANH_NHAP_MON_XU_LY_ANH_SO
Phạm Thanh Sang - 2174802010561
#3. Bài tập
#Câu 1: Viết chương trình nạp một ảnh và lưu thành 3 ảnh với 3 màu khác nhau:
Nạp các thư viện cần thiết
numpy: Thư viện hỗ trợ xử lý ma trận (dữ liệu ảnh dưới dạng mảng số).

imageio.v2: Dùng để đọc và lưu ảnh từ file.

matplotlib.pyplot: Dùng để hiển thị ảnh.
![alt text](image.png)


Đọc ảnh 'bird.png' từ file và lưu vào biến a (dưới dạng mảng 3 chiều: cao x rộng x 3 kênh màu RGB).
![alt text](image-1.png)

Tạo 3 bản sao của ảnh gốc để xử lý từng kênh màu Đỏ (Red), Xanh lá (Green) và Xanh dương (Blue).
![alt text](image-2.png)


Giữ lại kênh Red, đặt giá trị kênh Green và Blue bằng 0.
Giữ lại kênh Green, đặt giá trị kênh Red và Blue bằng 0.
Giữ lại kênh Blue, đặt giá trị kênh Red và Green bằng 0.
Lưu từng ảnh với kênh màu riêng vào file mới (bird_red.png, bird_green.png, bird_blue.png).
![alt text](image-3.png)


Tạo khung hiển thị ảnh với kích thước 10x5 inch.
Hiển thị ảnh kênh Red trong ô thứ nhất, tắt trục tọa độ.
Hiển thị ảnh kênh Green và Blue 
![alt text](image-4.png)