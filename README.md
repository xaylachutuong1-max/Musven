# MU SVEN Admin Gothic — R20

Repo này lưu gói source R20 và checkpoint của công cụ quản trị MU Online.

## Tệp phát hành

- `MUSVEN_Admin_Gothic_Complete_20261031_R20_Source.zip`: gói source đã rà soát; chỉ có `Config.ini.template`, không kèm `Config.ini` chứa thông tin kết nối.
- `MUSVEN_Gothic_R20_checkpoint_20261031.zip`: checkpoint khôi phục R20.
- `MUSVEN_Gothic_R20_checkpoint_20261031.txt`: manifest checkpoint và mã SHA-256.
- `MUSVEN_Gothic_R20_ACCEPTANCE_20261101.txt`: biên bản nghiệm thu một phần trong VM.

## Trạng thái nghiệm thu

Gothic UI khởi chạy trong VM; kết nối SQL Muonline và truy vấn danh sách online đã được kiểm tra ở chế độ chỉ đọc. Dữ liệu tài khoản/kho thật và các lệnh điều khiển GameServer chưa được nghiệm thu. Xem biên bản để biết giới hạn và bước tiếp theo.

## Lưu ý bảo mật

Không commit `Config.ini`, thông tin đăng nhập, connection string thật, hoặc dữ liệu database. Hãy tạo `Config.ini` cục bộ từ template theo môi trường của bạn.
