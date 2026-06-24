# MODLMH GitHub Pages

Bộ code tĩnh được chuyển từ HTML WordPress của MODLMH.io để chạy trên GitHub Pages.

## Cấu trúc

```txt
index.html
robots.txt
sitemap.xml
assets/github-fix.css
```

## Cách dùng

1. Tạo repo GitHub mới, ví dụ `modlmh-hub`
2. Upload toàn bộ file trong thư mục này lên repo
3. Vào `Settings → Pages`
4. Chọn `Deploy from a branch`
5. Chọn branch `main`, folder `/root`
6. Bấm `Save`

## Lưu ý

- File dùng ảnh/CSS public từ `https://modlmh.io/` để giao diện giống website gốc.
- Nếu đổi username hoặc repo, sửa lại `robots.txt` và `sitemap.xml`.
- `index.html` giữ link về website chính MODLMH.io.
