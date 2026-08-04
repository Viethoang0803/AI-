# Hand-Sync Particle Nexus

Ứng dụng hạt 3D điều khiển bằng cử chỉ tay qua webcam (Three.js + MediaPipe Hands).

Fork / dựa trên [talhahSalman/Hand-Sync-3D-Particle-System](https://github.com/talhahSalman/Hand-Sync-3D-Particle-System).

## Dùng trên điện thoại

**https://viethoang0803.github.io/AI-/**

1. Mở link trên Chrome hoặc Safari  
2. Cho phép quyền **camera**  
3. Đưa tay vào khung hình  

Cần HTTPS (GitHub Pages) để webcam hoạt động trên mobile.

## Cử chỉ

| Cử chỉ | Hành động |
|--------|-----------|
| Di chuyển tay | Xoay vật thể & đổi màu |
| Chụm ngón (pinch) | Đổi shape (cooldown ~4 giây) |
| Nắm tay (fist) | Phóng to |
| Xòe lòng bàn tay (open palm) | Thu nhỏ |
| Giơ 1 ngón | Đóng băng animation |

## Các hình

Sphere · Heart · Saturn · Flower · Fireworks

## Chạy local

```bash
python -m http.server 8000
```

Mở http://localhost:8000 rồi cho phép camera.

## Công nghệ

- Three.js  
- MediaPipe Hands  
- GSAP  
- Một file `index.html` — không cần npm / backend  

## Tác giả

**Viethoang0803** — https://github.com/Viethoang0803/AI-
