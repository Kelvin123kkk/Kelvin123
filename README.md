<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chúc Mừng Sinh Nhật Thanh Ngân</title>
  <style>
    /* Định dạng cơ bản */
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #fbe8d3;
      text-align: center;
      color: #333;
    }

    h1 {
      margin-top: 50px;
      font-size: 3rem;
      color: #ff6f61;
      text-shadow: 2px 2px 5px #f9d6b5;
    }

    p {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #444;
    }

    /* Bánh kem */
    .cake {
      width: 150px;
      height: 100px;
      background: #ffcc5c;
      border-radius: 10px;
      margin: 30px auto;
      position: relative;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    }

    .cake::before {
      content: '';
      position: absolute;
      top: -20px;
      left: 50%;
      width: 50px;
      height: 40px;
      background: #ff6f61;
      border-radius: 10px;
      transform: translateX(-50%);
    }

    .cake::after {
      content: '🎂 Happy Birthday!';
      position: absolute;
      bottom: -30px;
      left: 50%;
      transform: translateX(-50%);
      color: #fff;
      font-size: 1rem;
      background: #ff6f61;
      padding: 5px 10px;
      border-radius: 5px;
      text-shadow: 1px 1px 2px #333;
    }

    /* Nút tương tác */
    .btn {
      padding: 10px 20px;
      font-size: 1rem;
      background: #ff6f61;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      box-shadow: 0 3px 10px rgba(0, 0, 0, 0.3);
      margin-top: 20px;
    }

    .btn:hover {
      background: #e95c4e;
    }

    /* Ảnh */
    .photo {
      display: none;
      margin-top: 20px;
      max-width: 80%;
      border: 5px solid #ff6f61;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    }
  </style>
</head>
<body>
  <!-- Tiêu đề -->
  <h1>Chúc Mừng Sinh Nhật Thanh Ngân 🎉</h1>
  <p>Sinh nhật vui vẻ. Luôn vui và giàu ngôn ngữ hơn nhe...😍😍</p>

  <!-- Hiệu ứng bánh kem -->
  <div class="cake"></div>

  <!-- Nút bấm tương tác -->
  <button class="btn" onclick="showPhoto()">Xem ảnh bất ngờ</button>

  <!-- Hiển thị ảnh -->
  <img id="birthdayPhoto" class="photo" src="BC67AF6F-248B-4C65-8E60-8A80DC7F936D.jpeg" alt="Ảnh Chúc Mừng Sinh Nhật">

  <script>
    // Hàm hiển thị ảnh khi nhấn nút
    function showPhoto() {
      const photo = document.getElementById('birthdayPhoto');
      photo.style.display = 'block';
    }
  </script>
</body>
</html>
