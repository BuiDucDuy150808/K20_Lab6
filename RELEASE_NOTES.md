# Ghi chú bàn giao

## Phiên bản

- **Tên/mã:** Portfolio CV V5 / K20_Lab6. V5 lấy từ chú thích trong CSS; dự án chưa có tag hoặc quy ước phiên bản chính thức.
- **Ngày cập nhật ghi chú:** 2026-10-30.
- **Trạng thái:** Bản mã hiện tại trong workspace; chưa có commit đại diện chính xác cho toàn bộ trạng thái này.

## Mã nguồn được bàn giao

- [Trang portfolio](./portfolio/index.html)
- [Trang kết quả form](./portfolio/ket-qua.html)
- [CSS giao diện](./portfolio/css/style.css)
- [README dự án](./portfolio/README.md)

Commit nền gần nhất là [`d1bcacb19bbd9497fa699f0d2f6ce2da3d96f9cc`](https://github.com/vanhkazen/K20_Lab6/commit/d1bcacb19bbd9497fa699f0d2f6ce2da3d96f9cc), ngày 2026-10-23. **Commit này không chứa chính xác bản mã đang bàn giao:** `index.html` có thay đổi chưa commit, `ket-qua.html` đang staged, và `RELEASE_NOTES.md` ở thư mục dự án cùng `AI_log.md` cũng chưa được commit. Các liên kết tệp ở trên trỏ tới mã hiện có trong workspace, không phải snapshot của commit nền.

## Thay đổi chính

- Bản portfolio trình bày giới thiệu, kỹ năng, dự án, học tập và thông tin liên hệ; CSS có bố cục responsive.
- Có form liên hệ kiểm tra dữ liệu bằng HTML5 và trang kết quả thực hành.
- So với commit nền, `index.html` và `ket-qua.html` hiện dùng đường dẫn CSS tuyệt đối trên máy Windows; `ket-qua.html` cũng được định dạng lại. Đây là mô tả thay đổi, không phải xác nhận các thay đổi đã được kiểm thử.

## Lỗi đã sửa

- Chưa có bản sửa lỗi nào được xác nhận trong thay đổi hiện tại.

## Hạn chế còn lại

- Hai trang HTML trỏ stylesheet tới `D:\CNTT20-04\portfolio\css\style.css`. Đường dẫn này không khớp vị trí dự án hiện tại và không dùng được khi chuyển máy; giao diện có thể mất CSS. Cần đổi về đường dẫn tương đối `css/style.css` trước khi phát hành.
- Form dùng `GET`: dữ liệu có thể hiện trên URL; form không gửi email và không lưu dữ liệu lên máy chủ.
- Các liên kết GitHub trong thẻ dự án vẫn là nội dung chờ cập nhật.
- Chưa có kết quả kiểm thử trình duyệt/di động được ghi nhận. `git diff --check` cũng báo khoảng trắng cuối dòng trong thay đổi `ket-qua.html`.

## Tiếp tục kiểm tra và bàn giao

1. Sửa đường dẫn CSS trong cả hai trang HTML thành `css/style.css`.
2. Mở `index.html` và gửi thử form với dữ liệu hợp lệ/không hợp lệ; xác nhận trang kết quả, hiển thị CSS và bố cục ở màn hình rộng lẫn hẹp. Dùng dữ liệu giả vì nội dung form nằm trên URL.
3. Cập nhật các liên kết dự án, rà soát thay đổi và kiểm tra lại `git diff --check`.
4. Commit trạng thái đã kiểm tra, rồi ghi SHA commit mới tại đây để người nhận có thể lấy đúng snapshot. Không dùng commit nền nêu trên làm mã bàn giao cuối cùng.
