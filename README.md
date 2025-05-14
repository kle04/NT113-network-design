# Đồ án Thiết kế Mạng - NT113

## Tổng quan
Đồ án môn học **NT113 - Thiết kế mạng** trình bày việc thiết kế và triển khai hệ thống mạng cho trụ sở chính và chi nhánh của công ty O-UIT, với mục tiêu đảm bảo hiệu suất, bảo mật và khả năng mở rộng.

- **Giảng viên hướng dẫn:** Th.S Bùi Thanh Bình
- **Năm học:** 2024 - 2025
- **Thành viên nhóm:**
  - Lê Hữu Khánh - 22520636
  - Nguyễn Võ Đại Dương - 22520308
  - Bùi Quốc Minh - 22520855
  - Võ Huỳnh Kiều Ngân - 22520938

## Mục lục
- [Giới thiệu tổng quan](#giới-thiệu-tổng-quan)
- [Thông tin cơ bản về đề tài](#thông-tin-cơ-bản-về-đề-tài)
- [Thiết kế hệ thống mạng](#thiết-kế-hệ-thống-mạng)
- [Các dịch vụ và chi phí hoạt động](#các-dịch-vụ-và-chi-phí-hoạt-động)
- [Cấu hình mạng đề xuất](#cấu-hình-mạng-đề-xuất)
- [Kết luận và hướng phát triển](#kết-luận-và-hướng-phát-triển)

## Chi tiết đề tài

### Giới thiệu tổng quan
Công ty Outsource O-UIT có trụ sở chính tại Thủ Đức và chi nhánh tại Quận 3, TP.HCM, với nhu cầu triển khai một hệ thống mạng đảm bảo hiệu suất cao, an toàn, bảo mật, và dễ dàng quản lý.

### Thông tin cơ bản về đề tài
Đề tài tập trung vào phân tích yêu cầu, thiết kế mô hình logic và vật lý, lựa chọn thiết bị phù hợp và hoạch định địa chỉ IP cho cả hai địa điểm công ty.

### Thiết kế hệ thống mạng
- **Mô hình mạng logic:** phân tầng rõ ràng cho từng bộ phận công ty.
- **Mô hình mạng vật lý:** sử dụng các thiết bị chuyên dụng từ Cisco (router ISR4331, switch Catalyst C9200 và C1000, Wireless Controller Catalyst 9800-L, và Access Point Aironet 2802i).
- **Phân bổ địa chỉ IP:** Được chia theo từng subnet riêng biệt phục vụ các nhóm làm việc khác nhau, đảm bảo sự an toàn và quản lý dễ dàng.

### Các dịch vụ và chi phí hoạt động
- **Dịch vụ mạng nội bộ và công cộng:** Lux800, Lux500 từ FPT Telecom.
- **Cloud:** Azure Dev/Test.
- **Tổng chi phí:** Thiết bị (131,849.68 USD), dịch vụ duy trì (5,200,000 VNĐ/tháng).

### Cấu hình mạng đề xuất
- **ACL:** quản lý bảo mật truy cập.
- **HSRP:** đảm bảo tính sẵn sàng cao.
- **DHCP:** tự động cấp phát địa chỉ IP.
- **VPN:** kết nối bảo mật giữa các chi nhánh và trụ sở chính.

### Kết luận và hướng phát triển
Hệ thống đảm bảo tính ổn định và khả năng mở rộng với các hướng phát triển tập trung vào nâng cao bảo mật, tích hợp công nghệ hiện đại, và phát triển nhân lực.

## Tài liệu tham khảo
- [Cisco Enterprise Campus Architecture](https://www.cisco.com/c/en/us/td/docs/solutions/Enterprise/Campus/campover.html)
- [Cấu hình ACL](https://www.youtube.com/watch?v=BXOJS3cJ3_A&t=197s)
- [GRE – VPN Tunnel](https://www.youtube.com/watch?v=y_6eTs4rkvs&t=902s)
- [HSRP Configuration](https://securityzone.vn/t/lab-13-cau-hinh-hsrp-cisco.182/)
