# E-commerce UI Improvement - Cải Tiến Giao Diện Chi Tiết Sản Phẩm

## 1. Giới thiệu
Dự án thực hiện khảo sát website thương mại điện tử RUBIES (`https://rubies.vn/`) và xây dựng phiên bản cải tiến giao diện trang chi tiết sản phẩm nhằm tối ưu hóa trải nghiệm mua sắm trực tuyến cho khách hàng tại Việt Nam.

## 2. Website tham khảo
- Tên website: RUBIES
- URL: https://rubies.vn/
- Khu vực đã khảo sát: Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng

## 3. Chức năng
- Hiển thị thông tin chi tiết sản phẩm (Mã SKU, Tên, Giá bán)
- Tích hợp bộ chọn màu sắc và kích thước (Size S, M, L)
- Cảnh báo số lượng sản phẩm tồn kho thực tế.
- Hướng dẫn chọn size dạng cửa sổ Modal tương tác.
- Hiển thị đánh giá chi tiết từ khách hàng trước kèm hình ảnh thực tế
- Bố cục Responsive tương thích linh hoạt trên máy tính (Desktop) và điện thoại di động (Mobile).

## 4. Công nghệ
- HTML5 (Cấu trúc thẻ ngữ nghĩa)
- CSS3 (Flexbox, CSS Grid, Media Queries)
- JavaScript (Xử lý tương tác trạng thái chọn màu/size và bộ tăng giảm số lượng)

## 5. Cách chạy
Mở file `index.html` trực tiếp trên trình duyệt web hoặc sử dụng tiện ích Live Server trong VS Code

## 6. Cải tiến đã thực hiện
- Vấn đề ban đầu: Giao diện chi tiết sản phẩm ban đầu chưa hiển thị số lượng tồn kho còn lại, thiếu hình ảnh cận chất vải, không có bảng hướng dẫn chọn size chi tiết và thiếu phần đánh giá từ khách hàng trước.
- Thay đổi đã thực hiện:
  + Thêm khối cảnh báo tồn kho ("Chỉ còn 3 sản phẩm trong kho").
  + Bổ sung ảnh cận chất vải vào thư viện ảnh sản phẩm.
  + Thêm tính năng bật bảng quy đổi kích cỡ dạng Modal.
  + Tích hợp khu vực hiển thị đánh giá sao và bình luận của người mua.
  + Khắc phục lỗi không đổi trạng thái khi click chọn phân loại màu sắc/size bằng cách bổ sung sự kiện JavaScript và class `.active` cho CSS.

## 7. Hỗ trợ từ AI
- Phần AI hỗ trợ: Đề xuất phương án thiết kế bố cục trang chi tiết sản phẩm, cung cấp cấu trúc mã nguồn HTML5/CSS3 chuẩn Responsive và gợi ý cách tối ưu trải nghiệm mua sắm cho người dùng Việt Nam
- Phần tự kiểm tra và điều chỉnh: Tự kiểm tra giao diện thực tế qua Chrome DevTools (cả phiên bản Desktop và Mobile), tự phát hiện và bổ sung xử lý JavaScript cho các nút chọn phân loại màu/size để tạo phản hồi thị giác tốt nhất