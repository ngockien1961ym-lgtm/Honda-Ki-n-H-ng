# Mẫu quảng cáo xe

- [LEAD – gói nội dung](lead/20261026-goi-noi-dung/thong-tin.md)
- [Air Blade – gói nội dung](air-blade/20261026-goi-noi-dung/thong-tin.md)

- [Wave Alpha](wave-alpha/20261026-mau-quang-cao/thong-tin.md)
- [SH 125/160](sh-125-160/20261026-mau-quang-cao/thong-tin.md)

Đây là các công việc mẫu ở trạng thái `nhap`, chưa có ảnh xe hoặc thiết kế, chưa được duyệt để đăng. Khi tạo công việc thật, sao chép bộ mẫu sang thư mục `YYYYMMDD-chu-de/` trong dòng xe tương ứng; thay ngày trong tên file và cập nhật hồ sơ.

Mỗi công việc có `sources/` (nguồn), `working/` (nội dung và thiết kế nháp), `exports/` (chỉ bản đã duyệt) và `thong-tin.md`. File `.gitkeep` giữ chỗ cho thư mục rỗng.

## Quy ước tên file

Theo [quy ước chung](../../docs/quy-uoc-dat-ten.md):
`YYYYMMDD-kh-quang-cao-xe-dong-xe-kenh-kich-thuoc-vNN-trang-thai.ext`.

| Mục đích | Tỷ lệ | Kích thước mẫu (rộng × cao) | Kênh trong tên file |
| --- | --- | --- | --- |
| Facebook vuông | 1:1 | 1080×1080 px | facebook |
| Facebook dọc | 4:5 | 1080×1350 px | facebook |
| Hình nền điện thoại | 9:16 | 1080×1920 px | dien-thoai |

9:16 là mặc định mẫu; điều chỉnh theo màn hình đích khi có yêu cầu. Giữ chữ quan trọng tránh vùng đồng hồ và mép cắt.

Ví dụ cho từng dòng xe (chỉ minh họa tên, chưa có ảnh):

- `20261026-kh-quang-cao-xe-wave-alpha-facebook-1080x1080-v01-nhap.png`
- `20261026-kh-quang-cao-xe-wave-alpha-facebook-1080x1350-v01-nhap.png`
- `20261026-kh-quang-cao-xe-wave-alpha-dien-thoai-1080x1920-v01-nhap.png`

- `20261026-kh-quang-cao-xe-sh-125-160-facebook-1080x1080-v01-nhap.png`
- `20261026-kh-quang-cao-xe-sh-125-160-facebook-1080x1350-v01-nhap.png`
- `20261026-kh-quang-cao-xe-sh-125-160-dien-thoai-1080x1920-v01-nhap.png`

Nội dung Markdown dùng kích thước `na`. Nguồn thiết kế và bản xuất cùng nội dung dùng chung phần tên trước đuôi. Tăng `vNN` khi sửa; chỉ chuyển `nhap → cho-duyet → duyet` khi có căn cứ và ghi người/ngày duyệt trong hồ sơ. Bản nháp nằm ở `working/`; chỉ đưa bản đã duyệt vào `exports/`.

Không tự bổ sung giá, màu xe, ưu đãi, thông số hoặc tình trạng có hàng. Ghi nguồn và ngày kiểm tra trước khi thêm thông tin đó vào nội dung. Không dùng mẫu gộp SH để suy ra hai dòng có cùng trang bị; khi có dữ liệu, tách rõ SH 125 và SH 160.
