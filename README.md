# Baitap_web3_Linux
Bài tập 3   : môn Phát triển ứng dụng trên nền web
Giảng viên  : Đỗ Duy Cốp
Lớp học phần: 58KTPM
Ngày giao   : 2025-10-24 13:50
Hạn nộp     : 2025-11-05 00:00
--------------------------------------------------
Yêu cầu     : LẬP TRÌNH ỨNG DỤNG WEB trên nền linux
1. Cài đặt môi trường linux:
   Vào Control Panel chọn Windown Subsuytem for Linux


<img width="582" height="496" alt="image" src="https://github.com/user-attachments/assets/132e63e5-463f-4eae-8ca6-8c10e575063b" />


Tạo file docker-compose.yml trong thư mục F:\Linux\NoderedL


2. Cài đặt Docker :Tải docker bản mới nhất: 👉 https://www.docker.com/products/docker-desktop/
3. Sau khi chạy và cài đặt ta được giao diện với các container
mariadb (3306), phpmyadmin (8080), nodered/node-red (1880), influxdb (8086), grafana/grafana (3000), nginx (80,443)


<img width="1666" height="744" alt="image" src="https://github.com/user-attachments/assets/effbca8a-953e-426d-948e-5feaf4df6c76" />




4. Lập trình web frontend+backend: Web thương mại điện tử




Tại php MyAdmin:  Lập bảng và nhập các Dl cho bảng






<img width="1787" height="928" alt="image" src="https://github.com/user-attachments/assets/c9e8a6f3-e6f9-48ff-b1e3-ce9658f7bf74" />
   




Cấu hình đăng nhập trên nodered




<img width="1171" height="698" alt="image" src="https://github.com/user-attachments/assets/b93126fe-7368-47e8-8ba2-fa673e03bd30" />




 




Tạo file html D:\k58ktp\nginx\html 





<img width="1187" height="547" alt="image" src="https://github.com/user-attachments/assets/e64a65e9-2e08-475a-804e-4877fb918f41" />




     Test đăng nhập cho tài khoản Admin

  


<img width="1839" height="916" alt="image" src="https://github.com/user-attachments/assets/51d5da97-9a15-44e5-abb3-a66e88e92036" />





5. Nginx làm web-server
 - Cấu hình nginx để chạy được website qua url http://beachip.com/  (thay fullname bằng chuỗi ko dấu viết liền tên của bạn)
 - Cấu hình nginx để http://beachip.com/nodered truy cập vào nodered qua cổng 80, (dù nodered đang chạy ở port 1880)
 - Cấu hình nginx để http://beachip.com/grafana truy cập vào grafana qua cổng 80, (dù grafana đang chạy ở port 3000)





<img width="1883" height="579" alt="image" src="https://github.com/user-attachments/assets/872ffe70-e0d9-43ec-bcc8-dc0bf2e39d2b" />



  

