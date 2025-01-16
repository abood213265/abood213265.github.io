<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقعي الشخصي</title>
  <style>
    /* تعيين إعدادات أساسية */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      direction: rtl;
      background-color: #ffffff;
      color: #200303;
    }

    /* تصميم الهيدر */
    header {
      background-color: #000000;
      color: rgb(255, 255, 255);
      padding: 10px 0;
    }

    nav ul {
      list-style-type: none;
      text-align: center;
    }

    nav ul li {
      display: inline;
      margin: 0 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 18px;
    }

    /* تصميم الأقسام */
    section {
      padding: 40px 0;
    }

    section h2 {
      font-size: 28px;
      margin-bottom: 20px;
    }

    section p {
      font-size: 18px;
      line-height: 1.6;
    }

    .container {
      width: 80%;
      margin: 0 auto;
    }

    /* تصميم الفوتر */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 0;
      position: fixed;
      width: 100%;
      bottom: 0;
    }

    /* تحسين تنسيق النصوص */
    ul {
      list-style-type: none;
    }

    ul li {
      font-size: 18px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <!-- الهيدر -->
  <header>
    <nav>
      <ul>
        <li><a href="#home">الرئيسية</a></li>
        <li><a href="#about">عنّي</a></li>
        <li><a href="#services">الخدمات</a></li>
        <li><a href="#contact">اتصل بي</a></li>
      </ul>
    </nav>
  </header>

  <!-- القسم الأول - المقدمة -->
  <section id="home">
    <div class="container">
      <h1>أهلاً وسهلاً في موقع seyfo.com!</h1>
      <p>هنا سترى كل ما يخص سيفو سحنين</p>
    </div>
  </section>

  <!-- القسم الثاني - عنّي -->
  <section id="about">
    <div class="container">
      <h2>عنّي</h2>
      <p>انا سيفو انسان عطاي و نقش واحب الزب .</p>
    </div>
  </section>

  <!-- القسم الثالث - الخدمات -->
  <section id="services">
    <div class="container">
      <h2>الخدمات</h2>
      <ul>
        <li>ضرب البيبا</li>
        <li>اعطائك النيك </li>
        <li>خبير في لحس الزب</li>
      </ul>
    </div>
  </section>

  <!-- القسم الرابع - الاتصال -->
  <section id="contact">
    <div class="container">
      <h2>اتصل بي</h2>
      <p>يمكنك الاتصال بي عبر الانستا غرام أو عبر الهاتف.</p>
      <ul>
        <li>انستا <a href="https://www.instagram.com/sifsaife?igsh=MTNqZDVsczA3ejg3Mw==">زيارة انستا Example</a>
        </li>
        <li>الهاتف: 0541944897</li>
      </ul>
    </div>
  </section>

  <!-- الفوتر -->
  <footer>
    <p>&copy; 2025 موقعي الشخصي. جميع الحقوق محفوظة.</p>
  </footer>
</body>
</html>
