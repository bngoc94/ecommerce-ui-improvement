# NHẬT KÝ SỬ DỤNG AI

## I. BUỔI 1 – XÂY DỰNG GIAO DIỆN WEBSITE

### 1. Công cụ AI

- Tên công cụ: Gemini.

### 2. Mục đích sử dụng

- Phân tích website thương mại điện tử thực tế (RUBIES).
- Đề xuất phương án thiết kế giao diện chi tiết sản phẩm tối ưu cho người dùng Việt Nam.
- Hỗ trợ xây dựng cấu trúc HTML5 và định dạng CSS3 Responsive.
- Giải thích mã nguồn và hỗ trợ định hướng khắc phục lỗi giao diện.
- Hỗ trợ xây dựng các thành phần tương tác cơ bản trên trang chi tiết sản phẩm.

### 3. Prompt đã sử dụng

1. "Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng... Tôi đang khảo sát website RUBIES. Hãy phân tích các khu vực giao diện, chức năng và trải nghiệm người dùng của website."
2. "Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Hãy đề xuất bố cục trang chi tiết sản phẩm phù hợp, dễ sử dụng và tối ưu cho người dùng Việt Nam."
3. "Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3, có đầy đủ các thành phần cần thiết của trang chi tiết sản phẩm."
4. "T thấy cái giao diện của t k ấn được cái size và phân loại màu sắc khác. Hãy kiểm tra và hướng dẫn t chỉnh lại để khi nhấn vào màu sắc hoặc kích thước thì giao diện có thể cập nhật trạng thái được chọn."

### 4. Kết quả AI đề xuất

- Cung cấp bảng phân tích 5 khu vực của website tham khảo.
- Đề xuất bố cục 2 cột trên Desktop và 1 cột trên Mobile.
- Hỗ trợ xây dựng mã nguồn HTML/CSS/JS mẫu cho giao diện chi tiết sản phẩm.
- Đề xuất các thành phần như hình ảnh sản phẩm, tên, giá, lựa chọn màu sắc, kích thước, số lượng, nút thêm vào giỏ hàng và các thông tin liên quan.
- Hướng dẫn bổ sung chức năng tương tác cho các nút chọn màu sắc và kích thước.

### 5. Kiểm tra và điều chỉnh

- Kiểm tra giao diện trên trình duyệt bằng Live Server và Chrome DevTools (chế độ Mobile).
- Điểm tự phát hiện và điều chỉnh: Phát hiện các nút chọn màu sắc và chọn size chưa thay đổi trạng thái viền/nền khi nhấp chuột. Đã tự chỉnh sửa mã HTML/CSS và bổ sung hàm JavaScript (`selectSwatch`, `selectSize`) để cập nhật lớp `.active`, tạo phản hồi thị giác cho người dùng.
- Đối chiếu giao diện sau khi chỉnh sửa với yêu cầu ban đầu để đảm bảo các thành phần hiển thị phù hợp.

### 6. Phần tôi hiểu và có thể giải thích

- Cấu trúc các thẻ ngữ nghĩa HTML5: `<header>`, `<main>`, `<nav>`, `<article>`, `<section>`.
- Bố cục Responsive sử dụng `display: grid` và Media Queries `@media (min-width: 992px)`.
- Cách sử dụng JavaScript lắng nghe sự kiện `onclick` để thao tác DOM (`classList.add`, `classList.remove`) nhằm quản lý trạng thái giao diện.
- Vai trò của các thành phần trên trang chi tiết sản phẩm và cách tổ chức nội dung để người dùng dễ dàng theo dõi, lựa chọn sản phẩm.

---

## II. BUỔI 2 – THỰC HÀNH VÀ HOÀN THIỆN HTML5, CSS3

### 1. Công cụ AI

- Tên công cụ: Gemini.

### 2. Mục đích sử dụng

- Rà soát mã nguồn HTML/CSS được kế thừa từ Buổi 1 và xác định những nội dung cần cải thiện.
- Hỗ trợ củng cố cấu trúc HTML5 ngữ nghĩa, kiểm tra cách sử dụng các phần tử và thuộc tính HTML.
- Hướng dẫn tạo, liên kết và định dạng tệp CSS bên ngoài.
- Giải thích cách sử dụng CSS Selector và Box Model để kiểm soát cách trình bày các thành phần giao diện.
- Hỗ trợ thực hành Flexbox và CSS Grid để sắp xếp, căn chỉnh các thành phần trên website.
- Đề xuất hiệu ứng Hover và Focus-visible nhằm cải thiện khả năng tương tác và điều hướng bằng bàn phím.
- Hỗ trợ kiểm tra mã nguồn, xác định nguyên nhân lỗi và đề xuất phương án khắc phục.
- Hỗ trợ xây dựng, rà soát nội dung README.md và ghi nhận quá trình sử dụng AI trong tệp AI_USAGE.md.

### 3. Prompt đã sử dụng

**Prompt 1 – Phân tích mã nguồn hiện tại**

"Tôi đang làm bài tập cá nhân môn Phát triển ứng dụng thương mại điện tử. Trong Buổi 1, tôi đã khảo sát một website TMĐT và tạo giao diện cải tiến bằng HTML/CSS. Dựa trên mã HTML và CSS hiện tại, hãy xác định các thành phần đã có, chỉ ra những điểm chưa hợp lý về cấu trúc hoặc trình bày, đề xuất ít nhất ba vấn đề cần cải thiện và hướng khắc phục bằng kiến thức HTML5/CSS3 cơ bản. Chưa viết lại toàn bộ mã nguồn, hãy giúp tôi hiểu mã hiện tại trước khi sửa."

**Prompt 2 – Kiểm tra cấu trúc HTML5**

"Tôi đang học HTML5 và muốn cải thiện cấu trúc HTML của bài tập Buổi 1. Hãy kiểm tra cách sử dụng các phần tử `header`, `nav`, `main`, `section`, `article`, `footer`; kiểm tra thứ bậc tiêu đề `h1`, `h2`, `h3`; cách sử dụng `img`, `alt`, `a`; đồng thời phát hiện các thẻ chưa đóng hoặc lồng nhau chưa hợp lý. Hãy phân biệt lỗi cần sửa và đề xuất cải thiện, giải thích lý do của từng thay đổi và không viết lại toàn bộ website."

**Prompt 3 – Tạo và liên kết CSS cơ bản**

"Tôi có website HTML5 từ bài tập Buổi 1. Dựa trên cấu trúc thư mục và mã HTML hiện tại, hãy hướng dẫn tôi tạo và liên kết tệp CSS bên ngoài, định dạng font chữ, màu chữ, màu nền, thiết lập margin cho body và đảm bảo hình ảnh không vượt quá chiều rộng phần tử chứa. Chỉ tạo CSS cần thiết, không sử dụng Bootstrap hoặc Tailwind CSS. Hãy giải thích từng nhóm thuộc tính và hướng dẫn cách kiểm tra bằng trình duyệt."

**Prompt 4 – Thực hành CSS Selector và Box Model**

"Tôi muốn thực hành CSS Selector và Box Model trên một thành phần trong website của mình. Dựa trên HTML hiện tại, hãy hướng dẫn sử dụng element selector, class selector và descendant selector; điều chỉnh `margin`, `padding`, `border`, `border-radius`; định dạng tên và giá sản phẩm. Hãy giải thích sự khác nhau giữa margin và padding, tác dụng của `box-sizing: border-box` và chỉ đưa ra phần CSS cần thiết, không thay đổi toàn bộ HTML."

**Prompt 5 – Thực hành Flexbox**

"Tôi đang học CSS3 và muốn thực hành Flexbox trên một khu vực của website thương mại điện tử. Dựa trên HTML hiện tại, hãy xác định phần tử cha cần sử dụng `display: flex`, hướng dẫn căn chỉnh bằng `justify-content`, `align-items` và tạo khoảng cách bằng `gap`. Hãy đưa ra đoạn CSS ngắn phù hợp với HTML, giải thích từng thuộc tính và kết quả mong đợi. Không sử dụng framework CSS và không viết lại toàn bộ giao diện."

**Prompt 6 – Thực hành CSS Grid**

"Tôi đã có một danh sách sản phẩm bằng HTML. Hãy hướng dẫn tôi sử dụng CSS Grid để bố trí danh sách thành hai cột, điều chỉnh khoảng cách giữa các sản phẩm, giữ hình ảnh hiển thị đúng tỷ lệ và thay đổi số cột để quan sát kết quả. Giải thích `grid-template-columns`, `repeat`, `gap` và tác dụng của `object-fit: cover`. Chỉ viết CSS cần thiết cho danh sách hiện có, không sử dụng Bootstrap hoặc Tailwind CSS."

**Prompt 7 – Bổ sung hiệu ứng Hover và Focus-visible**

"Tôi muốn bổ sung hiệu ứng Hover và Focus-visible cho một nút bấm hoặc liên kết trong website. Dựa trên HTML và CSS hiện tại, hãy hướng dẫn tạo hiệu ứng khi di chuyển chuột, sử dụng `transition` để tạo chuyển đổi mượt và bổ sung `focus-visible` để hỗ trợ điều hướng bằng bàn phím. Hãy đảm bảo màu chữ và màu nền dễ nhìn, không làm thay đổi bố cục quá nhiều. Chỉ đưa ra phần CSS cần thêm hoặc sửa và giải thích cách kiểm tra."

**Prompt 8 – Nhờ AI hỗ trợ kiểm tra lỗi**

"Tôi đã hoàn thành một phần giao diện website thương mại điện tử bằng HTML5 và CSS3. Dựa trên mã nguồn HTML/CSS và vấn đề tôi mô tả, hãy xác định nguyên nhân có thể gây ra lỗi, chỉ ra thuộc tính hoặc phần tử cần kiểm tra, đề xuất cách sửa với ít thay đổi nhất và giải thích vì sao cách sửa có thể giải quyết vấn đề. Không viết lại toàn bộ mã nguồn, đồng thời hướng dẫn cách kiểm tra sau khi sửa."

**Prompt 9 – Kiểm tra và hoàn thiện README.md**

"Tôi đang hoàn thiện README.md cho bài tập cá nhân Buổi 2 của môn Phát triển ứng dụng thương mại điện tử. Bài tập tiếp tục phát triển website từ Buổi 1. Hãy hỗ trợ xây dựng cấu trúc README ngắn gọn, bao gồm giới thiệu bài tập, website tham khảo và khu vực đã cải tiến, các kỹ thuật HTML5/CSS3 đã thực hành, hướng dẫn chạy website, những thay đổi đã thực hiện, công cụ AI sử dụng và cách kiểm tra kết quả, đường dẫn repository GitHub. Không tự bịa thông tin về dự án và chỉ sử dụng những nội dung tôi cung cấp."

### 4. Kết quả AI đề xuất

- Hỗ trợ phân tích mã nguồn hiện tại, nhận diện các thành phần HTML đã có và đề xuất những nội dung cần cải thiện.
- Hướng dẫn sử dụng các phần tử HTML5 ngữ nghĩa phù hợp với nội dung website, kiểm tra thứ bậc tiêu đề, thuộc tính hình ảnh và liên kết.
- Cung cấp hướng dẫn tạo, liên kết tệp CSS bên ngoài và thiết lập các thuộc tính định dạng cơ bản như font chữ, màu sắc, margin và kích thước hình ảnh.
- Giải thích cách sử dụng element selector, class selector và descendant selector để lựa chọn thành phần HTML cần định dạng.
- Minh họa Box Model thông qua các thuộc tính `margin`, `padding`, `border`, `border-radius` và `box-sizing`.
- Đề xuất cách sử dụng Flexbox để căn chỉnh các thành phần giao diện theo hàng hoặc cột, điều chỉnh khoảng cách và vị trí của các phần tử.
- Hướng dẫn sử dụng CSS Grid để bố trí danh sách sản phẩm thành nhiều cột, điều chỉnh khoảng cách và giữ tỷ lệ hình ảnh.
- Cung cấp các đoạn mã CSS bổ sung hiệu ứng `:hover`, `:focus-visible` và `transition` cho các thành phần tương tác.
- Hỗ trợ rà soát mã nguồn, xác định những điểm chưa hợp lý và đề xuất phương án điều chỉnh nhằm cải thiện giao diện.
- Đề xuất cấu trúc README.md để trình bày thông tin dự án, nội dung thực hành, kết quả cải tiến và quá trình sử dụng AI.

### 5. Kiểm tra và điều chỉnh

- Sau khi nhận được đề xuất từ AI, tiến hành đối chiếu với mã nguồn HTML/CSS hiện tại và kiểm tra trực tiếp trên trình duyệt để đánh giá kết quả.
- Trong quá trình thực hành HTML5, kiểm tra cách tổ chức các phần tử và điều chỉnh cấu trúc khi cần thiết để nội dung được phân chia hợp lý hơn.
- Đối với CSS Selector và Box Model, sử dụng các class có sẵn trong mã nguồn để định dạng thành phần, đồng thời điều chỉnh khoảng cách, đường viền và cách trình bày phù hợp với giao diện.
- Trong quá trình thực hành Flexbox, nhận thấy cách bố trí ban đầu khiến các thẻ sản phẩm chưa cân đối. Sau đó, tiến hành điều chỉnh các thuộc tính Flexbox và tiếp tục thực hành CSS Grid để kiểm soát số cột cũng như khoảng cách giữa các sản phẩm.
- Bổ sung hiệu ứng Hover cho nút Thêm vào giỏ hàng nhằm tạo phản hồi trực quan khi người dùng di chuyển chuột. Đồng thời, sử dụng Focus-visible để làm nổi bật thành phần khi điều hướng bằng bàn phím.
- Sử dụng trình duyệt và Chrome DevTools để kiểm tra cách hiển thị của giao diện, quan sát những điểm chưa phù hợp và điều chỉnh lại mã nguồn.
- Đối với các đề xuất của AI, không áp dụng toàn bộ một cách máy móc mà tiến hành xem xét, lựa chọn và kiểm tra mức độ phù hợp với cấu trúc website hiện tại.
- Sau khi hoàn thiện, cập nhật nội dung README.md và AI_USAGE.md, đồng thời sử dụng Git để commit và push các thay đổi lên repository GitHub đã tạo từ Buổi 1.

### 6. Phần tôi hiểu và có thể giải thích

- Nhận biết và giải thích vai trò của các phần tử HTML5 cơ bản như `header`, `nav`, `main`, `section`, `article` và `footer`.
- Hiểu cách sử dụng các phần tử tiêu đề, hình ảnh, liên kết và danh sách trong việc tổ chức nội dung website.
- Biết cách tạo và liên kết tệp CSS bên ngoài với tài liệu HTML.
- Phân biệt element selector, class selector và descendant selector; hiểu cách áp dụng chúng để định dạng các thành phần cụ thể.
- Giải thích được sự khác nhau giữa `margin` và `padding`, vai trò của `border`, `border-radius` và `box-sizing: border-box` trong Box Model.
- Trình bày cách sử dụng Flexbox với các thuộc tính `display: flex`, `justify-content`, `align-items` và `gap` để căn chỉnh các thành phần giao diện.
- Phân biệt Flexbox và CSS Grid; hiểu cách sử dụng `display: grid`, `grid-template-columns`, `repeat()` và `gap` để xây dựng bố cục danh sách sản phẩm.
- Giải thích được sự khác nhau giữa `:hover` và `:focus-visible`, vai trò của `transition` trong việc tạo hiệu ứng chuyển đổi.
- Biết cách kiểm tra giao diện trên trình duyệt, sử dụng Chrome DevTools để quan sát lỗi và tự điều chỉnh mã nguồn.
- Hiểu rằng AI chỉ đóng vai trò hỗ trợ tham khảo và đề xuất giải pháp; người thực hiện cần kiểm tra, đánh giá và chịu trách nhiệm đối với những thay đổi được áp dụng vào sản phẩm.
