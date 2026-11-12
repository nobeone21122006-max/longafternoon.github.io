# Portfolio - Mai Văn Đồng

Trang portfolio cá nhân giới thiệu thông tin, học vấn, sở thích và thành tựu.

## Cách đưa lên GitHub Pages

### Bước 1: Tạo repository trên GitHub
1. Đăng nhập GitHub, bấm **New repository**.
2. Đặt tên theo dạng `TEN-GITHUB.github.io` (ví dụ `maivandong.github.io`) để trang có địa chỉ `https://TEN-GITHUB.github.io`.
3. Chọn **Public**, không tick thêm README, rồi bấm **Create repository**.

### Bước 2: Đưa code lên bằng git
Mở terminal trong thư mục `portfolio/` và chạy:

```bash
git init
git add .
git commit -m "Khởi tạo portfolio"
git branch -M main
git remote add origin https://github.com/TEN-GITHUB/TEN-GITHUB.github.io.git
git push -u origin main
```

### Bước 3: Bật GitHub Pages
1. Vào repository, chọn **Settings** → **Pages**.
2. Ở mục **Build and deployment**, chọn **Source: Deploy from a branch**.
3. Chọn branch `main`, thư mục `/ (root)`, rồi bấm **Save**.
4. Sau vài phút, trang sẽ có tại `https://TEN-GITHUB.github.io`.

## Cập nhật nội dung
1. Mở `index.html` bằng bất kỳ trình soạn thảo nào.
2. Thay các thông tin trong phần **Liên hệ** (email, GitHub, LinkedIn).
3. Trong phần **Thành tựu**, thay nội dung các khối có class `placeholder`, rồi xóa class đó.
4. Lưu, sau đó đẩy lên GitHub:

```bash
git add .
git commit -m "Cập nhật thành tựu"
git push
```

## Ghi chú
- Không cần cài đặt gì thêm, chỉ cần trình duyệt.
- Có thể thêm ảnh đại diện vào thư mục `images/` và chèn bằng thẻ `<img src="images/avatar.jpg">`.
