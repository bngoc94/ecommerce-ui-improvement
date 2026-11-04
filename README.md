# E-commerce UI Improvement - Cải Tiến Giao Diện Chi Tiết Sản Phẩm
**I. BUỔI 1 – XÂY DỰNG GIAO DIỆN WEBSITE**
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

**II. BUỔI 2 – THỰC HÀNH VÀ HOÀN THIỆN HTML5, CSS3**
**8. Nội dung thực hành HTML5 và CSS3**
Trong Buổi 2, dự án tiếp tục được hoàn thiện thông qua việc thực hành các kỹ thuật HTML5 và CSS3 trên giao diện chi tiết sản phẩm. Các nội dung đã thực hiện bao gồm:
HTML5: Sử dụng các phần tử HTML để xây dựng và tổ chức cấu trúc giao diện.
CSS Selector: Sử dụng bộ chọn CSS để định dạng các thành phần trên trang web.
Box Model: Áp dụng margin, padding và border để điều chỉnh khoảng cách, kích thước của các phần tử.
CSS Flexbox: Thực hành sắp xếp các thành phần giao diện theo hàng hoặc cột và căn chỉnh vị trí.
CSS Grid: Xây dựng bố cục dạng lưới cho khu vực danh sách sản phẩm liên quan.
Hover và Focus-visible: Bổ sung hiệu ứng tương tác cho nút chức năng và hỗ trợ điều hướng bằng bàn phím.
**9. Kiểm thử giao diện**
Sau khi hoàn thiện mã nguồn, website được kiểm tra trên trình duyệt Google Chrome nhằm đánh giá khả năng hiển thị và hoạt động của các thành phần giao diện và đã đạt các nội dung sau đây:
- Trang HTML mở được
- CSS được áp dụng
- Hình ảnh hiển thị đúng
- Liên kết hoạt động
- Bố cục không bị tràn nghiêm trọng
- Hiệu ứng Hover và Focus-visible hoạt động
- Đã phát hiện và tự sửa ít nhất một vấn đề
Các vấn đề phát hiện trong quá trình kiểm thử và phương án khắc phục được ghi nhận trong quá trình thực hiện bài tập.
**10. Hỗ trợ từ AI trong Buổi 2**
AI tiếp tục được sử dụng để hỗ trợ giải thích CSS Selector, Box Model, Flexbox, CSS Grid, các hiệu ứng Hover và Focus-visible, đồng thời rà soát và đề xuất phương án khắc phục lỗi mã nguồn.
Các đề xuất của AI được kiểm tra bằng cách đối chiếu với mã nguồn và chạy thử website trên trình duyệt trước khi áp dụng. Những prompt tiêu biểu, kết quả nhận được và các điều chỉnh sau khi kiểm tra được ghi lại trong tệp AI_USAGE.md.
**11. Repository và tài liệu dự án**
Mã nguồn website được lưu trữ và cập nhật trên GitHub. Repository tiếp tục sử dụng từ Buổi 1, đồng thời bổ sung các nội dung thực hành và cải tiến giao diện trong Buổi 2.
GitHub Repository: github.com/bngoc94/ecommerce-ui-improvement/
Website triển khai: http://127.0.0.1:3000/index.html?vscode-livepreview=true
Tài liệu ghi nhận quá trình sử dụng AI: AI_USAGE.md
