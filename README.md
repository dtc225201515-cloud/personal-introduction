# Trang giới thiệu cá nhân — Bài 6

Mở index.html bằng trình duyệt. Trang dùng HTML/CSS thuần, không cần cài thư viện.

Quy trình đã thực hiện:

1. `Initial structure` — tạo HTML/CSS, push lần đầu.
2. `Add introduction section` — thêm giới thiệu và push.
3. `Style introduction section` — thêm CSS và push.
4. `Introduce incorrect CSS for revert practice` — cố tình ẩn phần giới thiệu và push.
5. `Revert "Introduce incorrect CSS for revert practice"` — dùng git revert để hoàn tác lỗi và push bình thường, giữ các commit hợp lệ.

`git diff 454dfb8 7a77ae6 -- index.html style.css` không có thay đổi: bản cuối khớp bản đúng trước khi sửa sai.

Báo cáo đủ Bài 1–6, câu hỏi tư duy, bảng so sánh reset và minh chứng:
https://github.com/dtc225201515-cloud/git-basic-practice