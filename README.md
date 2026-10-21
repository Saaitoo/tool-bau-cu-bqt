# Tool bầu cử Ban quản trị (BQT) chung cư

Công cụ nhỏ, miễn phí, giúp Ban tổ chức hội nghị nhà chung cư quản lý việc bầu cử Ban quản trị: danh sách căn hộ, ứng viên, ủy quyền, tra cứu và xuất kết quả ra Excel.

Tool chạy **hoàn toàn offline** trong trình duyệt: chỉ cần mở file `index.html`, không cần cài đặt, không cần mạng, không gửi dữ liệu đi đâu.

## Tính năng

- **Danh sách căn hộ**: số căn hộ, chủ sở hữu, diện tích.
- **Danh sách ứng viên** tham gia bầu cử BQT.
- **Quản lý ủy quyền**: ghi nhận chủ hộ ủy quyền cho người khác đi họp và bỏ phiếu.
- **Tự động đồng bộ** giữa các danh sách khi thay đổi dữ liệu.
- **Tra cứu nhanh** theo số căn hộ, tên chủ hộ hoặc người nhận ủy quyền.
- **Xuất Excel** các danh sách và kết quả.

## Các file trong bộ tool

| File | Mô tả |
|---|---|
| `index.html` | Tool chính, mở bằng trình duyệt (Chrome, Edge...) |
| `Mau_cau_hinh_hoi_nghi.xlsx` | File Excel mẫu (trống) để điền thông tin tòa nhà của bạn |
| `Vi_du_cau_hinh_demo.xlsx` | File Excel ví dụ đã điền sẵn dữ liệu giả, dùng để chạy thử |
| `Huong_dan_su_dung.pdf` | Hướng dẫn sử dụng chi tiết |

## Cách dùng nhanh

1. Tải bộ tool về máy: bấm nút **Code** (màu xanh) → **Download ZIP**, rồi giải nén.
2. Mở `index.html` bằng trình duyệt.
3. Chạy thử với `Vi_du_cau_hinh_demo.xlsx` để làm quen.
4. Điền thông tin tòa nhà của bạn vào `Mau_cau_hinh_hoi_nghi.xlsx` và nạp vào tool.
5. Xem chi tiết trong `Huong_dan_su_dung.pdf`.

## Lưu ý khi dùng tại hội nghị

- Nên dùng **một máy duy nhất** xuyên suốt buổi bầu cử để dữ liệu không bị lệch giữa các máy.
- **Xuất Excel sao lưu** định kỳ trong quá trình làm việc.
- Chạy thử toàn bộ quy trình với dữ liệu demo **trước ngày hội nghị**.
- Dữ liệu cư dân là thông tin cá nhân: chỉ lưu trên máy của Ban tổ chức, không chia sẻ công khai.

## Tác giả

Nguyễn Tất Đạt ([@Saaitoo](https://github.com/Saaitoo)). Tool được tặng miễn phí cho cộng đồng cư dân chung cư. Góp ý, báo lỗi: mở mục **Issues** của repo này.
