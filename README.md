# rolex
most mark<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>FreshMart Supermarket | Online Shopping</title>

<meta name="description" content="FreshMart Supermarket online shopping website. Shop groceries, fresh fruits, vegetables, beverages and household products.">

<style>

/* =========================================
   GENERAL WEBSITE STYLING
========================================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #f7f8fa;
    color: #222;
    line-height: 1.6;
}

a {
    text-decoration: none;
    color: inherit;
}

button {
    cursor: pointer;
    border: none;
}

img {
    max-width: 100%;
}

.container {
    width: 92%;
    max-width: 1250px;
    margin: auto;
}


/* =========================================
   TOP INFORMATION BAR
========================================= */

.top-bar {
    background: #123d2a;
    color: white;
    padding: 9px 0;
    font-size: 13px;
}

.top-bar-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 15px;
    flex-wrap: wrap;
}

.top-bar a {
    color: #ffffff;
}


/* =========================================
   HEADER
========================================= */

header {
    background: white;
    padding: 18px 0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.header-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 25px;
}

.logo {
    font-size: 27px;
    font-weight: bold;
    color: #138347;
    white-space: nowrap;
}

.logo span {
    color: #f39c12;
}

.logo-icon {
    font-size: 30px;
}

.search-container {
    display: flex;
    flex: 1;
    max-width: 550px;
    border: 2px solid #138347;
    border-radius: 8px;
    overflow: hidden;
}

.search-container input {
    flex: 1;
    padding: 13px;
    border: none;
    outline: none;
    font-size: 15px;
    min-width: 0;
}

.search-container button {
    background: #138347;
    color: white;
    padding: 0 20px;
    font-size: 16px;
}

.header-actions {
    displajy: flex;
    align-items: center;
    gap: 20px;
}

.header-action {
    font-size: 14px;
    font-weight: bold;
}

.cart-button {
    background: #138347;
    color: white;
    padding: 12px 18px;
    border-radius: 8px;
    position: relative;
}

.cart-count {
    background: #f39c12;
    color: white;
    padding: 3px 7px;
    border-radius: 50%;
    font-size: 12px;
    margin-left: 5px;
}


/* =========================================
   NAVIGATION
========================================= */

nav {
    background: #138347;
    color: white;
}

.nav-content {
    display: flex;
    align-items: center;
    gap: 30px;
    padding: 13px 0;
    flex-wrap: wrap;
}

nav a {
    font-size: 14px;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: #ffd166;
}


/* =========================================
   HERO SECTION
========================================= */

.hero {
    background: linear-gradient(
        120deg,
        #123d2a,
        #138347
    );

    color: white;

    padding: 75px 0;

    overflow: hidden;
}

.hero-content {
    display: grid;
    grid-template-columns: 1.2fr 1fr;
    align-items: center;
    gap: 40px;
}

.hero-text h1 {
    font-size: 48px;
    line-height: 1.2;
    margin-bottom: 20px;
}

.hero-text h1 span {
    color: #ffd166;
}

.hero-text p {
    font-size: 17px;
    margin-bottom: 25px;
    max-width: 550px;
}

.hero-buttons {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.primary-button {
    display: inline-block;
    background: #f39c12;
    color: white;
    padding: 14px 25px;
    border-radius: 8px;
    font-weight: bold;
    transition: 0.3s;
}

.primary-button:hover {
    background: #e08a00;
    transform: translateY(-2px);
}

.secondary-button {
    display: inline-block;
    border: 2px solid white;
    color: white;
    padding: 12px 25px;
    border-radius: 8px;
    font-weight: bold;
}

.hero-image {
    text-align: center;
}

.hero-image img {
    width: 100%;
    max-width: 500px;
    border-radius: 20px;
}


/* =========================================
   BENEFITS
========================================= */

.benefits {
    background: white;
    padding: 25px 0;
}

.benefits-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.benefit {
    display: flex;
    align-items: center;
    gap: 12px;
}

.benefit-icon {
    font-size: 30px;
}

.benefit h3 {
    font-size: 15px;
    color: #123d2a;
}

.benefit p {
    font-size: 12px;
    color: #777;
}


/* =========================================
   SECTION HEADINGS
========================================= */

.section {
    padding: 60px 0;
}

.section-heading {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 30px;
    gap: 15px;
}

.section-heading h2 {
    font-size: 30px;
    color: #123d2a;
}

.section-heading p {
    color: #777;
    font-size: 14px;
}

.view-all {
    color: #138347;
    font-weight: bold;
}


/* =========================================
   CATEGORIES
========================================= */

.categories {
    background: #ffffff;
}

.category-grid {
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    gap: 20px;
}

.category-card {
    text-align: center;
    padding: 25px 15px;
    background: #f7f8fa;
    border-radius: 12px;
    transition: 0.3s;
    cursor: pointer;
}

.category-card:hover {
    transform: translateY(-5px);
    background: #e8f5ec;
}

.category-card img {
    width: 100px;
    height: 100px;
    object-fit: contain;
    margin-bottom: 15px;
}

.category-card h3 {
    font-size: 15px;
    color: #123d2a;
}


/* =========================================
   PROMOTION BANNER
========================================= */

.promotion {
    background: #fff3d6;
    padding: 35px;
    border-radius: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 25px;
    margin-bottom: 40px;
}

.promotion h2 {
    font-size: 28px;
    color: #123d2a;
}

.promotion p {
    color: #555;
    margin-top: 10px;
}

.promotion .primary-button {
    white-space: nowrap;
}


/* =========================================
   PRODUCT FILTERS
========================================= */

.filter-buttons {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    margin-bottom: 30px;
}

.filter-button {
    padding: 10px 18px;
    background: white;
    border: 1px solid #ddd;
    border-radius: 25px;
    font-size: 14px;
    transition: 0.3s;
}

.filter-button:hover,
.filter-button.active {
    background: #138347;
    color: white;
    border-color: #138347;
}


/* =========================================
   PRODUCTS GRID
========================================= */

.products-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 25px;
}

.product-card {
    background: white;
    border-radius: 12px;
    overflow: hidden;
    position: relative;
    transition: 0.3s;
    border: 1px solid #eee;
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.08);
}

.product-image {
    height: 220px;
    background: #f7f8fa;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.product-image img {
    width: 100%;
    height: 100%;
    object-fit: contain;
}

.product-badge {
    position: absolute;
    top: 12px;
    left: 12px;
    background: #f39c12;
    color: white;
    padding: 5px 10px;
    border-radius: 5px;
    font-size: 11px;
    font-weight: bold;
}

.product-details {
    padding: 20px;
}

.product-category {
    font-size: 12px;
    color: #138347;
    margin-bottom: 5px;
}

.product-name {
    font-size: 17px;
    font-weight: bold;
    margin-bottom: 8px;
}

.product-rating {
    color: #f39c12;
    font-size: 13px;
    margin-bottom: 12px;
}

.product-price {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 15px;
}

.current-price {
    font-size: 20px;
    font-weight: bold;
    color: #138347;
}

.old-price {
    font-size: 13px;
    color: #999;
    text-decoration: line-through;
}

.add-cart-button {
    width: 100%;
    background: #138347;
    color: white;
    padding: 12px;
    border-radius: 7px;
    font-weight: bold;
    transition: 0.3s;
}

.add-cart-button:hover {
    background: #0f6535;
}

.no-products {
    display: none;
    text-align: center;
    padding: 30px;
    color: #777;
}


/* =========================================
   ABOUT SECTION
========================================= */

.about {
    background: #eaf5ed;
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    align-items: center;
}

.about-image img {
    width: 100%;
    border-radius: 15px;
}

.about-text h2 {
    font-size: 35px;
    color: #123d2a;
    margin-bottom: 20px;
}

.about-text p {
    color: #555;
    margin-bottom: 20px;
}

.about-list {
    list-style: none;
}

.about-list li {
    margin-bottom: 12px;
    color: #123d2a;
    font-weight: bold;
}


/* =========================================
   STATISTICS
========================================= */

.statistics {
    background: #123d2a;
    color: white;
    padding: 45px 0;
}

.statistics-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    text-align: center;
}

.stat h2 {
    font-size: 35px;
    color: #ffd166;
}

.stat p {
    font-size: 14px;
}


/* =========================================
   CUSTOMER REVIEWS
========================================= */

.reviews {
    background: white;
}

.review-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.review-card {
    background: #f7f8fa;
    padding: 25px;
    border-radius: 12px;
}

.review-stars {
    color: #f39c12;
    margin-bottom: 15px;
}

.review-card p {
    font-size: 14px;
    color: #555;
    margin-bottom: 20px;
}

.review-author {
    font-weight: bold;
    color: #123d2a;
}


/* =========================================
   NEWSLETTER
========================================= */

.newsletter {
    background: #138347;
    color: white;
    padding: 55px 0;
}

.newsletter-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 30px;
}

.newsletter-text h2 {
    font-size: 30px;
    margin-bottom: 10px;
}

.newsletter-text p {
    font-size: 14px;
}

.newsletter-form {
    display: flex;
    width: 100%;
    max-width: 500px;
}

.newsletter-form input {
    flex: 1;
    padding: 15px;
    border: none;
    border-radius: 8px 0 0 8px;
    outline: none;
    min-width: 0;
}

.newsletter-form button {
    background: #f39c12;
    color: white;
    padding: 15px 20px;
    font-weight: bold;
    border-radius: 0 8px 8px 0;
}


/* =========================================
   CONTACT SECTION
========================================= */

.contact {
    background: #ffffff;
}

.contact-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.contact-card {
    padding: 25px;
    background: #f7f8fa;
    border-radius: 12px;
}

.contact-card h3 {
    color: #123d2a;
    margin-bottom: 10px;
}

.contact-card p {
    color: #777;
    font-size: 14px;
}


/* =========================================
   FOOTER
========================================= */

footer {
    background: #102e20;
    color: white;
    padding: 55px 0 20px;
}

.footer-grid {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 35px;
    margin-bottom: 40px;
}

.footer-column h3 {
    margin-bottom: 20px;
    color: #ffd166;
}

.footer-column p {
    font-size: 14px;
    color: #ccc;
    margin-bottom: 15px;
}

.footer-column ul {
    list-style: none;
}

.footer-column li {
    margin-bottom: 12px;
}

.footer-column a {
    font-size: 14px;
    color: #ccc;
    transition: 0.3s;
}

.footer-column a:hover {
    color: #ffd166;
}

.footer-bottom {
    border-top: 1px solid #345040;
    padding-top: 20px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 15px;
    font-size: 13px;
    color: #ccc;
}


/* =========================================
   SHOPPING CART
========================================= */

.cart-overlay {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.5);
    z-index: 2000;
}

.cart-overlay.show {
    display: block;
}

.cart-sidebar {
    position: fixed;
    top: 0;
    right: -450px;
    width: 420px;
    max-width: 100%;
    height: 100%;
    background: white;
    z-index: 2001;
    padding: 25px;
    transition: 0.3s;
    overflow-y: auto;
}

.cart-sidebar.open {
    right: 0;
}

.cart-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 25px;
}

.cart-header h2 {
    color: #123d2a;
}

.close-cart {
    background: #eee;
    width: 35px;
    height: 35px;
    border-radius: 50%;
    font-size: 20px;
}

.cart-item {
    display: flex;
    gap: 15px;
    padding: 15px 0;
    border-bottom: 1px solid #eee;
}

.cart-item img {
    width: 70px;
    height: 70px;
    object-fit: contain;
    background: #f7f8fa;
    border-radius: 8px;
}

.cart-item-details {
    flex: 1;
}

.cart-item-details h4 {
    font-size: 14px;
    margin-bottom: 5px;
}

.cart-item-price {
    color: #138347;
    font-weight: bold;
}

.quantity-controls {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-top: 8px;
}

.quantity-controls button {
    background: #eee;
    width: 25px;
    height: 25px;
    border-radius: 5px;
}

.remove-item {
    color: #e74c3c;
    background: none;
    font-size: 12px;
    margin-top: 5px;
}

.cart-summary {
    margin-top: 25px;
    padding-top: 20px;
    border-top: 2px solid #eee;
}

.cart-total {
    display: flex;
    justify-content: space-between;
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 20px;
}

.checkout-button {
    width: 100%;
    background: #138347;
    color: white;
    padding: 15px;
    border-radius: 8px;
    font-weight: bold;
}

.empty-cart {
    text-align: center;
    padding: 40px 0;
    color: #777;
}


/* =========================================
   CHECKOUT MODAL
========================================= */

.checkout-modal {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.6);
    z-index: 3000;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

.checkout-modal.show {
    display: flex;
}

.checkout-box {
    background: white;
    width: 550px;
    max-width: 100%;
    max-height: 90vh;
    overflow-y: auto;
    padding: 30px;
    border-radius: 15px;
}

.checkout-box h2 {
    color: #123d2a;
    margin-bottom: 20px;
}

.checkout-form {
    display: grid;
    gap: 15px;
}

.checkout-form label {
    font-weight: bold;
    font-size: 14px;
}

.checkout-form input,
.checkout-form textarea,
.checkout-form select {
    width: 100%;
    padding: 12px;
    border: 1px solid #ddd;
    border-radius: 7px;
    margin-top: 5px;
    outline: none;
}

.checkout-form input:focus,
.checkout-form textarea:focus,
.checkout-form select:focus {
    border-color: #138347;
}

.checkout-buttons {
    display: flex;
    gap: 10px;
}

.checkout-buttons button {
    flex: 1;
    padding: 13px;
    border-radius: 7px;
    font-weight: bold;
}

.cancel-checkout {
    background: #eee;
}

.confirm-order {
    background: #138347;
    color: white;
}


/* =========================================
   TOAST MESSAGE
========================================= */

.toast {
    position: fixed;
    bottom: 25px;
    left: 50%;
    transform: translateX(-50%);
    background: #123d2a;
    color: white;
    padding: 15px 25px;
    border-radius: 8px;
    z-index: 5000;
    display: none;
    box-shadow: 0 5px 20px rgba(0,0,0,0.2);
}

.toast.show {
    display: block;
}


/* =========================================
   BACK TO TOP
========================================= */

.back-to-top {
    position: fixed;
    bottom: 25px;
    right: 25px;
    background: #138347;
    color: white;
    width: 45px;
    height: 45px;
    border-radius: 50%;
    font-size: 20px;
    display: none;
    z-index: 1000;
}


/* =========================================
   RESPONSIVE DESIGN
========================================= */

@media (max-width: 1000px) {

    .products-grid {
        grid-template-columns: repeat(3, 1fr);
    }

    .category-grid {
        grid-template-columns: repeat(3, 1fr);
    }

    .benefits-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .hero-content {
        grid-template-columns: 1fr;
    }

    .hero-text {
        text-align: center;
    }

    .hero-text p {
        margin: 0 auto 25px;
    }

    .hero-buttons {
        justify-content: center;
    }

    .footer-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .header-content {
        flex-wrap: wrap;
    }

    .search-container {
        order: 3;
        max-width: 100%;
        flex-basis: 100%;
    }

}

@media (max-width: 700px) {

    .products-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 12px;
    }

    .category-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 12px;
    }

    .hero-text h1 {
        font-size: 35px;
    }

    .hero {
        padding: 50px 0;
    }

    .section {
        padding: 40px 0;
    }

    .section-heading h2 {
        font-size: 24px;
    }

    .promotion {
        flex-direction: column;
        align-items: flex-start;
    }

    .about-content {
        grid-template-columns: 1fr;
    }

    .statistics-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .review-grid {
        grid-template-columns: 1fr;
    }

    .newsletter-content {
        flex-direction: column;
        align-items: flex-start;
    }

    .contact-grid {
        grid-template-columns: 1fr;
    }

    .footer-grid {
        grid-template-columns: 1fr;
    }

    .top-bar-content {
        justify-content: center;
        text-align: center;
    }

    .nav-content {
        justify-content: center;
        gap: 15px;
    }

    .header-actions {
        gap: 10px;
    }

    .product-image {
        height: 150px;
    }

    .product-details {
        padding: 12px;
    }

    .product-name {
        font-size: 14px;
    }

    .current-price {
        font-size: 17px;
    }

    .product-price {
        flex-wrap: wrap;
    }

}

@media (max-width: 400px) {

    .products-grid {
        grid-template-columns: 1fr;
    }

    .product-image {
        height: 220px;
    }

    .logo {
        font-size: 22px;
    }

}

</style>

</head>


<body>


<!-- =====================================
     TOP BAR
===================================== -->

<div class="top-bar">

<div class="container top-bar-content">

<div>
🚚 Free delivery on orders above KSh 5,000
</div>

<div>
📞 Customer Support: 0700 000 000
</div>

<div>
📍 Serving customers across Kenya
</div>

</div>

</div>



<!-- =====================================
     HEADER
===================================== -->

<header>

<div class="container header-content">


<a href="#" class="logo">

<span class="logo-icon">🛒</span>

Fresh<span>Mart</span>

</a>


<div class="search-container">

<input

type="text"

id="searchInput"

placeholder="Search products, groceries, fruits..."

>

<button onclick="searchProducts()">

🔍 Search

</button>

</div>


<div class="header-actions">

<a href="#about" class="header-action">

About Us

</a>


<button class="cart-button" onclick="openCart()">

🛒 Cart

<span class="cart-count" id="cartCount">0</span>

</button>

</div>


</div>

</header>



<!-- =====================================
     NAVIGATION
===================================== -->

<nav>

<div class="container nav-content">

<a href="#">Home</a>

<a href="#categories">Categories</a>

<a href="#products">Products</a>

<a href="#about">About Us</a>

<a href="#reviews">Reviews</a>

<a href="#contact">Contact</a>

</div>

</nav>



<!-- =====================================
     HERO
===================================== -->

<section class="hero">

<div class="container hero-content">


<div class="hero-text">

<h1>

Fresh Food.

<br>

Fresh Prices.

<br>

<span>FreshMart.</span>

</h1>


<p>

Welcome to FreshMart Supermarket.

Discover fresh fruits, vegetables, groceries,

beverages and household products at affordable

prices. Shop conveniently and enjoy quality

products every day.

</p>


<div class="hero-buttons">

<a href="#products" class="primary-button">

Shop Now

</a>


<a href="#categories" class="secondary-button">

Explore Categories

</a>

</div>

</div>


<div class="hero-image">

<img

src="https://images.unsplash.com/photo-1542838132-92c53300491e?auto=format&fit=crop&w=900&q=85"

alt="Fresh supermarket groceries"

>

</div>


</div>

</section>



<!-- =====================================
     BENEFITS
===================================== -->

<section class="benefits">

<div class="container benefits-grid">


<div class="benefit">

<div class="benefit-icon">🚚</div>

<div>

<h3>Fast Delivery</h3>

<p>Convenient delivery options</p>

</div>

</div>


<div class="benefit">

<div class="benefit-icon">🥬</div>

<div>

<h3>Fresh Products</h3>

<p>Quality groceries every day</p>

</div>

</div>


<div class="benefit">

<div class="benefit-icon">💰</div>

<div>

<h3>Affordable Prices</h3>

<p>Great value for your money</p>

</div>

</div>


<div class="benefit">

<div class="benefit-icon">🔒</div>

<div>

<h3>Safe Shopping</h3>

<p>Convenient shopping experience</p>

</div>

</div>


</div>

</section>



<!-- =====================================
     CATEGORIES
===================================== -->

<section class="section categories" id="categories">

<div class="container">


<div class="section-heading">

<div>

<h2>Shop by Category</h2>

<p>Explore our supermarket departments</p>

</div>

</div>



<div class="category-grid">


<div class="category-card" onclick="filterProducts('Fruits')">

<img

src="https://images.unsplash.com/photo-1619566636858-adf3ef46400b?auto=format&fit=crop&w=300&q=80"

alt="Fresh fruits"

>

<h3>Fresh Fruits</h3>

</div>


<div class="category-card" onclick="filterProducts('Vegetables')">

<img

src="https://images.unsplash.com/photo-1540420773420-3366772f4999?auto=format&fit=crop&w=300&q=80"

alt="Vegetables"

>

<h3>Vegetables</h3>

</div>


<div class="category-card" onclick="filterProducts('Groceries')">

<img

src="https://images.unsplash.com/photo-1604719312566-8912e9c8a213?auto=format&fit=crop&w=300&q=80"

alt="Groceries"

>

<h3>Groceries</h3>

</div>


<div class="category-card" onclick="filterProducts('Drinks')">

<img

src="https://images.unsplash.com/photo-1544145945-f90425340c7e?auto=format&fit=crop&w=300&q=80"

alt="Drinks"

>

<h3>Drinks</h3>

</div>


<div class="category-card" onclick="filterProducts('Household')">

<img

src="https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=300&q=80"

alt="Household"

>

<h3>Household</h3>

</div>


<div class="category-card" onclick="filterProducts('Electronics')">

<img

src="https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=300&q=80"

alt="Electronics"

>

<h3>Electronics</h3>

</div>


</div>

</div>

</section>



<!-- =====================================
     PROMOTION
===================================== -->

<section class="container">

<div class="promotion">


<div>

<h2>FreshMart Special Offers 🎉</h2>

<p>

Enjoy amazing deals on selected groceries,

fresh produce and household products.

</p>

</div>


<a href="#products" class="primary-button">

Shop Offers

</a>


</div>

</section>



<!-- =====================================
     PRODUCTS
===================================== -->

<section class="section" id="products">

<div class="container">


<div class="section-heading">

<div>

<h2>Our Products</h2>

<p>Discover our supermarket products</p>

</div>


<a href="#products" class="view-all">

View Products →

</a>

</div>



<div class="filter-buttons">


<button

class="filter-button active"

onclick="filterProducts('All', this)"

>

All Products

</button>


<button

class="filter-button"

onclick="filterProducts('Fruits', this)"

>

Fruits

</button>


<button

class="filter-button"

onclick="filterProducts('Vegetables', this)"

>

Vegetables

</button>


<button

class="filter-button"

onclick="filterProducts('Groceries', this)"

>

Groceries

</button>


<button

class="filter-button"

onclick="filterProducts('Drinks', this)"

>

Drinks

</button>


<button

class="filter-button"

onclick="filterProducts('Household', this)"

>

Household

</button>


<button

class="filter-button"

onclick="filterProducts('Electronics', this)"

>

Electronics

</button>


</div>



<div class="products-grid" id="productsGrid">

</div>


<div class="no-products" id="noProducts">

No products found. Try another search.

</div>


</div>

</section>



<!-- =====================================
     ABOUT
===================================== -->

<section class="section about" id="about">

<div class="container about-content">


<div class="about-image">

<img

src="https://images.unsplash.com/photo-1542838132-92c53300491e?auto=format&fit=crop&w=800&q=80"

alt="FreshMart supermarket"

>

</div>


<div class="about-text">


<h2>

Welcome to FreshMart Supermarket

</h2>


<p>

FreshMart is your trusted destination for quality

groceries, fresh produce, household essentials

and everyday shopping needs.

</p>


<p>

Our mission is to make shopping convenient,

affordable and enjoyable for every customer.

We believe that quality products should be

available to everyone.

</p>


<ul class="about-list">

<li>✅ Quality products</li>

<li>✅ Affordable prices</li>

<li>✅ Friendly customer service</li>

<li>✅ Convenient shopping</li>

<li>✅ Fresh produce</li>

</ul>


<br>


<a href="#products" class="primary-button">

Start Shopping

</a>


</div>


</div>

</section>



<!-- =====================================
     STATISTICS
===================================== -->

<section class="statistics">

<div class="container statistics-grid">


<div class="stat">

<h2>500+</h2>

<p>Products Available</p>

</div>


<div class="stat">

<h2>1,000+</h2>

<p>Happy Customers</p>

</div>


<div class="stat">

<h2>7 Days</h2>

<p>Shopping Convenience</p>

</div>


<div class="stat">

<h2>100%</h2>

<p>Customer Commitment</p>

</div>


</div>

</section>



<!-- =====================================
     REVIEWS
===================================== -->

<section class="section reviews" id="reviews">

<div class="container">


<div class="section-heading">

<div>

<h2>Customer Reviews</h2>

<p>What our customers say</p>

</div>

</div>



<div class="review-grid">


<div class="review-card">

<div class="review-stars">

★★★★★

</div>

<p>

"FreshMart has a great selection of groceries.

The website is easy to use and the prices

are affordable."

</p>

<div class="review-author">

Customer Review

</div>

</div>



<div class="review-card">

<div class="review-stars">

★★★★★

</div>

<p>

"I enjoy shopping for fruits and vegetables

here. The products are easy to find and

the shopping experience is convenient."

</p>

<div class="review-author">

Customer Review

</div>

</div>



<div class="review-card">

<div class="review-stars">

★★★★★

</div>

<p>

"FreshMart makes grocery shopping easier.

I like the product categories and the

simple shopping cart."

</p>

<div class="review-author">

Customer Review

</div>

</div>


</div>

</div>

</section>



<!-- =====================================
     NEWSLETTER
===================================== -->

<section class="newsletter">

<div class="container newsletter-content">


<div class="newsletter-text">

<h2>Join the FreshMart Family</h2>

<p>

Subscribe to receive supermarket offers,

updates and shopping information.

</p>

</div>


<form

class="newsletter-form"

onsubmit="subscribeNewsletter(event)"

>

<input

type="email"

id="newsletterEmail"

placeholder="Enter your email address"

required

>

<button type="submit">

Subscribe

</button>

</form>


</div>

</section>



<!-- =====================================
     CONTACT
===================================== -->

<section class="section contact" id="contact">

<div class="container">


<div class="section-heading">

<div>

<h2>Contact FreshMart</h2>

<p>We are here to help you</p>

</div>

</div>



<div class="contact-grid">


<div class="contact-card">

<h3>📞 Phone</h3>

<p>

0700 000 000

</p>

</div>


<div class="contact-card">

<h3>📧 Email</h3>

<p>

info@freshmart.example

</p>

</div>


<div class="contact-card">

<h3>📍 Location</h3>

<p>

Kenya

</p>

</div>


</div>

</div>

</section>



<!-- =====================================
     FOOTER
===================================== -->

<footer>

<div class="container">


<div class="footer-grid">


<div class="footer-column">


<h3 class="logo">

Fresh<span>Mart</span>

</h3>


<p>

Your trusted supermarket for fresh groceries,

quality products and affordable prices.

</p>


<p>

Making everyday shopping easier.

</p>


</div>



<div class="footer-column">


<h3>Quick Links</h3>


<ul>

<li><a href="#">Home</a></li>

<li><a href="#products">Products</a></li>

<li><a href="#categories">Categories</a></li>

<li><a href="#about">About Us</a></li>

<li><a href="#contact">Contact</a></li>

</ul>


</div>



<div class="footer-column">


<h3>Departments</h3>


<ul>

<li><a href="#products">Fruits</a></li>

<li><a href="#products">Vegetables</a></li>

<li><a href="#products">Groceries</a></li>

<li><a href="#products">Drinks</a></li>

<li><a href="#products">Household</a></li>

</ul>


</div>



<div class="footer-column">


<h3>Customer Service</h3>


<ul>

<li><a href="#contact">Contact Us</a></li>

<li><a href="#contact">Delivery Information</a></li>

<li><a href="#contact">Customer Support</a></li>

<li><a href="#contact">Shopping Information</a></li>

</ul>


</div>


</div>



<div class="footer-bottom">


<p>

© <span id="currentYear"></span>

FreshMart Supermarket.

All Rights Reserved.

</p>


<p>

Fresh Food | Quality Products | Affordable Prices

</p>


</div>


</div>

</footer>



<!-- =====================================
     CART OVERLAY
===================================== -->

<div

class="cart-overlay"

id="cartOverlay"

onclick="closeCart()"

>

</div>



<!-- =====================================
     CART SIDEBAR
===================================== -->

<div class="cart-sidebar" id="cartSidebar">


<div class="cart-header">


<h2>Your Shopping Cart</h2>


<button

class="close-cart"

onclick="closeCart()"

>

×

</button>


</div>



<div id="cartItems">

</div>



<div class="cart-summary">


<div class="cart-total">


<span>Total:</span>


<span id="cartTotal">

KSh 0

</span>


</div>


<button

class="checkout-button"

onclick="openCheckout()"

>

Proceed to Checkout

</button>


</div>


</div>



<!-- =====================================
     CHECKOUT MODAL
===================================== -->

<div class="checkout-modal" id="checkoutModal">


<div class="checkout-box">


<h2>Checkout</h2>


<form

class="checkout-form"

id="checkoutForm"

onsubmit="submitOrder(event)"

>


<div>

<label>

Full Name

</label>

<input

type="text"

id="customerName"

placeholder="Enter your full name"

required

>

</div>



<div>

<label>

Phone Number

</label>

<input

type="tel"

id="customerPhone"

placeholder="Enter your phone number"

required

>

</div>



<div>

<label>

Email Address

</label>

<input

type="email"

id="customerEmail"

placeholder="Enter your email"

required

>

</div>



<div>

<label>

Delivery Address

</label>

<textarea

id="customerAddress"

placeholder="Enter your delivery location"

rows="3"

required

></textarea>

</div>



<div>

<label>

Payment Method

</label>

<select

id="paymentMethod"

required

>

<option value="">

Select Payment Method

</option>

<option value="Cash on Delivery">

Cash on Delivery

</option>

<option value="M-Pesa">

M-Pesa

</option>

</select>

</div>



<div id="checkoutTotal">

</div>



<div class="checkout-buttons">


<button

type="button"

class="cancel-checkout"

onclick="closeCheckout()"

>

Cancel

</button>


<button

type="submit"

class="confirm-order"

>

Place Order

</button>


</div>


</form>


</div>


</div>



<!-- =====================================
     TOAST
===================================== -->

<div class="toast" id="toast">

Product added to cart!

</div>



<!-- =====================================
     BACK TO TOP
===================================== -->

<button

class="back-to-top"

id="backToTop"

onclick="scrollToTop()"

>

↑

</button>



<!-- =====================================
     JAVASCRIPT
===================================== -->

<script>


/* =====================================
   PRODUCT DATABASE
===================================== */


const products = [

{

id: 1,

name: "Fresh Red Apples",

category: "Fruits",

price: 250,

oldPrice: 300,

image: "https://images.unsplash.com/photo-1560806887-1e4cd0b6cbd6?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★★"

},


{

id: 2,

name: "Fresh Bananas",

category: "Fruits",

price: 120,

oldPrice: 150,

image: "https://images.unsplash.com/photo-1571771894821-ce9b6c11b08e?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★★"

},


{

id: 3,

name: "Fresh Oranges",

category: "Fruits",

price: 180,

oldPrice: 220,

image: "https://images.unsplash.com/photo-1547514701-42782101795e?auto=format&fit=crop&w=500&q=80",

badge: "FRESH",

rating: "★★★★☆"

},


{

id: 4,

name: "Fresh Strawberries",

category: "Fruits",

price: 350,

oldPrice: 400,

image: "https://images.unsplash.com/photo-1464965911861-746a04b4bca6?auto=format&fit=crop&w=500&q=80",

badge: "NEW",

rating: "★★★★★"

},


{

id: 5,

name: "Fresh Tomatoes",

category: "Vegetables",

price: 100,

oldPrice: 130,

image: "https://images.unsplash.com/photo-1546094096-0df4bcaaa337?auto=format&fit=crop&w=500&q=80",

badge: "FRESH",

rating: "★★★★★"

},


{

id: 6,

name: "Fresh Carrots",

category: "Vegetables",

price: 90,

oldPrice: 120,

image: "https://images.unsplash.com/photo-1445282768818-728615cc910a?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★☆"

},


{

id: 7,

name: "Fresh Broccoli",

category: "Vegetables",

price: 180,

oldPrice: 220,

image: "https://images.unsplash.com/photo-1459411621453-7b03977f4bfc?auto=format&fit=crop&w=500&q=80",

badge: "FRESH",

rating: "★★★★★"

},


{

id: 8,

name: "Fresh Potatoes",

category: "Vegetables",

price: 150,

oldPrice: 180,

image: "https://images.unsplash.com/photo-1518977676601-b53f82aba655?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★☆"

},


{

id: 9,

name: "White Rice 2kg",

category: "Groceries",

price: 350,

oldPrice: 400,

image: "https://images.unsplash.com/photo-1586201375761-83865001e31c?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★★"

},


{

id: 10,

name: "Cooking Oil 1L",

category: "Groceries",

price: 280,

oldPrice: 320,

image: "https://images.unsplash.com/photo-1474979266404-7eaacbcd87c5?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★★"

},


{

id: 11,

name: "Wheat Flour 2kg",

category: "Groceries",

price: 180,

oldPrice: 200,

image: "https://images.unsplash.com/photo-1627485937980-221c88ac04f9?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★☆"

},


{

id: 12,

name: "Sugar 1kg",

category: "Groceries",

price: 160,

oldPrice: 180,

image: "https://images.unsplash.com/photo-1581441363689-1f3c3c414f0b?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★☆"

},


{

id: 13,

name: "Fresh Milk 1L",

category: "Drinks",

price: 100,

oldPrice: 120,

image: "https://images.unsplash.com/photo-1563636619-e9143da7973b?auto=format&fit=crop&w=500&q=80",

badge: "FRESH",

rating: "★★★★★"

},


{

id: 14,

name: "Orange Juice",

category: "Drinks",

price: 180,

oldPrice: 220,

image: "https://images.unsplash.com/photo-1600271886742-f049cd451bba?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★☆"

},


{

id: 15,

name: "Mineral Water",

category: "Drinks",

price: 80,

oldPrice: 100,

image: "https://images.unsplash.com/photo-1560023907-5f339617ea30?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★★"

},


{

id: 16,

name: "Soft Drink",

category: "Drinks",

price: 100,

oldPrice: 120,

image: "https://images.unsplash.com/photo-1629203851122-3726ecdf080e?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★☆"

},


{

id: 17,

name: "Laundry Detergent",

category: "Household",

price: 450,

oldPrice: 500,

image: "https://images.unsplash.com/photo-1600428853876-fb5a850b444f?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★★"

},


{

id: 18,

name: "Dishwashing Liquid",

category: "Household",

price: 180,

oldPrice: 220,

image: "https://images.unsplash.com/photo-1585421514738-01798e348b17?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★☆"

},


{

id: 19,

name: "Cleaning Sponge",

category: "Household",

price: 70,

oldPrice: 100,

image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★☆"

},


{

id: 20,

name: "Paper Towels",

category: "Household",

price: 250,

oldPrice: 300,

image: "https://images.unsplash.com/photo-1584556812952-905ffd0c611a?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★★"

},


{

id: 21,

name: "Wireless Headphones",

category: "Electronics",

price: 2500,

oldPrice: 3000,

image: "https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★★"

},


{

id: 22,

name: "Smart Watch",

category: "Electronics",

price: 3500,

oldPrice: 4000,

image: "https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=500&q=80",

badge: "NEW",

rating: "★★★★☆"

},


{

id: 23,

name: "Bluetooth Speaker",

category: "Electronics",

price: 1800,

oldPrice: 2200,

image: "https://images.unsplash.com/photo-1608043152269-423dbba4e7e1?auto=format&fit=crop&w=500&q=80",

badge: "SALE",

rating: "★★★★★"

},


{

id: 24,

name: "USB Charger",

category: "Electronics",

price: 900,

oldPrice: 1200,

image: "https://images.unsplash.com/photo-1591290619762-c5887d7f8b3c?auto=format&fit=crop&w=500&q=80",

badge: "POPULAR",

rating: "★★★★☆"

}

];



/* =====================================
   SHOPPING CART DATABASE
===================================== */


let cart = [];

let currentCategory = "All";

let currentSearch = "";



/* =====================================
   FORMAT CURRENCY
===================================== */


function formatCurrency(amount) {

return new Intl.NumberFormat("en-KE", {

style: "currency",

currency: "KES",

maximumFractionDigits: 0

}).format(amount);

}



/* =====================================
   DISPLAY PRODUCTS
===================================== */


function displayProducts() {


const productsGrid = document.getElementById("productsGrid");

const noProducts = document.getElementById("noProducts");


productsGrid.innerHTML = "";


const filteredProducts = products.filter(product => {


const matchesCategory =

currentCategory === "All" ||

product.category === currentCategory;


const matchesSearch =

product.name.toLowerCase().includes(currentSearch) ||

product.category.toLowerCase().includes(currentSearch);


return matchesCategory && matchesSearch;


});


if (filteredProducts.length === 0) {

noProducts.style.display = "block";

return;

}


noProducts.style.display = "none";


filteredProducts.forEach(product => {


const productCard = document.createElement("div");

productCard.className = "product-card";


productCard.innerHTML = `


<div class="product-badge">

${product.badge}

</div>


<div class="product-image">


<img

src="${product.image}"

alt="${product.name}"

loading="lazy"

onerror="this.src='https://placehold.co/400x300?text=FreshMart+Product'"

>


</div>


<div class="product-details">


<div class="product-category">

${product.category}

</div>


<h3 class="product-name">

${product.name}

</h3>


<div class="product-rating">

${product.rating}

</div>


<div class="product-price">


<span class="current-price">

${formatCurrency(product.price)}

</span>


<span class="old-price">

${formatCurrency(product.oldPrice)}

</span>


</div>


<button

class="add-cart-button"

onclick="addToCart(${product.id})"

>

🛒 Add to Cart

</button>


</div>


`;


productsGrid.appendChild(productCard);


});


}



/* =====================================
   FILTER PRODUCTS
===================================== */


function filterProducts(category, button) {


currentCategory = category;


if (button) {


document.querySelectorAll(".filter-button")

.forEach(btn => {

btn.classList.remove("active");

});


button.classList.add("active");


}


displayProducts();


document.getElementById("products")

.scrollIntoView({

behavior: "smooth"

});


}



/* =====================================
   SEARCH PRODUCTS
===================================== */


function searchProducts() {


const searchInput = document.getElementById("searchInput");


currentSearch = searchInput.value.toLowerCase().trim();


currentCategory = "All";


document.querySelectorAll(".filter-button")

.forEach(btn => {

btn.classList.remove("active");

});


document.querySelectorAll(".filter-button")[0]

.classList.add("active");


displayProducts();


document.getElementById("products")

.scrollIntoView({

behavior: "smooth"

});


}



/* =====================================
   LIVE SEARCH
===================================== */


document.getElementById("searchInput")

.addEventListener("input", function() {


currentSearch = this.value.toLowerCase().trim();


currentCategory = "All";


displayProducts();


});



/* =====================================
   ADD TO CART
===================================== */


function addToCart(productId) {


const product = products.find(

item => item.id === productId

);


if (!product) return;


const existingItem = cart.find(

item => item.id === productId

);


if (existingItem) {


existingItem.quantity++;


} else {


cart.push({

...product,

quantity: 1

});


}


updateCart();


showToast(product.name + " added to cart!");


}



/* =====================================
   UPDATE CART
===================================== */


function updateCart() {


const cartItems = document.getElementById("cartItems");


cartItems.innerHTML = "";


let total = 0;

let totalItems = 0;


if (cart.length === 0) {


cartItems.innerHTML = `

<div class="empty-cart">


<h3>Your cart is empty</h3>


<p>Add products to start shopping.</p>


</div>


`;


}


cart.forEach(item => {


const itemTotal = item.price * item.quantity;


total += itemTotal;


totalItems += item.quantity;


const cartItem = document.createElement("div");


cartItem.className = "cart-item";


cartItem.innerHTML = `


<img

src="${item.image}"

alt="${item.name}"

>


<div class="cart-item-details">


<h4>

${item.name}

</h4>


<div class="cart-item-price">

${formatCurrency(item.price)}

</div>


<div class="quantity-controls">


<button

onclick="changeQuantity(${item.id}, -1)"

>

-

</button>


<span>

${item.quantity}

</span>


<button

onclick="changeQuantity(${item.id}, 1)"

>

+

</button>


</div>


<button

class="remove-item"

onclick="removeFromCart(${item.id})"

>

Remove

</button>


</div>


`;


cartItems.appendChild(cartItem);


});


document.getElementById("cartCount")

.textContent = totalItems;


document.getElementById("cartTotal")

.textContent = formatCurrency(total);


document.getElementById("checkoutTotal")

.textContent = "Order Total: " + formatCurrency(total);


}



/* =====================================
   CHANGE PRODUCT QUANTITY
===================================== */


function changeQuantity(productId, change) {


const item = cart.find(

product => product.id === productId

);


if (!item) return;


item.quantity += change;


if (item.quantity <= 0) {


removeFromCart(productId);


return;


}


updateCart();


}



/* =====================================
   REMOVE PRODUCT
===================================== */


function removeFromCart(productId) {


cart = cart.filter(

item => item.id !== productId

);


updateCart();


showToast("Product removed from cart");


}



/* =====================================
   OPEN CART
===================================== */


function openCart() {


document.getElementById("cartSidebar")

.classList.add("open");


document.getElementById("cartOverlay")

.classList.add("show");


}



/* =====================================
   CLOSE CART
===================================== */


function closeCart() {


document.getElementById("cartSidebar")

.classList.remove("open");


document.getElementById("cartOverlay")

.classList.remove("show");


}



/* =====================================
   OPEN CHECKOUT
===================================== */


function openCheckout() {


if (cart.length === 0) {


showToast("Your cart is empty");


return;


}


closeCart();


document.getElementById("checkoutModal")

.classList.add("show");


}



/* =====================================
   CLOSE CHECKOUT
===================================== */


function closeCheckout() {


document.getElementById("checkoutModal")

.classList.remove("show");


}



/* =====================================
   SUBMIT ORDER
===================================== */


function submitOrder(event) {


event.preventDefault();


if (cart.length === 0) {


showToast("Your cart is empty");


return;


}


const customerName =

document.getElementById("customerName").value;


const customerPhone =

document.getElementById("customerPhone").value;


const customerEmail =

document.getElementById("customerEmail").value;


const customerAddress =

document.getElementById("customerAddress").value;


const paymentMethod =

document.getElementById("paymentMethod").value;


let orderTotal = 0;


cart.forEach(item => {


orderTotal += item.price * item.quantity;


});


const orderNumber =

"FM" + Date.now().toString().slice(-8);



const orderDetails = cart.map(item => {


return {


name: item.name,


quantity: item.quantity,


price: item.price,


subtotal: item.price * item.quantity


};


});


const order = {


orderNumber: orderNumber,


customerName: customerName,


customerPhone: customerPhone,


customerEmail: customerEmail,


customerAddress: customerAddress,


paymentMethod: paymentMethod,


products: orderDetails,


total: orderTotal,


orderDate: new Date().toISOString()


};



console.log("Customer Order:", order);



alert(


"Thank you, " + customerName + "!\n\n" +


"Your order number is: " + orderNumber + "\n\n" +


"Total: " + formatCurrency(orderTotal) + "\n\n" +


"Payment Method: " + paymentMethod + "\n\n" +


"This demo has recorded the order in your browser session only. " +


"A real supermarket order system requires a secure backend."


);



cart = [];


updateCart();


closeCheckout();


document.getElementById("checkoutForm").reset();


}



/* =====================================
   NEWSLETTER
===================================== */


function subscribeNewsletter(event) {


event.preventDefault();


const email =

document.getElementById("newsletterEmail").value;


if (!email) {


showToast("Please enter your email");


return;


}


showToast("Thank you for subscribing!");


document.getElementById("newsletterEmail").value = "";


}



/* =====================================
   TOAST MESSAGE
===================================== */


function showToast(message) {


const toast = document.getElementById("toast");


toast.textContent = message;


toast.classList.add("show");


setTimeout(() => {


toast.classList.remove("show");


}, 3000);


}



/* =====================================
   BACK TO TOP
===================================== */


function scrollToTop() {


window.scrollTo({

top: 0,

behavior: "smooth"

});


}



/* =====================================
   SHOW BACK TO TOP BUTTON
===================================== */


window.addEventListener("scroll", function() {


const button = document.getElementById("backToTop");


if (window.scrollY > 400) {


button.style.display = "block";


} else {


button.style.display = "none";


}


});



/* =====================================
   CLOSE MODAL WHEN CLICKING OUTSIDE
===================================== */


document.getElementById("checkoutModal")

.addEventListener("click", function(event) {


if (event.target === this) {


closeCheckout();


}


});



/* =====================================
   CLOSE CART WITH ESCAPE KEY
===================================== */


document.addEventListener("keydown", function(event) {


if (event.key === "Escape") {


closeCart();


closeCheckout();


}


});



/* =====================================
   CURRENT YEAR
===================================== */


document.getElementById("currentYear")

.textContent = new Date().getFullYear();



/* =====================================
   INITIALIZE WEBSITE
===================================== */


displayProducts();


updateCart();



</script>


</body>

</html>etable coding
