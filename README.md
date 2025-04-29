<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Trang Quảng Cáo Xe </title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom right, #fceabb, #f8b500);
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      text-align: center;
      padding: 40px 20px;
      background-color: #ff6f61;
      color: white;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    header h1 {
      font-size: 3em;
      margin: 0;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 40px 20px;
      gap: 40px;
    }

    .product-card {
      background: white;
      border-radius: 16px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      overflow: hidden;
      width: 300px;
      transition: transform 0.3s ease;
    }

    .product-card:hover {
      transform: scale(1.05);
    }

    .product-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .product-info {
      padding: 20px;
      text-align: center;
    }

    .product-info h2 {
      margin-top: 0;
      font-size: 1.5em;
    }

    .product-info p {
      margin: 10px 0;
      color: #666;
    }

    .product-info .price {
      font-size: 1.3em;
      color: #ff6f61;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>Khám Phá Xe Độc Đáo</h1>
    <p>Vui chơi & Trang trí cùng xe bánh to và bánh nhỏ</p>
  </header>

  <div class="container">
    <div class="product-card">
      <img src="hinh anh xe banh to.jpg" alt="Xe Bánh To" />
      <div class="product-info">
        <h2>Xe Bánh To</h2>
        <p>Thiết kế mạnh mẽ, phù hợp cho các hoạt động ngoài trời.</p>
        <div class="price">799.000đ</div>
      </div>
    </div>

    <div class="product-card">
      <img src="hinh anh xe can cau.jpg" alt="Xe Cần cẩu" />
      <div class="product-info">
        <h2>Xe Bánh Nhỏ</h2>
        <p>Nhẹ nhàng, nhỏ gọn, lý tưởng để trang trí hoặc chơi trong nhà.</p>
        <div class="price">399.000đ</div>
        </div>
    </div>
  </div>
</body>
</html>
<footer style="text-align: center; padding: 20px; background-color: #333; color: white;">
    <p>Thiết kế bởi: <strong>Đồng anh và an thuyên</strong></p>
  </footer>
