# Listening Dictation

Website nghe chép chính tả chạy bằng HTML/CSS/JavaScript thuần.

## Đưa lên GitHub Pages

1. Tạo repository GitHub mới, để **Public**.
2. Upload file `index.html` vào thư mục gốc.
3. Vào **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch: **main** và folder **/ (root)**.
6. Save và chờ GitHub publish.

Website có:
- Student Mode
- Teacher Mode
- Play/Replay
- tốc độ 0.75x/1x/1.25x
- transcript checking
- xem đáp án
- tính điểm
- tạo/chỉnh lesson
- thêm audio URL MP3/WAV
- export/import JSON
- tạo link lesson để gửi học viên

Lưu ý: Teacher Mode lưu dữ liệu trong trình duyệt (localStorage). Nếu muốn tất cả học viên nhìn thấy dữ liệu mới nhất từ một link cố định, hãy cập nhật dữ liệu trong file/hoặc dùng backend/database ở phiên bản tiếp theo.
