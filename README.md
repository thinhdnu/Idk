<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mini Dashboard</title>
  <style>
   
     {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #f9f9f9;
      padding: 20px;
    }

  
    ul.menu {
      list-style: none;
      background-color: #333;
      padding: 10px;
      text-align: center;
    }

    ul.menu li {
      display: inline-block;
      margin: 0 15px;
    }

    ul.menu li a {
      text-decoration: none;
      color: white;
      font-weight: bold;
      padding: 6px 12px;
      border-radius: 5px;
      transition: 0.3s;
    }

    ul.menu li a:hover {
      background-color: #555;
    }

 
    .info-container {
      margin: 20px 0;
    }

    .info-box {
      display: inline-block;
      background-color: #e0f7fa;
      border-radius: 10px;
      padding: 15px 20px;
      margin-right: 10px;
      
    }

    .info-box span {
      font-weight: bold;
      color: #333;
    }

    
    table {
      width: 100%;
      border-collapse: collapse;
      background-color: white;
      margin-top: 10px;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
    }

    th {
      background-color: #4CAF50;
      color: white;
    }

    tr:nth-child(even) {
      background-color: #f2f2f2;
    }

 
    .notification {
      position: absolute;
      top: 80px;
      right: 20px;
      background-color: #ffeb3b;
      padding: 15px;
      
      z-index: 1;
    }

   
    .support {
      position: absolute;
      top: 160px;
      right: 40px;
      background-color: #b3e5fc;
      padding: 15px;
     
     
      z-index: 0;
    }
  </style>
</head>
<body>

  <ul class="menu">
    <li><a href="#">Trang chủ</a></li>
    <li><a href="#">Bảng điểm</a></li>
    <li><a href="#">Liên hệ</a></li>
  </ul>

  <div class="info-container">
    <div class="info-box"><span>Sĩ số:</span> 40</div>
    <div class="info-box"><span>Điểm cao:</span> 9.5</div>
    <div class="info-box"><span>TB:</span> 7.2</div>
  </div>
  <div class="notification">Thông báo</div>
  <div class="support">Hỗ trợ</div>
  <table>
    <thead>
      <tr>
        <th>Họ tên</th>
        <th>Toán</th>
<th>Văn</th>
        <th>Anh</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Nguyễn An</td>
        <td>8</td>
        <td>7</td>
        <td>9</td>
      </tr>
      <tr>
        <td>Trần Bình</td>
        <td>7</td>
        <td>8</td>
        <td>8</td>
      </tr>
      <tr>
        <td>Lê Cường</td>
        <td>9</td>
        <td>8</td>
        <td>9</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
