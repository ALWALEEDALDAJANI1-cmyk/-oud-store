<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>

<meta charset="UTF-8">

<meta name="viewport"
content="width=device-width, initial-scale=1.0">

<title>ترف العود | عود فاخر</title>

<meta name="description"
content="ترف العود - عود فاخر مختار بعناية، 50 جرام بـ 300 ريال">

<style>

/* =========================
   الهوية
========================= */

:root{
--black:#100b08;
--dark:#1b100b;
--brown:#2d1b11;
--gold:#c89b5b;
--gold2:#e2bd7b;
--cream:#f7f1e8;
--white:#fff;
--text:#241810;
--muted:#75675d;
--border:#e8dccb;
--green:#159447;
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
font-family:Tahoma,Arial,sans-serif;
background:var(--cream);
color:var(--text);
line-height:1.8;
}

a{
text-decoration:none;
color:inherit;
}

button,
input,
select,
textarea{
font-family:inherit;
}


/* =========================
   الشريط العلوي
========================= */

.top{
background:#080604;
color:#d8bd91;
text-align:center;
padding:7px;
font-size:12px;
}


/* =========================
   الهيدر
========================= */

header{
position:sticky;
top:0;
z-index:1000;
background:rgba(16,11,8,.97);
border-bottom:1px solid rgba(200,155,91,.25);
}

.header{
max-width:1250px;
margin:auto;
padding:14px 20px;
display:flex;
align-items:center;
justify-content:space-between;
gap:20px;
}

.logo{
font-size:27px;
font-weight:bold;
color:white;
}

.logo span{
color:var(--gold);
}

.logo small{
display:block;
font-size:9px;
font-weight:normal;
color:#bda98e;
letter-spacing:2px;
text-align:center;
}

nav{
display:flex;
gap:25px;
}

nav a{
color:#eee;
font-size:13px;
transition:.2s;
}

nav a:hover{
color:var(--gold);
}

.cart-button{
background:var(--gold);
border:0;
border-radius:30px;
padding:10px 17px;
font-weight:bold;
color:#1a100a;
cursor:pointer;
}


/* =========================
   البطل
========================= */

.hero{

min-height:690px;

background:
linear-gradient(
90deg,
rgba(8,5,3,.97) 0%,
rgba(15,9,6,.88) 38%,
rgba(15,9,6,.35) 100%
),
url("https://down-id.img.susercontent.com/file/id-11134207-7rbk6-m6wq5ubgw184a7")
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

.hero-label{
color:var(--gold2);
font-size:14px;
margin-bottom:12px;
}

.hero h1{
font-size:62px;
line-height:1.15;
max-width:650px;
margin-bottom:20px;
}

.hero h1 span{
color:var(--gold2);
}

.hero p{
max-width:560px;
font-size:17px;
color:#ddd;
margin-bottom:30px;
}

.hero-buttons{
display:flex;
gap:12px;
flex-wrap:wrap;
}

.btn{
padding:13px 25px;
border-radius:8px;
border:1px solid transparent;
font-weight:bold;
display:inline-block;
cursor:pointer;
}

.btn-gold{
background:var(--gold);
color:#160d08;
}

.btn-outline{
border-color:var(--gold);
color:var(--gold2);
background:transparent;
}


/* =========================
   المميزات
========================= */

.features{
background:#fff;
border-bottom:1px solid var(--border);
}

.features-inner{
max-width:1200px;
margin:auto;
padding:28px 20px;
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
}

.feature{
display:flex;
align-items:center;
gap:12px;
}

.feature-icon{
font-size:27px;
}

.feature h4{
font-size:14px;
}

.feature p{
font-size:11px;
color:var(--muted);
}


/* =========================
   الأقسام
========================= */

.section{
max-width:1200px;
margin:auto;
padding:80px 20px;
}

.title{
text-align:center;
margin-bottom:45px;
}

.title .small{
color:var(--gold2);
font-size:13px;
font-weight:bold;
}

.title h2{
font-size:38px;
margin:4px 0;
}

.title p{
color:var(--muted);
font-size:14px;
}


/* =========================
   المنتجات
========================= */

.products{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:25px;
}

.product{
background:white;
border:1px solid var(--border);
border-radius:18px;
overflow:hidden;
transition:.3s;
box-shadow:0 8px 30px rgba(40,20,5,.06);
}

.product:hover{
transform:translateY(-7px);
box-shadow:0 18px 45px rgba(40,20,5,.14);
}

.product-image{
height:330px;
position:relative;
overflow:hidden;
background:#ddd;
}

.product-image img{
width:100%;
height:100%;
object-fit:cover;
transition:.5s;
}

.product:hover img{
transform:scale(1.06);
}

.badge{
position:absolute;
top:15px;
right:15px;
background:var(--gold);
color:#1c1009;
padding:5px 12px;
border-radius:30px;
font-size:11px;
font-weight:bold;
}

.product-body{
padding:22px;
}

.product-type{
font-size:11px;
color:var(--gold2);
font-weight:bold;
}

.product h3{
font-size:23px;
margin:3px 0;
}

.product-description{
color:var(--muted);
font-size:13px;
min-height:55px;
}

.product-bottom{
display:flex;
justify-content:space-between;
align-items:center;
gap:10px;
margin-top:18px;
}

.price strong{
font-size:24px;
}

.price small{
display:block;
font-size:11px;
color:var(--muted);
}

.order{
border:0;
background:var(--dark);
color:white;
padding:12px 17px;
border-radius:8px;
font-weight:bold;
cursor:pointer;
}

.order:hover{
background:var(--gold2);
color:#1b100b;
}


/* =========================
   المنتج المميز
========================= */

.featured{
background:
linear-gradient(
90deg,
#160d08,
#2b190e
);
color:white;
}

.featured-inner{
max-width:1200px;
margin:auto;
padding:80px 20px;
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;
}

.featured-image{
height:470px;
border-radius:20px;
overflow:hidden;
}

.featured-image img{
width:100%;
height:100%;
object-fit:cover;
}

.featured h2{
font-size:42px;
margin:8px 0 15px;
}

.featured p{
color:#d5c9bc;
}

.featured-price{
font-size:32px;
color:var(--gold2);
font-weight:bold;
margin:20px 0;
}


/* =========================
   لماذا ترف العود
========================= */

.why-grid{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
}

.why{
background:white;
padding:28px;
border-radius:15px;
border:1px solid var(--border);
text-align:center;
}

.why-icon{
font-size:38px;
margin-bottom:10px;
}

.why h3{
font-size:18px;
}

.why p{
font-size:13px;
color:var(--muted);
}


/* =========================
   الشحن
========================= */

.shipping{
background:#eee5d8;
}

.shipping-grid{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:18px;
}

.ship{
background:white;
padding:25px;
border-radius:15px;
text-align:center;
border:1px solid var(--border);
}

.ship-icon{
font-size:35px;
}

.ship h3{
font-size:17px;
}

.ship p{
font-size:12px;
color:var(--muted);
}


/* =========================
   واتساب
========================= */

.contact{
background:var(--dark);
color:white;
text-align:center;
}

.contact h2{
font-size:38px;
}

.contact p{
color:#ccc;
}

.whatsapp-big{
display:inline-block;
margin-top:25px;
background:#19a957;
color:white;
padding:15px 30px;
border-radius:40px;
font-weight:bold;
}


/* =========================
   الفوتر
========================= */

footer{
background:#090604;
color:#aaa;
text-align:center;
padding:35px 20px;
}

.footer-logo{
font-size:27px;
color:white;
font-weight:bold;
}

.footer-logo span{
color:var(--gold);
}

footer p{
font-size:12px;
margin-top:5px;
}


/* =========================
   زر واتساب العائم
========================= */

.whatsapp-float{
position:fixed;
bottom:22px;
left:22px;
width:58px;
height:58px;
border-radius:50%;
background:#19b75b;
color:white;
display:flex;
align-items:center;
justify-content:center;
font-size:28px;
z-index:3000;
box-shadow:0 5px 25px rgba(0,0,0,.3);
}


/* =========================
   نافذة الطلب
========================= */

.modal{
display:none;
position:fixed;
inset:0;
background:rgba(0,0,0,.75);
z-index:5000;
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
max-width:520px;
border-radius:18px;
padding:25px;
max-height:90vh;
overflow:auto;
}

.modal-header{
display:flex;
justify-content:space-between;
align-items:center;
margin-bottom:20px;
}

.close{
border:0;
background:#eee;
width:35px;
height:35px;
border-radius:50%;
font-size:20px;
cursor:pointer;
}

.selected-product{
background:#f5eee4;
padding:15px;
border-radius:10px;
margin-bottom:15px;
}

.selected-product strong{
font-size:18px;
}

.form-group{
margin-bottom:12px;
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
height:80px;
resize:none;
}

.send-order{
width:100%;
background:#19a957;
color:white;
border:0;
padding:15px;
border-radius:8px;
font-weight:bold;
font-size:16px;
cursor:pointer;
}


/* =========================
   تجاوب الجوال
========================= */

@media(max-width:900px){

nav{
display:none;
}

.features-inner{
grid-template-columns:repeat(2,1fr);
}

.products{
grid-template-columns:1fr;
}

.shipping-grid{
grid-template-columns:repeat(2,1fr);
}

.featured-inner{
grid-template-columns:1fr;
}

.why-grid{
grid-template-columns:1fr;
}

.hero h1{
font-size:44px;
}

}

@media(max-width:600px){

.header{
padding:11px 14px;
}

.logo{
font-size:21px;
}

.cart-button{
padding:8px 12px;
font-size:12px;
}

.hero{
min-height:590px;
}

.hero h1{
font-size:39px;
}

.hero p{
font-size:14px;
}

.section{
padding:60px 15px;
}

.title h2{
font-size:30px;
}

.product-image{
height:280px;
}

.featured-image{
height:320px;
}

.featured h2{
font-size:31px;
}

.shipping-grid{
grid-template-columns:1fr 1fr;
}

.features-inner{
padding:22px 14px;
gap:14px;
}

.feature{
gap:7px;
}

.feature-icon{
font-size:22px;
}

}

</style>

</head>


<body>


<!-- أعلى الموقع -->

<div class="top">
🚚 شحن داخل المملكة &nbsp; | &nbsp;
🎁 تغليف أنيق &nbsp; | &nbsp;
💬 الطلب مباشرة عبر واتساب
</div>


<!-- الهيدر -->

<header>

<div class="header">

<a href="#home" class="logo">
ترف <span>العود</span>
<small>TAرف AL OUD</small>
</a>


<nav>

<a href="#home">الرئيسية</a>

<a href="#products">المنتجات</a>

<a href="#about">عن المتجر</a>

<a href="#shipping">الشحن</a>

<a href="#contact">تواصل معنا</a>

</nav>


<button class="cart-button"
onclick="scrollToProducts()">

تسوق الآن

</button>

</div>

</header>


<!-- الرئيسية -->

<section class="hero" id="home">

<div class="hero-content">

<div class="hero-label">
ترف العود • اختيارك للفخامة
</div>

<h1>
رائحة <span>تبقى</span><br>
وأثر لا يُنسى
</h1>

<p>
نقدم لك مجموعة مختارة من العود الفاخر
بوزن 50 جرام، لتعيش تجربة العود الأصيل
بلمسة فاخرة تليق بذوقك.
</p>

<div class="hero-buttons">

<a href="#products"
class="btn btn-gold">

اكتشف المنتجات

</a>

<a href="#contact"
class="btn btn-outline">

تواصل معنا

</a>

</div>

</div>

</section>


<!-- المميزات -->

<section class="features">

<div class="features-inner">

<div class="feature">

<div class="feature-icon">🌿</div>

<div>
<h4>عود مختار</h4>
<p>اختيارات بعناية</p>
</div>

</div>


<div class="feature">

<div class="feature-icon">⚖️</div>

<div>
<h4>50 جرام</h4>
<p>وزن واضح لكل منتج</p>
</div>

</div>


<div class="feature">

<div class="feature-icon">📦</div>

<div>
<h4>تغليف أنيق</h4>
<p>جاهز للإهداء</p>
</div>

</div>


<div class="feature">

<div class="feature-icon">🚚</div>

<div>
<h4>شحن المملكة</h4>
<p>إلى مختلف المدن</p>
</div>

</div>

</div>

</section>


<!-- المنتجات -->

<section class="section"
id="products">

<div class="title">

<div class="small">
تشكيلة ترف العود
</div>

<h2>
اختياراتنا
</h2>

<p>
ثلاثة أنواع مختارة لعشاق العود
</p>

</div>


<div class="products">


<!-- دقة مروكي -->

<div class="product">

<div class="product-image">

<img
src="https://down-id.img.susercontent.com/file/id-11134207-7rbk6-m6wq5ubgw184a7"
alt="دقة مروكي محسن">

<div class="badge">
مميز
</div>

</div>


<div class="product-body">

<div class="product-type">
MERAUKE • INDONESIA
</div>

<h3>
دقة مروكي محسن
</h3>

<p class="product-description">
عود مروكي بطابع غني ومميز، مناسب لعشاق
الروائح الشرقية العميقة والفاخرة.
</p>


<div class="product-bottom">

<div class="price">

<strong>300</strong> ريال

<small>
50 جرام
</small>

</div>

<button class="order"
onclick="openOrder('دقة مروكي محسن')">

اطلب الآن

</button>

</div>

</div>

</div>


<!-- أزرق كلمنتان -->

<div class="product">

<div class="product-image">

<img
src="https://media.zid.store/68708c1b-8aac-4704-af31-13fd77f887c5/cebbf2c9-6cdc-47c5-b0cb-ee9928aa5cf3.jpg"
alt="عود أزرق كلمنتان">

<div class="badge">
فاخر
</div>

</div>


<div class="product-body">

<div class="product-type">
KALIMANTAN • INDONESIA
</div>

<h3>
أزرق كلمنتان
</h3>

<p class="product-description">
قطع عود كلمنتان ذات مظهر طبيعي مميز،
اختيار أنيق لعشاق العود الإندونيسي.
</p>


<div class="product-bottom">

<div class="price">

<strong>300</strong> ريال

<small>
50 جرام
</small>

</div>

<button class="order"
onclick="openOrder('أزرق كلمنتان')">

اطلب الآن

</button>

</div>

</div>

</div>


<!-- سيوفي مروكي -->

<div class="product">

<div class="product-image">

<img
src="https://miya.odoo.com/web/image/product.image/2204/image_1024/ChatGPT%20Image%20Feb%2012%2C%202026%2C%2002_22_47%20AM.webp?unique=a2ea740"
alt="سيوفي مروكي">

<div class="badge">
مختار
</div>

</div>


<div class="product-body">

<div class="product-type">
MERAUKE • INDONESIA
</div>

<h3>
سيوفي مروكي
</h3>

<p class="product-description">
عود مروكي بتقطيع سيوفي ومظهر طبيعي،
مناسب لمن يبحث عن تجربة عود مختلفة.
</p>


<div class="product-bottom">

<div class="price">

<strong>300</strong> ريال

<small>
50 جرام
</small>

</div>

<button class="order"
onclick="openOrder('سيوفي مروكي')">

اطلب الآن

</button>

</div>

</div>

</div>


</div>

</section>


<!-- المنتج المميز -->

<section class="featured">

<div class="featured-inner">

<div class="featured-image">

<img
src="https://media.zid.store/68708c1b-8aac-4704-af31-13fd77f887c5/cebbf2c9-6cdc-47c5-b0cb-ee9928aa5cf3.jpg"
alt="ترف العود">

</div>


<div>

<div style="color:#c89b5b">
اختيار ترف العود
</div>

<h2>
أزرق كلمنتان
</h2>

<p>
قطعة مختارة لعشاق العود الإندونيسي،
بتفاصيل طبيعية ومظهر يليق بتجربة فاخرة.
</p>

<div class="featured-price">
300 ريال
</div>

<div style="color:#bbb;font-size:13px;margin-bottom:20px">
50 جرام
</div>

<button
class="btn btn-gold"
onclick="openOrder('أزرق كلمنتان')">

اطلبه الآن عبر واتساب

</button>

</div>

</div>

</section>


<!-- لماذا ترف العود -->

<section class="section"
id="about">

<div class="title">

<div class="small">
لماذا ترف العود؟
</div>

<h2>
الفخامة في التفاصيل
</h2>

<p>
تجربة بسيطة، واضحة وفاخرة
</p>

</div>


<div class="why-grid">


<div class="why">

<div class="why-icon">
🌿
</div>

<h3>
اختيار بعناية
</h3>

<p>
نهتم بمظهر المنتج ونختار الأنواع
التي تناسب محبي العود.
</p>

</div>


<div class="why">

<div class="why-icon">
⚖️
</div>

<h3>
وزن واضح
</h3>

<p>
جميع المنتجات المعروضة هنا
بوزن 50 جرام.
</p>

</div>


<div class="why">

<div class="why-icon">
🤝
</div>

<h3>
تواصل مباشر
</h3>

<p>
بعد اختيار المنتج، يصلك الطلب
مباشرة إلى واتساب المتجر.
</p>

</div>


</div>

</section>


<!-- الشحن -->

<section class="shipping"
id="shipping">

<div class="section">

<div class="title">

<div class="small">
التوصيل
</div>

<h2>
نوصل طلبك
</h2>

<p>
يتم اختيار شركة الشحن المناسبة حسب المدينة
</p>

</div>


<div class="shipping-grid">


<div class="ship">

<div class="ship-icon">
📦
</div>

<h3>
SPL
</h3>

<p>
البريد السعودي
</p>

</div>


<div class="ship">

<div class="ship-icon">
🚚
</div>

<h3>
Aramex
</h3>

<p>
أرامكس
</p>

</div>


<div class="ship">

<div class="ship-icon">
🚀
</div>

<h3>
SMSA
</h3>

<p>
سمسا
</p>

</div>


<div class="ship">

<div class="ship-icon">
📍
</div>

<h3>
حسب المدينة
</h3>

<p>
يتم التنسيق عند الطلب
</p>

</div>


</div>

</div>

</section>


<!-- التواصل -->

<section class="contact"
id="contact">

<div class="section">

<div class="title"
style="color:white">

<div class="small">
خدمة العملاء
</div>

<h2>
جاهزين لطلبك
</h2>

<p>
اختر المنتج واضغط اطلب الآن
وسيتم تحويلك مباشرة إلى واتساب ترف العود.
</p>


<a
class="whatsapp-big"
href="https://wa.me/966539400955"
target="_blank">

💬 تواصل عبر واتساب

</a>

</div>

</div>

</section>


<!-- الفوتر -->

<footer>

<div class="footer-logo">
ترف <span>العود</span>
</div>

<p>
عود فاخر • اختيار بعناية • تجربة تليق بك
</p>

<p>
© 2026 ترف العود — جميع الحقوق محفوظة
</p>

</footer>


<!-- زر واتساب عائم -->

<a
class="whatsapp-float"
href="https://wa.me/966539400955"
target="_blank">

💬

</a>


<!-- نافذة الطلب -->

<div
class="modal"
id="orderModal">

<div class="modal-box">


<div class="modal-header">

<h2>
إتمام الطلب
</h2>

<button
class="close"
onclick="closeOrder()">

×

</button>

</div>


<div class="selected-product">

<div style="font-size:11px;color:#a9783d">
المنتج المختار
</div>

<strong id="selectedProduct">
</strong>

<div>
50 جرام — 300 ريال
</div>

</div>


<div class="form-group">

<label>
الاسم
</label>

<input
id="customerName"
placeholder="اكتب اسمك">

</div>


<div class="form-group">

<label>
رقم الجوال
</label>

<input
id="customerPhone"
placeholder="05xxxxxxxx">

</div>


<div class="form-group">

<label>
المدينة
</label>

<input
id="customerCity"
placeholder="مثال: الرياض">

</div>


<div class="form-group">

<label>
العنوان
</label>

<textarea
id="customerAddress"
placeholder="الحي، الشارع، رقم المبنى...">
</textarea>

</div>


<div class="form-group">

<label>
شركة الشحن المفضلة
</label>

<select id="shippingCompany">

<option>
SPL - البريد السعودي
</option>

<option>
Aramex - أرامكس
</option>

<option>
SMSA - سمسا
</option>

<option>
حسب المتاح
</option>

</select>

</div>


<div class="form-group">

<label>
ملاحظات
</label>

<textarea
id="notes"
placeholder="أي ملاحظات على الطلب...">
</textarea>

</div>


<button
class="send-order"
onclick="sendOrder()">

📲 إرسال الطلب مباشرة عبر واتساب

</button>


</div>

</div>


<script>

/* =========================
   رقم واتساب المتجر
========================= */

const STORE_WHATSAPP =
"966539400955";


let selectedProduct = "";


/* =========================
   فتح الطلب
========================= */

function openOrder(product){

selectedProduct = product;

document
.getElementById("selectedProduct")
.innerText = product;

document
.getElementById("orderModal")
.classList.add("show");

}


/* =========================
   إغلاق الطلب
========================= */

function closeOrder(){

document
.getElementById("orderModal")
.classList.remove("show");

}


/* =========================
   إرسال الطلب
========================= */

function sendOrder(){

const name =
document
.getElementById("customerName")
.value
.trim();

const phone =
document
.getElementById("customerPhone")
.value
.trim();

const city =
document
.getElementById("customerCity")
.value
.trim();

const address =
document
.getElementById("customerAddress")
.value
.trim();

const shipping =
document
.getElementById("shippingCompany")
.value;

const notes =
document
.getElementById("notes")
.value
.trim();


if(!name){

alert("اكتب الاسم أولاً");

return;

}


if(!phone){

alert("اكتب رقم الجوال");

return;

}


if(!city){

alert("اكتب المدينة");

return;

}


let message =

"السلام عليكم، أريد الطلب من متجر ترف العود 🌿\n\n"+

"المنتج: "+
selectedProduct+
"\n"+

"الوزن: 50 جرام\n"+

"السعر: 300 ريال\n\n"+

"بيانات العميل:\n"+

"الاسم: "+
name+
"\n"+

"الجوال: "+
phone+
"\n"+

"المدينة: "+
city+
"\n"+

"العنوان: "+
(address || "سيتم تحديده")+
"\n"+

"شركة الشحن: "+
shipping+
"\n";


if(notes){

message +=

"\nملاحظات:\n"+
notes;

}


message +=

"\n\nأرغب بتأكيد الطلب ومعرفة تكلفة الشحن.";

const url =

"https://wa.me/"+
STORE_WHATSAPP+
"?text="+
encodeURIComponent(message);


window.open(
url,
"_blank"
);

}


/* =========================
   النزول للمنتجات
========================= */

function scrollToProducts(){

document
.getElementById("products")
.scrollIntoView({
behavior:"smooth"
});

}


/* =========================
   إغلاق النافذة خارجها
========================= */

document
.getElementById("orderModal")
.addEventListener(
"click",
function(event){

if(event.target===this){

closeOrder();

}

});


</script>


</body>

</html>
