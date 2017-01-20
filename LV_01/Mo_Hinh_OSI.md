## MÔ HÌNH OSI ##

##I.CÁC MÔ HÌNH TRUYỀN TẢI ##

**1.CÁC MÔ HÌNH TRUYỀN TẢI**

1.Older model

- Proprietary
- Applicatons anh com binantions software controlled by one vendor

2.Standards-based model

- Multivendor software 
- Layered approach ( Phân Lớp)

**2.PHƯƠNG PHÁP PHÂN LỚP**

**Lợi ích của việc phân lớp**

- giảm thiểu được độ phứt tạp của các công việc
- Chuẩn hóa giao diện
- Đảm bảo tính tương thích về mặt công nghệ
- Thúc đẩy kỉ thuật modun hóa
- Đơn giản cho việc dạy và học đối với sinh viên
# Mô Hình OSI _ OPEN SYSTEM INTERCONMETION 

                                             7.APPLICATION
                                            6.PRESENTATION
                                               5.SESSION
                                              4.TRANSPORT
                                               3.NETWORK
                                              2.DATA LINK
                                               1.PHYSICAL

# Physical #

- Cách kết nối ...Nối dây gì ( cáp gì ) 
- Cự ly của đoạn cáp mạng
- Đường truyền của Bit
- Các kỉ thuật truyền vào không gian
- Tốc độ đường truyền 

**Quy định về: cơ, điện, quan**

# DATA LINK (LỚP LIÊN KẾT DỮ LIỆU) #

- Điều khiển việc truy nhận vào đường truyền vật lý 
- Đóng khung giữ liệu
- khóa giữ liệu
- Cung cấp cơ chế dò lổi

# Network (LỚP MẠNG) #

- Phân bố dữ liệu
- Định tuyến cho gói dữ liệu
- Xác định đường đi tối ưu
- Quy định địa chỉ logic ( Địa chỉ logic nổi tiếng >> địa chỉ IP)

#Transport ( Quản lý kết nội đầu với đầu cuối)#

- Xử lý vấn đề truyền tải giữa các Host
- Đảm bảo thiết lập duy trùy kết nối các đường mạch ảo
- Sử lổi tin cậy.....

#Session ( Tổ chức các phiên kết nối)#

- Tổ chức các phiên kết nối cho các ứng dụng

#Presentation #

- Định dạng lại dữ liệu
- Cơ chế hóa lại dữ liệu
- Thương lượng cú pháp truyền
- Cung cấp cơ chế mã hóa

#Application#

- Cung cấp các ứng dụng cho ngươi dùng

## CÁCH HOẠT ĐỘNG CỦA MÔ HÌNH OSI##
 
Tiến trình được đi từ trên xuống dưới...được chuyễn thành các Bit nhị phân zui được truyền qua đường truyền luận lý qua host bên kia vào đi từ dưới lên trên theo mô hình OSI

             ![](http://data.sinhvienit.net/lab1/Giao-Trinh-Toan-Tap-Mang-May-Tinh_files/image014.gif)
##PPHƯƠNG THỨC TRUYỀN NGANG HÀNG##
 
                     ![](https://www.digistar.vn/wp-content/uploads/2016/11/osi-3.jpg)