CARRENT PRO – ỨNG DỤNG QUẢN LÝ XE CHO THUÊ TỰ LÁI
==================================================

CHỨC NĂNG
- Thêm/sửa nhiều xe, xem lịch theo từng xe và toàn đội xe.
- Tạo/sửa/xóa cuốc: khách, ngày/giờ nhận và trả, tuyến đi/đến từ 63 tỉnh/thành cũ.
- Cảnh báo lịch trùng cho đúng chiếc xe được chọn; khóa lịch bảo dưỡng.
- Phụ phí nhập tay (vượt km, xăng, cầu đường, sạc điện, phụ phí tùy chỉnh).
- Ghi tiền đã nhận, theo dõi khoản phải thu, chi phí vận hành và báo cáo đội xe.
- Xuất/nhập sao lưu JSON; hoạt động ngoại tuyến sau khi cài từ HTTPS.
- Chủ đạo giao diện đỏ hiện đại, tối ưu iPhone.

CÁCH DÙNG
1. Giải nén thư mục car-rent-pro.
2. Đưa NGUYÊN thư mục lên một hosting HTTPS miễn phí như GitHub Pages
   hoặc Cloudflare Pages. Website tĩnh, không cần máy chủ hay database.
3. Mở đường dẫn HTTPS bằng Safari trên iPhone.
4. Chọn Chia sẻ → Thêm vào Màn hình chính → Thêm.
5. Mở app và vào mục Xe → Thêm xe, rồi đặt cuốc tại mục Cuốc xe.

THỬ TRÊN MÁY TÍNH
- Mở file index.html trong trình duyệt để xem thử (dữ liệu cục bộ).
- Để cài PWA và chạy offline trên iPhone, cần đường dẫn HTTPS hợp lệ.

LƯU Ý QUAN TRỌNG
- Đây là phiên bản đầu chạy thực tế, không phải bản demo hình ảnh.
- Dữ liệu chỉ được lưu trong bộ nhớ của TRÌNH DUYỆT/TRANG WEB trên thiết bị,
  KHÔNG tự đồng bộ giữa điện thoại và máy tính. Định kỳ vào Cài đặt → Xuất bản sao.
- Xóa dữ liệu website, dùng chế độ riêng tư, đổi hostname hoặc chuyển thiết bị
  có thể khiến dữ liệu cũ không còn truy cập được. Phải phục hồi bằng bản sao JSON.
- Chưa có đăng nhập, phân quyền, đồng bộ online, gửi thông báo đẩy, GPS, thanh toán
  trực tuyến, quản lý giấy tờ khách hàng hoặc tiền cọc hoàn lại riêng.
- Giá cuốc là số tiền nhập bằng tay, không tự áp dụng quy tắc giờ thuê.
- Danh mục 63 tỉnh/thành là danh mục hành chính cũ (trước sắp xếp năm 2025).
- Không đưa dữ liệu riêng tư nhạy cảm lên bản app chưa có hệ thống tài khoản bảo mật.
