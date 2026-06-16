<!-- MINI-PROJECT: Mini-project 1: Trang HTML chuẩn đầu tiên
Yêu cầu: Tạo repo GitHub có index.html trình bày cấu trúc tài liệu HTML, giải thích DOCTYPE, html, head, body và có README; bật GitHub Pages.
Yêu cầu bắt buộc bổ sung: Bắt buộc bổ sung ảnh chụp thiết kế UI các page, phân vùng file HTML theo ảnh thiết kế, tổ chức dự án bài bản trên GitHub cá nhân và bật GitHub Pages để mở khóa bài tiếp theo.

Cấu trúc repo đề xuất:
- index.html
- css/style.css
- js/script.js
- assets/
- README.md

TODO: Tự viết website hoàn chỉnh, không nộp một file rỗng hoặc code copy sẵn.
-->
2. Nội dung bài:
2.1. Cấu trúc tài liệu HTML
Tài liệu HTML là đơn vị cơ bản của một trang web. Trình duyệt đọc tài liệu
này để hiểu cấu trúc nội dung, thông tin cấu hình và các tài nguyên liên quan. Khi
học HTML, chúng ta cần nắm đúng bố cục chuẩn của một tài liệu, hiểu rõ vai trò
từng vùng và hình thành thói quen viết mã có tổ chức ngay từ đầu.
Một tài liệu HTML hoàn chỉnh thường gồm ba phần chính. Phần đầu là
khai báo kiểu tài liệu để trình duyệt biết chuẩn HTML đang được sử dụng. Phần
tiếp theo là phần tử gốc <html> bao bọc toàn bộ nội dung trang. Bên trong <html>,
tài liệu được chia thành hai khu vực lớn là <head> và <body>. Phần <head> chứa
thông tin cấu hình và siêu dữ liệu của trang. Phần <body> chứa nội dung thực tế
mà người dùng nhìn thấy trên trình duyệt.
2.1.1. Khai báo kiểu tài liệu (doctype), các thẻ html, head, body
Khi tạo một tài liệu HTML mới, bước đầu tiên là khai báo DOCTYPE.
Đây là dòng đầu tiên của tệp HTML, có nhiệm vụ thông báo cho trình duyệt rằng
tài liệu này được viết theo chuẩn HTML hiện đại. Nếu thiếu khai báo này, trình
duyệt có thể hiển thị trang theo chế độ tương thích cũ, dẫn đến sai khác về bố cục
hoặc hành vi hiển thị.
Ngay sau DOCTYPE là thẻ <html>. Đây là phần tử gốc của toàn bộ tài liệu.
Tất cả các phần khác của trang đều nằm bên trong thẻ này. Thông thường, nên
khai báo thêm thuộc tính ngôn ngữ, ví dụ lang="vi", để trình duyệt và các công
cụ hỗ trợ biết nội dung chính của trang được viết bằng tiếng Việt.
Bên trong <html> có hai vùng bắt buộc cần hiểu rõ. Thẻ <head> chứa các
thông tin mà người dùng không nhìn thấy trực tiếp trên giao diện, chẳng hạn như
bảng mã ký tự, tiêu đề trang, liên kết tới tệp CSS hoặc JavaScript ngoài. Thẻ
<body> chứa nội dung hiển thị thực tế như tiêu đề, đoạn văn, hình ảnh, liên kết,
bảng biểu, biểu mẫu và các thành phần giao diện khác.
