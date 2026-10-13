# HTGIS — Hội thảo GIS toàn quốc 2009–2026

WebGIS tổng hợp hành trình **Hội thảo Ứng dụng GIS toàn quốc** từ 2009 đến 2026.

## Mục tiêu

- Lấy **WebGIS làm giao diện chính** để trực quan hóa các địa điểm đăng cai theo không gian.
- Tra cứu theo năm: thời gian, nơi tổ chức, chủ đề, nội dung, mục tiêu, số bài báo/tham luận và liên kết tài liệu.
- Giữ trạng thái **“đang cập nhật”** cho các trường dữ liệu chưa có nguồn công khai đủ chắc chắn, thay vì tự suy đoán.
- Tạo một bộ dữ liệu lịch sử có thể tiếp tục bổ sung kỷ yếu, PDF, DOI, ISBN, diễn giả và danh sách bài báo.

## Công nghệ

Trang dùng thư viện **Vietflex** của `Vietflexmap/VN`, được ghim tại commit:

`6144d565fcf236727577ab3c4471bbe49f86892f`

Vietflex được phát triển trên lõi Leaflet và hỗ trợ lớp nền Google tương thích theo cấu hình của dự án.

## Chức năng hiện có

- Bản đồ các địa phương/cơ sở đăng cai.
- Timeline 2009–2026.
- Tìm kiếm theo địa điểm, chủ đề và nội dung.
- Lọc theo năm.
- Chuyển lớp nền: Đường phố / Vệ tinh / Địa hình.
- Panel hồ sơ từng kỳ hội thảo.
- Link nguồn đối chiếu cho từng năm.
- Link tài liệu/kỷ yếu khi đã có nguồn trực tuyến phù hợp.
- Responsive cho desktop và mobile.

## Ghi chú dữ liệu

Nguồn được ưu tiên theo thứ tự: website đơn vị đăng cai, trường/đại học, cơ quan chuyên môn, kỷ yếu hoặc nguồn báo chí chính thống. Mốc 2021 được giữ trên timeline vì nguồn tổng kết năm 2022 cho biết đến 2021 đã có 12 hội thảo; chuỗi 2009–2020 đã tương ứng 12 kỳ, trong khi chưa xác nhận được một kỳ riêng của năm 2021 từ nguồn công khai.

Một số năm chưa xác nhận được tổng số bài nộp nên giao diện hiển thị **Đang cập nhật**.

## Chạy trang

Mở trực tiếp `index.html` hoặc bật GitHub Pages cho nhánh `main` / thư mục gốc.

Dự kiến URL sau khi GitHub Pages được bật:

`https://vietflexmap.github.io/HTGIS/`

## Cập nhật dữ liệu

Dữ liệu hiện được đặt trong mảng `conferences` ở `index.html`. Mỗi kỳ có các trường chính:

- `year`
- `date`
- `city`
- `venue`
- `theme`
- `content`
- `objective`
- `papers`
- `docs`
- `source`
- `lat`, `lng`
- `status`

## Bản quyền / ghi nguồn

Mã website: dự án `Vietflexmap/HTGIS`.

Thư viện bản đồ: `Vietflexmap/VN`.

Thông tin hội thảo thuộc về các đơn vị tổ chức và các nguồn được liên kết trong từng hồ sơ năm.

## Tài liệu toàn văn GIS 2024–2026

Các tài liệu PDF được liên kết từ thư mục Google Drive gốc, không sao chép vào repository. Tại hồ sơ hội thảo từng năm, chọn **Toàn văn GIS · PDF (Google Drive)** để mở tài liệu.

| Năm | Tệp trong Drive | Dung lượng | Toàn văn |
|---|---|---:|---|
| 2024 | GIS_full_2024 | 35.98 MB | [Xem PDF](https://drive.google.com/file/d/1CSiW-QzCmm_vKSrp2PhCVwhiavEOcJT5/view) |
| 2025 | GIS_full_2025.pdf | 30.75 MB | [Xem PDF](https://drive.google.com/file/d/1cF0T0i6qFshHjifm5jHUY-G3OgbaeTdC/view) |
| 2026 | GIS_full_2026 | 158.04 MB | [Xem PDF](https://drive.google.com/file/d/1VnyDvLyjBCIAVH6MlVSuLW75K_NadEXC/view) |

[Thư mục nguồn Google Drive](https://drive.google.com/drive/folders/1BXVoow69o24xK_-hjTVOt8kKy7BDDhxB). Quyền xem PDF phụ thuộc vào cài đặt chia sẻ của chủ sở hữu Drive. Tài liệu thuộc quyền của các tác giả/đơn vị xuất bản tương ứng.
