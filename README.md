# Hand Particle Universe

Trải nghiệm hạt 3D điều khiển bằng cử chỉ tay (MediaPipe Hands + Three.js).

## Dùng trên điện thoại

**https://viethoang0803.github.io/AI-/**

1. Mở link trên Chrome / Safari  
2. Nhấn **Enable Camera** và cho phép quyền camera  
3. Đưa tay vào khung hình  

HTTPS từ GitHub Pages là bắt buộc để webcam hoạt động trên mobile.

## Chạy local

```bash
python -m http.server 8000
```

Mở http://localhost:8000

## Cử chỉ chính

| Cử chỉ | Hành động |
|--------|-----------|
| Một tay | Di chuyển / xoay |
| Vuốt trái / phải | Đổi shape |
| Vuốt lên / xuống | Tăng / giảm energy |
| Chụm giữ rồi thả (100%) | Nổ và đổi hình |
| Hai tay | Phóng to / thu nhỏ |
| Đếm ngón 0–5 | Đổi màu |
| Nắm tay / mở lòng | Freeze / resume |

Chỉ cần file `index.html` — không backend, không npm.
