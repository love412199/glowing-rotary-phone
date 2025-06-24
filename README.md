<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>慾茶園</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>慾茶園</h1>
    <div class="online">在線人數：<span id="onlineCount">872</span></div>
  </header>

  <section class="filters">
    <input type="text" id="searchName" placeholder="搜尋姓名">
    <select id="filterArea">
      <option value="">地區</option>
      <option value="台北">台北</option>
      <option value="台中">台中</option>
      <option value="高雄">高雄</option>
    </select>
    <select id="filterCup">
      <option value="">罩杯</option>
      <option value="B">B</option>
      <option value="C">C</option>
      <option value="D">D</option>
    </select>
    <!-- 可再擴充更多篩選 -->
    <button onclick="applyFilters()">篩選</button>
  </section>

  <main id="cardContainer">
    <!-- 範例卡片 -->
    <div class="girl-card" data-name="小艾" data-area="台北" data-cup="C">
      <h2>小艾</h2>
      <ul>
        <li>年齡：22</li>
        <li>國籍：台灣</li>
        <li>地區：台北</li>
        <li>罩杯：C</li>
        <li>價格：5000</li>
        <li>身高：162 cm</li>
        <li>體重：48 kg</li>
        <li>LINE：@aixx</li>
        <li>Telegram：@tea_xiaoai</li>
        <li>服務：親切陪聊、深度放鬆</li>
      </ul>
    </div>
  </main>

  <script src="script.js"></script>
</body>
</html>
