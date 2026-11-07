# gymatlas-media

Dữ liệu bài tập (JSON) và video minh họa (MP4) dùng cho [GymATLAS](https://gymatlashub.lovable.app).

- `data/exercises.json`, `data/muscles.json`, `data/equipment.json`
- `media/video/*.mp4` — kiểm tra toàn vẹn: `shasum -a 256 -c media/SHA256SUMS`
- `media/poster/*.webp` — ảnh đại diện 1280×720 (khung hình giây thứ 1 của video cùng tên)

Phục vụ qua jsDelivr theo tag cố định, ví dụ:
`https://cdn.jsdelivr.net/gh/mytoandeptrai/gymatlas-media@v1.1.0/data/exercises.json`

Giấy phép: CC0 1.0 Universal (xem `LICENSE`).
