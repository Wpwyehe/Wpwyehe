<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>水杯代买商城</title>
  <style>
    /* 页面基础样式 */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      text-align: center;
      margin: 20px 0;
    }

    nav a {
      text-decoration: none;
      color: #4CAF50;
      margin: 0 15px;
      font-size: 18px;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    .product {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
    }

    .card {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      width: 300px;
      text-align: center;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .card img {
      width: 80%;
      height: auto;
      border-radius: 5px;
    }

    .card h3 {
      color: #4CAF50;
    }

    .card button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
    }

    .card button:hover {
      background-color: #45a049;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- 顶部导航栏 -->
  <header>
    <h1>水杯代买商城</h1>
    <p>精选优质水杯，让您的生活更便利！</p>
  </header>

  <!-- 导航菜单 -->
  <nav>
    <a href="#">首页</a>
    <a href="#products">产品</a>
    <a href="#contact">联系我们</a>
  </nav>

  <!-- 产品展示区 -->
  <div class="container" id="products">
    <h2>热销水杯</h2>
    <div class="product">
      <!-- 产品卡片 1 -->
      <div class="card">
        <img src="https://via.placeholder.com/250" alt="水杯A">
        <h3>保温水杯 A</h3>
        <p>价格：¥59.00</p>
        <button onclick="addToCart('保温水杯 A')">加入购物车</button>
      </div>

      <!-- 产品卡片 2 -->
      <div class="card">
        <img src="https://via.placeholder.com/250" alt="水杯B">
        <h3>玻璃水杯 B</h3>
        <p>价格：¥39.00</p>
        <button onclick="addToCart('玻璃水杯 B')">加入购物车</button>
      </div>

      <!-- 产品卡片 3 -->
      <div class="card">
        <img src="https://via.placeholder.com/250" alt="水杯C">
        <h3>旅行水杯 C</h3>
        <p>价格：¥79.00</p>
        <button onclick="addToCart('旅行水杯 C')">加入购物车</button>
      </div>
    </div>
  </div>

  <!-- 联系我们 -->
  <div class="container" id="contact">
    <h2>联系我们</h2>
    <p>如有任何问题，请随时联系我们：<strong>support@watercupstore.com</strong></p>
  </div>

  <!-- 页脚 -->
  <footer>
    <p>&copy; 2024 水杯代买商城 | 精选优质产品，贴心服务</p>
  </footer>

  <!-- JavaScript -->
  <script>
    function addToCart(productName) {
      alert(productName + " 已加入购物车！");
    }
  </script>
</body>
</html>

<!---
Wpwyehe/Wpwyehe is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
