# game-water123
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>น้ำใส123!หยุด</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      text-align: center;
    }
    .game-container {
      margin-top: 50px;
    }
    .btn-start {
      padding: 10px 20px;
      font-size: 18px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <h1>น้ำใส123!หยุด</h1>
  <div class="game-container">
    <button class="btn-start" onclick="startGame()">เริ่มเกม</button>
    <p id="game-status">รอเริ่มเกม...</p>
  </div>

  <script>
    function startGame() {
      document.getElementById('game-status').innerHTML = "เริ่มเกม! พยายามหยุดตามเวลานะ!";
      // เริ่มเกมจริงๆ ที่นี่
    }
  </script>

</body>
</html>