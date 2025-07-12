<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>灰毛開括者 - 崩鐵角色總覽</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #2e1065, #6b21a8);
      color: #fff;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    header {
      padding: 2em;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2em;
      color: #f3e8ff;
    }
    .card-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2em;
      padding: 2em;
      max-width: 1000px;
    }
    .card {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(6px);
      border-radius: 12px;
      width: 200px;
      padding: 1em;
      text-align: center;
      transition: transform 0.3s;
      box-shadow: 0 0 12px rgba(255, 255, 255, 0.1);
    }
    .card:hover {
      transform: translateY(-8px);
    }
    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 0.5em;
    }
    .card a {
      text-decoration: none;
      color: #d8b4fe;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>灰毛開括者：崩鐵角色總覽</h1>
  </header>

  <div class="card-container">
    <div class="card">
      <a href="huohuo.html">
        <img src="https://uploadstatic-sea.hoyoverse.com/hoyolab-web-upload/3f3852e149cb5469a65b493d707c58d1.png" alt="花火">
        花火
      </a>
    </div>
    <div class="card">
      <a href="liuying.html">
        <img src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2d/Character_Liu_Ying_Icon.png" alt="流螢">
        流螢
      </a>
    </div>
    <!-- 可再加入更多角色卡片 -->
  </div>
</body>
</html>
