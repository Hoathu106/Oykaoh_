<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shop Túi Móc Len</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f5f2;
            text-align: center;
        }
        header {
            background-color: #d4a373;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
        }
        .product {
            display: inline-block;
            margin: 10px;
            padding: 10px;
            background: white;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 200px;
            border-radius: 10px;
        }
        .order-button {
            display: block;
            margin: 10px auto;
            padding: 10px 15px;
            background-color: #d4a373;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background-color: #d4a373;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .about, .policy, .feedback {
            background: white;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .order-form {
            background: white;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .order-form input, .order-form button {
            display: block;
            width: 80%;
            margin: 10px auto;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .order-form button {
            background-color: #d4a373;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>Shop Túi Móc Len</header>
    
    <div class="container">
        <div class="about">
            <h2>Giới thiệu</h2>
            <p>Shop chuyên cung cấp các mẫu túi móc len độc đáo, thủ công và chất lượng cao. Mỗi sản phẩm đều được làm bằng tình yêu và sự sáng tạo.</p>
        </div>
        
        <h2>Sản phẩm nổi bật</h2>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Túi Móc Len 1">
            <p>Túi Móc Len Hoa Phong Lan</p>
            <p>Giá: 500.000đ</p>
            <button class="order-button">Đặt hàng</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Túi Móc Len 2">
            <p>Túi Móc Len Vintage</p>
            <p>Giá: 450.000đ</p>
            <button class="order-button">Đặt hàng</button>
        </div>
    </div>
    
    <div class="order-form">
        <h2>Đặt hàng ngay</h2>
        <form>
            <input type="text" placeholder="Tên của bạn" required>
            <input type="text" placeholder="Sản phẩm muốn đặt" required>
            <input type="text" placeholder="Số điện thoại" required>
            <button type="submit">Gửi đơn hàng</button>
        </form>
    </div>
    
    <div class="policy">
        <h2>Chính sách vận chuyển và bảo hành</h2>
        <p>- Giao hàng toàn quốc từ 3-5 ngày.</p>
        <p>- Miễn phí ship cho đơn từ 800.000đ.</p>
        <p>- Bảo hành sản phẩm 6 tháng với lỗi từ nhà sản xuất.</p>
    </div>
    
    <div class="feedback">
        <h2>Phản hồi từ khách hàng</h2>
        <p>🌟 "Túi rất đẹp, chất lượng và bền. Sẽ ủng hộ shop dài lâu!" - Khách hàng A</p>
        <p>🌟 "Sản phẩm độc đáo, giao hàng nhanh, rất ưng ý." - Khách hàng B</p>
    </div>
    
    <footer>
        Liên hệ: <a href="#">Instagram</a> | <a href="#">Facebook</a> | <a href="#">Zalo</a>
    </footer>
</body>
</html>
