# docker exec
![image](https://user-images.githubusercontent.com/6966136/182551494-06ecf652-19d5-4aad-9f6e-926afecfffac.png)
### khi gặp lỗi 
```
OCI runtime exec failed: exec failed: container_linux.go:380: starting container process caused: exec: "bash": executable file not found in $PATH: unknown
```
### docker exec -it 0f9e2a18cc4a /bin/sh
### docker exec -it container_name /bin/sh
## Truy cập vào chế độ bash của container 
![image](https://user-images.githubusercontent.com/6966136/182552139-14f8a23f-9ae8-437b-8560-f2d62b29a7ec.png)
## xem cấu trúc thư mục : ls -l




