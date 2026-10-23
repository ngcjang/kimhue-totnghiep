# Thiệp mời tốt nghiệp — Kim Huệ

Link thiệp: https://totnghiepkimhue.netlify.app · https://ngcjang.github.io/kimhue-totnghiep/

## Link riêng cho từng khách
Thêm `?to=Tên khách` vào cuối link, ví dụ `https://totnghiepkimhue.netlify.app/?to=Chị Lan`.
Không có `?to=` thì thiệp hiện "Thân mời bạn".

## Thay ảnh (khi có ảnh pre-graduation)
Chép ảnh mới **đè lên đúng tên file** trong `assets/photos/`:

| File | Vị trí trên thiệp |
|---|---|
| `hero.jpg` | Ảnh chính trong khung vòm — nên dùng ảnh dọc |
| `album-1.jpg` … `album-6.jpg` | 6 ảnh polaroid ở mục "Thanh xuân của Huệ" |
| `truong.jpg` | Ảnh trường ở mục Địa điểm |

Ảnh nên thu nhỏ còn khoảng 1000–1400px cạnh dài (dưới ~500 KB) để thiệp mở nhanh trên điện thoại.

## Đưa lên Netlify
Tab **Deploys** → kéo thả cả thư mục, hoặc chỉ các mục cần thiết: `index.html`, `vo-tay.mp3`, thư mục `assets`.
Thư mục `img/` chứa ảnh gốc, không cần đưa lên.

## Cập nhật GitHub
```
git add -A
git commit -m "Cập nhật thiệp"
git push
```
