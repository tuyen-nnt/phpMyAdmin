# my-docker

MụC TIÊU:

    Tạo image có nhiệm vụ:

    Chạy được MYSQL chứa database của Tuyền thông qua phpMyAdmin trên máy khác.

    Expose ra port 9090.

    Máy khác chỉ cần pull image về và truy cập IP qua port 9090 để hiện ra trang phpMyAdmin và đăng nhập.

    Máy khác khi đem về chạy câu: docker run -it -p 127.0.0.1:8080:80 image_name port 8080 sẽ có thể truy cập với địa chỉ 127.0.0.1 (localhost)

    Sau đó nhờ Bảo chuyển địa chỉ máy để truy cập trang trên sang tuyen.tech

