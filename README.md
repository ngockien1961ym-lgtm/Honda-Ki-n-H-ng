# Head Honda Kiên Hương – Vòng xuyến Yên Mỹ

Kho quản lý tài sản marketing: nhận diện thương hiệu, poster dịch vụ, quảng cáo xe, khuyến mãi, phông sự kiện và hình ảnh truyền thông của Head Honda Kiên Hương.

Đây là bộ khung khởi đầu; các thư mục chưa có thiết kế thực tế. Ví dụ trong tài liệu chỉ minh họa cách tổ chức, không xác nhận giá bán, ưu đãi hay phiên bản xe đang có hàng.

## Bắt đầu sử dụng

1. Chọn nhóm tài sản trong bảng bên dưới.
2. Tạo thư mục công việc theo mẫu `YYYYMMDD-chu-de`.
3. Sao chép [mẫu thông tin tài sản](templates/thong-tin-tai-san.md) thành `thong-tin.md` trong thư mục công việc.
4. Đặt file theo [quy ước đặt tên](docs/quy-uoc-dat-ten.md), ghi nguồn và trạng thái duyệt.
5. Lưu bản xuất đã duyệt trong `exports/`; cập nhật [danh mục tài sản](docs/danh-muc-tai-san.md).

## Cấu trúc và nhóm tài sản

| Thư mục | Nội dung |
| --- | --- |
| `assets/01-thuong-hieu/logo/` | Logo KH, chữ nổi 3D, bản nền đỏ/chữ trắng, bản trong suốt |
| `assets/01-thuong-hieu/nhan-dien/` | Màu sắc, phông chữ, cách dùng tên HEAD và bộ nhận diện đã duyệt |
| `assets/02-dich-vu/` | Poster bảo dưỡng, thay dầu, sửa chữa động cơ, dọn xe theo yêu cầu |
| `assets/03-quang-cao-xe/` | Quảng cáo theo dòng xe: SH, SH Mode, Vision, LEAD, Air Blade, Future, Wave Alpha, RSX, Vario, Winner |
| `assets/04-khuyen-mai/` | Thu cũ đổi mới, trả góp, ưu đãi mua xe và dịch vụ |
| `assets/05-su-kien/ban-giao-xe/` | Phông và ảnh lễ bàn giao xe |
| `assets/05-su-kien/le-tet/` | Banner lễ, Tết, thông báo lịch hoạt động |
| `assets/05-su-kien/vong-quay-may-man/` | Vòng quay, hình quà tặng, thông báo trúng thưởng |
| `assets/06-hinh-anh/cua-hang/` | Hình HEAD, quầy tiếp nhận, xưởng dịch vụ |
| `assets/06-hinh-anh/san-pham/` | Ảnh xe, chi tiết và phụ kiện có nguồn sử dụng rõ ràng |
| `assets/06-hinh-anh/nhan-su-khach-hang/` | Ảnh được phép công khai của nhân viên và khách hàng |
| `assets/07-noi-dung/bai-dang/` | Nội dung Facebook, lời mời mua xe, thông điệp dịch vụ |
| `assets/07-noi-dung/tuyen-dung/` | Nội dung tuyển dụng nhân sự HEAD |
| `assets/08-mau-thiet-ke/` | Mẫu avatar, bài đăng, hình nền điện thoại, poster và phông |
| `archive/` | Tài sản hết hiệu lực hoặc đã được thay thế |
| `docs/` | Quy ước và danh mục quản lý |
| `templates/` | Biểu mẫu cho từng công việc |

Trong mỗi công việc, tạo các thư mục khi cần:

- `sources/`: file gốc và tài liệu đầu vào được phép lưu công khai.
- `working/`: file chỉnh sửa và bản nháp.
- `exports/`: bản xuất đã được duyệt để đăng hoặc in.

Ví dụ đường dẫn:
`assets/02-dich-vu/20261025-bao-duong/exports/20261025-kh-dich-vu-bao-duong-facebook-1080x1350-v01-duyet.png`.

Git không lưu thư mục rỗng; các file `.gitkeep` chỉ giữ chỗ và có thể xóa khi đã thêm tài sản.

## Quy trình duyệt và tái sử dụng

- Bắt đầu ở trạng thái `nhap`, chuyển `cho-duyet` khi gửi duyệt, chỉ ghi `duyet` khi có xác nhận.
- Ghi người duyệt và ngày duyệt trong `thong-tin.md`. Bộ khung này chưa xác lập người có quyền duyệt.
- Mỗi lần sửa nội dung hoặc bố cục tăng phiên bản; giữ bản đã duyệt trước đó để đối chiếu.
- Trước khi đăng: kiểm tra chính tả “Vòng xuyến Yên Mỹ”, số liên hệ, dòng xe, thông số, giá và thời hạn ưu đãi.
- Với ảnh người: giữ nhận diện, khuôn mặt và tỷ lệ tự nhiên; ghi rõ nếu ảnh là ảnh ghép hoặc tạo bằng AI.
- Với file in: ghi khổ thành phẩm, chiều rộng × chiều cao, đơn vị, vùng tràn lề và yêu cầu của nhà in. Với file số: ghi kích thước pixel và kênh sử dụng.
- Tài sản hết hạn chuyển sang `archive/YYYY/`, giữ thông tin nguồn và ngày hết hiệu lực; không coi bản lưu trữ là nội dung đang áp dụng.

## Lưu trữ trong repo công khai

Chỉ đưa lên tài sản đã được phép công khai và có quyền sử dụng. Không đưa ảnh khách hàng chưa đồng ý, hồ sơ mua xe/trả góp, giấy tờ cá nhân, dữ liệu nội bộ hoặc thông tin đăng nhập. Nếu cần giữ bản gốc riêng tư, chỉ ghi tham chiếu nội bộ phù hợp; không đưa liên kết truy cập riêng tư vào repo.

Ưu tiên bản xuất gọn để xem nhanh. File thiết kế/video nặng nên lưu ở nơi phù hợp và ghi tham chiếu công khai được phép dùng; nếu chọn Git LFS, cần thiết lập trước khi thêm file lớn. Repo này chưa cấu hình Git LFS.

Logo, nhãn hiệu Honda, ảnh sản phẩm và phông chữ có điều kiện sử dụng riêng; việc xuất hiện trong repo không mặc nhiên cấp quyền tái sử dụng.

## Tài liệu liên quan

- [Quy ước đặt tên và phiên bản](docs/quy-uoc-dat-ten.md)
- [Danh mục nhóm và bảng theo dõi tài sản](docs/danh-muc-tai-san.md)
- [Mẫu thông tin tài sản](templates/thong-tin-tai-san.md)
