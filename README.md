<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>أردن العز للتخليص الجمركي</title>
  <meta name="description" content="أردن العز للتخليص - خدمات تخليص جمركي ونقل ومعاملات جمركية باحترافية.">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Tahoma, Arial, sans-serif;
      background: #f7f7f7;
      color: #222;
      line-height: 1.7;
    }
    header {
      background: #111;
      color: white;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 10px rgba(0,0,0,.15);
    }
    .nav {
      max-width: 1150px;
      margin: auto;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }
    .logo {
      font-size: 23px;
      font-weight: bold;
    }
    .logo span {
      color: #d4af37;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 15px;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #d4af37;
    }

    /* Hero Section */
    .hero-full {
      position: relative;
      width: 100%;
      min-height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                  url('https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 40px 20px;
    }
    .hero-content {
      max-width: 800px;
      z-index: 2;
    }
    .hero-content h1 {
      font-size: clamp(32px, 5vw, 56px);
      margin-bottom: 20px;
    }
    .hero-content h1 span {
      color: #d4af37;
    }
    .hero-content p {
      font-size: clamp(16px, 2vw, 22px);
      margin-bottom: 30px;
      color: #ddd;
    }

    .buttons {
      display: flex;
      gap: 15px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .btn {
      display: inline-block;
      padding: 12px 30px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s ease;
    }
    .btn-primary {
      background: #d4af37;
      color: #111;
    }
    .btn-primary:hover {
      background: #f0ce55;
      transform: translateY(-2px);
    }
    .btn-dark {
      border: 1px solid #fff;
      color: #fff;
    }
    .btn-dark:hover {
      background: white;
      color: #111;
    }

    /* Services Section */
    .services-modern {
      background: linear-gradient(180deg, #f8f8f8 0%, #eeeeee 100%);
      padding: 80px 20px;
    }
    .services-wrap {
      max-width: 1150px;
      margin: auto;
    }
    .services-heading {
      text-align: center;
      margin-bottom: 45px;
    }
    .services-heading > span {
      display: inline-block;
      color: #a98416;
      font-weight: bold;
      font-size: 16px;
      margin-bottom: 8px;
    }
    .services-heading h2 {
      font-size: clamp(28px, 4vw, 40px);
      margin-bottom: 10px;
    }
    .services-heading p {
      color: #666;
      font-size: 17px;
    }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 25px;
    }
    .service-card {
      position: relative;
      background: white;
      border-radius: 16px;
      padding: 30px 25px;
      border: 1px solid #e4e4e4;
      box-shadow: 0 10px 25px rgba(0,0,0,.05);
      transition: transform .25s ease, box-shadow .25s ease;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .service-card::before {
      content: "";
      position: absolute;
      top: 0;
      right: 0;
      width: 100%;
      height: 5px;
      background: #d4af37;
      border-radius: 16px 16px 0 0;
    }
    .service-card:hover {
      transform: translateY(-7px);
      box-shadow: 0 18px 35px rgba(0,0,0,.12);
    }
    .service-icon {
      width: 58px;
      height: 58px;
      border-radius: 16px;
      background: #f5e7ad;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 28px;
      margin-bottom: 18px;
    }
    .service-card h3 {
      font-size: 22px;
      margin-bottom: 10px;
    }
    .service-card p {
      color: #666;
      font-size: 15px;
      line-height: 1.8;
      margin-bottom: 20px;
    }
    .service-actions {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }
    .service-file-btn {
      flex: 1 1 120px;
      padding: 10px 12px;
      border-radius: 8px;
      text-decoration: none;
      text-align: center;
      font-weight: bold;
      font-size: 14px;
      transition: .2s ease;
    }
    .service-file-btn.primary {
      background: #d4af37;
      color: #111;
    }
    .service-file-btn.secondary {
      background: #111;
      color: white;
    }

    /* About Section */
    .about {
      background: #111;
      color: white;
      padding: 70px 20px;
    }
    .about-wrap {
      max-width: 1150px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 35px;
      align-items: center;
    }
    .about p {
      color: #ddd;
      font-size: 17px;
      margin-top: 15px;
    }
    .badge {
      background: #d4af37;
      color: #111;
      border-radius: 15px;
      padding: 35px;
      text-align: center;
      font-size: 24px;
      font-weight: bold;
    }

    /* Contact & Footer */
    .contact-section {
      padding: 70px 20px;
      text-align: center;
    }
    .contact-box {
      max-width: 600px;
      margin: auto;
      background: white;
      padding: 35px;
      border-radius: 15px;
      box-shadow: 0 5px 22px rgba(0,0,0,.07);
    }
    footer {
      background: #0a0a0a;
      color: #aaa;
      text-align: center;
      padding: 25px 15px;
      font-size: 14px;
    }
    .whatsapp {
      position: fixed;
      left: 20px;
      bottom: 20px;
      width: 58px;
      height: 58px;
      border-radius: 50%;
      background: #25d366;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      text-decoration: none;
      box-shadow: 0 5px 18px rgba(0,0,0,.25);
      z-index: 1000;
    }

    @media (max-width: 768px) {
      nav { display: none; }
      .hero-full { min-height: 60vh; }
    }
  </style>
</head>
<body>

<header>
  <div class="nav">
    <div class="logo">أردن <span>العز</span> للتخليص</div>
    <nav>
      <a href="#home">الرئيسية</a>
      <a href="#services">الخدمات</a>
      <a href="#about">من نحن</a>
      <a href="#contact">اتصل بنا</a>
    </nav>
  </div>
</header>

<main>
  <!-- Hero Section -->
  <section class="hero-full" id="home">
    <div class="hero-content">
      <h1>أردن <span>العز</span> للتخليص الجمركي ونقل البضائع</h1>
      <p>نقدم لك أفضل الحلول الجمركية السريعة والآمنة لتسهيل استيراد وتصدير شحناتك باحترافية عالية.</p>
      <div class="buttons">
        <a href="#services" class="btn btn-primary">خدماتنا</a>
        <a href="#contact" class="btn btn-dark">تواصل معنا</a>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section class="services-modern" id="services">
    <div class="services-wrap">
      <div class="services-heading">
        <span>خدماتنا المتميزة</span>
        <h2>حلول تخليص جمركي شاملة</h2>
        <p>نرافق شحنتك خطوة بخطوة لضمان وصولها بكل سرعة وأمان</p>
      </div>

      <div class="services-grid">
        <!-- Service 1 -->
        <div class="service-card">
          <div>
            <div class="service-icon">📦</div>
            <h3>التخليص الجمركي</h3>
            <p>إنجاز كافة المعاملات والمستندات الجمركية للبضائع الواردة والصادرة عبر جميع المنافذ.</p>
          </div>
          <div class="service-actions">
            <a href="#contact" class="service-file-btn primary">طلب الخدمة</a>
            <a href="#contact" class="service-file-btn secondary">استفسار</a>
          </div>
        </div>

        <!-- Service 2 -->
        <div class="service-card">
          <div>
            <div class="service-icon">🚛</div>
            <h3>تخليص الشحنات والنقل</h3>
            <p>تنسيق عمليات شحن ونقل البضائع من الموانئ والمطارات إلى مستودعاتكم مباشرة.</p>
          </div>
          <div class="service-actions">
            <a href="#contact" class="service-file-btn primary">طلب الخدمة</a>
            <a href="#contact" class="service-file-btn secondary">استفسار</a>
          </div>
        </div>

        <!-- Service 3 -->
        <div class="service-card">
          <div>
            <div class="service-icon">📝</div>
            <h3>الاستشارات الجمركية</h3>
            <p>تقديم النصح والحلول التقنية والتعريفات الجمركية لتفادي أي تأخير أو غرامات.</p>
          </div>
          <div class="service-actions">
            <a href="#contact" class="service-file-btn primary">طلب الخدمة</a>
            <a href="#contact" class="service-file-btn secondary">استفسار</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section class="about" id="about">
    <div class="about-wrap">
      <div>
        <h2>من نحن</h2>
        <p>شركة "أردن العز للتخليص الجمركي" هي شريكك الموثوق في خدمات التخليص والنقل البحري والبري والجوّي. نمتلك خبرة واسعة في التعامل مع كافة الإجراءات والقوانين الجمركية لضمان سير أعمالكم بسلاسة ودون معوقات.</p>
      </div>
      <div class="badge">
        خبرة وسرعة في الإنجاز
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="contact-section" id="contact">
    <div class="contact-box">
      <h2>تواصل معنا</h2>
      <p style="margin-top: 10px; color: #555;">يسعدنا تقديم استشاراتنا وتسهيل خدماتكم الجمركية في أي وقت.</p>
      <div class="buttons" style="margin-top: 25px;">
        <a href="https://wa.me/" class="btn btn-primary" target="_blank">محادثة واتساب</a>
      </div>
    </div>
  </section>
</main>

<!-- Floating WhatsApp Button -->
<a href="https://wa.me/" class="whatsapp" target="_blank" title="تواصل عبر الواتساب">💬</a>

<footer>
  <p>جميع الحقوق محفوظة &copy; 2026 أردن العز للتخليص الجمركي</p>
</footer>

</body>
</html>
