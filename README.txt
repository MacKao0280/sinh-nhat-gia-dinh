SINH NHẬT GIA ĐÌNH — HƯỚNG DẪN BẮT ĐẦU

CÁCH DÙNG NGAY (không cần cài đặt):
1. Giải nén file ZIP.
2. Mở thư mục sinh_nhat_gia_dinh.
3. Nhấp đúp index.html để mở bằng Chrome hoặc Edge.
4. Thêm một người thân thử nghiệm và kiểm tra danh sách.

LƯU Ý QUAN TRỌNG:
- Dữ liệu lưu trong localStorage của trình duyệt trên thiết bị hiện tại.
- Không tự đồng bộ giữa máy tính và điện thoại.
- Nếu xóa dữ liệu trình duyệt, dùng cửa sổ ẩn danh, hoặc đổi trình duyệt/hồ sơ, dữ liệu có thể không còn truy cập được.
- Dùng nút “Sao lưu dữ liệu” để tải JSON; giữ tệp đó an toàn.
- Chỉ khôi phục tệp JSON tin cậy. Khôi phục sẽ thay thế danh sách hiện tại.
- Phiên bản này chưa có thông báo đẩy tự động khi đóng ứng dụng; mục “sắp tới” hiển thị khi mở app.
- Để cài như ứng dụng PWA và dùng offline ổn định, cần đưa thư mục lên một máy chủ HTTPS riêng tư/được bảo vệ hoặc chạy local server. Không tải thông tin thật lên dịch vụ công cộng nếu chưa xem xét quyền riêng tư.

CÁCH KIỂM THỬ:
1. Thêm thành viên với ngày sinh hôm nay (tháng/ngày hiện tại).
2. Kiểm tra bộ đếm “Sinh nhật hôm nay” và nhãn “Hôm nay”.
3. Sửa tên rồi lưu; xác nhận thông tin đổi.
4. Tìm theo tên ở ô tìm kiếm.
5. Nhấn “Sao lưu dữ liệu”, kiểm tra tệp JSON đã tải.
6. Xóa một bản ghi thử nghiệm, sau đó khôi phục tệp JSON và xác nhận bản ghi trở lại.
7. Thử tải trang lại; dữ liệu vẫn còn trên cùng trình duyệt.

CẤU TRÚC:
- index.html: ứng dụng chính, giao diện và chức năng.
- manifest.webmanifest: thông tin cài đặt PWA.
- sw.js: bộ nhớ đệm cơ bản cho bản PWA.
