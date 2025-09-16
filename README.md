/factory-website
   ├── index.html
   ├── style.css
   ├── script.js
   └── /images
   🔹 index.html
   <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مصنع الإسفنج</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- رأس الموقع -->
  <header>
    <div class="logo">🏭 مصنع الإسفنج</div>
    <nav>
      <ul>
        <li><a href="#home">الرئيسية</a></li>
        <li><a href="#products">المنتجات</a></li>
        <li><a href="#about">من نحن</a></li>
        <li><a href="#contact">اتصل بنا</a></li>
      </ul>
    </nav>
  </header>

  <!-- بانر -->
  <section id="home" class="banner">
    <h1>أهلاً بكم في مصنع الإسفنج</h1>
    <p>جودة عالية – أسعار تنافسية – ثقة دائمة</p>
  </section>

  <!-- المنتجات -->
  <section id="products" class="products">
    <h2>منتجاتنا</h2>
    <div class="product-list">
      <div class="product">
        <img src="images/sponge1.jpg" alt="إسفنج 1">
        <h3>إسفنج مراتب</h3>
      </div>
      <div class="product">
        <img src="images/sponge2.jpg" alt="إسفنج 2">
        <h3>إسفنج أثاث</h3>
      </div>
      <div class="product">
        <img src="images/sponge3.jpg" alt="إسفنج 3">
        <h3>إسفنج تغليف</h3>
      </div>
    </div>
  </section>

  <!-- من نحن -->
  <section id="about" class="about">
    <h2>من نحن</h2>
    <p>نحن مصنع متخصص في صناعة جميع أنواع الإسفنج، نسعى لتقديم أفضل جودة لعملائنا الكرام مع التزامنا بالابتكار والتطوير المستمر.</p>
  </section>

  <!-- اتصل بنا -->
  <section id="contact" class="contact">
    <h2>اتصل بنا</h2>
    <p>📍 نواكشوط - موريتانيا</p>
    <p>📞 222-XXXXXXX</p>
    <p>✉️ info@factory.com</p>
  </section>

  <!-- الفوتر -->
  <footer>
    <p>جميع الحقوق محفوظة © مصنع الإسفنج 2025</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
🔹 style.css
body {
  margin: 0;
  font-family: "Tahoma", sans-serif;
  line-height: 1.6;
}

header {
  background: #0066cc;
  color: #fff;
  display: flex;
  justify-content: space-between;
  padding: 15px 30px;
  align-items: center;
}
header .logo {
  font-weight: bold;
  font-size: 20px;
}
header ul {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
}
header ul li {
  margin: 0 10px;
}
header ul li a {
  color: white;
  text-decoration: none;
}

.banner {
  background: url("images/factory-banner.jpg") no-repeat center center/cover;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.products {
  padding: 40px;
  text-align: center;
}
.product-list {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}
.product img {
  width: 200px;
  height: 150px;
  object-fit: cover;
  border-radius: 8px;
}

.about, .contact {
  padding: 40px;
  background: #f4f4f4;
  text-align: center;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 10px;
}
🔹 script.js
document.addEventListener("DOMContentLoaded", () => {
  console.log("الموقع يعمل بنجاح!");
});
