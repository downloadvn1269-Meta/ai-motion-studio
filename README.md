# AI Motion Studio (Free)

Ứng dụng Motion Graphic tĩnh, chạy hoàn toàn trong trình duyệt, triển khai được trên Cloudflare Pages Free.

## Chức năng hiện tại
- Nhập mỗi dòng là một cảnh
- Tỉ lệ 9:16, 16:9, 1:1; chọn bảng màu và thời lượng
- Xem trước hiệu ứng Canvas
- Ghi video qua MediaRecorder: WebM, hoặc MP4 nếu trình duyệt hỗ trợ

## Triển khai
Trên Cloudflare Dashboard → Workers & Pages → Create Pages → Connect to Git → chọn repo này. Framework: None, build command: để trống, output directory: `/` (hoặc `.` tùy giao diện). Mở URL được Cloudflare cấp.

## Giới hạn rõ ràng
Đây là MVP nền tảng, **chưa có AI tạo kịch bản, TTS, ảnh AI, tự đăng Facebook, và chưa đảm bảo MP4**. Không lưu Page Access Token trong mã nguồn frontend. Không cấu hình dịch vụ trả phí. Giữ tab mở khi render.
