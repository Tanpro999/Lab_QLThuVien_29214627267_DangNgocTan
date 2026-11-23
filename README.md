# Lab_QLThuVien_29214627267_DangNgocTan
# Hệ thống Quản lý Thư viện

Web App quản lý thư viện (sách, độc giả, mượn/trả/gia hạn, tra cứu, thống kê). Được phân tích, thiết kế và xây dựng với sự hỗ trợ của công cụ AI.

## Yêu cầu
- Một trình duyệt web bất kỳ (Chrome, Edge, Firefox, Safari), cả máy tính lẫn điện thoại.
- Không cần cài đặt thư viện, không cần internet, không cần server.

## Cách chạy
1. Tải thư mục dự án về máy và giải nén (nếu là file ZIP).
2. Mở file `src/index.html` bằng trình duyệt (nhấp đúp hoặc chọn Open with).
3. Dữ liệu mẫu (10 sách, 5 độc giả, 3 phiếu mượn) được nạp sẵn. Dữ liệu thay đổi được lưu trong LocalStorage của trình duyệt.
4. Muốn quay lại dữ liệu mẫu: vào tab Thống kê, bấm Đặt lại dữ liệu mẫu.

## Chức năng
Quản lý sách, quản lý độc giả, lập phiếu mượn, trả sách (tự tính phạt), gia hạn, tra cứu sách và lịch sử độc giả, thống kê.

## Quy định nghiệp vụ
- Thời hạn mượn 14 ngày; gia hạn thêm 7 ngày, tối đa 2 lần.
- Mỗi độc giả mượn tối đa 3 cuốn cùng lúc.
- Độc giả có sách quá hạn không được mượn thêm.
- Phạt 2.000đ/ngày trễ hạn.

## Cấu trúc thư mục
- `src/index.html`: mã nguồn ứng dụng (HTML + CSS + JS)
- `BaoCao_Lab.md`: báo cáo phân tích và thiết kế
- `README.md`: hướng dẫn này

Sinh viên: Đặng Ngọc Tân - MSSV: 29214627267
