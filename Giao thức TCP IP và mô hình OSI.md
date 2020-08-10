# Giao thức TCP/IP và mô hình OSI


## 1. Giao thức TCP/IP là gì ?
- Giao thức **TCP/IP** là một sự kết hợp của nhiều giao thức riêng biệt, và nhiệm vụ của nó là giúp các máy tính có thể giao tiếp kết nối và truyền tin qua lại với nhau. 
- **các tầng của giao thức TCP/IP**: gồm 4 tầng 
	+ Tầng Ứng Dụng (Applycation): Cung cấp các ứng dụng trao đổi dữ liệu chuẩn hóa. Tầng này gồm các giao thức HTTP, FTP, POP3, SMTP, SNMP mỗi giao thức có một nhiệm vụ và đặc trưng riêng.  
	+ Tầng Mạng (Network): sử lý các gói tin sau đó kết nối tới các mạng độc lập và vận chuyển các tin mã hóa qua ranh giới mạng. Tầng này có nhiêu giao thức điển hình như IP, ICMP.
	+ Tầng Giao Vận (Transport): Tầng này duy trì liên lạc tới đầu cuối trên toàn mạng gồm giao thức TCP và UDP. Nhiều trường hợp giao thức UDP sẽ Thay thế TCP.
	+ Tầng Vật Lý (Network Access): các giao thức hoạt động trên tầng này là Ethernet và ARP(Address Resolution Protocol). Ethernet thường sử dụng cho mạng cục bộ Lan.
![sơ đồ  các lớp của TCP/IP](https://i.imgur.com/rvGD1ZW.png)

- **Ưu điểm của giao thức TCP/IP**: 
	 - Ưu điểm đầu tiên : Giao thức TCP/IP là giao thức không chịu bất kỳ sự kiểm soát của bất kỳ một công ty nào cả. Và nó tương tích với mọi hệ điều hành cũng như hầu hết các loại phần cứng hiện tại. Và cho phép giao tiếp với nhiều hệ thống khác nhau.
	- Ưu điểm thứ 2: TCP/IP có tính mở rộng cao, thông qua mạng có thể xác định đường dẫn hiệu quả nhất.
- **Cách thức hoạt động của giao thức TCP/IP**

	- Hiện nay, TCP/IP có rất nhiều giao thức, tuy nhiên có 3 giao thức được sử dụng phổ biến nhất là HTTP, HTTPS, FTP.
	- Giao thức HTTP : giao thức sẽ sử dụng truyền dữ liệu không an toàn từ 1 web client sẽ gửi 1 yêu cầu đến web server khi nhận được yêu cầu web server sẽ gửi câu trả lời lại cho web client.
	- Giao thức HTTPS: là giao thức sẽ truyền kiểu dữ liệu an toàn, thích hợp với những web có liên quan đến thẻ tín dụng hay là một số bảo mật thông tin của khách hàng.
	- Giao thức FTP: là giao thức này không giớ giạn số lượng máy tính và có thể gửi dữ liệu đến 1 hoặc nhiều máy tính khác một cách trực tiếp.
![mô hình tcp/ip](https://i.imgur.com/zS45izp.png)
## 2. So Sánh Mô Hình OSI và TCP/IP
![mo hinh osi va tcp/ip](https://i.imgur.com/ZbHib4A.png)
### Mô hình OSI 
- Mô hình OSI hay còn được gọi là mô hình tham chiếu kết nối các hệ thống mở. 
- Mô hình này chia giao tiếp mạng thành 7 lớp. Từ lớp 1 đến lớp 4 là những lớp thuộc cấp thấp và chỉ thực hiện các nhiệm vụ di chuyển dữ liệu. Những lớp từ 5 đến 7 thuộc những lớp cấp cao. Mỗi lớp này sẽ được thực hiện một nhiệm vụ đặc thù riêng mà sau đó sẽ chuyển tiếp dữ liệu đến lớp tiếp theo.
### So sánh
- Mô hình OSI và TCP/IP khác nhau ở chỗ mô hình TCP/IP được nhiều người tin dùng hơn vì mô hình TCP/IP cung cấp các nguyên tắc chung và cho phép nới lỏng các nguyên tắc hơn.
- Cách ứng dụng thì mô hình TCP/IP với mỗi tầng thể kết hợp để ứng dụng còn OSI thì chỉ tầng nào làm việc của tầng đó.
- Mô hình TCP/IP thiết kế trước rồi mới phát triển mô hình, còn OSI thì ngược lại.
