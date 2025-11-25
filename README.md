<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Meal Planner</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Daily Meal Planner</h1>

    <!-- ปุ่มสลับภาษา -->
    <div class="lang-switch">
        <button class="lang-btn" data-lang="th">ไทย</button>
        <button class="lang-btn" data-lang="en">EN</button>
        <button class="lang-btn" data-lang="zh">中文</button>
    </div>
</header>

<main>

    <!-- มื้อเช้า -->
    <section class="meal-section" id="breakfast-section">
        <h2 id="breakfast-title">Breakfast</h2>
        <button class="add-btn" id="add-breakfast">+</button>
        <div class="meal-list" id="breakfast-list"></div>
    </section>

    <!-- มื้อกลางวัน -->
    <section class="meal-section" id="lunch-section">
        <h2 id="lunch-title">Lunch</h2>
        <button class="add-btn" id="add-lunch">+</button>
        <div class="meal-list" id="lunch-list"></div>
    </section>

    <!-- มื้อเย็น -->
    <section class="meal-section" id="dinner-section">
        <h2 id="dinner-title">Dinner</h2>
        <button class="add-btn" id="add-dinner">+</button>
        <div class="meal-list" id="dinner-list"></div>
    </section>

    <!-- ของว่าง -->
    <section class="meal-section" id="snacks-section">
        <h2 id="snacks-title">Snacks</h2>
        <button class="add-btn" id="add-snacks">+</button>
        <div class="meal-list" id="snacks-list"></div>
    </section>

    <!-- สรุปทั้งวัน -->
    <section id="summary">
        <h2 id="summary-title">Daily Summary</h2>
        <p id="total-kcal">Total: 0 kcal</p>
    </section>

</main>

<!-- เชื่อมกับไฟล์ JS -->
<script src="app.js"></script>
</body>
</html>
