# MINH QUANG TV — kênh cập nhật

Repo này chỉ dùng cho **tự cập nhật trong app**:

- `update.json` — manifest phiên bản mới nhất (app đọc raw hoặc jsDelivr).
- `minh-quang-tv-<phiên bản>.apk` — **chỉ giữ đúng 1 APK mới nhất**; mỗi lần phát hành phải xoá APK cũ.
- `index.html` — trang nhật ký thay đổi (GitHub Pages).

Quy trình: chạy `scripts/publish-public.sh` trong repo chính, hoặc push tag `v*` để CI đồng bộ.
