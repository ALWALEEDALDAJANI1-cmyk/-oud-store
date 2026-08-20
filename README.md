# -oud-store
    متجر عود وبخور<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>دار العود | عود وبخور فاخر</title>

<meta name="description"
content="دار العود - متجر متخصص في أجود أنواع العود والبخور والهدايا الفاخرة">

<style>

:root{
--bg:#f7f3ed;
--card:#fff;
--dark:#21150e;
--dark2:#332116;
--gold:#c79a5b;
--gold2:#a9783d;
--text:#281c15;
--muted:#776c64;
--border:#e9dfd3;
--success:#18864b;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
}

html{
scroll-behavior:smooth;
}

body{
font-family:
Tahoma,
Arial,
sans-serif;
background:var(--bg);
color:var(--text);
line-height:1.7;
}

button,
input,
select,
textarea{
font-family:inherit;
}

button{
cursor:pointer;
}

a{
text-decoration:none;
color:inherit;
}


/* TOP BAR */

.topbar{
background:#160d08;
color:#fff;
text-align:center;
font-size:13px;
padding:7px;
}


/* HEADER */

header{
position:sticky;
top:0;
z-index:999;
background:rgba(33,21,14,.97);
color:white;
border-bottom:1px solid rgba(255,255,255,.08);
}

.header-inner{
max-width:1250px;
margin:auto;
padding:15px 20px;
display:flex;
align-items:center;
justify-content:space-between;
gap:20px;
}

.logo{
font-size:24px;
font-weight:bold;
white-space:nowrap;
}

.logo span{
color:var(--gold);
}

nav{
display:flex;
gap:22px;
}

nav a{
font-size:14px;
color:#eee;
transition:.2s;
}

nav a:hover{
color:var(--gold);
}

.header-actions{
display:flex;
gap:8px;
align-items:center;
}

.icon-btn{
background:#38261a;
color:white;
border:1px solid rgba(255,255,255,.1);
width:43px;
height:43px;
border-radius:50%;
font-size:18px;
position:relative;
}

.badge{
position:absolute;
top:-4px;
right:-4px;
background:#c13d2d;
color:white;
width:19px;
height:19px;
font-size:11px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
}


/* HERO */

.hero{
min-height:650px;
background:
linear-gradient(
90deg,
rgba(22,13,8,.97),
rgba(22,13,8,.78),
rgba(22,13,8,.25)
),
url("https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=1800&q=85")
center/cover;

display:flex;
align-items:center;
}

.hero-content{
max-width:1250px;
width:100%;
margin:auto;
padding:70px 20px;
color:white;
}

.hero-small{
color:var(--gold);
font-size:16px;
margin-bottom:10px;
}

.hero h1{
font-size:55px;
line-height:1.2;
max-width:650px;
margin-bottom:20px;
}

.hero p{
max-width:570px;
font-size:18px;
color:#eee;
margin-bottom:30px;
}

.btn{
border:none;
padding:13px 25px;
border-radius:9px;
font-size:15px;
font-weight:bold;
transition:.2s;
display:inline-flex;
align-items:center;
justify-content:center;
gap:8px;
}

.btn-gold{
background:var(--gold);
color:#21150e;
}

.btn-gold:hover{
background:#d9b275;
transform:translateY(-2px);
}

.btn-dark{
background:var(--dark);
color:white;
}

.btn-outline{
border:1px solid var(--gold);
color:var(--gold);
background:transparent;
}


/* FEATURES */

.features{
background:white;
border-bottom:1px solid var(--border);
}

.features-grid{
max-width:1250px;
margin:auto;
padding:30px 20px;
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
}

.feature{
display:flex;
gap:13px;
align-items:center;
}

.feature-icon{
font-size:28px;
}

.feature h4{
font-size:15px;
}

.feature p{
font-size:12px;
color:var(--muted);
}


/* GENERAL */

.container{
max-width:1250px;
margin:auto;
padding:75px 20px;
}

.section-title{
text-align:center;
margin-bottom:40px;
}

.section-title .eyebrow{
color:var(--gold2);
font-weight:bold;
font-size:14px;
}

.section-title h2{
font-size:34px;
margin:6px 0;
}

.section-title p{
color:var(--muted);
}


/* CATEGORIES */

.categories{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:18px;
}

.category{
height:190px;
border-radius:15px;
overflow:hidden;
position:relative;
color:white;
display:flex;
align-items:flex-end;
padding:20px;
background-size:cover;
background-position:center;
}

.category:after{
content:"";
position:absolute;
inset:0;
background:linear-gradient(transparent,rgba(0,0,0,.8));
}

.category div{
position:relative;
z-index:1;
}

.category h3{
font-size:20px;
}

.category p{
font-size:12px;
opacity:.9;
}


/* SHOP */

.shop-toolbar{
display:flex;
justify-content:space-between;
align-items:center;
gap:15px;
margin-bottom:25px;
flex-wrap:wrap;
}

.search{
flex:1;
min-width:220px;
position:relative;
}

.search input{
width:100%;
padding:14px 45px 14px 15px;
border:1px solid var(--border);
border-radius:10px;
background:white;
outline:none;
}

.search span{
position:absolute;
right:15px;
top:10px;
font-size:20px;
}

.filters{
display:flex;
gap:7px;
flex-wrap:wrap;
}

.filter{
border:1px solid var(--border);
background:white;
padding:9px 15px;
border-radius:30px;
font-size:13px;
}

.filter.active,
.filter:hover{
background:var(--dark);
color:white;
}


/* PRODUCTS */

.products{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:22px;
}

.product{
background:white;
border-radius:16px;
overflow:hidden;
border:1px solid var(--border);
transition:.25s;
position:relative;
}

.product:hover{
transform:translateY(-5px);
box-shadow:0 15px 35px rgba(0,0,0,.08);
}

.product-image{
height:270px;
position:relative;
overflow:hidden;
background:#eee;
}

.product-image img{
width:100%;
height:100%;
object-fit:cover;
transition:.5s;
}

.product:hover .product-image img{
transform:scale(1.05);
}

.product-tag{
position:absolute;
top:12px;
right:12px;
background:#b83b2f;
color:white;
padding:4px 9px;
border-radius:20px;
font-size:11px;
}

.favorite{
position:absolute;
top:12px;
left:12px;
border:0;
background:white;
width:35px;
height:35px;
border-radius:50%;
font-size:18px;
}

.product-body{
padding:17px;
}

.product-category{
color:var(--gold2);
font-size:11px;
font-weight:bold;
}

.product h3{
font-size:18px;
margin:3px 0;
}

.stars{
color:#d69d39;
font-size:13px;
}

.product-description{
color:var(--muted);
font-size:12px;
height:42px;
overflow:hidden;
margin:5px 0;
}

.price-row{
display:flex;
align-items:center;
justify-content:space-between;
margin-top:12px;
}

.price{
font-size:20px;
font-weight:bold;
}

.old-price{
font-size:12px;
color:#999;
text-decoration:line-through;
margin-right:5px;
}

.add-cart{
background:var(--dark);
color:white;
border:0;
padding:10px 14px;
border-radius:8px;
}

.add-cart:hover{
background:var(--gold2);
}


/* OFFER */

.offer{
background:
linear-gradient(90deg,rgba(33,21,14,.96),rgba(33,21,14,.78)),
url("https://images.unsplash.com/photo-1608571423902-eed4a5ad8108?auto=format&fit=crop&w=1600&q=80")
center/cover;
color:white;
}

.offer-inner{
max-width:1250px;
margin:auto;
padding:65px 20px;
display:flex;
justify-content:space-between;
align-items:center;
gap:30px;
}

.offer h2{
font-size:35px;
}

.offer p{
color:#ddd;
}

.offer-code{
border:1px dashed var(--gold);
padding:15px 25px;
text-align:center;
border-radius:10px;
min-width:180px;
}

.offer-code strong{
font-size:24px;
color:var(--gold);
display:block;
}


/* WHY */

.why{
background:white;
}

.why-grid{
display:grid;
grid-template-columns:1fr 1fr;
gap:45px;
align-items:center;
}

.why-image{
height:450px;
border-radius:20px;
background:
url("https://images.unsplash.com/photo-1599443015574-b8318f4d4f18?auto=format&fit=crop&w=1000&q=85")
center/cover;
}

.check-list{
margin-top:25px;
display:grid;
gap:15px;
}

.check{
display:flex;
gap:10px;
align-items:flex-start;
}

.check-icon{
color:var(--success);
font-size:20px;
}


/* DELIVERY */

.delivery{
background:#f0e9df;
}

.delivery-grid{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:18px;
}

.delivery-card{
background:white;
padding:25px;
border-radius:15px;
text-align:center;
border:1px solid var(--border);
}

.delivery-card .icon{
font-size:35px;
margin-bottom:8px;
}

.delivery-card h3{
font-size:18px;
}

.delivery-card p{
color:var(--muted);
font-size:13px;
}


/* REVIEWS */

.reviews{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
}

.review{
background:white;
padding:25px;
border-radius:15px;
border:1px solid var(--border);
}

.review-stars{
color:#d69d39;
}

.review-text{
margin:12px 0;
font-size:14px;
color:#555;
}

.reviewer{
font-weight:bold;
font-size:13px;
}


/* FAQ */

.faq{
max-width:850px;
margin:auto;
}

details{
background:white;
border:1px solid var(--border);
border-radius:10px;
margin-bottom:10px;
padding:17px;
}

summary{
cursor:pointer;
font-weight:bold;
}


/* CONTACT */

.contact{
background:var(--dark);
color:white;
text-align:center;
}

.contact p{
color:#ddd;
}

.socials{
display:flex;
justify-content:center;
gap:12px;
margin-top:25px;
flex-wrap:wrap;
}

.social{
padding:12px 25px;
border-radius:30px;
font-weight:bold;
}

.whatsapp{
background:#1fbf62;
}

.snap{
background:#f6d000;
color:#111;
}

.instagram{
background:#d62b70;
}


/* FOOTER */

footer{
background:#140c07;
color:#bbb;
}

.footer-grid{
max-width:1250px;
margin:auto;
padding:50px 20px;
display:grid;
grid-template-columns:2fr 1fr 1fr 1fr;
gap:35px;
}

footer h3{
color:white;
margin-bottom:12px;
}

footer a{
display:block;
font-size:13px;
margin:7px 0;
}

.footer-bottom{
border-top:1px solid rgba(255,255,255,.08);
text-align:center;
padding:18px;
font-size:12px;
}


/* MODAL */

.modal{
display:none;
position:fixed;
inset:0;
background:rgba(0,0,0,.65);
z-index:2000;
align-items:center;
justify-content:center;
padding:15px;
}

.modal.show{
display:flex;
}

.modal-box{
background:white;
width:100%;
max-width:620px;
max-height:92vh;
overflow:auto;
border-radius:18px;
padding:25px;
}

.modal-head{
display:flex;
justify-content:space-between;
align-items:center;
margin-bottom:15px;
}

.close{
border:0;
background:#eee;
width:35px;
height:35px;
border-radius:50%;
font-size:20px;
}

.cart-item{
display:grid;
grid-template-columns:60px 1fr auto;
gap:12px;
align-items:center;
padding:12px 0;
border-bottom:1px solid var(--border);
}

.cart-item img{
width:60px;
height:60px;
object-fit:cover;
border-radius:8px;
}

.qty{
display:flex;
align-items:center;
gap:7px;
margin-top:5px;
}

.qty button{
width:25px;
height:25px;
border:0;
background:#eee;
border-radius:5px;
}

.remove{
border:0;
background:none;
color:#b33;
}

.cart-total{
display:flex;
justify-content:space-between;
font-size:21px;
font-weight:bold;
margin:20px 0;
}

.form-grid{
display:grid;
grid-template-columns:1fr 1fr;
gap:10px;
}

.form-group{
margin-bottom:10px;
}

.form-group.full{
grid-column:1/-1;
}

.form-group label{
font-size:12px;
display:block;
margin-bottom:4px;
}

.form-group input,
.form-group select,
.form-group textarea{
width:100%;
border:1px solid var(--border);
border-radius:8px;
padding:12px;
outline:none;
}

.form-group textarea{
min-height:90px;
resize:vertical;
}

.checkout{
width:100%;
padding:14px;
border:0;
background:var(--success);
color:white;
border-radius:9px;
font-size:16px;
font-weight:bold;
}


/* TOAST */

.toast{
position:fixed;
bottom:25px;
right:25px;
background:var(--dark);
color:white;
padding:14px 20px;
border-radius:9px;
z-index:5000;
transform:translateY(100px);
opacity:0;
transition:.3s;
}

.toast.show{
transform:translateY(0);
opacity:1;
}


/* MOBILE */

@media(max-width:1000px){

.products{
grid-template-columns:repeat(3,1fr);
}

.categories,
.delivery-grid{
grid-template-columns:repeat(2,1fr);
}

.features-grid{
grid-template-columns:repeat(2,1fr);
}

.footer-grid{
grid-template-columns:1fr 1fr;
}

}

@media(max-width:700px){

.header-inner{
padding:12px 14px;
}

.logo{
font-size:18px;
}

nav{
display:none;
}

.hero{
min-height:570px;
}

.hero h1{
font-size:38px;
}

.hero p{
font-size:15px;
}

.container{
padding:55px 15px;
}

.products{
grid-template-columns:repeat(2,1fr);
gap:12px;
}

.product-image{
height:190px;
}

.product-body{
padding:12px;
}

.product h3{
font-size:15px;
}

.price{
font-size:17px;
}

.add-cart{
padding:8px 10px;
font-size:11px;
}

.categories{
grid-template-columns:1fr 1fr;
}

.category{
height:145px;
padding:12px;
}

.features-grid{
grid-template-columns:1fr 1fr;
padding:25px 15px;
}

.feature p{
font-size:10px;
}

.offer-inner{
flex-direction:column;
text-align:center;
}

.why-grid{
grid-template-columns:1fr;
}

.why-image{
height:300px;
}

.delivery-grid{
grid-template-columns:1fr 1fr;
}

.reviews{
grid-template-columns:1fr;
}

.footer-grid{
grid-template-columns:1fr;
}

.form-grid{
grid-template-columns:1fr;
}

.form-group.full{
grid-column:auto;
}

}

</style>
</head>

<body>


<div class="topbar">
🚚 شحن لجميع مناطق المملكة | 🎁 تغليف هدايا فاخر | 💬 خدمة عملاء
</div>


<header>

<div class="header-inner">

<div class="logo">
دار <span>العود</span> 🌿
</div>

<nav>
<a href="#home">الرئيسية</a>
<a href="#shop">المنتجات</a>
<a href="#offers">العروض</a>
<a href="#delivery">الشحن</a>
<a href="#contact">تواصل معنا</a>
</nav>

<div class="header-actions">

<button class="icon-btn"
onclick="document.getElementById('shop').scrollIntoView()">
⌕
</button>

<button class="icon-btn" onclick="openCart()">
🛒
<span class="badge" id="cartCount">0</span>
</button>

</div>

</div>

</header>


<main id="home">


<section class="hero">

<div class="hero-content">

<div class="hero-small">
عود طبيعي • بخور فاخر • هدايا
</div>

<h1>
فخامة العود تبدأ من الاختيار الصحيح
</h1>

<p>
تشكيلة مختارة من أجود أنواع العود والبخور بروائح شرقية
أصيلة تناسب ذوقك ومناسباتك.
</p>

<div style="display:flex;gap:10px;flex-wrap:wrap">

<a class="btn btn-gold" href="#shop">
تسوق الآن 🛒
</a>

<a class="btn btn-outline" href="#contact">
تواصل معنا
</a>

</div>

</div>

</section>


<section class="features">

<div class="features-grid">

<div class="feature">
<div class="feature-icon">🌿</div>
<div>
<h4>اختيارات مميزة</h4>
<p>منتجات مختارة بعناية</p>
</div>
</div>

<div class="feature">
<div class="feature-icon">📦</div>
<div>
<h4>تغليف فاخر</h4>
<p>مناسب للهدايا</p>
</div>
</div>

<div class="feature">
<div class="feature-icon">🚚</div>
<div>
<h4>شحن سريع</h4>
<p>لجميع مناطق المملكة</p>
</div>
</div>

<div class="feature">
<div class="feature-icon">🔒</div>
<div>
<h4>طلب آمن</h4>
<p>تأكيد الطلب عبر الواتساب</p>
</div>
</div>

</div>

</section>


<section class="container">

<div class="section-title">

<div class="eyebrow">اكتشف تشكيلتنا</div>

<h2>تسوق حسب النوع</h2>

<p>اختر نوع العود الذي يناسب ذوقك</p>

</div>


<div class="categories">

<a class="category"
style="background-image:url('https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=700&q=80')"
href="#shop">

<div>
<h3>العود المروكي</h3>
<p>روائح شرقية فاخرة</p>
</div>

</a>


<a class="category"
style="background-image:url('https://images.unsplash.com/photo-1608571423902-eed4a5ad8108?auto=format&fit=crop&w=700&q=80')"
href="#shop">

<div>
<h3>العود الكمبودي</h3>
<p>رائحة عميقة ومميزة</p>
</div>

</a>


<a class="category"
style="background-image:url('https://images.unsplash.com/photo-1615485500704-8e990f9900f7?auto=format&fit=crop&w=700&q=80')"
href="#shop">

<div>
<h3>العود الأزرق</h3>
<p>اختيارات خاصة</p>
</div>

</a>


<a class="category"
style="background-image:url('https://images.unsplash.com/photo-1599443015574-b8318f4d4f18?auto=format&fit=crop&w=700&q=80')"
href="#shop">

<div>
<h3>البخور والهدايا</h3>
<p>للمناسبات والهدايا</p>
</div>

</a>

</div>

</section>


<section id="shop" class="container">

<div class="section-title">

<div class="eyebrow">منتجاتنا</div>

<h2>أجود الاختيارات</h2>

<p>اختر المنتج وأضفه إلى السلة</p>

</div>


<div class="shop-toolbar">

<div class="search">

<span>🔍</span>

<input
id="searchInput"
type="text"
placeholder="ابحث عن عود أو بخور..."
oninput="renderProducts()">

</div>


<div class="filters">

<button class="filter active"
onclick="setCategory('all',this)">
الكل
</button>

<button class="filter"
onclick="setCategory('مروكي',this)">
مروكي
</button>

<button class="filter"
onclick="setCategory('كمبودي',this)">
كمبودي
</button>

<button class="filter"
onclick="setCategory('أزرق',this)">
أزرق
</button>

<button class="filter"
onclick="setCategory('بخور',this)">
بخور
</button>

</div>

</div>


<div class="products" id="products"></div>

</section>


<section id="offers" class="offer">

<div class="offer-inner">

<div>

<div style="color:#c79a5b">
عرض خاص لفترة محدودة
</div>

<h2>
خصم 10% على أول طلب
</h2>

<p>
استخدم كود الخصم عند إتمام الطلب.
</p>

</div>

<div class="offer-code">

الكود

<strong>FIRST10</strong>

خصم 10%

</div>

</div>

</section>


<section class="why">

<div class="container">

<div class="why-grid">

<div class="why-image"></div>

<div>

<div class="section-title" style="text-align:right;margin-bottom:10px">

<div class="eyebrow">لماذا دار العود؟</div>

<h2>
نختار الجودة قبل كل شيء
</h2>

</div>

<p style="color:#665d57">
هدفنا أن نقدم لك تجربة شراء سهلة، واضحة وفاخرة،
من اختيار المنتج حتى وصوله إلى باب منزلك.
</p>

<div class="check-list">

<div class="check">
<div class="check-icon">✓</div>
<div>
<strong>منتجات متنوعة</strong>
<br>
<span style="font-size:13px;color:#777">
خيارات متعددة تناسب مختلف الأذواق.
</span>
</div>
</div>

<div class="check">
<div class="check-icon">✓</div>
<div>
<strong>تغليف أنيق</strong>
<br>
<span style="font-size:13px;color:#777">
مناسب للاستخدام الشخصي والهدايا.
</span>
</div>
</div>

<div class="check">
<div class="check-icon">✓</div>
<div>
<strong>تواصل مباشر</strong>
<br>
<span style="font-size:13px;color:#777">
تأكيد الطلب ومتابعته عبر الواتساب.
</span>
</div>
</div>

<div class="check">
<div class="check-icon">✓</div>
<div>
<strong>خيارات شحن متعددة</strong>
<br>
<span style="font-size:13px;color:#777">
اختيار شركة الشحن المناسبة حسب المدينة.
</span>
</div>
</div>

</div>

</div>

</div>

</div>

</section>


<section id="delivery" class="delivery">

<div class="container">

<div class="section-title">

<div class="eyebrow">التوصيل</div>

<h2>نوصل طلبك إلى بابك</h2>

<p>
يمكن اختيار شركة الشحن المناسبة عند الطلب.
</p>

</div>


<div class="delivery-grid">

<div class="delivery-card">

<div class="icon">📮</div>

<h3>SPL</h3>

<p>
البريد السعودي
</p>

</div>


<div class="delivery-card">

<div class="icon">📦</div>

<h3>Aramex</h3>

<p>
أرامكس
</p>

</div>


<div class="delivery-card">

<div class="icon">🚚</div>

<h3>SMSA</h3>

<p>
سمسا
</p>

</div>


<div class="delivery-card">

<div class="icon">⚡</div>

<h3>شحن آخر</h3>

<p>
حسب المدينة والطلب
</p>

</div>

</div>

</div>

</section>


<section class="container">

<div class="section-title">

<div class="eyebrow">آراء العملاء</div>

<h2>ماذا يقول عملاؤنا؟</h2>

</div>


<div class="reviews">

<div class="review">

<div class="review-stars">★★★★★</div>

<div class="review-text">
"الرائحة ممتازة والتغليف مرتب جدًا."
</div>

<div class="reviewer">
محمد — الرياض
</div>

</div>


<div class="review">

<div class="review-stars">★★★★★</div>

<div class="review-text">
"طلبت عود هدية ووصلني بشكل ممتاز."
</div>

<div class="reviewer">
عبدالله — جدة
</div>

</div>


<div class="review">

<div class="review-stars">★★★★★</div>

<div class="review-text">
"تجربة جميلة وسرعة في الرد والتواصل."
</div>

<div class="reviewer">
سعد — الدمام
</div>

</div>

</div>

</section>


<section class="container">

<div class="section-title">

<div class="eyebrow">الأسئلة الشائعة</div>

<h2>أسئلة العملاء</h2>

</div>


<div class="faq">

<details>

<summary>
كيف أطلب؟
</summary>

<p>
اختر المنتجات وأضفها للسلة ثم اكتب بياناتك واضغط
"إرسال الطلب عبر واتساب".
</p>

</details>


<details>

<summary>
هل يوجد شحن لجميع مناطق السعودية؟
</summary>

<p>
نعم، يتم تحديد شركة الشحن المناسبة حسب المدينة والطلب.
</p>

</details>


<details>

<summary>
كم مدة التوصيل؟
</summary>

<p>
مدة التوصيل تختلف حسب المدينة وشركة الشحن، ويتم تأكيدها عند الطلب.
</p>

</details>


<details>

<summary>
هل يمكن تجهيز الطلب كهدية؟
</summary>

<p>
نعم، يمكن طلب التغليف كهدية والتنسيق مع خدمة العملاء.
</p>

</details>


<details>

<summary>
كيف أتواصل معكم؟
</summary>

<p>
يمكن التواصل معنا عبر الواتساب أو سناب شات.
</p>

</details>

</div>

</section>


<section id="contact" class="contact">

<div class="container">

<div class="section-title">

<div class="eyebrow">
خدمة العملاء
</div>

<h2>
نحن بخدمتك
</h2>

<p>
للطلب والاستفسار تواصل معنا مباشرة.
</p>

</div>


<div class="socials">

<a
class="social whatsapp"
href="https://wa.me/966500000000"
target="_blank">

💬 واتساب

</a>


<a
class="social snap"
href="https://www.snapchat.com/"
target="_blank">

👻 سناب شات

</a>


<a
class="social instagram"
href="https://www.instagram.com/"
target="_blank">

📸 إنستغرام

</a>

</div>

</div>

</section>


</main>


<footer>

<div class="footer-grid">

<div>

<h3>دار العود 🌿</h3>

<p style="font-size:13px">
متجر متخصص في العود والبخور والهدايا الفاخرة.
نسعى لتقديم تجربة مميزة من أول زيارة حتى استلام الطلب.
</p>

</div>


<div>

<h3>روابط</h3>

<a href="#home">الرئيسية</a>

<a href="#shop">المنتجات</a>

<a href="#offers">العروض</a>

<a href="#delivery">الشحن</a>

</div>


<div>

<h3>خدمة العملاء</h3>

<a href="#contact">تواصل معنا</a>

<a href="#contact">الواتساب</a>

<a href="#contact">سناب شات</a>

</div>


<div>

<h3>معلومات</h3>

<a href="#">سياسة الخصوصية</a>

<a href="#">الشروط والأحكام</a>

<a href="#">سياسة الاستبدال</a>

</div>

</div>


<div class="footer-bottom">

© 2026 دار العود — جميع الحقوق محفوظة

</div>

</footer>


<!-- CART MODAL -->

<div class="modal" id="cartModal">

<div class="modal-box">

<div class="modal-head">

<h2>🛒 سلة المشتريات</h2>

<button class="close" onclick="closeCart()">
×
</button>

</div>


<div id="cartItems"></div>


<div class="cart-total">

<span>الإجمالي</span>

<span>
<span id="cartTotal">0</span>
 ريال
</span>

</div>


<h3 style="margin-bottom:15px">
بيانات العميل
</h3>


<div class="form-grid">


<div class="form-group">

<label>الاسم *</label>

<input
id="customerName"
placeholder="اكتب اسمك">

</div>


<div class="form-group">

<label>رقم الجوال *</label>

<input
id="customerPhone"
placeholder="05xxxxxxxx">

</div>


<div class="form-group">

<label>المدينة *</label>

<input
id="customerCity"
placeholder="مثال: الرياض">

</div>


<div class="form-group">

<label>شركة الشحن</label>

<select id="shipping">

<option>SPL</option>

<option>Aramex</option>

<option>SMSA</option>

<option>حسب المتاح</option>

</select>

</div>


<div class="form-group full">

<label>العنوان</label>

<textarea
id="customerAddress"
placeholder="الحي، الشارع، رقم المبنى..."></textarea>

</div>


<div class="form-group full">

<label>ملاحظات الطلب</label>

<textarea
id="orderNotes"
placeholder="أي ملاحظات إضافية"></textarea>

</div>


<div class="form-group full">

<label>كوبون الخصم</label>

<input
id="coupon"
placeholder="مثال: FIRST10">

</div>

</div>


<button class="checkout" onclick="sendOrder()">

📲 إرسال الطلب عبر واتساب

</button>


</div>

</div>


<div class="toast" id="toast">
تمت إضافة المنتج إلى السلة ✓
</div>


<script>


/* ==============================
   بيانات المنتجات
============================== */

const products = [

{
id:1,
name:"عود مروكي فاخر",
category:"مروكي",
price:350,
oldPrice:420,
rating:5,
tag:"الأكثر مبيعًا",
image:"https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=900&q=85",
description:"عود مروكي فاخر برائحة شرقية مميزة وثبات جميل."
},

{
id:2,
name:"عود كمبودي فاخر",
category:"كمبودي",
price:500,
oldPrice:590,
rating:5,
tag:"مميز",
image:"https://images.unsplash.com/photo-1608571423902-eed4a5ad8108?auto=format&fit=crop&w=900&q=85",
description:"رائحة عميقة وفاخرة لمحبي العود الكمبودي."
},

{
id:3,
name:"دقة مروكي",
category:"مروكي",
price:450,
oldPrice:520,
rating:5,
tag:"",
image:"https://images.unsplash.com/photo-1615485500704-8e990f9900f7?auto=format&fit=crop&w=900&q=85",
description:"اختيار فاخر لمحبي الروائح الشرقية الأصيلة."
},

{
id:4,
name:"مروكي سيوفي",
category:"مروكي",
price:600,
oldPrice:700,
rating:5,
tag:"فاخر",
image:"https://images.unsplash.com/photo-1599443015574-b8318f4d4f18?auto=format&fit=crop&w=900&q=85",
description:"عود مميز بطابع قوي ومناسب للمناسبات."
},

{
id:5,
name:"أزرق مالينو",
category:"أزرق",
price:750,
oldPrice:850,
rating:5,
tag:"جديد",
image:"https://images.unsplash.com/photo-1612196808214-b7e239e5f6f4?auto=format&fit=crop&w=900&q=85",
description:"اختيار فاخر لعشاق العود الأزرق."
},

{
id:6,
name:"عود أزرق BM",
category:"أزرق",
price:550,
oldPrice:650,
rating:4,
tag:"",
image:"https://images.unsplash.com/photo-1605651202774-7d573fd31a50?auto=format&fit=crop&w=900&q=85",
description:"رائحة مميزة مناسبة للاستخدام اليومي والمناسبات."
},

{
id:7,
name:"بخور فاخر",
category:"بخور",
price:180,
oldPrice:220,
rating:5,
tag:"عرض",
image:"https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=900&q=85",
description:"بخور شرقي فاخر برائحة دافئة وثابتة."
},

{
id:8,
name:"خلطة العود الملكية",
category:"بخور",
price:250,
oldPrice:300,
rating:5,
tag:"مميز",
image:"https://images.unsplash.com/photo-1608571423902-eed4a5ad8108?auto=format&fit=crop&w=900&q=85",
description:"خلطة خاصة لمحبي الروائح الفخمة."
},

{
id:9,
name:"كمبودي AB",
category:"كمبودي",
price:680,
oldPrice:760,
rating:5,
tag:"",
image:"https://images.unsplash.com/photo-1599443015574-b8318f4d4f18?auto=format&fit=crop&w=900&q=85",
description:"عود كمبودي مختار بعناية."
},

{
id:10,
name:"مروكي أصفر",
category:"مروكي",
price:390,
oldPrice:450,
rating:4,
tag:"",
image:"https://images.unsplash.com/photo-1605651202774-7d573fd31a50?auto=format&fit=crop&w=900&q=85",
description:"اختيار مميز بسعر مناسب."
},

{
id:11,
name:"بوكس هدية فاخر",
category:"بخور",
price:299,
oldPrice:350,
rating:5,
tag:"هدية",
image:"https://images.unsplash.com/photo-1615485500704-8e990f9900f7?auto=format&fit=crop&w=900&q=85",
description:"بوكس أنيق مناسب للإهداء."
},

{
id:12,
name:"عود فاخر VIP",
category:"أزرق",
price:950,
oldPrice:1100,
rating:5,
tag:"VIP",
image:"https://images.unsplash.com/photo-1603006905003-be475563bc59?auto=format&fit=crop&w=900&q=85",
description:"اختيار فاخر لمحبي الجودة العالية."
}

];


let cart = [];

let currentCategory = "all";


/* ==============================
   عرض المنتجات
============================== */

function renderProducts(){

const container =
document.getElementById("products");

const search =
document.getElementById("searchInput")
.value
.trim()
.toLowerCase();


const filtered = products.filter(product=>{

const categoryMatch =
currentCategory === "all" ||
product.category === currentCategory;

const searchMatch =
product.name.toLowerCase().includes(search) ||
product.category.toLowerCase().includes(search);

return categoryMatch && searchMatch;

});


container.innerHTML = filtered.map(product=>`

<div class="product">

<div class="product-image">

<img
src="${product.image}"
alt="${product.name}"
loading="lazy">

${product.tag ?
`<div class="product-tag">${product.tag}</div>`
:""}

<button class="favorite"
onclick="toggleFavorite(this)">
♡
</button>

</div>


<div class="product-body">

<div class="product-category">
${product.category}
</div>

<h3>
${product.name}
</h3>

<div class="stars">
${"★".repeat(product.rating)}
${"☆".repeat(5-product.rating)}
</div>

<div class="product-description">
${product.description}
</div>


<div class="price-row">

<div>

<span class="price">
${product.price}
 ريال
</span>

${product.oldPrice ?
`<span class="old-price">
${product.oldPrice}
</span>`
:""}

</div>


<button class="add-cart"
onclick="addToCart(${product.id})">

🛒 أضف

</button>

</div>

</div>

</div>

`).join("");


if(filtered.length===0){

container.innerHTML=`
<div style="grid-column:1/-1;text-align:center;padding:50px">
لا توجد منتجات مطابقة للبحث.
</div>
`;

}

}


/* ==============================
   الفلاتر
============================== */

function setCategory(category,button){

currentCategory=category;

document
.querySelectorAll(".filter")
.forEach(btn=>btn.classList.remove("active"));

button.classList.add("active");

renderProducts();

}


/* ==============================
   السلة
============================== */

function addToCart(id){

const product =
products.find(p=>p.id===id);

const existing =
cart.find(item=>item.id===id);


if(existing){

existing.qty++;

}else{

cart.push({
...product,
qty:1
});

}

updateCart();

showToast();

}


function updateCart(){

const count =
cart.reduce((sum,item)=>sum+item.qty,0);

document.getElementById("cartCount").innerText=count;


const items =
document.getElementById("cartItems");


if(cart.length===0){

items.innerHTML=`
<div style="text-align:center;padding:40px;color:#777">
السلة فارغة 🛒
</div>
`;

document.getElementById("cartTotal").innerText="0";

return;

}


items.innerHTML=cart.map(item=>`

<div class="cart-item">

<img
src="${item.image}"
alt="${item.name}">

<div>

<strong>${item.name}</strong>

<div style="font-size:13px">
${item.price} ريال
</div>

<div class="qty">

<button onclick="changeQty(${item.id},-1)">
−
</button>

<span>${item.qty}</span>

<button onclick="changeQty(${item.id},1)">
+
</button>

</div>

</div>


<button
class="remove"
onclick="removeItem(${item.id})">

حذف

</button>

</div>

`).join("");


let total =
cart.reduce(
(sum,item)=>sum+(item.price*item.qty),
0
);

document.getElementById("cartTotal").innerText=total;

}


function changeQty(id,amount){

const item =
cart.find(item=>item.id===id);

if(!item) return;

item.qty += amount;

if(item.qty<=0){

removeItem(id);

return;

}

updateCart();

}


function removeItem(id){

cart =
cart.filter(item=>item.id!==id);

updateCart();

}


function openCart(){

document
.getElementById("cartModal")
.classList.add("show");

updateCart();

}


function closeCart(){

document
.getElementById("cartModal")
.classList.remove("show");

}


/* ==============================
   الخصم
============================== */

function calculateTotal(){

let total =
cart.reduce(
(sum,item)=>sum+(item.price*item.qty),
0
);

const coupon =
document.getElementById("coupon")
.value
.trim()
.toUpperCase();

if(coupon==="FIRST10"){

total = total * .90;

}

return Math.round(total);

}


/* ==============================
   إرسال الطلب
============================== */

function sendOrder(){

if(cart.length===0){

alert("السلة فارغة");

return;

}


const name =
document.getElementById("customerName")
.value.trim();

const phone =
document.getElementById("customerPhone")
.value.trim();

const city =
document.getElementById("customerCity")
.value.trim();

const shipping =
document.getElementById("shipping")
.value;

const address =
document.getElementById("customerAddress")
.value.trim();

const notes =
document.getElementById("orderNotes")
.value.trim();

const coupon =
document.getElementById("coupon")
.value.trim()
.toUpperCase();


if(!name || !phone || !city){

alert("فضلاً أكمل الاسم والجوال والمدينة.");

return;

}


let message =
"طلب جديد من متجر دار العود 🌿\n\n";


message +=
"👤 الاسم: "+name+"\n";

message +=
"📱 الجوال: "+phone+"\n";

message +=
"📍 المدينة: "+city+"\n";

message +=
"🚚 الشحن: "+shipping+"\n";

message +=
"🏠 العنوان: "+(address || "سيتم تحديده لاحقًا")+"\n\n";


message +=
"🛒 المنتجات:\n";


cart.forEach(item=>{

message +=
"• "+
item.name+
" × "+
item.qty+
" = "+
(item.price*item.qty)+
" ريال\n";

});


const subtotal =
cart.reduce(
(sum,item)=>sum+(item.price*item.qty),
0
);


const total =
calculateTotal();


message +=
"\nالمجموع قبل الخصم: "+
subtotal+
" ريال\n";


if(coupon==="FIRST10"){

message +=
"🎁 الخصم: 10%\n";

}


message +=
"💰 الإجمالي: "+
total+
" ريال\n";


if(notes){

message +=
"\n📝 ملاحظات:\n"+
notes;

}


/*
غيّر الرقم هنا إلى رقم واتساب المتجر
*/

const whatsapp =
"966500000000";


const url =
"https://wa.me/"+
whatsapp+
"?text="+
encodeURIComponent(message);


window.open(url,"_blank");

}


/* ==============================
   مفضلة
============================== */

function toggleFavorite(button){

if(button.innerText==="♡"){

button.innerText="♥";

}else{

button.innerText="♡";

}

}


/* ==============================
   إشعار
============================== */

function showToast(){

const toast =
document.getElementById("toast");

toast.classList.add("show");

setTimeout(()=>{

toast.classList.remove("show");

},1800);

}


/* ==============================
   تشغيل
============================== */

renderProducts();

updateCart();


/* إغلاق النافذة عند الضغط خارجها */

document
.getElementById("cartModal")
.addEventListener("click",function(e){

if(e.target===this){

closeCart();

}

});

</script>

</body>
</html>
