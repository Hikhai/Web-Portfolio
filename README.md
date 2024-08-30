# Ứng Dụng Web Portfolio Hình Ảnh

Chào mừng bạn đến với README của Ứng Dụng Web Portfolio Hình Ảnh! Tài liệu này sẽ cung cấp cho bạn cái nhìn tổng quan về dự án, các tính năng, công nghệ sử dụng, và hướng dẫn để cài đặt ứng dụng.

## Mục Lục
- Giới Thiệu
- Tính Năng
- Công Nghệ Sử Dụng
- Cài Đặt
- Sử Dụng
- Cấu Trúc Dự Án
- Đóng Góp
- Giấy Phép
- Liên Hệ

## Giới Thiệu
Ứng Dụng Web Portfolio Hình Ảnh là một nền tảng web động, đáp ứng được thiết kế nhằm cho phép người dùng trưng bày các portfolio về nhiếp ảnh, thiết kế hoặc nghệ thuật của họ. Người dùng có thể tải lên hình ảnh, tổ chức chúng thành các danh mục và hiển thị chúng trong một giao diện thân thiện, dễ sử dụng. Ứng dụng này lý tưởng cho các nhiếp ảnh gia, nghệ sĩ, và nhà thiết kế muốn tạo ra sự hiện diện số cho tác phẩm của mình.

## Tính Năng
- Xác Thực Người Dùng: Chức năng đăng ký và đăng nhập an toàn.
- Tải Lên Hình Ảnh: Người dùng có thể tải lên hình ảnh vào portfolio của mình.
- Quản Lý Danh Mục: Người dùng có thể tổ chức hình ảnh thành các danh mục khác nhau.
- Thiết Kế Đáp Ứng: Ứng dụng hoàn toàn đáp ứng và hoạt động tốt trên mọi thiết bị.
- Xem Hình Ảnh: Người dùng có thể xem hình ảnh dưới dạng gallery với các tùy chọn xem toàn màn hình.
- Phần Bình Luận: Khách thăm có thể để lại bình luận trên các hình ảnh.
- Tìm Kiếm: Người dùng có thể tìm kiếm hình ảnh theo danh mục hoặc từ khóa.

## Công Nghệ Sử Dụng
- Frontend:

- HTML5
- CSS3
- JavaScript (ES6+)
- React.js
- Bootstrap / Material UI
- Backend:

- reactjs.js
- TypeScrip
- Vite
- Nodejs
- JWT (JSON Web Tokens) cho xác thực
- Multer cho việc tải lên hình ảnh
-Công Cụ Khác:

Git & GitHub cho quản lý phiên bản
Postman cho kiểm tra API
AWS S3 / Cloudinary cho lưu trữ hình ảnh

# Sử Dụng
1. Đăng Ký Tài Khoản: Đăng ký với email và tạo mật khẩu.
2. Tải Lên Hình Ảnh: Sau khi đăng nhập, điều hướng đến phần tải lên để thêm hình ảnh vào portfolio của bạn.
3. Tổ Chức Hình Ảnh: Sử dụng danh mục để tổ chức các hình ảnh.
4. Xem Portfolio: Khách thăm có thể xem portfolio của bạn, duyệt hình ảnh và để lại bình luận.
5. Tìm Kiếm: Sử dụng tính năng tìm kiếm để tìm các hình ảnh cụ thể.

## cấu trúc dự án
image-portfolio-web-application/
├── backend/                 # Mã backend
│   ├── config/              # Tệp cấu hình
│   ├── controllers/         # Các hàm xử lý route
│   ├── repositories/        # Các lớp tương tác với cơ sở dữ liệu
│   └── routes/              # Định nghĩa các route API
├── frontend/                # Mã frontend
│   ├── public/              # Tài nguyên công khai
│   │   └── img/             # Ảnh
│   └── src/                 # Tệp nguồn
│       ├── components/      # Các thành phần React
│       ├── context/         # Quản lý trạng thái toàn cục
│       ├── hooks/           # Các hooks tuỳ chỉnh
│       ├── pages/           # Các trang của ứng dụng
│       ├── requests/        # Các yêu cầu API
│       ├── styles/          # Các tệp kiểu dáng
│       ├── utils/           # Các hàm tiện ích
│       ├── app.tsx          # Thành phần chính của ứng dụng
│       └── main.tsx         # Điểm vào của ứng dụng
├── .env                     # Biến môi trường
├── package.json             # Phụ thuộc và script của Node.js
└── README.md                # Tài liệu dự án


