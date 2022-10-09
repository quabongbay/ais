### Context
Thường lừa đảo càng muốn ăn tiền bạn càng nhanh càng tốt, nên thủ tục đăng ký vào hệ thống khá đơn giản, không có hoặc rất ít bước bước xác minh. Nên lựa chọn hàng đầu của tôi là DDoS

### Note
Không bao giờ hack người khác trừ khi bạn biết chắc đó là lừa đảo
Và khi bạn đã quyết định hack thì ưu tiên bảo vệ mình là điều quan trọng nhất: ít nhất bạn phải qua 1 lớp VPN.

### Quá Trình:
Client dùng mã hoá payload nhưng key thì để trong JS nên tôi copy ra dễ dàng rồi tạo vài trăm ngàn account, máy chủ đơ.
Nó chặn IP VPN cuả tôi, tôi chuyển qua dùng tor để luân chuyển IP. 
Nó đơ rồi nâng cấp, nó chỉ cho tạo 3 accounts trên 1 IP. 
Tôi dùng tiếp đến api nạp tiền, giờ nó chặn hầu hết IP nước ngoài cho tất cả endpoint.

Nhưng 1 thời gian quay lại thì nó không chặn nữa nên tôi suy luận:
Nhóm bảo trì hệ thống này không dùng version control, có thể quá trình deploy đã revert lại version cũ, điều này cũng dễ hiểu: hầu hết các nhóm lừa đảo làm việc khá cục bộ, phòng này không biết phòng kia làm gì, và nhân viên ăn lương tối thiểu luân chuyển khá thường xuyên, nên việc hệ thống vận hành không trơn tru là điều dễ hiểu.


