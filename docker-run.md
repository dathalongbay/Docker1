Bạn có thể chỉ định vùng chứa bằng cách sử dụng tên hoặc ID của nó (dài hoặc ngắn).

Để tạo một vùng chứa mới từ một hình ảnh và bắt đầu nó, hãy sử dụng docker run:

docker run [options] image [command] [argument] 

Nếu bạn không xác định tên cho vùng chứa mới được tạo của mình, hàm deamon sẽ tạo ra một tên chuỗi ngẫu nhiên. Để xác định tên vùng chứa, hãy sử dụng ––nametùy chọn:

docker run ––name=Ubuntu_Test ubuntu:14.04

Lệnh được đề cập ở trên sẽ tạo vùng chứa Ubuntu_test dựa trên hình ảnh ubuntu: 14.04 và khởi động nó.

Một vùng chứa có thể đang chạy, nhưng bạn không thể tương tác với nó. Để bắt đầu vùng chứa ở chế độ tương tác, hãy sử dụng –i và –t các tùy chọn:

docker run –it ––name=Ubuntu_Test ubuntu:14.04

cách bắt đầu một vùng chứa trong chế độ tương tác

![image](https://user-images.githubusercontent.com/6966136/182555534-2e60dda1-3620-412e-af2c-9a8de082f2ee.png)
