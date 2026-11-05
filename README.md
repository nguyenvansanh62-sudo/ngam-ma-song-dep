# Ngẫm mà sống đẹp — Trang thương hiệu cá nhân của Nguyễn Văn Sánh

Trang đang chạy: https://ngam-ma-song-dep-nguyen-van-sanh.pages.dev/
Nền tảng: Cloudflare Pages (trang tĩnh, 1 file HTML + thư mục ảnh assets/).

## Cấu trúc thư mục

- `index.html` — toàn bộ trang (bản chuẩn v4, nhãn build: v4-whole-page-title-motion-shooting-stars-2026-10-22, đã gồm hiệu ứng sao băng được khôi phục; md5: be2cdc7e5bb2f8db4f7ababbe58beff4)
- `assets/nguyen-van-sanh.jpg` — ảnh chân dung chính
- `assets/chan-dung-phong-cach/` — 6 ảnh phong cách

## Lịch sử phiên bản (theo các gói người dùng đã lưu)

- v3 (18/10/2026): bản đầu còn giữ gói zip — chỉ 1 ảnh, CHƯA có mục ảnh phong cách. Không dùng nữa.
- v4 (22/10/2026): thêm mục 6 ảnh phong cách, hiệu ứng chuyển động tiêu đề; sau đó vá thêm hiệu ứng sao băng (đây là bản đang chạy, là nguồn chuẩn trong thư mục này).

## Cách xuất bản hiện tại (trước khi có trang quản trị)

Tải trực tiếp trên Cloudflare: vào dự án Pages → Deployments → New deployment → tải gói zip (index.html nằm ngoài cùng của zip) → Deploy.

## Kế hoạch trang quản trị (phương án A)

1. Kho này là nguồn chính thức trên GitHub (tài khoản của Nguyễn Văn Sánh).
2. Gắn CMS dạng Git (bản nháp cấu hình: thư mục `admin/` — sẽ hoàn thiện khi nối kho thật).
3. Nội dung sửa trong trang quản trị sẽ lưu vào file dữ liệu `data/du-lieu-noi-dung.json`; cơ chế tự động xuất bản đưa bản mới về đúng dự án Cloudflare Pages hiện tại để giữ nguyên địa chỉ trang.
