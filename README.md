<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>For You ❤️</title>
  <style>
    body {
      background: linear-gradient(to bottom right, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
      color: #fff;
    }

    .card {
      background: rgba(0, 0, 0, 0.25);
      padding: 30px;
      border-radius: 20px;
      max-width: 350px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    }

    .rose {
      font-size: 80px;
      animation: float 2s ease-in-out infinite;
    }

    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    button {
      margin-top: 20px;
      padding: 10px 20px;
      border: none;
      border-radius: 25px;
      background: #ff4d6d;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #ff1f4b;
    }

    .hidden {
      display: none;
      margin-top: 20px;
      font-size: 18px;
    }
  </style>
</head>
<body>

  <div class="card">
    <div class="rose">🌹</div>
    <h1>Happy Rose Day ❤️</h1>
    <p>This rose is for the one who makes my world beautiful.</p>

    <button onclick="showMessage()">Click Me 💌</button>

    <div id="message" class="hidden">
      <p>
        From the moment you came into my life, everything felt brighter.  
        Will you be mine today, tomorrow, and always? 💍❤️
      </p>
      <p><strong>I love you.</strong></p>
    </div>
  </div>

  <script>
    function showMessage() {
      document.getElementById("message").style.display = "block";
    }
  </script>

</body>
</html>
