# Giao bài tập

Ứng dụng web đơn giản để giáo viên giao bài tập và học sinh nộp bài. Chỉ gồm 1 file `index.html`, không cần máy chủ.

## Cách hoạt động
1. **Giáo viên** tạo bài (tiêu đề, lớp, môn, hạn nộp, các câu hỏi) → nhận **link bài tập** → gửi cho học sinh.
2. **Học sinh** mở link, nhập họ tên, làm bài, bấm **Nộp bài** → nhận một **mã bài nộp** → gửi mã cho giáo viên.
3. **Giáo viên** dán mã vào mục "Bài nộp", chấm điểm, nhận xét, xuất CSV.

Dữ liệu của giáo viên lưu trong trình duyệt (localStorage), vì vậy hãy dùng cùng một trình duyệt/máy khi chấm bài.

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub, tải 2 file `index.html` và `README.md` lên.
2. Vào **Settings → Pages → Build and deployment**: chọn *Deploy from a branch*, nhánh `main`, thư mục `/ (root)` → Save.
3. Sau ít phút, ứng dụng chạy tại `https://<tên-github>.github.io/<tên-repo>/`.
4. 
