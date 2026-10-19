# Orilynth StudyOS v1.14.2

Không gian học tập cá nhân: kế hoạch, ghi chú, tài liệu, Quiz Lab, Exam Mode, flashcard, ôn tập ngắt quãng và thống kê học tập.

## Đưa lên GitHub Pages

1. Giải nén gói ZIP trên máy tính.
2. Mở repository GitHub của bạn và tải **các tệp bên trong thư mục này** lên thư mục gốc đang được GitHub Pages publish. Không tải nguyên file ZIP như một tệp website.
3. Giữ các tệp cạnh `index.html`; không đổi tên `app.js`, `styles.css`, `manifest.webmanifest` hoặc các SVG.
4. Trong **Settings → Pages**, chọn đúng branch và thư mục root mà repository của bạn đang dùng. Chờ GitHub Pages publish xong rồi mở URL website để kiểm tra.
5. Thử tạo tài khoản, đăng nhập đúng/sai mật khẩu, tạo bộ flashcard, mở bộ thẻ để học trong cửa sổ riêng, lật thẻ, chấm mức nhớ, tạo quiz, tạo và nộp bài thi thử.

## Những tệp cần có

- `index.html` — trang ứng dụng.
- `app.js` — logic ứng dụng và lưu dữ liệu cục bộ.
- `styles.css` — giao diện responsive.
- `manifest.webmanifest`, `favicon.svg`, `orilynth-mark.svg` — metadata/biểu tượng.
- `.nojekyll` — tránh GitHub Pages bỏ qua một số tệp.
- `README.md` và `LICENSE` — hướng dẫn và giấy phép.

Các báo cáo QA, dữ liệu kết quả kiểm thử cũ và script kiểm thử không được đưa vào ZIP phát hành này để repository gọn hơn; chúng không cần để website chạy.

## Flashcards trong v1.14.2

Chọn một ô bộ thẻ trong **Thư viện bộ thẻ** để mở cửa sổ học tập riêng. Trong cửa sổ có thể lật thẻ, chuyển trước/tiếp và tự đánh giá *Lại / Khó / Tốt / Dễ*. Bấm **Esc**, nút đóng hoặc vùng nền để thoát. Cửa sổ được tối ưu cho desktop, tablet và màn hình điện thoại.

## Lưu dữ liệu và giới hạn tài khoản

Đây là website tĩnh. Tài khoản và dữ liệu học tập được lưu trong bộ nhớ của trình duyệt trên thiết bị hiện tại; không có backend xác thực hay đồng bộ cloud giữa các thiết bị trong gói này. Hãy thường xuyên xuất file sao lưu JSON trong phần Cài đặt trước khi dọn dữ liệu trình duyệt hoặc thay đổi triển khai. Bộ tạo quiz/flashcard xử lý nội dung tại trình duyệt, không cần API key.

GitHub Pages phân phối mã nguồn frontend công khai. Đăng nhập cục bộ giúp phân tách hồ sơ trên trình duyệt nhưng không thay thế hệ thống xác thực máy chủ cho dữ liệu nhạy cảm hoặc website cần tài khoản thật.
