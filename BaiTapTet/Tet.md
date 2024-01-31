## Docker,  Docker Compose là gì?

**Docker** là một nền tảng cung cấp cách để building, deploying và running ứng dụng dễ dàng hơn bằng cách sử dụng các containers (trên nền tảng ảo hóa). Containers cho phép các developer tách biệt ứng dụng của họ khỏi môi trường của nó.

**Docker Compose** là một công cụ giúp developer xác định và chạy các ứng dụng multi-container. Với Docker Compose, ta có thể xác định tất cả các services tạo nên ứng dụng của mình trong một tệp YAML duy nhất. Khi đã tạo tệp Docker Compose, ta có thể sử dụng một lệnh duy nhất để khởi động tất cả các dịch vụ trong ứng dụng của mình.

## Linux, Unix, BSD hay *nix 
**Unix**  là một họ hệ điều hành máy tính đa nhiệm, đa người dùng được viết vào những năm 1960 và 1970 do một số nhân viên của Bell Labs thuộc AT&T. Nó được thiết kế với tiêu chí portable, nghĩa là nó có thể được sử dụng trên các loại phần cứng khác nhau Có thể coi Unix là nền tảng của các hệ điều hành khác.
**Linux** là một hệ điều hành mã nguồn mở miễn phí được xây dựng dựa trên Unix vào đầu những năm 1990 bởi Linus Torvalds. Khác với Unix, Linux có giao diện  đồ hoạ giúp cho việc sử dụng thuận tiện hơn. Linux có rất nhiều distributions khác nhau, một số phổ biến có thể kể đến: Ubuntu, Red Hat, Debian, CentOS, Kali Linux...
**BSD** hay Berkeley Software Distribution, là một phiên bản của Unix được phát triển tại Đại học California, Berkeley. Nó lần đầu tiên được phát hành vào những năm 1970 và được biết đến với khả năng kết nối mạng và tối ưu hóa hiệu suất. Mặc dù nó chưa bao giờ đạt được mức độ phổ biến như Linux, nhưng nó vẫn có vai trò quan trọng và có ảnh hưởng trong thế giới phần mềm mã nguồn mở.

## Alpine và Ubuntu 
**Alpine** và **Ubuntu** đều là các distribution của Linux. Đây là 2 base image phổ biến sử dụng trong Docker containers. 
**Alpine** là một distribution nhẹ, chỉ chiếm khoảng 5 MB dung lượng ổ đĩa. Nó được thiết kế đơn giản, nhanh chóng và an toàn với các tính năng và dependencies tối thiểu.
**Ubuntu** cung cấp một bộ sưu tập lớn và đa dạng các gói, công cụ và tài liệu. Ubuntu được hỗ trợ tốt và cập nhật thường xuyên. Ubuntu cũng có giao diện quen thuộc và thân thiện với người dùng

## VNC (Virtual Network Computing)
Giao thức VNC là một giao thức đơn giản để truy cập từ xa vào giao diện người dùng đồ họa. Nó hoạt động ở cấp độ bộ đệm khung (framebuffer level) nên nó có khả năng áp dụng cho tất cả các hệ điều hành, ứng dụng. Giao thức sẽ hoạt động trên mọi phương tiện truyền tin đáng tin cậy như TCP/IP. VNC được thiết kế để cho phép người dùng điều khiển từ xa một máy tính khác từ hầu hết mọi vị trí.