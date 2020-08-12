# So sánh giữa giao thức TCP và giao thức UDP

## 1. Những điều cơ bản về TCP và UDP
![so sanh tcp va udp](https://i.imgur.com/fxC1PQ1.png)
![truyendulieu](https://i.imgur.com/sHRGGTa.png) 
- Giao thức TCP và UDP đều truyền dữ liệu theo dạng gói. Nhưng TCP thì truyền dữ liệu theo cách an toàn hơn có kết nối, đảm bảo được việc gói tin sẽ được truyền đầy đủ và không có bị mất gói tin
- Còn UDP thì truyền dữ liệu không có kết nối, không đảm bảo được người dùng sẽ nhận được gói tin đầy đủ, nhưng bù lại tốc độ của UDP lại nhanh hơn vì tính chất gửi không phải kiểm tra gói tin có bị mất hay có bị lỗi hay không như TCP. TCP an toàn đảm bảo dữ liệu, còn UDP thì tốc độ nhanh.
- Ngoài ra TCP xử lý kiểm soát luồng, còn UDP thì không có tùy chọn để xử lý luồng.
## 2. Điểm giống nhau
- Cả 2 đều sử dụng để gửi gói tin ( bit dữ liệu) qua internet. Đều được xây dựng theo giao thức IP. Vì vậy bạn gửi gói tin theo giao thức TCP hay UDP đều sẽ gửi đến 1 địa chỉ IP. Chúng sẽ chuyển gói tin qua router và đến đích vì vậy những gói tin này đều được xử lý.
- Có rất nhiều giao thức hoạt động trên IP, nhưng trong đó có TCP và UDP là 2 giao thức được sử dụng rộng rãi nhất. 
## 3. Cách thức hoạt động của TCP
- TCP là giao thức phổ biến nhất được nhiều người tin dùng. Khi bạn nhấn vào 1 đường link trang web, thì máy bạn sẽ gửi 1 gói tin TCP yêu cầu gửi giao diện web đến máy bạn  đến web server và web server sẽ nhận được yêu cầu đó và gửi lại bạn gói tin TCP để bạn có thể thấy được giao diện web.
- TCP có độ an toàn cao, và đảm bảo sẽ không bị mất gói tin vì khi truyền gói tin TCP sẽ được theo dõi và gửi request liên tục, nếu đối phương không phản hồi nó sẽ tự động gửi lại request để các gói tin không bị mất. Nhưng nếu mạng giữ client và server bị ngắt thì sẽ hiện lên 1 bảng thông báo là lỗi không thể giao tiếp với máy chủ.
![cach thuc hoat dong](https://i.imgur.com/EpUSVSa.png)
## 4. Cách thức hoạt động của UDP
- Giao thức UDP hoạt động tương đồng như TCP nhưng khác ở chỗ, giao thức UDP không kiểm tra lỗi khi truyền tin, và khi truyền tin UDP sẽ không quan tâm là bạn có nhận được gói tin hay không. Nên giao thức UDP thường được sử dụng trong các trương trình phát sóng trực tiếp ,... Nếu như đường truyền bị lỗi khi bạn đang xem video trực tiếp, nó sẽ vẫn truyền gói tin đi, khi bạn kết nối lại thành công thì nó sẽ phát video ở thời điểm hiện tại mặc cho video ở khoảng thời gian bị lỗi không đến được người dùng. 
## Về giao thức TCP
- Tốt nhất cho độ tin cậy .
![dotincaytcp](https://i.imgur.com/V36k9Jh.png)
## Về giao thức UDP 
- Tốt nhất về tốc độ 
![vegiaothucudptocdo](https://i.imgur.com/D6Key76.png)
## Tùy chọn vào nhu cầu sử dụng
![nhucau](https://i.imgur.com/UtAnWGD.png)
## Tóm tắt lại , so sánh giữa 2 giao thức 
![](https://i.imgur.com/yLzahaK.png)


nguồn : [https://quantrimang.com/su-khac-nhau-giua-giao-thuc-tcp-va-udp-154559#mcetoc_1ef3hek141](https://quantrimang.com/su-khac-nhau-giua-giao-thuc-tcp-va-udp-154559#mcetoc_1ef3hek141)
