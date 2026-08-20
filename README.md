<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>ترف العود | فخامة العود</title>

  <meta name="description" content="ترف العود — عود فاخر ومعمول دوسري. اختر منتجك وأرسل طلبك مباشرة عبر واتساب.">
  <meta name="theme-color" content="#0b0907">

  <meta property="og:title" content="ترف العود | فخامة العود">
  <meta property="og:description" content="يامرحبا ترحيبة كلها أطياب — أحلى من العنبر وأزكى من العود 🤍🤍">
  <meta property="og:type" content="website">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700;800&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --black: #090705;
      --dark: #110d09;
      --card: #18120d;
      --card-2: #201811;
      --gold: #c9a15d;
      --gold-light: #f0d69e;
      --cream: #f8f0e3;
      --muted: #a99b8a;
      --border: rgba(240,214,158,.15);
      --green: #25D366;
      --radius: 24px;
      --shadow: 0 25px 70px rgba(0,0,0,.45);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background:
        radial-gradient(circle at 10% 0%, rgba(114,78,38,.20), transparent 30%),
        radial-gradient(circle at 90% 10%, rgba(94,62,29,.16), transparent 28%),
        var(--black);
      color: var(--cream);
      font-family: "Cairo", sans-serif;
      line-height: 1.7;
    }

    body.no-scroll {
      overflow: hidden;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    button,
    input,
    select {
      font-family: inherit;
    }

    button {
      cursor: pointer;
    }

    .container {
      width: min(1180px, calc(100% - 30px));
      margin: auto;
    }

    /* TOP BAR */

    .top-bar {
      text-align: center;
      padding: 8px 12px;
      font-size: 12px;
      color: var(--gold-light);
      background: #070503;
      border-bottom: 1px solid var(--border);
    }

    /* HEADER */

    header {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(9,7,5,.86);
      backdrop-filter: blur(18px);
      border-bottom: 1px solid var(--border);
    }

    .nav {
      height: 76px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 12px;
      font-size: 21px;
      font-weight: 800;
      white-space: nowrap;
    }

    .logo-icon {
      width: 43px;
      height: 43px;
      border: 1px solid var(--gold);
      border-radius: 50%;
      display: grid;
      place-items: center;
      color: var(--gold-light);
      font-family: "Playfair Display", serif;
      box-shadow: inset 0 0 20px rgba(201,161,93,.08);
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 28px;
      color: #cfc1b1;
      font-size: 14px;
    }

    .nav-links a {
      transition: .2s;
    }

    .nav-links a:hover {
      color: var(--gold-light);
    }

    .nav-order {
      border: 1px solid var(--border);
      background: var(--card);
      color: var(--cream);
      border-radius: 13px;
      padding: 9px 15px;
      font-weight: 700;
    }

    /* HERO */

    .hero {
      min-height: 680px;
      display: flex;
      align-items: center;
      padding: 70px 0;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 55px;
      align-items: center;
    }

    .eyebrow {
      color: var(--gold-light);
      font-size: 14px;
      font-weight: 700;
      letter-spacing: .3px;
    }

    .hero h1 {
      margin: 12px 0 20px;
      font-family: "Playfair Display", serif;
      font-size: clamp(48px, 7vw, 82px);
      line-height: 1.05;
      font-weight: 700;
    }

    .hero h1 span {
      color: var(--gold-light);
    }

    .hero-message {
      font-size: 19px;
      color: #ddd0bf;
      max-width: 600px;
      line-height: 2;
    }

    .hero-sub {
      margin-top: 12px;
      color: var(--muted);
      font-size: 13px;
      max-width: 600px;
    }

    .hero-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 30px;
    }

    .btn {
      border: 0;
      border-radius: 15px;
      padding: 13px 21px;
      font-weight: 800;
      transition: .25s;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    .btn-gold {
      background: linear-gradient(135deg, #f0d69e, #a87938);
      color: #17100a;
      box-shadow: 0 14px 35px rgba(201,161,93,.18);
    }

    .btn-dark {
      background: var(--card);
      border: 1px solid var(--border);
      color: var(--cream);
    }

    .hero-visual {
      height: 520px;
      border: 1px solid var(--border);
      border-radius: 35px;
      overflow: hidden;
      position: relative;
      background:
        linear-gradient(180deg, transparent 25%, rgba(0,0,0,.9)),
        url("https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=1400&q=90")
        center / cover;
      box-shadow: var(--shadow);
    }

    .hero-visual::after {
      content: "";
      position: absolute;
      inset: 15px;
      border: 1px solid rgba(240,214,158,.18);
      border-radius: 25px;
      pointer-events: none;
    }

    .hero-label {
      position: absolute;
      right: 25px;
      left: 25px;
      bottom: 25px;
      z-index: 2;
      padding: 18px;
      border-radius: 19px;
      background: rgba(10,7,5,.70);
      backdrop-filter: blur(12px);
      border: 1px solid var(--border);
    }

    .hero-label strong {
      display: block;
      font-size: 19px;
    }

    .hero-label span {
      color: var(--muted);
      font-size: 12px;
    }

    /* SECTION */

    section {
      padding: 75px 0;
    }

    .section-head {
      display: flex;
      justify-content: space-between;
      align-items: end;
      gap: 20px;
      margin-bottom: 28px;
    }

    .section-head h2 {
      font-size: 32px;
      margin-bottom: 4px;
    }

    .section-head p {
      color: var(--muted);
      font-size: 13px;
    }

    /* PRODUCTS */

    .products {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 18px;
    }

    .product {
      overflow: hidden;
      border: 1px solid var(--border);
      border-radius: var(--radius);
      background: linear-gradient(180deg, var(--card-2), var(--card));
      transition: .3s;
    }

    .product:hover {
      transform: translateY(-6px);
      border-color: rgba(240,214,158,.35);
      box-shadow: 0 18px 50px rgba(0,0,0,.30);
    }

    .product-image {
      height: 255px;
      overflow: hidden;
      position: relative;
      background: #241a12;
    }

    .product-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      transition: .5s;
    }

    .product:hover .product-image img {
      transform: scale(1.06);
    }

    .sale {
      position: absolute;
      top: 13px;
      right: 13px;
      z-index: 2;
      background: var(--gold-light);
      color: #181109;
      border-radius: 50px;
      padding: 5px 10px;
      font-size: 11px;
      font-weight: 800;
    }

    .product-info {
      padding: 17px;
    }

    .product-info h3 {
      font-size: 18px;
      margin-bottom: 5px;
    }

    .product-description {
      color: var(--muted);
      font-size: 12px;
      min-height: 45px;
    }

    .price {
      display: flex;
      align-items: center;
      gap: 9px;
      margin: 13px 0;
    }

    .old-price {
      color: #756b61;
      font-size: 13px;
      text-decoration: line-through;
    }

    .new-price {
      color: var(--gold-light);
      font-size: 23px;
      font-weight: 800;
    }

    .currency {
      color: var(--muted);
      font-size: 11px;
    }

    .product-button {
      width: 100%;
    }

    /* OFFER */

    .offer {
      padding-top: 10px;
    }

    .offer-box {
      border: 1px solid var(--border);
      border-radius: 30px;
      padding: 28px;
      background:
        radial-gradient(circle at 15% 50%, rgba(201,161,93,.16), transparent 35%),
        linear-gradient(135deg, #271c13, #120d09);
      display: grid;
      grid-template-columns: 1fr auto;
      align-items: center;
      gap: 25px;
    }

    .offer-box h3 {
      font-size: 25px;
      margin-bottom: 5px;
    }

    .offer-box p {
      color: var(--muted);
      font-size: 13px;
    }

    .timer {
      display: flex;
      gap: 8px;
    }

    .timer-item {
      min-width: 67px;
      text-align: center;
      background: #0c0907;
      border: 1px solid var(--border);
      border-radius: 14px;
      padding: 8px;
    }

    .timer-item strong {
      display: block;
      color: var(--gold-light);
      font-size: 22px;
    }

    .timer-item small {
      color: var(--muted);
      font-size: 10px;
    }

    /* FEATURES */

    .features {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 17px;
    }

    .feature {
      padding: 25px;
      border: 1px solid var(--border);
      background: var(--card);
      border-radius: 21px;
    }

    .feature-icon {
      font-size: 26px;
    }

    .feature h3 {
      margin: 10px 0 4px;
    }

    .feature p {
      color: var(--muted);
      font-size: 13px;
      line-height: 1.9;
    }

    /* QUOTE */

    .quote {
      text-align: center;
      padding: 42px 20px;
      border: 1px solid var(--border);
      border-radius: 30px;
      background: radial-gradient(circle, #2b1e13, #100c09);
    }

    .quote p {
      font-family: "Playfair Display", serif;
      font-size: 27px;
      line-height: 1.8;
    }

    .quote small {
      color: var(--muted);
    }

    /* FOOTER */

    footer {
      padding: 45px 0 100px;
      border-top: 1px solid var(--border);
      color: var(--muted);
    }

    .footer-grid {
      display: grid;
      grid-template-columns: 1.4fr 1fr 1fr;
      gap: 35px;
    }

    .footer-title {
      color: var(--cream);
      font-weight: 800;
      margin-bottom: 10px;
    }

    .footer-links {
      display: grid;
      gap: 7px;
      font-size: 13px;
    }

    /* WHATSAPP */

    .whatsapp {
      position: fixed;
      left: 18px;
      bottom: 18px;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      background: var(--green);
      color: white;
      display: grid;
      place-items: center;
      z-index: 90;
      font-size: 27px;
      box-shadow: 0 12px 35px rgba(37,211,102,.28);
      transition: .2s;
    }

    .whatsapp:hover {
      transform: scale(1.06);
    }

    /* MODAL */

    .modal {
      position: fixed;
      inset: 0;
      z-index: 200;
      background: rgba(0,0,0,.75);
      backdrop-filter: blur(10px);
      display: none;
      align-items: end;
      justify-content: center;
      padding: 15px;
    }

    .modal.active {
      display: flex;
    }

    .modal-content {
      width: min(620px, 100%);
      max-height: 93vh;
      overflow: auto;
      background: #17110d;
      border: 1px solid var(--border);
      border-radius: 28px;
      padding: 23px;
      box-shadow: var(--shadow);
    }

    .modal-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .close {
      width: 40px;
      height: 40px;
      border-radius: 12px;
      border: 1px solid var(--border);
      background: #241a13;
      color: white;
      font-size: 20px;
    }

    .form {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 13px;
      margin-top: 20px;
    }

    .field {
      display: grid;
      gap: 6px;
    }

    .field.full {
      grid-column: 1 / -1;
    }

    .field label {
      font-size: 12px;
      color: var(--muted);
    }

    .field input,
    .field select {
      width: 100%;
      background: #0d0907;
      color: var(--cream);
      border: 1px solid var(--border);
      border-radius: 13px;
      padding: 12px;
      outline: none;
    }

    .field input:focus,
    .field select:focus {
      border-color: var(--gold);
    }

    .summary {
      margin-top: 18px;
      padding: 15px;
      border-radius: 16px;
      background: #0d0907;
      border: 1px solid var(--border);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .summary strong {
      color: var(--gold-light);
      font-size: 22px;
    }

    .note {
      margin-top: 10px;
      color: #817568;
      font-size: 11px;
      line-height: 1.8;
    }

    /* RESPONSIVE */

    @media (max-width: 950px) {
      .hero-grid {
        grid-template-columns: 1fr;
      }

      .hero-visual {
        height: 430px;
      }

      .products {
        grid-template-columns: repeat(2, 1fr);
      }

      .nav-links {
        display: none;
      }
    }

    @media (max-width: 620px) {
      .container {
        width: min(100% - 20px, 1180px);
      }

      .nav {
        height: 67px;
      }

      .logo {
        font-size: 18px;
      }

      .logo-icon {
        width: 39px;
        height: 39px;
      }

      .nav-order {
        padding: 8px 11px;
        font-size: 12px;
      }

      .hero {
        padding: 48px 0 35px;
        min-height: auto;
      }

      .hero h1 {
        font-size: 50px;
      }

      .hero-message {
        font-size: 15px;
      }

      .hero-visual {
        height: 330px;
      }

      section {
        padding: 48px 0;
      }

      .products {
        grid-template-columns: 1fr 1fr;
        gap: 10px;
      }

      .product-image {
        height: 185px;
      }

      .product-info {
        padding: 12px;
      }

      .product-info h3 {
        font-size: 15px;
      }

      .product-description {
        font-size: 10px;
      }

      .new-price {
        font-size: 19px;
      }

      .offer-box {
        grid-template-columns: 1fr;
        padding: 20px;
      }

      .timer {
        justify-content: center;
      }

      .timer-item {
        min-width: 57px;
      }

      .features {
        grid-template-columns: 1fr;
      }

      .footer-grid {
        grid-template-columns: 1fr;
      }

      .form {
        grid-template-columns: 1fr;
      }

      .field.full {
        grid-column: auto;
      }

      .quote p {
        font-size: 21px;
      }
    }
  </style>
</head>

<body>

  <div class="top-bar">
    شحن داخل المملكة 🇸🇦 &nbsp; • &nbsp; الطلب المباشر عبر واتساب &nbsp; • &nbsp; ترف العود
  </div>

  <header>
    <div class="container nav">

      <a href="#home" class="logo">
        <span class="logo-icon">ت</span>
        <span>ترف العود</span>
      </a>

      <nav class="nav-links">
        <a href="#products">المنتجات</a>
        <a href="#offer">العروض</a>
        <a href="#shipping">الشحن</a>
        <a href="#contact">تواصل</a>
      </nav>

      <button class="nav-order" onclick="openOrder()">
        🛍️ اطلب الآن
      </button>

    </div>
  </header>


  <main id="home">

    <!-- HERO -->

    <section class="hero">
      <div class="container hero-grid">

        <div>

          <div class="eyebrow">
            ترف العود • فخامة بطابع عربي
          </div>

          <h1>
            فخامة<br>
            <span>تُشم.</span>
          </h1>

          <p class="hero-message">
            يامرحبا ترحيبة كلها أطياب —
            أحلى من العنبر وأزكى من العود 🤍🤍
          </p>

          <p class="hero-sub">
            عود مختار بعناية، وأسعار عرض مباشرة.
            اختر منتجك وحدد الكمية ثم أرسل طلبك مباشرة عبر واتساب.
          </p>

          <div class="hero-buttons">

            <a href="#products" class="btn btn-gold">
              اكتشف المنتجات ✦
            </a>

            <a
              href="https://wa.me/966539400955"
              target="_blank"
              rel="noopener"
              class="btn btn-dark"
            >
              تواصل واتساب
            </a>

          </div>

        </div>


        <div class="hero-visual">

          <div class="hero-label">
            <strong>ترف العود</strong>
            <span>رائحة تُعرف قبل أن تُرى.</span>
          </div>

        </div>

      </div>
    </section>


    <!-- PRODUCTS -->

    <section id="products">

      <div class="container">

        <div class="section-head">

          <div>
            <h2>مختاراتنا</h2>
            <p>
              منتجات ترف العود الحالية
            </p>
          </div>

        </div>


        <div class="products">


          <!-- PRODUCT 1 -->

          <article class="product">

            <div class="product-image">

              <span class="sale">
                عرض خاص
              </span>

              <img
                src="https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=1200&q=90"
                alt="دقة مروكي"
                loading="lazy"
              >

            </div>

            <div class="product-info">

              <h3>دقة مروكي</h3>

              <div class="product-description">
                خيار فاخر لمحبي العود بطابع عميق وحضور واضح.
              </div>

              <div class="price">
                <span class="old-price">290 ر.س</span>
                <span class="new-price">160</span>
                <span class="currency">ر.س</span>
              </div>

              <button
                class="btn btn-gold product-button"
                onclick="openOrder('دقة مروكي',160)"
              >
                اطلب الآن
              </button>

            </div>

          </article>


          <!-- PRODUCT 2 -->

          <article class="product">

            <div class="product-image">

              <span class="sale">
                عرض خاص
              </span>

              <img
                src="https://images.unsplash.com/photo-1612196808214-b8e1d6145a8c?auto=format&fit=crop&w=1200&q=90"
                alt="أزرق كلمنتان"
                loading="lazy"
              >

            </div>

            <div class="product-info">

              <h3>أزرق كلمنتان</h3>

              <div class="product-description">
                حضور أنيق ولمسة تليق بالمجالس والمناسبات.
              </div>

              <div class="price">
                <span class="old-price">445 ر.س</span>
                <span class="new-price">160</span>
                <span class="currency">ر.س</span>
              </div>

              <button
                class="btn btn-gold product-button"
                onclick="openOrder('أزرق كلمنتان',160)"
              >
                اطلب الآن
              </button>

            </div>

          </article>


          <!-- PRODUCT 3 -->

          <article class="product">

            <div class="product-image">

              <span class="sale">
                عرض خاص
              </span>

              <img
                src="https://images.unsplash.com/photo-1584302179602-e4c3f0e9e3d3?auto=format&fit=crop&w=1200&q=90"
                alt="مروكي سيوفي"
                loading="lazy"
              >

            </div>

            <div class="product-info">

              <h3>مروكي سيوفي</h3>

              <div class="product-description">
                اختيار بطابع فاخر لمحبي العود المميز.
              </div>

              <div class="price">
                <span class="old-price">250 ر.س</span>
                <span class="new-price">160</span>
                <span class="currency">ر.س</span>
              </div>

              <button
                class="btn btn-gold product-button"
                onclick="openOrder('مروكي سيوفي',160)"
              >
                اطلب الآن
              </button>

            </div>

          </article>


          <!-- PRODUCT 4 -->

          <article class="product">

            <div class="product-image">

              <span class="sale">
                عرض خاص
              </span>

              <img
                src="https://images.unsplash.com/photo-1603905179139-db12ab535e2a?auto=format&fit=crop&w=1200&q=90"
                alt="معمول دوسري 250 جم"
                loading="lazy"
              >

            </div>

            <div class="product-info">

              <h3>معمول دوسري 250 جم</h3>

              <div class="product-description">
                معمول دوسري بوزن 250 جم.
              </div>

              <div class="price">
                <span class="old-price">250 ر.س</span>
                <span class="new-price">40</span>
                <span class="currency">ر.س</span>
              </div>

              <button
                class="btn btn-gold product-button"
                onclick="openOrder('معمول دوسري 250 جم',40)"
              >
                اطلب الآن
              </button>

            </div>

          </article>

        </div>

      </div>

    </section>


    <!-- OFFER -->

    <section id="offer" class="offer">

      <div class="container">

        <div class="offer-box">

          <div>

            <h3>
              ⏳ العرض الحالي
            </h3>

            <p>
              اطلب الآن واستفد من السعر الظاهر في المتجر.
            </p>

          </div>


          <div class="timer">

            <div class="timer-item">
              <strong id="days">00</strong>
              <small>يوم</small>
            </div>

            <div class="timer-item">
              <strong id="hours">00</strong>
              <small>ساعة</small>
            </div>

            <div class="timer-item">
              <strong id="minutes">00</strong>
              <small>دقيقة</small>
            </div>

            <div class="timer-item">
              <strong id="seconds">00</strong>
              <small>ثانية</small>
            </div>

          </div>

        </div>

      </div>

    </section>


    <!-- SHIPPING -->

    <section id="shipping">

      <div class="container">

        <div class="section-head">

          <div>
            <h2>تجربة طلب تليق بك</h2>
            <p>
              بسيطة، سريعة، ومباشرة.
            </p>
          </div>

        </div>


        <div class="features">

          <div class="feature">

            <div class="feature-icon">
              ✦
            </div>

            <h3>
              اختر عطرك
            </h3>

            <p>
              اختر المنتج الذي يناسب ذوقك ثم حدّد الوزن والكمية من نموذج الطلب.
            </p>

          </div>


          <div class="feature">

            <div class="feature-icon">
              🚚
            </div>

            <h3>
              شحن داخل المملكة
            </h3>

            <p>
              تفاصيل الشحن النهائية يتم تأكيدها معك قبل إتمام الطلب.
            </p>

          </div>


          <div class="feature">

            <div class="feature-icon">
              💬
            </div>

            <h3>
              طلب مباشر
            </h3>

            <p>
              لا تحتاج إلى إنشاء حساب. أرسل طلبك مباشرة عبر واتساب.
            </p>

          </div>

        </div>

      </div>

    </section>


    <!-- QUOTE -->

    <section>

      <div class="container">

        <div class="quote">

          <p>
            يامرحبا ترحيبة كلها أطياب<br>
            أحلى من العنبر وأزكى من العود 🤍🤍
          </p>

          <small>
            ترف العود
          </small>

        </div>

      </div>

    </section>

  </main>


  <!-- FOOTER -->

  <footer id="contact">

    <div class="container footer-grid">

      <div>

        <div class="footer-title">
          ترف العود
        </div>

        <p style="font-size:13px;line-height:2">
          فخامة العود تبدأ من الاختيار.
          متجر ترف العود للطلب المباشر.
        </p>

      </div>


      <div>

        <div class="footer-title">
          المتجر
        </div>

        <div class="footer-links">

          <a href="#products">
            المنتجات
          </a>

          <a href="#offer">
            العروض
          </a>

          <a href="#shipping">
            الشحن
          </a>

        </div>

      </div>


      <div>

        <div class="footer-title">
          تواصل معنا
        </div>

        <div class="footer-links">

          <a
            href="https://wa.me/966539400955"
            target="_blank"
            rel="noopener"
          >
            واتساب: 0539400955
          </a>

          <a href="#home">
            العودة للأعلى ↑
          </a>

        </div>

      </div>

    </div>

  </footer>


  <!-- WHATSAPP FLOAT -->

  <a
    class="whatsapp"
    href="https://wa.me/966539400955"
    target="_blank"
    rel="noopener"
    aria-label="التواصل عبر واتساب"
  >
    ☎
  </a>


  <!-- ORDER MODAL -->

  <div
    class="modal"
    id="orderModal"
    onclick="closeFromOutside(event)"
  >

    <div class="modal-content">

      <div class="modal-header">

        <div>

          <div class="eyebrow">
            ترف العود
          </div>

          <h2 id="modalTitle">
            أكمل طلبك
          </h2>

        </div>

        <button
          class="close"
          onclick="closeOrder()"
          aria-label="إغلاق"
        >
          ×
        </button>

      </div>


      <div class="form">

        <div class="field full">

          <label>
            المنتج
          </label>

          <select id="productSelect" onchange="updateProduct()">

            <option value="دقة مروكي|160">
              دقة مروكي — 160 ر.س
            </option>

            <option value="أزرق كلمنتان|160">
              أزرق كلمنتان — 160 ر.س
            </option>

            <option value="مروكي سيوفي|160">
              مروكي سيوفي — 160 ر.س
            </option>

            <option value="معمول دوسري 250 جم|40">
              معمول دوسري 250 جم — 40 ر.س
            </option>

          </select>

        </div>


        <div class="field">

          <label>
            الوزن
          </label>

          <select id="weight">

            <option>
              الوزن الأساسي
            </option>

            <option>
              3 جم
            </option>

            <option>
              6 جم
            </option>

            <option>
              12 جم
            </option>

            <option>
              25 جم
            </option>

            <option>
              50 جم
            </option>

            <option>
              100 جم
            </option>

          </select>

        </div>


        <div class="field">

          <label>
            الكمية
          </label>

          <input
            id="quantity"
            type="number"
            value="1"
            min="1"
            max="99"
            oninput="calculateTotal()"
          >

        </div>


        <div class="field full">

          <label>
            المدينة / الحي — اختياري
          </label>

          <input
            id="location"
            type="text"
            placeholder="مثال: الرياض — شمال الرياض"
          >

        </div>


        <div class="field full">

          <label>
            ملاحظة للطلب — اختياري
          </label>

          <input
            id="note"
            type="text"
            placeholder="اكتب أي ملاحظة هنا"
          >

        </div>

      </div>


      <div class="summary">

        <span>
          الإجمالي المبدئي
        </span>

        <strong id="total">
          160 ر.س
        </strong>

      </div>


      <button
        class="btn btn-gold"
        style="width:100%;margin-top:13px"
        onclick="sendWhatsApp()"
      >
        إرسال الطلب عبر واتساب ↗
      </button>


      <div class="note">
        الأسعار الظاهرة هي أسعار المنتجات المحددة في المتجر.
        أي تفاصيل إضافية للوزن أو الشحن يتم تأكيدها مع العميل عبر واتساب.
      </div>

    </div>

  </div>


  <script>

    /* =========================
       إعدادات المتجر
    ========================= */

    const WHATSAPP_NUMBER = "966539400955";

    let currentPrice = 160;


    /* =========================
       فتح نافذة الطلب
    ========================= */

    function openOrder(product = "دقة مروكي", price = 160) {

      const modal = document.getElementById("orderModal");

      modal.classList.add("active");

      document.body.classList.add("no-scroll");

      const select = document.getElementById("productSelect");

      [...select.options].forEach(option => {

        if (option.value.startsWith(product + "|")) {

          option.selected = true;

        }

      });

      currentPrice = Number(price);

      document.getElementById("modalTitle").textContent =
        "طلب " + product;

      calculateTotal();

    }


    /* =========================
       إغلاق النافذة
    ========================= */

    function closeOrder() {

      document.getElementById("orderModal")
        .classList.remove("active");

      document.body.classList.remove("no-scroll");

    }


    function closeFromOutside(event) {

      if (event.target.id === "orderModal") {

        closeOrder();

      }

    }


    /* =========================
       تحديث المنتج
    ========================= */

    function updateProduct() {

      const value =
        document.getElementById("productSelect").value;

      const [product, price] = value.split("|");

      currentPrice = Number(price);

      document.getElementById("modalTitle").textContent =
        "طلب " + product;

      calculateTotal();

    }


    /* =========================
       حساب السعر
    ========================= */

    function calculateTotal() {

      let quantity =
        Number(document.getElementById("quantity").value) || 1;

      quantity = Math.max(1, Math.min(99, quantity));

      document.getElementById("quantity").value = quantity;

      const total = currentPrice * quantity;

      document.getElementById("total").textContent =
        total.toLocaleString("ar-SA") + " ر.س";

    }


    /* =========================
       إرسال الطلب إلى واتساب
    ========================= */

    function sendWhatsApp() {

      const value =
        document.getElementById("productSelect").value;

      const [product, price] = value.split("|");

      const weight =
        document.getElementById("weight").value;

      const quantity =
        document.getElementById("quantity").value;

      const location =
        document.getElementById("location").value.trim();

      const note =
        document.getElementById("note").value.trim();

      const total =
        Number(price) * Number(quantity || 1);


      let message =
`السلام عليكم ورحمة الله وبركاته 🤍

أرغب بالطلب من متجر ترف العود

🪵 المنتج: ${product}
⚖️ الوزن: ${weight}
🔢 الكمية: ${quantity}
💰 السعر: ${price} ر.س
💵 الإجمالي المبدئي: ${total} ر.س`;


      if (location) {

        message +=
          `\n📍 المدينة / الحي: ${location}`;

      }


      if (note) {

        message +=
          `\n📝 ملاحظتي: ${note}`;

      }


      message +=
`

يامرحبا ترحيبة كلها أطياب
أحلى من العنبر وأزكى من العود 🤍🤍`;


      const url =
        "https://wa.me/" +
        WHATSAPP_NUMBER +
        "?text=" +
        encodeURIComponent(message);


      window.open(url, "_blank");

    }


    /* =========================
       عداد العرض
       48 ساعة من فتح الصفحة
    ========================= */

    const timerKey = "tarafAloudOfferEnd";

    let endTime =
      localStorage.getItem(timerKey);


    if (!endTime || Number(endTime) < Date.now()) {

      endTime =
        Date.now() + (48 * 60 * 60 * 1000);

      localStorage.setItem(
        timerKey,
        endTime
      );

    }


    function updateTimer() {

      let remaining =
        Math.max(0, Number(endTime) - Date.now());


      const days =
        Math.floor(remaining / 86400000);

      remaining %= 86400000;


      const hours =
        Math.floor(remaining / 3600000);

      remaining %= 3600000;


      const minutes =
        Math.floor(remaining / 60000);

      const seconds =
        Math.floor((remaining % 60000) / 1000);


      document.getElementById("days").textContent =
        String(days).padStart(2, "0");

      document.getElementById("hours").textContent =
        String(hours).padStart(2, "0");

      document.getElementById("minutes").textContent =
        String(minutes).padStart(2, "0");

      document.getElementById("seconds").textContent =
        String(seconds).padStart(2, "0");

    }


    updateTimer();

    setInterval(updateTimer, 1000);


    /* =========================
       ESC لإغلاق النافذة
    ========================= */

    document.addEventListener(
      "keydown",
      function(event) {

        if (event.key === "Escape") {

          closeOrder();

        }

      }
    );

  </script>

</body>
</html>
