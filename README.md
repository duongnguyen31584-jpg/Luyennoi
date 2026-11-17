# Luyện nói: đưa lên GitHub và chạy online bằng Netlify (hoặc GitHub Pages)

Gói gồm 8 file: index.html, manifest.webmanifest, sw.js, netlify.toml, icon-192.png, icon-512.png, apple-touch-icon.png, README.md.

## A. Đưa lên GitHub
1. Đăng nhập github.com, bấm dấu + > New repository, đặt tên `luyen-noi`, chọn Public, bấm Create repository.
2. Bấm "uploading an existing file", kéo thả 8 file (đã giải nén) vào, bấm Commit changes.

## B. Chạy online bằng Netlify (nên dùng)
1. Vào netlify.com, đăng ký bằng tài khoản GitHub.
2. Trong Netlify: Add new project (hoặc Sites) > Import an existing project > GitHub, cho phép truy cập kho `luyen-noi`.
3. Cài đặt: Build command để trống, Publish directory để `.` (hoặc để file netlify.toml tự cấu hình). Bấm Deploy.
4. Sau ít phút có link dạng https://ten-site.netlify.app. Có thể đổi tên ở Site configuration > Change site name.

Cách nhanh để thử (không cần GitHub): vào app.netlify.com/drop, kéo cả thư mục đã giải nén vào.

## C. Hoặc GitHub Pages
Settings > Pages > Deploy from a branch > main, thư mục / (root) > Save.

## Cập nhật sau này
Sửa index.html trên GitHub (bút chì) rồi Commit. Đổi số trong sw.js (luyennoi-v4 thành tăng số kế tiếp). Netlify tự phát hành lại sau mỗi lần commit.

## Lưu ý
- Kho Public: ai cũng xem được nội dung. Không đưa thông tin mật.
- Các nút AI không chạy ngoài Claude (app sẽ báo). Không dán khóa API vào file.
- Dữ liệu lưu nằm trên từng thiết bị. Dùng Học tập của tôi > Sao lưu.
- Gói miễn phí của Netlify có hạn mức riêng, hãy xem lại điều khoản hiện hành.
