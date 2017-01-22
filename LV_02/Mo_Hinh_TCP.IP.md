## MÔ HÌNH TCP/IP ##
## Transport Layer ##
**1.Giao Thức**

- Có hai giao thức nổi tiếng là UDP và TCP 

**2.Chức Năng**

- Nghép các phiên truy nhập giữa các máy
- Phân mạch giữ liệu
- Cơ chế điều khiển luồng ( chỉ có cơ chế TCP mới có )
- Cung cấp đường truyền
       - Connetction - orrented : truyền theo kiểu hướng kết nối..Thiết lập xong kết nối mới truyền ( Giao thức TCP )
       - Connectionless : Không cần thao tác kết nối ( Giao thức UDP)
- Độ tin cậy

**3.So sánh hai kiểu truyền**
    
**Reliable ( Truyền tin cậy )**

- Kiểu kết nối: Connection - oriented 
- Giao thức : TCP
- Có đánh số thứ tự
- Sử dụng trong: E-mail, File sharing, Downloading
**Best-Effort ( truyền tổng lực)**
- Kiểu kết nối: Connectionless
- Giao thức: UDP
- Không đánh số thứ tự
- Ungứ dụng : Voice Streaming.....

## Giao thức UDP ##

- Hoạt động ở tầng transport layer của mô hình OSI và TCP/IP
- Cho phép các ứng dụng truy nhập vào lớp mạng
- Có giao thức connectionless
- Cung cấp kiểm tra lổi giới hạn
- Không có cơ chế phụ hồi file lổi
- Cung cấp kiểu phân phối Best- Effort Delivery

**1. Các trường của UDP**

![](https://anninhmang.net/wp-content/uploads/2014/12/udp1.png)

- Source port và Destination port sẽ định danh cho một session truy nhập có thể coi là địa chỉ của lớp thứ 4
- UDP length cho biết chiều dài của gói tin
- Checksum : kiểm tra lổi gói tin

## giao Thức TCP ##

- hoạt động trên tầng transport của mô hình TCP/IP
- Giup ứng dụng truy nhập vào đường tầng mạng
- Kết nối kiểu Connection - oriented
- Có thể truyền và nhận cùng một thời điểm
- Kiểm tra lổi
- Đánh sô thứ tự của các gói tin
- Báo cáo sau khi nhận
- Phục hồi giữ liệu bị mất 

**1. Trường Của TCP**

![](https://duongtuanan.files.wordpress.com/2012/10/102912_1438_11.png?w=604)

**Úng dụng của TCP/IP**

- File transfes : FTP, TFTP, Network file system
- E-Mail
- Remote Login: Telnet, rlogin
- Network managemant: Simple network management protocol
- Name maagament: Domain Name system

**Mapping layer 3 to layer 4**

![](http://www.learncisco.net/assets/images/icnd1/14-mappint-layers.jpg)

**Mapping layer 4 to applications**

![](http://image.slidesharecdn.com/icnd110s01l05understandingthetcpiptransportlayer-130312094244-phpapp01/95/cours-cisco-10-638.jpg?cb=1363081403)

**ket Noi trong TCP**

![](http://3.bp.blogspot.com/-Ayn5Upxa5Kk/VEy2xGxkTmI/AAAAAAAAATI/2Gig1OEtAWw/s1600/threewayhandshark.jpg)


**TCP Acknowledgment**

![](http://www.potaroo.net/ispcol/2004-07/fig4.jpg)

**TCP Sequence and Acknowledgment**

![](http://www.learncisco.net/assets/images/icnd1/18-sequence-and-acknowledgment.jpg)






