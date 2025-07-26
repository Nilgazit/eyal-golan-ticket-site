<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>הופעה של אייל גולן - רכישת כרטיסים</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>הופעה של אייל גולן</h1>
  <div class="event-details">
    <p><strong>מתי:</strong> יום ראשון, 27 ביולי 2025</p>
    <p><strong>שעה:</strong> 22:30</p>
    <p><strong>איפה:</strong> Rodous Palace Club</p>
    <p><strong>מחיר:</strong> ₪150</p>
    <button onclick="showForm()">קנה כרטיס</button>
  </div>

  <div id="form-section">
    <h2>פרטי קונה</h2>
    <input type="text" id="name" placeholder="שם מלא" /><br />
    <input type="email" id="email" placeholder="אימייל" /><br />
    <button onclick="simulatePayment()">לתשלום</button>
    <p id="confirmation" style="color: green; display: none;">
      התשלום התקבל! הכרטיס נשלח לאימייל 🎫
    </p>
  </div>

  <script src="script.js"></script>
</body>
</html>git clone https://github.com/Nilgazit/eyal-golan-ticket-site.git
cd eyal-golan-ticket-site# eyal-golan-ticket-site
מופע של אייל גולן ברודוס
