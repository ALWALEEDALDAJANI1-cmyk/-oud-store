<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0,viewport-fit=cover">

<title>ترف العود | عود يليق بالذوق الرفيع</title>

<meta name="description" content="ترف العود — مختارات من العود والمعمول بأسعار خاصة. اطلب مباشرة عبر واتساب.">
<meta name="theme-color" content="#090806">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700;800&family=IBM+Plex+Sans+Arabic:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

<style>
:root{
  --bg:#080705;
  --bg2:#0e0b08;
  --panel:#15100c;
  --panel2:#1d1510;
  --gold:#c99b54;
  --gold2:#f1d59a;
  --cream:#f8f0e3;
  --muted:#9d8e7c;
  --line:rgba(241,213,154,.13);
  --green:#25d366;
  --danger:#b85c3e;
  --shadow:0 30px 90px rgba(0,0,0,.55);
}

*{box-sizing:border-box;margin:0;padding:0}

html{scroll-behavior:smooth}

body{
  background:
    radial-gradient(circle at 0 0,rgba(144,99,42,.17),transparent 27%),
    radial-gradient(circle at 100% 10%,rgba(107,68,27,.12),transparent 30%),
    var(--bg);
  color:var(--cream);
  font-family:"IBM Plex Sans Arabic","Cairo",sans-serif;
  overflow-x:hidden;
}

body.lock{overflow:hidden}

a{text-decoration:none;color:inherit}

button,input,select{font:inherit}

button{cursor:pointer}

.container{
  width:min(1220px,calc(100% - 32px));
  margin:auto;
}

/* =========================
   announcement
========================= */

.announcement{
  height:35px;
  display:flex;
  align-items:center;
  justify-content:center;
  background:#050403;
  border-bottom:1px solid var(--line);
  color:#d9bd84;
  font-size:11px;
}

/* =========================
   header
========================= */

.header{
  position:sticky;
  top:0;
  z-index:100;
  height:82px;
  background:rgba(8,7,5,.76);
  backdrop-filter:blur(22px);
  border-bottom:1px solid var(--line);
}

.nav{
  height:100%;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:25px;
}

.brand{
  display:flex;
  align-items:center;
  gap:12px;
  font-weight:800;
  font-size:21px;
}

.brand-symbol{
  width:45px;
  height:45px;
  border:1px solid #b98c4a;
  border-radius:50%;
  display:grid;
  place-items:center;
  color:var(--gold2);
  font-family:"Playfair Display",serif;
  font-size:21px;
  box-shadow:inset 0 0 25px rgba(201,155,84,.08);
}

.nav-center{
  display:flex;
  align-items:center;
  gap:31px;
  color:#bfb1a1;
  font-size:13px;
}

.nav-center a{
  position:relative;
  transition:.2s;
}

.nav-center a:hover{color:var(--gold2)}

.nav-center a:after{
  content:"";
  position:absolute;
  right:0;
  bottom:-9px;
  width:0;
  height:1px;
  background:var(--gold2);
  transition:.25s;
}

.nav-center a:hover:after{width:100%}

.nav-actions{
  display:flex;
  gap:9px;
}

.icon-btn{
  width:43px;
  height:43px;
  border-radius:13px;
  border:1px solid var(--line);
  background:#120e0b;
  color:var(--cream);
  display:grid;
  place-items:center;
  transition:.2s;
}

.icon-btn:hover{
  border-color:rgba(241,213,154,.35);
  transform:translateY(-2px);
}

.cart-count{
  position:absolute;
  margin-top:-29px;
  margin-right:-28px;
  background:var(--gold2);
  color:#17100a;
  width:17px;
  height:17px;
  border-radius:50%;
  font-size:9px;
  font-weight:800;
  display:grid;
  place-items:center;
}

/* =========================
   hero
========================= */

.hero{
  min-height:calc(100vh - 117px);
  display:flex;
  align-items:center;
  padding:70px 0 90px;
  position:relative;
}

.hero:before{
  content:"";
  position:absolute;
  width:650px;
  height:650px;
  border-radius:50%;
  background:rgba(159,109,45,.07);
  filter:blur(90px);
  top:-250px;
  right:-180px;
}

.hero-grid{
  display:grid;
  grid-template-columns:.9fr 1.1fr;
  gap:65px;
  align-items:center;
}

.hero-copy{
  position:relative;
  z-index:2;
}

.mini-label{
  display:inline-flex;
  align-items:center;
  gap:8px;
  color:var(--gold2);
  font-size:12px;
  font-weight:700;
  margin-bottom:17px;
}

.mini-label:before{
  content:"";
  width:25px;
  height:1px;
  background:var(--gold);
}

.hero h1{
  font-family:"Playfair Display",serif;
  font-size:clamp(54px,7.5vw,96px);
  line-height:.98;
  letter-spacing:-2px;
  margin-bottom:25px;
}

.hero h1 em{
  color:var(--gold2);
  font-style:normal;
}

.hero-intro{
  max-width:600px;
  color:#d0c2b0;
  font-size:18px;
  line-height:2;
}

.hero-sub{
  color:var(--muted);
  font-size:12px;
  margin-top:12px;
  max-width:560px;
}

.hero-buttons{
  display:flex;
  gap:10px;
  flex-wrap:wrap;
  margin-top:30px;
}

.btn{
  border:0;
  border-radius:14px;
  padding:13px 21px;
  font-weight:800;
  display:inline-flex;
  justify-content:center;
  align-items:center;
  gap:8px;
  transition:.25s;
}

.btn:hover{
  transform:translateY(-3px);
}

.btn-gold{
  color:#171008;
  background:linear-gradient(135deg,#f5daa0,#a97836);
  box-shadow:0 16px 35px rgba(201,155,84,.16);
}

.btn-outline{
  background:#120e0b;
  border:1px solid var(--line);
  color:var(--cream);
}

.hero-note{
  margin-top:22px;
  display:flex;
  align-items:center;
  gap:17px;
  color:#827568;
  font-size:11px;
}

.hero-note span{
  display:flex;
  align-items:center;
  gap:6px;
}

/* hero visual */

.hero-photo{
  height:620px;
  border-radius:40px;
  overflow:hidden;
  position:relative;
  border:1px solid var(--line);
  background:
    linear-gradient(180deg,rgba(0,0,0,.05) 20%,rgba(0,0,0,.9) 100%),
    url("https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=1600&q=92")
    center/cover;
  box-shadow:var(--shadow);
}

.hero-photo:before{
  content:"";
  position:absolute;
  inset:16px;
  border:1px solid rgba(241,213,154,.18);
  border-radius:30px;
}

.hero-photo-text{
  position:absolute;
  bottom:30px;
  right:30px;
  left:30px;
}

.hero-photo-text small{
  color:#d4bd91;
  font-size:11px;
}

.hero-photo-text h2{
  font-family:"Playfair Display",serif;
  font-size:34px;
  margin-top:3px;
}

.hero-photo-text p{
  color:#a99b8b;
  font-size:11px;
}

/* =========================
   ticker
========================= */

.ticker{
  border-top:1px solid var(--line);
  border-bottom:1px solid var(--line);
  overflow:hidden;
  background:#0c0907;
}

.ticker-track{
  display:flex;
  width:max-content;
  animation:ticker 30s linear infinite;
}

.ticker-item{
  padding:16px 35px;
  color:#bda16e;
  font-size:12px;
  white-space:nowrap;
}

.ticker-item b{color:var(--gold2)}

@keyframes ticker{
  from{transform:translateX(0)}
  to{transform:translateX(50%)}
}

/* =========================
   sections
========================= */

.section{
  padding:105px 0;
}

.section-top{
  display:flex;
  justify-content:space-between;
  align-items:end;
  margin-bottom:35px;
  gap:25px;
}

.section-kicker{
  color:var(--gold2);
  font-size:11px;
  font-weight:700;
  letter-spacing:.3px;
  margin-bottom:7px;
}

.section-title{
  font-size:38px;
  line-height:1.25;
}

.section-description{
  color:var(--muted);
  font-size:12px;
  max-width:420px;
  line-height:1.9;
}

/* =========================
   products
========================= */

.product-grid{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:16px;
}

.product{
  background:linear-gradient(180deg,#1a130e,#100c09);
  border:1px solid var(--line);
  border-radius:25px;
  overflow:hidden;
  position:relative;
  transition:.35s;
}

.product:hover{
  transform:translateY(-8px);
  border-color:rgba(241,213,154,.32);
  box-shadow:0 25px 55px rgba(0,0,0,.3);
}

.product-image{
  height:310px;
  overflow:hidden;
  position:relative;
  background:#241910;
}

.product-image img{
  width:100%;
  height:100%;
  object-fit:cover;
  transition:.6s;
}

.product:hover img{transform:scale(1.08)}

.product-badge{
  position:absolute;
  z-index:2;
  top:14px;
  right:14px;
  padding:6px 10px;
  border-radius:50px;
  background:#eed299;
  color:#171009;
  font-size:9px;
  font-weight:800;
}

.product-number{
  position:absolute;
  left:15px;
  top:15px;
  color:rgba(255,255,255,.5);
  font-family:"Playfair Display",serif;
  font-size:14px;
}

.product-body{
  padding:19px;
}

.product-body h3{
  font-size:18px;
  margin-bottom:6px;
}

.product-subtitle{
  min-height:45px;
  color:#8f8172;
  font-size:11px;
  line-height:1.8;
}

.product-price{
  display:flex;
  align-items:baseline;
  gap:9px;
  margin:15px 0;
}

.old{
  color:#665e56;
  font-size:12px;
  text-decoration:line-through;
}

.price{
  color:var(--gold2);
  font-size:25px;
  font-weight:800;
}

.sar{
  color:#887a6b;
  font-size:10px;
}

.product-actions{
  display:grid;
  grid-template-columns:1fr 43px;
  gap:8px;
}

.product-actions .btn{
  width:100%;
}

.quick{
  width:43px;
  border-radius:13px;
  border:1px solid var(--line);
  background:#120d09;
  color:var(--gold2);
}

/* =========================
   offer
========================= */

.offer-section{
  padding-top:0;
}

.offer{
  min-height:300px;
  border-radius:32px;
  overflow:hidden;
  position:relative;
  border:1px solid var(--line);
  background:
    linear-gradient(90deg,rgba(13,9,6,.98),rgba(13,9,6,.72),rgba(13,9,6,.93)),
    url("https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=1600&q=90")
    center/cover;
  display:flex;
  align-items:center;
}

.offer-content{
  padding:42px;
  max-width:700px;
}

.offer-label{
  color:var(--gold2);
  font-size:11px;
  font-weight:800;
}

.offer h2{
  font-family:"Playfair Display",serif;
  font-size:43px;
  margin:7px 0;
}

.offer p{
  color:#a99b8b;
  font-size:13px;
}

.countdown{
  display:flex;
  gap:7px;
  margin-top:22px;
}

.count{
  min-width:65px;
  padding:8px;
  text-align:center;
  background:rgba(5,4,3,.75);
  border:1px solid var(--line);
  border-radius:12px;
}

.count strong{
  display:block;
  color:var(--gold2);
  font-size:21px;
}

.count span{
  color:#796d61;
  font-size:9px;
}

/* =========================
   brand story
========================= */

.story{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:20px;
}

.story-card{
  min-height:420px;
  border-radius:30px;
  border:1px solid var(--line);
  padding:42px;
  background:linear-gradient(135deg,#1c140e,#0f0b08);
}

.story-card:first-child{
  background:
    linear-gradient(180deg,rgba(9,7,5,.15),rgba(9,7,5,.92)),
    url("https://images.unsplash.com/photo-1603905179139-db12ab535e2a?auto=format&fit=crop&w=1200&q=90")
    center/cover;
}

.story-card h2{
  font-family:"Playfair Display",serif;
  font-size:40px;
  margin-bottom:15px;
}

.story-card p{
  color:#a99b8b;
  font-size:13px;
  line-height:2;
  max-width:520px;
}

.story-list{
  margin-top:28px;
  display:grid;
  gap:13px;
}

.story-list div{
  display:flex;
  gap:12px;
  color:#c9b9a7;
  font-size:12px;
}

.story-list i{
  color:var(--gold2);
  font-style:normal;
}

/* =========================
   trust
========================= */

.trust{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:15px;
}

.trust-card{
  padding:27px;
  border-radius:22px;
  border:1px solid var(--line);
  background:#120e0b;
}

.trust-icon{
  font-size:23px;
  margin-bottom:10px;
}

.trust-card h3{
  font-size:16px;
  margin-bottom:5px;
}

.trust-card p{
  color:#8f8173;
  font-size:11px;
  line-height:1.9;
}

/* =========================
   faq
========================= */

.faq{
  max-width:850px;
  margin:auto;
}

.faq-item{
  border-bottom:1px solid var(--line);
}

.faq-question{
  width:100%;
  border:0;
  background:none;
  color:var(--cream);
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:20px 0;
  text-align:right;
  font-weight:700;
}

.faq-question span{
  color:var(--gold2);
  font-size:20px;
  transition:.2s;
}

.faq-answer{
  display:none;
  color:#918476;
  font-size:12px;
  line-height:2;
  padding:0 0 20px;
}

.faq-item.open .faq-answer{display:block}

.faq-item.open .faq-question span{
  transform:rotate(45deg);
}

/* =========================
   footer
========================= */

.footer{
  border-top:1px solid var(--line);
  padding:55px 0 100px;
}

.footer-grid{
  display:grid;
  grid-template-columns:1.5fr 1fr 1fr;
  gap:35px;
}

.footer-brand{
  font-family:"Playfair Display",serif;
  font-size:29px;
  color:var(--gold2);
}

.footer p{
  margin-top:8px;
  color:#776c61;
  font-size:11px;
  line-height:2;
  max-width:400px;
}

.footer-title{
  color:var(--cream);
  font-size:13px;
  font-weight:800;
  margin-bottom:12px;
}

.footer-links{
  display:grid;
  gap:8px;
  color:#82766a;
  font-size:11px;
}

.footer-links a:hover{color:var(--gold2)}

/* =========================
   whatsapp
========================= */

.whatsapp{
  position:fixed;
  left:18px;
  bottom:18px;
  width:61px;
  height:61px;
  border-radius:50%;
  background:var(--green);
  color:#fff;
  z-index:150;
  display:grid;
  place-items:center;
  font-size:25px;
  box-shadow:0 15px 45px rgba(37,211,102,.28);
  transition:.2s;
}

.whatsapp:hover{
  transform:scale(1.08);
}

/* =========================
   modal
========================= */

.modal{
  position:fixed;
  inset:0;
  z-index:500;
  display:none;
  align-items:flex-end;
  justify-content:center;
  padding:14px;
  background:rgba(0,0,0,.78);
  backdrop-filter:blur(13px);
}

.modal.active{display:flex}

.sheet{
  width:min(650px,100%);
  max-height:94vh;
  overflow:auto;
  border-radius:30px;
  border:1px solid var(--line);
  background:#15100c;
  box-shadow:var(--shadow);
  padding:24px;
  animation:sheet .25s ease;
}

@keyframes sheet{
  from{transform:translateY(30px);opacity:0}
  to{transform:translateY(0);opacity:1}
}

.sheet-head{
  display:flex;
  justify-content:space-between;
  align-items:start;
}

.sheet-kicker{
  color:var(--gold2);
  font-size:10px;
  font-weight:800;
}

.sheet h2{
  font-size:25px;
  margin-top:3px;
}

.close{
  width:40px;
  height:40px;
  border-radius:12px;
  background:#221811;
  color:white;
  border:1px solid var(--line);
  font-size:20px;
}

.form{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:13px;
  margin-top:20px;
}

.field{
  display:grid;
  gap:6px;
}

.full{grid-column:1/-1}

.field label{
  color:#958778;
  font-size:10px;
}

.field input,
.field select{
  width:100%;
  padding:12px;
  color:var(--cream);
  background:#0d0907;
  border:1px solid var(--line);
  border-radius:13px;
  outline:none;
}

.field input:focus,
.field select:focus{
  border-color:#b98a47;
}

.summary{
  margin-top:17px;
  border:1px solid var(--line);
  background:#0c0907;
  border-radius:16px;
  padding:15px;
  display:flex;
  align-items:center;
  justify-content:space-between;
}

.summary span{
  color:#948576;
  font-size:11px;
}

.summary strong{
  color:var(--gold2);
  font-size:23px;
}

.sheet-note{
  color:#6f655b;
  font-size:10px;
  line-height:1.8;
  margin-top:10px;
}

/* =========================
   cart drawer
========================= */

.drawer{
  position:fixed;
  top:0;
  left:0;
  bottom:0;
  width:min(410px,92%);
  background:#110c09;
  border-right:1px solid var(--line);
  z-index:600;
  transform:translateX(-100%);
  transition:.3s;
  box-shadow:30px 0 80px rgba(0,0,0,.4);
  padding:23px;
}

.drawer.active{transform:translateX(0)}

.drawer-head{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding-bottom:18px;
  border-bottom:1px solid var(--line);
}

.drawer-items{
  padding:20px 0;
  color:#a99987;
  font-size:12px;
}

.drawer-empty{
  text-align:center;
  padding:50px 0;
  color:#6e645a;
}

.drawer-overlay{
  position:fixed;
  inset:0;
  background:rgba(0,0,0,.55);
  z-index:550;
  display:none;
}

.drawer-overlay.active{display:block}

.drawer-total{
  border-top:1px solid var(--line);
  padding-top:20px;
}

.drawer-total-row{
  display:flex;
  justify-content:space-between;
  margin-bottom:14px;
}

.drawer-total-row strong{
  color:var(--gold2);
  font-size:21px;
}

/* =========================
   toast
========================= */

.toast{
  position:fixed;
  top:100px;
  right:50%;
  transform:translate(50%,-15px);
  z-index:900;
  background:#efd396;
  color:#171009;
  padding:10px 17px;
  border-radius:50px;
  font-size:11px;
  font-weight:800;
  opacity:0;
  pointer-events:none;
  transition:.25s;
}

.toast.show{
  opacity:1;
  transform:translate(50%,0);
}

/* =========================
   mobile
========================= */

@media(max-width:1000px){

  .hero-grid{
    grid-template-columns:1fr;
  }

  .hero-photo{
    height:480px;
  }

  .product-grid{
    grid-template-columns:repeat(2,1fr);
  }

  .story{
    grid-template-columns:1fr;
  }

}

@media(max-width:700px){

  .container{
    width:calc(100% - 20px);
  }

  .header{
    height:68px;
  }

  .nav-center{
    display:none;
  }

  .brand{
    font-size:18px;
  }

  .brand-symbol{
    width:39px;
    height:39px;
  }

  .hero{
    padding:55px 0;
  }

  .hero h1{
    font-size:58px;
  }

  .hero-intro{
    font-size:15px;
  }

  .hero-photo{
    height:390px;
    border-radius:27px;
  }

  .section{
    padding:70px 0;
  }

  .section-title{
    font-size:29px;
  }

  .section-top{
    display:block;
  }

  .section-description{
    margin-top:8px;
  }

  .product-grid{
    grid-template-columns:1fr 1fr;
    gap:9px;
  }

  .product-image{
    height:190px;
  }

  .product-body{
    padding:13px;
  }

  .product-body h3{
    font-size:14px;
  }

  .product-subtitle{
    font-size:9px;
    min-height:42px;
  }

  .price{
    font-size:19px;
  }

  .old{
    font-size:9px;
  }

  .product-actions{
    grid-template-columns:1fr;
  }

  .quick{
    display:none;
  }

  .offer{
    min-height:400px;
  }

  .offer-content{
    padding:27px;
  }

  .offer h2{
    font-size:34px;
  }

  .count{
    min-width:55px;
  }

  .trust{
    grid-template-columns:1fr;
  }

  .footer-grid{
    grid-template-columns:1fr;
  }

  .form{
    grid-template-columns:1fr;
  }

  .full{
    grid-column:auto;
  }

  .sheet{
    padding:18px;
  }

}

@media(max-width:390px){

  .product-image{
    height:165px;
  }

  .hero h1{
    font-size:51px;
  }

  .hero-buttons .btn{
    width:100%;
  }

  .timer{
    gap:4px;
  }

  .count{
    min-width:49px;
  }

}
</style>
</head>

<body>

<!-- =========================
     TOP
========================= -->

<div class="announcement">
  ✦ ترف العود &nbsp; • &nbsp; شحن داخل المملكة &nbsp; • &nbsp; الطلب المباشر عبر واتساب ✦
</div>


<!-- =========================
     HEADER
========================= -->

<header class="header">

  <div class="container nav">

    <a href="#home" class="brand">
      <span class="brand-symbol">ت</span>
      <span>ترف العود</span>
    </a>

    <nav class="nav-center">
      <a href="#products">المتجر</a>
      <a href="#offer">العروض</a>
      <a href="#story">عن ترف العود</a>
      <a href="#faq">الأسئلة</a>
      <a href="#contact">تواصل</a>
    </nav>

    <div class="nav-actions">

      <button class="icon-btn" onclick="openCart()" aria-label="السلة">
        🛍
        <span class="cart-count" id="cartCount">0</span>
      </button>

    </div>

  </div>

</header>


<main id="home">


<!-- =========================
     HERO
========================= -->

<section class="hero">

  <div class="container hero-grid">

    <div class="hero-copy">

      <div class="mini-label">
        ترف العود
      </div>

      <h1>
        لأن العود<br>
        <em>ترف.</em>
      </h1>

      <p class="hero-intro">
        يامرحبا ترحيبة كلها أطياب —
        أحلى من العنبر وأزكى من العود 🤍🤍
      </p>

      <p class="hero-sub">
        مختارات من العود والمعمول بأسعار خاصة،
        وتجربة طلب مباشرة وسريعة عبر واتساب.
      </p>

      <div class="hero-buttons">

        <a href="#products" class="btn btn-gold">
          اكتشف المختارات ✦
        </a>

        <a
          href="https://wa.me/966539400955"
          target="_blank"
          rel="noopener"
          class="btn btn-outline"
        >
          واتساب مباشر
        </a>

      </div>

      <div class="hero-note">

        <span>✦ أسعار واضحة</span>
        <span>✦ طلب مباشر</span>
        <span>✦ شحن داخل المملكة</span>

      </div>

    </div>


    <div class="hero-photo">

      <div class="hero-photo-text">

        <small>ترف العود</small>

        <h2>
          رائحة تُعرف<br>
          قبل أن تُرى.
        </h2>

        <p>
          اختر عطرك واترك الباقي علينا.
        </p>

      </div>

    </div>

  </div>

</section>


<!-- =========================
     TICKER
========================= -->

<div class="ticker">

  <div class="ticker-track">

    <div class="ticker-item">ترف العود <b>✦</b></div>
    <div class="ticker-item">دقة مروكي <b>160 ر.س</b></div>
    <div class="ticker-item">أزرق كلمنتان <b>160 ر.س</b></div>
    <div class="ticker-item">مروكي سيوفي <b>160 ر.س</b></div>
    <div class="ticker-item">معمول دوسري 250 جم <b>40 ر.س</b></div>
    <div class="ticker-item">يامرحبا ترحيبة كلها أطياب 🤍</div>

    <div class="ticker-item">ترف العود <b>✦</b></div>
    <div class="ticker-item">دقة مروكي <b>160 ر.س</b></div>
    <div class="ticker-item">أزرق كلمنتان <b>160 ر.س</b></div>
    <div class="ticker-item">مروكي سيوفي <b>160 ر.س</b></div>
    <div class="ticker-item">معمول دوسري 250 جم <b>40 ر.س</b></div>

  </div>

</div>


<!-- =========================
     PRODUCTS
========================= -->

<section class="section" id="products">

  <div class="container">

    <div class="section-top">

      <div>

        <div class="section-kicker">
          THE COLLECTION
        </div>

        <h2 class="section-title">
          مختارات ترف العود
        </h2>

      </div>

      <p class="section-description">
        مجموعة المتجر الحالية. اختر منتجك ثم أرسل الطلب
        مباشرة إلى واتساب.
      </p>

    </div>


    <div class="product-grid">


      <!-- 01 -->

      <article class="product">

        <div class="product-image">

          <span class="product-badge">
            عرض خاص
          </span>

          <span class="product-number">
            01
          </span>

          <img
            src="https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=1200&q=92"
            alt="دقة مروكي"
            loading="lazy"
          >

        </div>

        <div class="product-body">

          <h3>دقة مروكي</h3>

          <div class="product-subtitle">
            اختيار فاخر لمحبي حضور العود القوي والأنيق.
          </div>

          <div class="product-price">

            <span class="old">290 ر.س</span>

            <span class="price">160</span>

            <span class="sar">ر.س</span>

          </div>

          <div class="product-actions">

            <button
              class="btn btn-gold"
              onclick="openOrder('دقة مروكي',160)"
            >
              اطلب الآن
            </button>

            <button
              class="quick"
              onclick="quickAdd('دقة مروكي',160)"
              aria-label="إضافة للسلة"
            >
              +
            </button>

          </div>

        </div>

      </article>


      <!-- 02 -->

      <article class="product">

        <div class="product-image">

          <span class="product-badge">
            عرض خاص
          </span>

          <span class="product-number">
            02
          </span>

          <img
            src="https://images.unsplash.com/photo-1612196808214-b8e1d6145a8c?auto=format&fit=crop&w=1200&q=92"
            alt="أزرق كلمنتان"
            loading="lazy"
          >

        </div>

        <div class="product-body">

          <h3>أزرق كلمنتان</h3>

          <div class="product-subtitle">
            حضور مميز بطابع أنيق للمجالس والمناسبات.
          </div>

          <div class="product-price">

            <span class="old">445 ر.س</span>

            <span class="price">160</span>

            <span class="sar">ر.س</span>

          </div>

          <div class="product-actions">

            <button
              class="btn btn-gold"
              onclick="openOrder('أزرق كلمنتان',160)"
            >
              اطلب الآن
            </button>

            <button
              class="quick"
              onclick="quickAdd('أزرق كلمنتان',160)"
              aria-label="إضافة للسلة"
            >
              +
            </button>

          </div>

        </div>

      </article>


      <!-- 03 -->

      <article class="product">

        <div class="product-image">

          <span class="product-badge">
            عرض خاص
          </span>

          <span class="product-number">
            03
          </span>

          <img
            src="https://images.unsplash.com/photo-1584302179602-e4c3f0e9e3d3?auto=format&fit=crop&w=1200&q=92"
            alt="مروكي سيوفي"
            loading="lazy"
          >

        </div>

        <div class="product-body">

          <h3>مروكي سيوفي</h3>

          <div class="product-subtitle">
            اختيار بطابع فاخر لمحبي العود المميز.
          </div>

          <div class="product-price">

            <span class="old">250 ر.س</span>

            <span class="price">160</span>

            <span class="sar">ر.س</span>

          </div>

          <div class="product-actions">

            <button
              class="btn btn-gold"
              onclick="openOrder('مروكي سيوفي',160)"
            >
              اطلب الآن
            </button>

            <button
              class="quick"
              onclick="quickAdd('مروكي سيوفي',160)"
              aria-label="إضافة للسلة"
            >
              +
            </button>

          </div>

        </div>

      </article>


      <!-- 04 -->

      <article class="product">

        <div class="product-image">

          <span class="product-badge">
            عرض خاص
          </span>

          <span class="product-number">
            04
          </span>

          <img
            src="https://images.unsplash.com/photo-1603905179139-db12ab535e2a?auto=format&fit=crop&w=1200&q=92"
            alt="معمول دوسري 250 جم"
            loading="lazy"
          >

        </div>

        <div class="product-body">

          <h3>معمول دوسري 250 جم</h3>

          <div class="product-subtitle">
            معمول دوسري بوزن 250 جم حسب المنتج المحدد.
          </div>

          <div class="product-price">

            <span class="old">250 ر.س</span>

            <span class="price">40</span>

            <span class="sar">ر.س</span>

          </div>

          <div class="product-actions">

            <button
              class="btn btn-gold"
              onclick="openOrder('معمول دوسري 250 جم',40)"
            >
              اطلب الآن
            </button>

            <button
              class="quick"
              onclick="quickAdd('معمول دوسري 250 جم',40)"
              aria-label="إضافة للسلة"
            >
              +
            </button>

          </div>

        </div>

      </article>


    </div>

  </div>

</section>


<!-- =========================
     OFFER
========================= -->

<section class="section offer-section" id="offer">

  <div class="container">

    <div class="offer">

      <div class="offer-content">

        <div class="offer-label">
          عرض ترف العود
        </div>

        <h2>
          لا تخلي العرض يفوتك.
        </h2>

        <p>
          الأسعار الحالية ظاهرة أمام كل منتج.
          أرسل طلبك الآن وسيتم تأكيد التفاصيل عبر واتساب.
        </p>

        <div class="countdown">

          <div class="count">
            <strong id="days">00</strong>
            <span>يوم</span>
          </div>

          <div class="count">
            <strong id="hours">00</strong>
            <span>ساعة</span>
          </div>

          <div class="count">
            <strong id="minutes">00</strong>
            <span>دقيقة</span>
          </div>

          <div class="count">
            <strong id="seconds">00</strong>
            <span>ثانية</span>
          </div>

        </div>

      </div>

    </div>

  </div>

</section>


<!-- =========================
     STORY
========================= -->

<section class="section" id="story">

  <div class="container">

    <div class="section-top">

      <div>

        <div class="section-kicker">
          THE HOUSE
        </div>

        <h2 class="section-title">
          ترف العود
        </h2>

      </div>

      <p class="section-description">
        اسم صُمم ليكون بسيطًا، فاخرًا، وسهل التذكر.
      </p>

    </div>


    <div class="story">

      <div class="story-card">

      </div>


      <div class="story-card">

        <h2>
          العود مو مجرد رائحة.
        </h2>

        <p>
          هو حضور. هو ذكرى. وهو أول شيء يلاحظه الناس
          قبل الكلام وبعد السلام.
        </p>

        <div class="story-list">

          <div>
            <i>✦</i>
            <span>اختيارات واضحة وأسعار مباشرة</span>
          </div>

          <div>
            <i>✦</i>
            <span>طلب سريع من خلال واتساب</span>
          </div>

          <div>
            <i>✦</i>
            <span>تجربة مصممة للجوال أولًا</span>
          </div>

          <div>
            <i>✦</i>
            <span>بدون تقييمات أو ادعاءات غير موثقة</span>
          </div>

        </div>

      </div>

    </div>

  </div>

</section>


<!-- =========================
     TRUST
========================= -->

<section class="section">

  <div class="container">

    <div class="trust">

      <div class="trust-card">

        <div class="trust-icon">
          ✦
        </div>

        <h3>
          اختيارك أولًا
        </h3>

        <p>
          اختر المنتج والكمية التي تناسبك قبل إرسال الطلب.
        </p>

      </div>


      <div class="trust-card">

        <div class="trust-icon">
          💬
        </div>

        <h3>
          واتساب مباشر
        </h3>

        <p>
          طلبك يذهب مباشرة إلى محادثة واتساب بدون خطوات معقدة.
        </p>

      </div>


      <div class="trust-card">

        <div class="trust-icon">
          🚚
        </div>

        <h3>
          شحن داخل المملكة
        </h3>

        <p>
          يتم تأكيد تفاصيل الشحن معك قبل إتمام الطلب.
        </p>

      </div>

    </div>

  </div>

</section>


<!-- =========================
     FAQ
========================= -->

<section class="section" id="faq">

  <div class="container">

    <div class="section-top">

      <div>

        <div class="section-kicker">
          FAQ
        </div>

        <h2 class="section-title">
          الأسئلة الشائعة
        </h2>

      </div>

    </div>


    <div class="faq">


      <div class="faq-item">

        <button class="faq-question" onclick="toggleFaq(this)">
          كيف أطلب؟
          <span>+</span>
        </button>

        <div class="faq-answer">
          اختر المنتج واضغط «اطلب الآن»، ثم حدد الكمية والوزن
          وأرسل الطلب مباشرة عبر واتساب.
        </div>

      </div>


      <div class="faq-item">

        <button class="faq-question" onclick="toggleFaq(this)">
          هل يوجد شحن؟
          <span>+</span>
        </button>

        <div class="faq-answer">
          نعم، المتجر مهيأ للطلب داخل المملكة، ويتم تأكيد تفاصيل
          الشحن النهائية مع العميل عبر واتساب.
        </div>

      </div>


      <div class="faq-item">

        <button class="faq-question" onclick="toggleFaq(this)">
          هل الأسعار الظاهرة نهائية؟
          <span>+</span>
        </button>

        <div class="faq-answer">
          السعر الأساسي هو السعر الظاهر في بطاقة المنتج.
          تفاصيل الوزن والشحن وأي متطلبات إضافية يتم تأكيدها
          قبل إتمام الطلب.
        </div>

      </div>


      <div class="faq-item">

        <button class="faq-question" onclick="toggleFaq(this)">
          كيف أتواصل مع المتجر؟
          <span>+</span>
        </button>

        <div class="faq-answer">
          عن طريق واتساب على الرقم 0539400955.
        </div>

      </div>


    </div>

  </div>

</section>


</main>


<!-- =========================
     FOOTER
========================= -->

<footer class="footer" id="contact">

  <div class="container footer-grid">

    <div>

      <div class="footer-brand">
        ترف العود
      </div>

      <p>
        يامرحبا ترحيبة كلها أطياب —
        أحلى من العنبر وأزكى من العود 🤍🤍
      </p>

    </div>


    <div>

      <div class="footer-title">
        المتجر
      </div>

      <div class="footer-links">

        <a href="#products">المنتجات</a>
        <a href="#offer">العروض</a>
        <a href="#story">عن ترف العود</a>
        <a href="#faq">الأسئلة الشائعة</a>

      </div>

    </div>


    <div>

      <div class="footer-title">
        تواصل
      </div>

      <div class="footer-links">

        <a
          href="https://wa.me/966539400955"
          target="_blank"
          rel="noopener"
        >
          واتساب 0539400955
        </a>

        <a href="#home">
          العودة للأعلى ↑
        </a>

      </div>

    </div>

  </div>

</footer>


<!-- =========================
     WHATSAPP
========================= -->

<a
  class="whatsapp"
  href="https://wa.me/966539400955"
  target="_blank"
  rel="noopener"
  aria-label="واتساب"
>
  ☎
</a>


<!-- =========================
     CART DRAWER
========================= -->

<div
  class="drawer-overlay"
  id="drawerOverlay"
  onclick="closeCart()"
></div>


<aside class="drawer" id="cartDrawer">

  <div class="drawer-head">

    <strong>
      سلة ترف العود
    </strong>

    <button
      class="close"
      onclick="closeCart()"
    >
      ×
    </button>

  </div>


  <div class="drawer-items" id="drawerItems">

    <div class="drawer-empty">
      السلة فارغة حاليًا 🤍
    </div>

  </div>


  <div class="drawer-total">

    <div class="drawer-total-row">

      <span>
        الإجمالي
      </span>

      <strong id="drawerTotal">
        0 ر.س
      </strong>

    </div>

    <button
      class="btn btn-gold"
      style="width:100%"
      onclick="checkoutCart()"
    >
      إتمام الطلب عبر واتساب
    </button>

  </div>

</aside>


<!-- =========================
     ORDER MODAL
========================= -->

<div
  class="modal"
  id="orderModal"
  onclick="outsideModal(event)"
>

  <div class="sheet">

    <div class="sheet-head">

      <div>

        <div class="sheet-kicker">
          ترف العود
        </div>

        <h2 id="modalTitle">
          أكمل طلبك
        </h2>

      </div>

      <button
        class="close"
        onclick="closeOrder()"
      >
        ×
      </button>

    </div>


    <div class="form">

      <div class="field full">

        <label>
          المنتج
        </label>

        <select id="productSelect" onchange="changeProduct()">

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

          <option>الوزن الأساسي</option>
          <option>3 جم</option>
          <option>6 جم</option>
          <option>12 جم</option>
          <option>25 جم</option>
          <option>50 جم</option>
          <option>100 جم</option>

        </select>

      </div>


      <div class="field">

        <label>
          الكمية
        </label>

        <input
          id="quantity"
          type="number"
          min="1"
          max="99"
          value="1"
          oninput="calculate()"
        >

      </div>


      <div class="field full">

        <label>
          المدينة / الحي
        </label>

        <input
          id="location"
          placeholder="مثال: الرياض — شمال الرياض"
        >

      </div>


      <div class="field full">

        <label>
          ملاحظة للطلب
        </label>

        <input
          id="orderNote"
          placeholder="اختياري"
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
      onclick="sendOrder()"
    >
      إرسال الطلب عبر واتساب ↗
    </button>


    <p class="sheet-note">
      ملاحظة: أسعار الأوزان الإضافية غير محددة في بيانات المتجر،
      لذلك لا يتم اختراع سعر لها. السعر الظاهر هو سعر المنتج × الكمية،
      ويتم تأكيد التفاصيل النهائية عبر واتساب.
    </p>

  </div>

</div>


<div class="toast" id="toast">
  تمت الإضافة إلى السلة 🤍
</div>


<script>

/* =========================================
   STORE SETTINGS
========================================= */

const WHATSAPP = "966539400955";

let currentPrice = 160;

let cart = [];


/* =========================================
   ORDER
========================================= */

function openOrder(product="دقة مروكي",price=160){

  const modal =
    document.getElementById("orderModal");

  modal.classList.add("active");

  document.body.classList.add("lock");

  const select =
    document.getElementById("productSelect");

  [...select.options].forEach(option=>{

    if(option.value.startsWith(product+"|")){
      option.selected=true;
    }

  });

  currentPrice=Number(price);

  document.getElementById("modalTitle").textContent=
    "طلب "+product;

  calculate();

}


function closeOrder(){

  document
    .getElementById("orderModal")
    .classList.remove("active");

  document.body.classList.remove("lock");

}


function outsideModal(e){

  if(e.target.id==="orderModal"){
    closeOrder();
  }

}


/* =========================================
   PRODUCT CHANGE
========================================= */

function changeProduct(){

  const value=
    document.getElementById("productSelect").value;

  const parts=value.split("|");

  currentPrice=Number(parts[1]);

  document.getElementById("modalTitle").textContent=
    "طلب "+parts[0];

  calculate();

}


/* =========================================
   CALCULATE
========================================= */

function calculate(){

  let quantity=
    Number(document.getElementById("quantity").value)||1;

  quantity=Math.max(1,Math.min(99,quantity));

  document.getElementById("quantity").value=quantity;

  const total=currentPrice*quantity;

  document.getElementById("total").textContent=
    total.toLocaleString("ar-SA")+" ر.س";

}


/* =========================================
   SEND ORDER
========================================= */

function sendOrder(){

  const value=
    document.getElementById("productSelect").value;

  const parts=value.split("|");

  const product=parts[0];

  const price=Number(parts[1]);

  const weight=
    document.getElementById("weight").value;

  const quantity=
    Number(document.getElementById("quantity").value)||1;

  const location=
    document.getElementById("location").value.trim();

  const note=
    document.getElementById("orderNote").value.trim();

  const total=price*quantity;


  let message=
`السلام عليكم ورحمة الله وبركاته 🤍

أرغب بالطلب من متجر ترف العود.

🪵 المنتج: ${product}
⚖️ الوزن: ${weight}
🔢 الكمية: ${quantity}
💰 السعر: ${price} ر.س
💵 الإجمالي المبدئي: ${total} ر.س`;


  if(location){
    message+=
      `\n📍 المدينة / الحي: ${location}`;
  }


  if(note){
    message+=
      `\n📝 ملاحظة: ${note}`;
  }


  message+=`

يامرحبا ترحيبة كلها أطياب
أحلى من العنبر وأزكى من العود 🤍🤍`;


  const url=
    "https://wa.me/"+WHATSAPP+
    "?text="+encodeURIComponent(message);


  window.open(url,"_blank");

}


/* =========================================
   CART
========================================= */

function quickAdd(product,price){

  const existing=
    cart.find(item=>item.product===product);

  if(existing){
    existing.quantity++;
  }else{
    cart.push({
      product,
      price,
      quantity:1
    });
  }

  updateCart();

  showToast();

}


function updateCart(){

  const count=
    cart.reduce((sum,item)=>sum+item.quantity,0);

  document.getElementById("cartCount").textContent=
    count;


  const container=
    document.getElementById("drawerItems");


  if(cart.length===0){

    container.innerHTML=
      `<div class="drawer-empty">
        السلة فارغة حاليًا 🤍
      </div>`;

  }else{

    container.innerHTML=
      cart.map((item,index)=>`

        <div style="
          padding:13px 0;
          border-bottom:1px solid var(--line);
          display:flex;
          justify-content:space-between;
          gap:12px;
        ">

          <div>

            <strong style="
              color:var(--cream);
              font-size:12px;
            ">
              ${item.product}
            </strong>

            <div style="
              color:#766b60;
              margin-top:4px;
              font-size:10px;
            ">
              ${item.quantity} × ${item.price} ر.س
            </div>

          </div>

          <button
            onclick="removeItem(${index})"
            style="
              background:none;
              border:0;
              color:#98745c;
            "
          >
            حذف
          </button>

        </div>

      `).join("");

  }


  const total=
    cart.reduce(
      (sum,item)=>sum+(item.price*item.quantity),
      0
    );


  document.getElementById("drawerTotal").textContent=
    total.toLocaleString("ar-SA")+" ر.س";

}


function removeItem(index){

  cart.splice(index,1);

  updateCart();

}


function openCart(){

  document
    .getElementById("cartDrawer")
    .classList.add("active");

  document
    .getElementById("drawerOverlay")
    .classList.add("active");

}


function closeCart(){

  document
    .getElementById("cartDrawer")
    .classList.remove("active");

  document
    .getElementById("drawerOverlay")
    .classList.remove("active");

}


function checkoutCart(){

  if(cart.length===0){

    showToast("السلة فارغة");

    return;

  }


  let message=
`السلام عليكم ورحمة الله وبركاته 🤍

أرغب بالطلب من متجر ترف العود:

`;


  cart.forEach((item,index)=>{

    message+=
`${index+1}. ${item.product}
الكمية: ${item.quantity}
السعر: ${item.price} ر.س
الإجمالي: ${item.price*item.quantity} ر.س

`;

  });


  const total=
    cart.reduce(
      (sum,item)=>sum+(item.price*item.quantity),
      0
    );


  message+=
`الإجمالي المبدئي: ${total} ر.س

يامرحبا ترحيبة كلها أطياب
أحلى من العنبر وأزكى من العود 🤍🤍`;


  window.open(
    "https://wa.me/"+WHATSAPP+
    "?text="+encodeURIComponent(message),
    "_blank"
  );

}


/* =========================================
   TOAST
========================================= */

function showToast(text="تمت الإضافة إلى السلة 🤍"){

  const toast=
    document.getElementById("toast");

  toast.textContent=text;

  toast.classList.add("show");

  setTimeout(()=>{
    toast.classList.remove("show");
  },1800);

}


/* =========================================
   FAQ
========================================= */

function toggleFaq(button){

  const item=
    button.parentElement;

  document
    .querySelectorAll(".faq-item")
    .forEach(el=>{

      if(el!==item){
        el.classList.remove("open");
      }

    });

  item.classList.toggle("open");

}


/* =========================================
   COUNTDOWN
   48 HOURS
========================================= */

const timerKey=
  "tarafAloudTimer";

let endTime=
  localStorage.getItem(timerKey);


if(!endTime || Number(endTime)<Date.now()){

  endTime=
    Date.now()+(48*60*60*1000);

  localStorage.setItem(
    timerKey,
    endTime
  );

}


function updateCountdown(){

  let remaining=
    Math.max(
      0,
      Number(endTime)-Date.now()
    );


  const days=
    Math.floor(remaining/86400000);

  remaining%=86400000;


  const hours=
    Math.floor(remaining/3600000);

  remaining%=3600000;


  const minutes=
    Math.floor(remaining/60000);

  const seconds=
    Math.floor(
      (remaining%60000)/1000
    );


  document.getElementById("days").textContent=
    String(days).padStart(2,"0");

  document.getElementById("hours").textContent=
    String(hours).padStart(2,"0");

  document.getElementById("minutes").textContent=
    String(minutes).padStart(2,"0");

  document.getElementById("seconds").textContent=
    String(seconds).padStart(2,"0");

}


updateCountdown();

setInterval(updateCountdown,1000);


/* =========================================
   ESC
========================================= */

document.addEventListener("keydown",e=>{

  if(e.key==="Escape"){

    closeOrder();
    closeCart();

  }

});


/* =========================================
   INIT
========================================= */

updateCart();

</script>

</body>
</html>
