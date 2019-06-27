# CentOS

## Mục Lục

### [1. Overview](#overview)

- ### [Các phiên bản phát hành của CentOS](#cacphienbanphathanhcuacentos)

### [2. Install CentOS](#installcentos)


------------



<a name="overview"></a>

### 1. Overview

CentOS là viết tắt của **C**ommunity **ENT**erprise **O**perating **S**ystem. Đây là  một bản phân phối của hệ điều hành mã nguồn mở dựa trên Linux kernel. Nó có nguồn gốc từ bản phân phối Red Hat Enterprise Linux (RHEL). Mỗi phiên bản CentOS được duy trì tối đa 10 năm (bằng các cập nhật bảo mật - thời lượng của khoảng thời gian hỗ trợ của Red Hat đã thay đổi theo thời gian liên quan đến nguồn được phát hành). Một phiên bản CentOS mới được phát hành khoảng 2 năm một lần và mỗi phiên bản CentOS được cập nhật định kỳ (khoảng 6 tháng một lần) để hỗ trợ phần cứng mới hơn.

<a name="cacphienbanphathanhcuacentos"></a>

### Các phiên bản phát hành của CentOS

Số phiên bản của CentOS có hai phần, một phiên bản chính và một phiên bản nhỏ, tương ứng với phiên bản chính và cập nhật của Red Hat Enterprise Linux được sử dụng để xây dựng là phiên bản của CentOS. Ví dụ, CentOS 4.4 được xây dựng từ các gói nguồn từ Red Hat Enterprise Linux 4 cập nhật 4. Từ giữa 2006, bắt đầu với phiên bản 4.4 (chính thức được gọi là Red Hat Enterprise Linux 4.0 cập nhật 4), Red Hat đã thông qua một quy ước phiên bản giống hệt của CentOS, ví dụ như, Red Hat Enterprise Linux 4.5.

Bắt đầu với phiên bản 7.0 trở đi, các số phiên bản CentOS sẽ bao gồm thêm một phần số cho biết tháng năm của mã nguồn hệ điều hành CentOS phát hành. Ví dụ phiên bản 7.0-1406, cho biết bản cập nhật đầu tiên của CentOS 7, trong khi "1406" chỉ ra rằng bản này phát hành tháng 6 năm 2014.

Phiên bản mới nhất hiện nay của CentOS là 7.6-1810.

<a name="installcentos"></a>

### 2. Install CentOS

Ở bài viết này, mình sẽ hướng dẫn các bạn cài đặt CentOS 7 phiên bản minimal iso trên vmware.

- Khởi động vmware và bấm tạo máy ảo

![Ảnh](https://i.imgur.com/aAlh9FD.png)

- Bấm `Next` để tiếp tục

![Ảnh](https://i.imgur.com/gNgglLt.png)

- Chọn `Installer disk image file (iso)`

![Ảnh](https://i.imgur.com/ca98wqQ.png)

- Đặt tên và chọn nơi lưu trữ máy ảo

![Ảnh](https://i.imgur.com/jhfzuWa.png)

- Chọn mục `Customize Hardware` để cấu hình phần cứng, nếu không bấm `Finish` để tiếp tục

![Ảnh](https://i.imgur.com/K4z78EH.png)

- Chọn `Install CentOS 7`

![Ảnh](https://i.imgur.com/Dlm32z1.png)

- Chọn ngôn ngữ cài đặt, mặc định là English

![Ảnh](https://i.imgur.com/9uQAV6z.png)

- Tiếp tục chọn múi giờ

![Ảnh](https://i.imgur.com/MWov2NE.png)

- Mục `INSTALLATION DESTINATION` chọn ổ cứng để cài đặt hệ điều hành

![Ảnh](https://i.imgur.com/z3ybaAy.png)

- Mục `NETWORK & HOSTNAME` chọn card mạng nếu muốn có kết nối mạng

![Ảnh](https://i.imgur.com/bC0dOWJ.png)

- Bấm `Begin Installation` để bắt đầu việc cài đặt

![Ảnh](https://i.imgur.com/IzbaoI0.png)

- Chọn mục `CREATE USER` để tạo người dùng và mật khẩu

![Ảnh](https://i.imgur.com/ZSWMUpX.png)

- Chọn mục `ROOT PASSWORD` để đặt mật khẩu cho tài khoản root

![Ảnh](https://i.imgur.com/oFeRlKp.png)

- Bấm `Reboot` để khởi động lại

![Ảnh](https://i.imgur.com/qy3wXQR.png)

- Đăng nhập theo username và password đã tạo

![Ảnh](https://i.imgur.com/kTB2KQS.png)
