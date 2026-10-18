# Nhật Ký Sử Dụng AI

## 1. Công cụ AI
- Tên công cụ: Gemini 

## 2. Mục đích sử dụng
- Phân tích website thương mại điện tử thực tế (RUBIES).
- Đề xuất phương án thiết kế giao diện chi tiết sản phẩm tối ưu cho người dùng Việt Nam.
- Hỗ trợ tạo cấu trúc HTML5 ngữ nghĩa và định dạng CSS3 Responsive.
- Giải thích mã nguồn và hỗ trợ định hướng khắc phục lỗi giao diện.

## 3. Prompt đã sử dụng
1. "Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng... Tôi đang khảo sát website RUBIES..."
2. "Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3... Hãy đề xuất bố cục..."
3. "Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3..."
4. "T thấy cái giao diện của t k ấn được cái size và phân loại màu sắc khác..."

## 4. Kết quả AI đề xuất
- Cung cấp bảng phân tích 5 khu vực website.
- Đề xuất bố cục 2 cột (Desktop) và 1 cột (Mobile)
- Cung cấp mã nguồn HTML/CSS/JS mẫu chứa đầy đủ các tính năng yêu cầu.

## 5. Kiểm tra và điều chỉnh
- Kiểm tra giao diện trên trình duyệt bằng Live Server và Chrome DevTools (chế độ Mobile).
- Điểm tự phát hiện và điều chỉnh: Phát hiện các nút chọn màu sắc và chọn size chưa thay đổi trạng thái viền/nền khi nhấp chuột. Đã tự chỉnh sửa mã HTML/CSS và bổ sung hàm JavaScript (`selectSwatch`, `selectSize`) để cập nhật lớp `.active` tạo phản hồi thị giác mượt mà cho người dùng.

## 6. Phần tôi hiểu và có thể giải thích
- Cấu trúc các thẻ ngữ nghĩa HTML5: `<header>`, `<main>`, `<nav>`, `<article>`, `<section>`.
- Bố cục responsive dùng `display: grid` và Media Queries `@media (min-width: 992px)`.
- Cách dùng JavaScript lắng nghe sự kiện `onclick` để thao tác DOM (`classList.add`, `classList.remove`) nhằm quản lý trạng thái giao diện.