<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tỏ tình với trái tim</title>
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #e91e63;
      --secondary-color: #ff80ab;
      --background-gradient: linear-gradient(135deg, #ffe6e6 0%, #ffb3d9 100%);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      text-align: center;
      font-family: 'Dancing Script', cursive;
      background: var(--background-gradient);
      height: 100vh;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      overflow: hidden;
    }

    h1 {
      font-family: 'Dancing Script', cursive;
      color: var(--primary-color);
      font-size: 3.5rem;
      margin-bottom: 2rem;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
      animation: fadeIn 2s ease, float 3s ease-in-out infinite;
    }

    #heart {
      font-size: 7rem;
      color: var(--primary-color);
      animation: heartBeat 1.5s infinite, float 3s ease-in-out infinite;
    }

    #message {
      font-size: 1.5rem;
      color: #333;
      margin-top: 20px;
      font-weight: bold;
      animation: fadeIn 2s ease 1s;
    }

    #buttons {
      margin-top: 20px;
    }

    .button {
      padding: 10px 20px;
      font-size: 1.2rem;
      margin: 10px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    .button:hover {
      transform: scale(1.1);
    }

    .yes {
      background-color: #4CAF50;
      color: white;
    }

    .no {
      background-color: #f44336;
      color: white;
    }

    @keyframes heartBeat {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.2);
      }
    }

    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    @keyframes float {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-20px);
      }
    }

    @keyframes moveButton {
      0% {
        transform: translateX(0);
      }
      20% {
        transform: translateX(50px);
      }
      40% {
        transform: translateX(-50px);
      }
      60% {
        transform: translateX(50px);
      }
      80% {
        transform: translateX(-50px);
      }
      100% {
        transform: translateX(0);
      }
    }
  </style>
</head>
<body>
  <h1>Chúc mừng sinh nhật Mỹ Duyên</h1>

  <div id="buttons">
    <button class="button yes" onclick="showMessage(true)">Đồng ý</button>
    <button class="button no" onclick="moveButton()">Không đồng ý</button>
  </div>

  <div id="heart" style="display: none;">❤️</div>
  <div id="message" style="display: none;">Em có muốn nhận tình yêu của anh không?</div>

  <script>
    function showMessage(yes) {
      const heart = document.getElementById('heart');
      const message = document.getElementById('message');
      const buttons = document.getElementById('buttons');

      if (yes) {
        heart.style.display = 'block';
        message.style.display = 'block';
        buttons.style.display = 'none';
      } else {
        alert("Cảm ơn, hy vọng một ngày nào đó bạn sẽ đồng ý!");
        buttons.style.display = 'none';
      }
    }

    function moveButton() {
      const noButton = document.querySelector('.no');
      noButton.style.animation = 'moveButton 1s ease 5'; // Hiệu ứng di chuyển 5 lần
    }
  </script>
</body>
</html>
