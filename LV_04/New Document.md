## ROUTER'S COMPONENTS ##
# CÁC THÀNH PHẦN CỦA ROUTER #
**1.THÀNH PHẦN BÊN TRONG**

- CPU 
- ROM
- FLASH
- NVRAM
- RAM

**2. THÀNH PHẦN BÊN NGOÀI**

- WAN
- LAN
- Console/AUX ( Auxiliary : Hỗ trợ )

![](https://i.ytimg.com/vi/bNMzyF0l8vs/maxresdefault.jpg) CPU

#CPU #
 - Thực hiện các chỉ thị của hệ điều hành
          Khởi tạo hệ thống
          Định tuyến
          Điều khiển các card mạng
- giống với vai trò của CPU trong PC

# ROM #

- Chứa chương trình kiểm tra phần cứng, chương trình Bootstrap và hệ điều hành phụ
- Kiểm tra phần cứng trong khi Router khởi động lên và loading Cisco và ram
- Chỉ được đọc và không xóa được và chỉ có thể năng cấp bằng Rom chíp và sockets thôi

# RAM #

- Ram được chia làm bộ nhớ chính và bộ nhớ phụ
- Bộ nhớ chính chứa lưu file, chứa định tuyến , chứa ARP ...
- Bộ nhớ phụ chạy các chương trình
- Có thể nâng cấp được

#VNRAM#

 - Chứa file cấu hình của Router . không bị mất khi tắt máy
 
# FLASH#

- Chứa mọi tài nguyên của router và hệ điều hành chính thức của Router trên router sài hệ điều hành IOS 
- Chứa với dạng nén và bung ra ở bộ nhớ Ram
- Có thể xóa được và nghi đè được

# BUSES #
- Các đầu nối với các thành phần bộ nhớ


# INTERFACE #

Các cổng kết nối với các thiết bị ngoài

![](http://421-415-ne7.weebly.com/uploads/1/3/6/1/13614157/4161025.jpg?560)

# LỆNH CƠ BẢN TRONG ROUTER #

** Router > _** Không làm được gì cả 

**enable** -- **Router#** thực được câu lệnh hiện thị tất cả và đến các bus 

** Confijgure _ Terminal** --> ** Router( config)** có thể cấu hình cơ bản trên Router 

vd : Router(config)#interface _f010 ---> Router ( config -if ) # _ chỉ ảnh hưởng tới cổng F010.