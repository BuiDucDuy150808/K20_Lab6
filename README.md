# Portfolio CV - K20_Lab6

Portfolio cá nhân dạng website tĩnh, giới thiệu thông tin, kỹ năng, dự án, quá trình học tập và kênh liên hệ. Trang được làm bằng HTML5 và CSS3, không có backend hay bước build.

## Thông tin sản phẩm

- **Tên sản phẩm:** Portfolio CV cá nhân
- **Tên repository:** K20_Lab6
- **Tác giả hiển thị trong `index.html` của workspace:** Bui Duc Duy
- **Hồ sơ GitHub được gắn trong trang:** [CutChoDenXi](https://github.com/CutChoDenXi)
- **Repository:** [vanhkazen/K20_Lab6](https://github.com/vanhkazen/K20_Lab6)
- **GitHub Pages:** [https://vanhkazen.github.io/K20_Lab6/](https://vanhkazen.github.io/K20_Lab6/)

> **Lưu ý khi bàn giao:** URL Pages đang truy cập được, nhưng bản xuất bản hiện hiển thị tên Trần Việt Anh, trong khi `index.html` tại workspace hiển thị Bui Duc Duy. Trang `ket-qua.html` trong workspace cũng còn nội dung nhận diện Việt Anh. Ngoài ra, email hiển thị trên trang chủ khác địa chỉ trong liên kết `mailto:`. Hãy thống nhất tên và thông tin liên hệ trên hai trang rồi xuất bản lại trước khi giới thiệu đây là bản hoàn chỉnh của tác giả. URL hồ sơ trên trang và chủ sở hữu repository cũng khác nhau; xác nhận đó là chủ ý.

## Cấu trúc thư mục

```text
K20_Lab6/
├── index.html       # Trang portfolio chính
├── ket-qua.html     # Trang kết quả của form liên hệ
├── README.md
├── RELEASE_NOTES.md
├── AI_log.md
├── css/
│   └── style.css    # Giao diện responsive
└── assets/
    ├── avatar.svg
    ├── du-an-1.svg
    ├── du-an-2.svg
    └── du-an-3.svg
```

Trang chủ tham chiếu thêm ảnh `assets/791975572_1060704449904978_7434436045093909714_n.jpg`, nhưng ảnh đó hiện không có trong thư mục `assets` của workspace. Khôi phục tệp ảnh hoặc cập nhật `src` trong `index.html` trước khi kiểm tra ảnh đại diện.

## Chạy local

Đây là website tĩnh; không cần cài thư viện hay build:

1. Mở terminal tại thư mục chứa `index.html`.
2. Chạy `python -m http.server 8000` (hoặc dùng tiện ích Live Server trong VS Code).
3. Mở [http://localhost:8000/](http://localhost:8000/) trong trình duyệt.

Để kiểm tra đúng như khi xuất bản, chạy qua HTTP thay vì mở trực tiếp bằng `file://`. CSS dùng đường dẫn tương đối `css/style.css`. Font Inter được lấy từ Google Fonts khi có kết nối mạng; có font dự phòng nếu ngoại tuyến.

## Nguồn xuất bản

- **Mã nguồn:** [GitHub repository](https://github.com/vanhkazen/K20_Lab6)
- **Website:** [GitHub Pages](https://vanhkazen.github.io/K20_Lab6/)
- Repository công khai có nhánh `main`; URL Pages ở trên đã được kiểm tra truy cập. Chưa xác minh cấu hình nguồn triển khai trong phần Settings của GitHub.
- Trang Pages được kiểm tra đang là bản khác với workspace hiện tại. Commit nền gần nhất được workspace ghi nhận là [`d1bcacb`](https://github.com/vanhkazen/K20_Lab6/commit/d1bcacb19bbd9497fa699f0d2f6ce2da3d96f9cc); các thay đổi local chưa được commit nên commit này không đại diện cho toàn bộ nội dung đang sửa.

## Kiểm tra các trang và chức năng

1. **Trang chính:** mở `/` hoặc `index.html`; kiểm tra giới thiệu, ảnh đại diện, kỹ năng, ba thẻ dự án, bảng học tập và thông tin liên hệ.
2. **Menu điều hướng:** lần lượt chọn Giới thiệu, Kỹ năng, Dự án, Học tập và Liên hệ; xác nhận trang cuộn tới đúng mục.
3. **Responsive:** thu nhỏ cửa sổ hoặc dùng chế độ thiết bị di động của DevTools; kiểm tra menu, phần giới thiệu, thẻ dự án, bảng và form không tràn ngang.
4. **Kiểm tra form:** thử gửi thiếu trường, email sai định dạng, họ tên ngắn hơn 2 ký tự, lời nhắn ngắn hơn 10 hoặc dài hơn 500 ký tự; trình duyệt cần chặn gửi. Sau đó nhập dữ liệu giả hợp lệ để xác nhận chuyển tới `ket-qua.html`.
5. **Trang kết quả:** xác nhận có thông báo không gửi email/không lưu dữ liệu và nút quay lại liên hệ hoạt động.

Form dùng `GET` để thực hành; dữ liệu gửi có thể xuất hiện trong URL. Không nhập thông tin cá nhân thật. Form không gửi email và không lưu dữ liệu lên máy chủ.

## Hồ sơ và minh chứng

- **Hồ sơ được liên kết từ portfolio:** [github.com/CutChoDenXi](https://github.com/CutChoDenXi)
- **Mã nguồn dự án:** [Repository K20_Lab6](https://github.com/vanhkazen/K20_Lab6)
- **Trang đã xuất bản:** [GitHub Pages](https://vanhkazen.github.io/K20_Lab6/)
- **Lịch sử commit công khai:** [Commits trên nhánh main](https://github.com/vanhkazen/K20_Lab6/commits/main)
- **Minh chứng tương tác:** dùng trang Pages để kiểm tra các mục điều hướng, responsive và form theo các bước ở trên. Repository hiện không có ảnh chụp màn hình hoặc bộ kiểm thử tự động riêng.