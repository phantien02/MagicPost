
# Magic Post

## _Website hệ thống quản lý vận chuyển đơn hàng._ 
MagicPost là công ty hoạt động trong lĩnh vực chuyển phát. Công ty này có các điểm giao dịch phủ khắp cả nước. Mỗi điểm giao dịch phụ trách một vùng. Ngoài các điểm giao dịch, công ty cũng có nhiều điểm tập kết hàng hóa. Mỗi điểm giao dịch sẽ làm việc với một điểm tập kết. Ngược lại, một điểm tập kết sẽ làm việc với nhiều điểm giao dịch.

Người gửi, có hàng cần gửi, đem hàng đến một điểm giao dịch (thường là gần nhất) để gửi. Hàng, sau đó, được đưa đến điểm tập kết ứng với điểm giao dịch của người gửi, rồi được chuyển đến điểm tập kết ứng với điểm giao dịch của người nhận. Tại điểm giao dịch của người nhận, nhân viên giao hàng sẽ chuyển hàng đến tận tay người nhận.

## Chức năng cho từng đối tượng sử dụng

1. Chức năng cho giao dịch viên tại điểm giao dịch:
- Ghi nhận hàng cần gửi của khách (người gửi), in giấy biên nhận chuyển phát và phát cho khách hàng.
- Tạo đơn chuyển hàng gửi đến điểm tập kết mỗi/trước khi đem hàng gửi đến điểm tập kết.
- Xác nhận (đơn) hàng về từ điểm tập kết.
- Tạo đơn hàng cần chuyển đến tay người nhận.
- Xác nhận hàng đã chuyển đến tay người nhận theo .
- Xác nhận hàng không chuyển được đến người nhận và trả lại điểm giao dịch.
- Thống kê các hàng đã chuyển thành công, các hàng chuyển không thành công và trả lại điểm giao dịch.

2. Chức năng cho nhân viên tại điểm tập kết
- Xác nhận (đơn) hàng đi từ điểm giao dịch chuyển đến.
- Tạo đơn chuyển hàng đến điểm tập kết đích (ứng với điểm giao dịch đích, tức điểm giao dịch phụ trách vùng ứng với địa chỉ của người nhận).
- Xác nhận (đơn) hàng nhận về từ điểm tập kết khác.
- Tạo đơn chuyển hàng đến điểm giao dịch đích.

3. Chức năng cho trưởng điểm tại điểm giao dịch
- Cấp tài khoản cho giao dịch viên tại điểm giao dịch.
- Thống kê hàng gửi, hàng nhận tại điểm giao dịch.

4. Chức năng cho trưởng điểm tại điểm tập kết
- Quản lý tài khoản nhân viên tại điểm tập kết.
- Thống kê hàng đi, đến.

5. Chức năng cho khách hàng
- Tra cứu trạng thái và tiến trình chuyển phát của kiện hàng mình gửi.
