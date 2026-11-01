# MU SVEN Admin Gothic — R20

Gói mã nguồn R20 Gothic của công cụ quản trị MU Online.

## Gói nguồn và checkpoint

- `MUSVEN_R20_Gothic_Account_UI_20261102_checkpoint.zip`
- SHA-256: `7D383752D87FD8E9D082AE2295A248412C71EEE4B3A83B051A8DDB3583767BC0`
- Archive: 1,052 files; chứa source và tài nguyên, không chứa `bin`, `obj`, `Config.ini` thật, `.env`, database dump hoặc bí mật cấu hình.
- `MUSVEN_R20_Gothic_Account_UI_20261102_checkpoint.txt` ghi checksum và trạng thái nghiệm thu.

Bản Release DLL riêng được giữ cùng checkpoint cục bộ; không đưa lên repo công khai.

## Kiểm tra

- Release build: 0 warning, 0 error.
- `node --check`: `app.js`, `api.js`, `options.js` đều đạt.
- Contract audit: 27 khai báo API, 27 route backend, 24 lời gọi UI.
- VM: mở R20 qua nút `GOTHIC UI`; trang Dashboard Gothic, trang nhân vật rỗng khi chưa chọn, kho ba vùng, catalog 941 mục chỉ đọc đã hiển thị.
- Mô hình 3D đang là mẫu xem trước, chưa chứng minh đồng bộ trang bị của nhân vật online. Ba thẻ dịch vụ hiện `KHÔNG THỂ XÁC MINH`.

## Chưa nghiệm thu

Ghi SQL/migration, lưu currency, Harmony/Socket, kéo thả kho và lưu item vẫn **CHƯA NGHIỆM THU**. Không chạy kiểm thử ghi database hoặc điều khiển/dừng/khởi động lại dịch vụ MU.