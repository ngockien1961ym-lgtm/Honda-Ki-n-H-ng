# Quy ước tên file của chương trình

Theo [quy ước chung](../../../docs/quy-uoc-dat-ten.md):
`YYYYMMDD-kh-khuyen-mai-chu-de-kenh-kich-thuoc-vNN-trang-thai.ext`.

- Dùng chữ thường không dấu, dấu gạch ngang; giữ ngày tạo công việc 20261027 khi tăng phiên bản.
- Văn bản dùng kích thước `na`; tăng phiên bản khi chỉnh sửa. Trạng thái: `nhap`, `cho-duyet`, `duyet`, `het-hieu-luc`.
- Chỉ chuyển sang `duyet` sau khi ghi người duyệt và ngày duyệt trong hồ sơ.
- Ví dụ bản ảnh tương lai, không xác nhận đã có file thiết kế:
  - Facebook 1:1: `20261027-kh-khuyen-mai-cung-len-ga-facebook-1080x1080-v01-nhap.png`
  - Facebook 4:5: `20261027-kh-khuyen-mai-cung-len-ga-facebook-1080x1350-v01-nhap.png`
  - Điện thoại: `20261027-kh-khuyen-mai-cung-len-ga-dien-thoai-1080x1920-v01-nhap.png`
- Tài liệu đầu vào được phép công khai lưu ở `sources/`, bản nháp trong `working/`, bản xuất đã duyệt trong `exports/`. Tạo thư mục khi có nội dung.
