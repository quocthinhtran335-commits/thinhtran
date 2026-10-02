# Portfolio cá nhân — Trần Quốc Thịnh

Website tĩnh 4 trang mô tả quá trình học tập, kỹ năng, dự án và thông tin liên hệ của Trần Quốc Thịnh — sinh viên ngành Công nghệ thông tin, đang học tập tại Học Viện Hàng Không Việt Nam.

## Tổng quan dự án

Dự án này là một portfolio cá nhân được xây dựng bằng HTML5 và CSS3 thuần. Giao diện có phong cách hiện đại, tối giản nhưng mang cảm giác "bản vẽ kỹ thuật" nhờ cách sắp xếp layout, typography và các yếu tố hình khối.

### Các trang chính

- `index.html` — Trang chủ giới thiệu bản thân và mục tiêu phát triển
- `gioi-thieu.html` — Thông tin cá nhân, quá trình học tập và kỹ năng đang rèn luyện
- `du-an.html` — Tổng hợp các dự án học tập và sản phẩm thực hành
- `lien-he.html` — Thông tin liên hệ và form liên lạc tĩnh
- `chi-tiet-du-an.html` _ Chi tiết các dự án đã và đang làm
- `chung-chi.html` _ Các chứng chỉ đã đạt được

## Cấu trúc thư mục

```text
portfolio/
├── index.html              # Trang chủ
├── gioi-thieu.html         # Giới thiệu bản thân
├── du-an.html              # Danh sách dự án
├── lien-he.html            # Liên hệ
├── css/
│   └── style.css          # File CSS chung cho 4 trang
├── images/
│   ├── DSC_5210.JPG        # Ảnh chính trên trang chủ
│   ├── du-an-cua-hang.svg
│   ├── du-an-thoi-tiet.svg
│   ├── du-an-blog.svg
│   └── ...
├── README.md
└── .gitignore
```

## Tính năng chính

- Thiết kế responsive cho các kích thước màn hình
- Navigation cố định và rõ ràng cho 4 trang
- Giao diện thống nhất qua file CSS chung
- Trang giới thiệu có timeline và danh sách kỹ năng
- Trang dự án có các project card mô tả dự án học tập
- Trang liên hệ có form minh họa và thông tin liên lạc
- Sử dụng Google Fonts để tăng tính thẩm mỹ cho typography

## Chạy thử ở máy local

Bạn có thể mở trực tiếp file `index.html` trong trình duyệt, hoặc chạy một máy chủ tĩnh như sau:

```bash
python -m http.server 8000
```

Sau đó truy cập:

```text
http://localhost:8000
```

## Triển khai lên GitHub Pages

1. Tạo repository trên GitHub.
2. Khởi tạo git trong thư mục dự án:

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/<ten-tai-khoan>/<ten-repo>.git
git push -u origin main
```

3. Vào GitHub → Settings → Pages.
4. Chọn nguồn triển khai: `Deploy from a branch`.
5. Chọn branch `main` và thư mục gốc `/`.
6. Lưu lại và chờ hệ thống xuất bản.

Website sẽ có dạng:

```text
https://<ten-tai-khoan>.github.io/<ten-repo>/
```

## Thông tin cá nhân hiện tại trong website

- Họ tên: Trần Quốc Thịnh
- Nghề nghiệp: Sinh viên năm 2 ngành Công nghệ thông tin
- Trường: Học Viện Hàng Không Việt Nam (VAA)
- Email: quocthinhtran335@gmail.com
- GitHub: github.com/quocthinhtran335
- LinkedIn: linkedin.com/in/quocthinhtran335
- Khu vực: Tây Ninh, Việt Nam

## Lưu ý

- Nếu muốn thay đổi thông tin cá nhân, hãy cập nhật trực tiếp trong các file HTML tương ứng.
- Nếu muốn chỉnh màu sắc hoặc typography, xem lại phần biến CSS trong `css/style.css`.
- Ảnh minh họa và hình nền nằm trong thư mục `images/` và có thể thay thế tùy theo nhu cầu.
