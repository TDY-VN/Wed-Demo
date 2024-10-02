<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới thiệu về Tôi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            color: white; /* Để văn bản có màu trắng cho dễ đọc */
            overflow: hidden; /* Để ẩn thanh cuộn nếu video lớn */
        }
        h1 {
            color: #fff; /* Đặt màu tiêu đề trắng */
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: rgba(0, 0, 0, 0.7); /* Nền tối cho nội dung */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            display: flex; /* Sử dụng Flexbox để bố trí */
            align-items: center; /* Căn giữa theo chiều dọc */
            position: relative; /* Để sử dụng absolute cho video */
            z-index: 1; /* Để nội dung nổi trên video */
        }
        .info {
            margin: 10px 0;
        }
        .social {
            margin-top: 20px;
        }
        .social a {
            color: #3b5998; /* Màu cho liên kết Facebook */
            text-decoration: none;
            display: flex; /* Sử dụng Flexbox để căn giữa logo và văn bản */
            align-items: center; /* Căn giữa theo chiều dọc */
        }
        .avatar {
            width: 150px; /* Kích thước ảnh đại diện */
            height: 150px; /* Kích thước ảnh đại diện */
            border-radius: 50%; /* Để tạo hình tròn */
            margin-right: 20px; /* Khoảng cách giữa ảnh và tên */
        }
        .logo {
            width: 24px; /* Kích thước logo */
            height: 24px; /* Kích thước logo */
            margin-right: 8px; /* Khoảng cách giữa logo và văn bản */
        }
        video {
            position: absolute; /* Để video ở nền */
            top: 50%;
            left: 50%;
            width: 100%;
            height: 100%;
            object-fit: cover; /* Để video làm đầy màn hình */
            transform: translate(-50%, -50%);
            z-index: 0; /* Để video ở dưới cùng */
        }
    </style>
</head>
<body>

<video autoplay loop muted>
    <source src="img/nền.mp4" type="video/mp4"> <!-- Đường dẫn đến video nền -->
    Trình duyệt của bạn không hỗ trợ video.
</video>

<div class="container">
    <img src="img/ảnh chính.jpg" alt="Hình đại diện của Dy_Nam" class="avatar"> <!-- Đường dẫn đến ảnh đại diện -->
    <div>
        <h1>Dy_Nam</h1>
        <div class="info">
            <strong>Tuổi:</strong> 16
        </div>
        <div class="info">
            <strong>Năm sinh:</strong> 2009
        </div>
        <div class="info">
            <strong>Mô tả:</strong> Dy_Nam chuyên code script.
        </div>
        <div class="social">
            <a href="https://www.facebook.com/CapybaraDuy" target="_blank">
                <img src="img/facebook.png" alt="Facebook Logo" class="logo">Facebook
            </a>
        </div>
        <div class="social">
            <a href="https://discord.gg/kEtMGjgF" target="_blank">
                <img src="img/discord.png" alt="Discord Logo" class="logo">Nhấn vào để truy cập máy chủ Discord
            </a>
        </div>
    </div>
</div>

</body>
</html>
# Demo-by-TDY
# Demo-by-TDY
# Demo-by-TDY
# Wed-Demo
