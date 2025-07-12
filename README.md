# www.taswiqinukum.com
خدمات تسويق الإلكتروني عبر الانترنت 
<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>تسويقنالكم | متجرك الإلكتروني الأنيق</title>
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
 <style>
  @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700;900&display=swap');
        
        :root {
            --primary-color: #00ebff;
            --primary-light: #ffd700;
            --secondary-color: #ffd700;
            --accent-color: #ffab91;
            --dark-color: #1a237e;
            --text-color: #2b2d42;
            --light-text: #f5f5f5;
            --light-bg: #f5f3ff;
            --card-bg: #ffffff;
            --success-color: #4caf50;
            --transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
            --shadow-sm: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
            --shadow-md: 0 10px 20px rgba(0,0,0,0.1), 0 6px 6px rgba(0,0,0,0.1);
            --shadow-lg: 0 14px 28px rgba(0,0,0,0.12), 0 10px 10px rgba(0,0,0,0.08);
            --border-radius: 12px;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Tajawal', sans-serif;
            background-color: var(--light-bg);
            color: var(--text-color);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        /* التصميم العام */
        .container {
            width: 100%;
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* الشريط العلوي */
        .top-bar {
            background-color: var(--primary-color);
            color: var(--light-text);
            padding: 15px 0;
            font-size: 0.9rem;
            box-shadow: var(--shadow-sm);
        }
        
        .top-bar-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .contact-info {
            display: flex;
            gap: 20px;
        }
        
        .contact-info a {
            color: var(--light-text);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 5px;
            transition: var(--transition);
        }
        
        .contact-info a:hover {
            color: var(--accent-color);
        }
        
        .social-links {
            display: flex;
            gap: 15px;
        }
        
        .social-links a {
            color: var(--light-text);
            transition: var(--transition);
        }
        
        .social-links a:hover {
            color: var(--accent-color);
            transform: translateY(-2px);
        }
        
        /* رأس الصفحة */
        header {
            background-color: var(--card-bg);
            box-shadow: var(--shadow-md);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
        }
        
        .logo img {
            height: 40px;
        }
        
        .logo-text {
            display: flex;
            flex-direction: column;
        }
        
        .logo-main {
            font-size: 1.8rem;
            font-weight: 900;
            color: var(--primary-color);
            line-height: 1;
        }
        
        .logo-sub {
            font-size: 0.7rem;
            color: var(--secondary-color);
            letter-spacing: 1px;
        }
        
        /* شريط البحث */
        .search-bar {
            flex-grow: 1;
            max-width: 600px;
            margin: 0 30px;
            position: relative;
        }
        
        .search-input {
            width: 100%;
            padding: 12px 20px;
            border: 2px solid var(--light-bg);
            border-radius: 30px;
            font-size: 1rem;
            outline: none;
            transition: var(--transition);
            background-color: var(--light-bg);
            padding-right: 50px;
        }
        
        .search-input:focus {
            border-color: var(--primary-light);
            background-color: var(--card-bg);
            box-shadow: 0 0 0 3px rgba(94, 53, 177, 0.2);
        }
        
        .search-btn {
            position: absolute;
            left: 15px;
            top: 50%;
            transform: translateY(-50%);
            background: none;
            border: none;
            color: var(--primary-color);
            cursor: pointer;
            font-size: 1.1rem;
        }
        
        /* أدوات المستخدم */
        .user-tools {
            display: flex;
            align-items: center;
            gap: 20px;
        }
        
        .user-tool {
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-decoration: none;
            color: var(--text-color);
            font-size: 0.8rem;
            transition: var(--transition);
        }
        
        .user-tool i {
            font-size: 1.4rem;
            margin-bottom: 3px;
        }
        
        .user-tool:hover {
            color: var(--primary-color);
        }
        
        .cart-count {
            position: absolute;
            top: -5px;
            left: 15px;
            background-color: var(--secondary-color);
            color: white;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.7rem;
            font-weight: bold;
        }
        
        /* القائمة الرئيسية */
        nav {
            background-color: var(--dark-color);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-link {
            position: relative;
        }
        
        .nav-link a {
            display: block;
            color: var(--light-text);
            text-decoration: none;
            padding: 15px 20px;
            transition: var(--transition);
            font-weight: 500;
        }
        
        .nav-link a:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }
        
        .nav-link.active a {
            background-color: var(--primary-light);
        }
        
        /* القائمة المنسدلة */
        .dropdown-menu {
            position: absolute;
            top: 100%;
            right: 0;
            background-color: var(--card-bg);
            width: 220px;
            border-radius: 0 0 var(--border-radius) var(--border-radius);
            box-shadow: var(--shadow-lg);
            opacity: 0;
            visibility: hidden;
            transition: var(--transition);
            z-index: 100;
        }
        
        .nav-link:hover .dropdown-menu {
            opacity: 1;
            visibility: visible;
        }
        
        .dropdown-menu a {
            color: var(--text-color);
            padding: 12px 20px;
            border-bottom: 1px solid rgba(0, 0, 0, 0.05);
        }
        
        .dropdown-menu a:hover {
            background-color: var(--light-bg);
            color: var(--primary-color);
        }
        
        /* قسم الهيرو */
        .hero {
            position: relative;
            height: 500px;
            background: linear-gradient(135deg, var(--primary-color), var(--dark-color));
            color: var(--light-text);
            overflow: hidden;
            margin-bottom: 50px;
        }
        
        .hero-content {
            position: relative;
            height: 100%;
            display: flex;
            align-items: center;
            z-index: 2;
        }
        
        .hero-text {
            max-width: 600px;
        }
        
        .hero-title {
            font-size: 3rem;
            font-weight: 900;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero-subtitle {
            font-size: 1.2rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: var(--secondary-color);
            color: white;
            border: none;
            border-radius: 30px;
            font-size: 1rem;
            font-weight: 600;
            text-decoration: none;
            cursor: pointer;
            transition: var(--transition);
            box-shadow: var(--shadow-sm);
        }
        
        .btn:hover {
            background-color: var(--accent-color);
            transform: translateY(-3px);
            box-shadow: var(--shadow-md);
        }
        
        .btn-outline {
            background-color: transparent;
            border: 2px solid var(--light-text);
            margin-right: 15px;
        }
        
        .btn-outline:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }
        
        .hero-image {
            position: absolute;
            left: 50%;
            bottom: 0;
            height: 90%;
            filter: drop-shadow(0 20px 30px rgba(0, 0, 0, 0.3));
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0% { transform: translateX(-50%) translateY(0px); }
            50% { transform: translateX(-50%) translateY(-20px); }
            100% { transform: translateX(-50%) translateY(0px); }
        }
        
        /* قسم المميزات */
        .features {
            padding: 80px 0;
            background-color: var(--card-bg);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }
        
        .section-title h2 {
            font-size: 2.2rem;
            color: var(--primary-color);
            margin-bottom: 15px;
            position: relative;
            display: inline-block;
        }
        
        .section-title h2::after {
            content: "";
            position: absolute;
            bottom: -10px;
            right: 50%;
            transform: translateX(50%);
            width: 80px;
            height: 4px;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            border-radius: 2px;
        }
        
        .section-title p {
            color: #666;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 30px;
            text-align: center;
            transition: var(--transition);
            box-shadow: var(--shadow-sm);
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: var(--shadow-md);
        }
        
        .feature-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, var(--primary-light), var(--primary-color));
            color: white;
            border-radius: 50%;
            font-size: 1.8rem;
        }
        
        .feature-title {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: var(--primary-color);
        }
        
        /* قسم المنتجات */
        .products {
            padding: 80px 0;
        }
        
        .products-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
        }
        
        .products-tabs {
            display: flex;
            gap: 10px;
        }
        
        .tab-btn {
            padding: 8px 20px;
            background-color: transparent;
            border: 1px solid #ddd;
            border-radius: 30px;
            cursor: pointer;
            transition: var(--transition);
        }
        
        .tab-btn.active, .tab-btn:hover {
            background-color: var(--primary-color);
            color: white;
            border-color: var(--primary-color);
        }
        
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 30px;
        }
        
        .product-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            overflow: hidden;
            transition: var(--transition);
            box-shadow: var(--shadow-sm);
            position: relative;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-md);
        }
        
        .product-badge {
            position: absolute;
            top: 15px;
            right: 15px;
            background-color: var(--secondary-color);
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.8rem;
            font-weight: bold;
            z-index: 2;
        }
        
        .product-image {
            height: 250px;
            background-size: cover;
            background-position: center;
            position: relative;
            overflow: hidden;
        }
        
        .product-actions {
            position: absolute;
            bottom: -50px;
            left: 0;
            width: 100%;
            display: flex;
            justify-content: center;
            gap: 15px;
            padding: 15px;
            background-color: rgba(0, 0, 0, 0.7);
            transition: var(--transition);
        }
        
        .product-card:hover .product-actions {
            bottom: 0;
        }
        
        .action-btn {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: var(--card-bg);
            color: var(--primary-color);
            border: none;
            cursor: pointer;
            transition: var(--transition);
        }
        
        .action-btn:hover {
            background-color: var(--primary-color);
            color: white;
            transform: rotate(360deg);
        }
        
        .product-info {
            padding: 20px;
        }
        
        .product-category {
            color: var(--primary-light);
            font-size: 0.8rem;
            margin-bottom: 5px;
            display: block;
        }
        
        .product-title {
            font-weight: 700;
            margin-bottom: 10px;
            font-size: 1.1rem;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }
        
        .product-rating {
            color: #ffc107;
            margin-bottom: 15px;
            font-size: 0.9rem;
        }
        
        .product-price {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .price {
            font-weight: bold;
            color: var(--primary-color);
            font-size: 1.2rem;
        }
        
        .original-price {
            text-decoration: line-through;
            color: #999;
            font-size: 0.9rem;
            margin-left: 5px;
        }
        
        .add-to-cart {
            background-color: var(--primary-color);
            color: white;
            border: none;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: var(--transition);
        }
        
        .add-to-cart:hover {
            background-color: var(--primary-light);
            transform: scale(1.1);
        }
        
        /* قسم العروض */
        .offer-banner {
            background: linear-gradient(135deg, var(--secondary-color), #ff8a65);
            color: white;
            padding: 60px 0;
            margin: 50px 0;
            position: relative;
            overflow: hidden;
        }
        
        .offer-content {
            position: relative;
            z-index: 2;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .offer-text {
            max-width: 600px;
        }
        
        .offer-title {
            font-size: 2.5rem;
            font-weight: 900;
            margin-bottom: 20px;
        }
        
        .offer-description {
            font-size: 1.1rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }
        
        .offer-image {
            height: 300px;
            filter: drop-shadow(0 10px 20px rgba(0, 0, 0, 0.2));
            animation: pulse 2s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .offer-shape {
            position: absolute;
            width: 300px;
            height: 300px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
        }
        
        .shape-1 {
            top: -100px;
            left: -100px;
        }
        
        .shape-2 {
            bottom: -150px;
            right: -100px;
            width: 400px;
            height: 400px;
        }
        
        /* قسم المدونة */
        .blog {
            padding: 80px 0;
            background-color: var(--light-bg);
        }
        
        .blog-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 30px;
        }
        
        .blog-card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            overflow: hidden;
            transition: var(--transition);
            box-shadow: var(--shadow-sm);
        }
        
        .blog-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-md);
        }
        
        .blog-image {
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        
        .blog-content {
            padding: 20px;
        }
        
        .blog-date {
            color: var(--primary-light);
            font-size: 0.8rem;
            margin-bottom: 10px;
            display: block;
        }
        
        .blog-title {
            font-weight: 700;
            margin-bottom: 15px;
            font-size: 1.2rem;
        }
        
        .blog-excerpt {
            color: #666;
            margin-bottom: 20px;
            display: -webkit-box;
            -webkit-line-clamp: 3;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }
        
        .read-more {
            color: var(--primary-color);
            text-decoration: none;
            font-weight: 600;
            display: inline-flex;
            align-items: center;
            gap: 5px;
            transition: var(--transition);
        }
        
        .read-more:hover {
            color: var(--primary-light);
            gap: 10px;
        }
        
        /* النشرة البريدية */
        .newsletter {
            padding: 80px 0;
            background: linear-gradient(135deg, var(--primary-color), var(--dark-color));
            color: white;
            text-align: center;
        }
        
        .newsletter .section-title h2 {
            color: white;
        }
        
        .newsletter-form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            gap: 10px;
        }
        
        .newsletter-input {
            flex-grow: 1;
            padding: 15px 20px;
            border: none;
            border-radius: 30px;
            font-size: 1rem;
            outline: none;
        }
        
        .newsletter-btn {
            padding: 15px 30px;
            background-color: var(--secondary-color);
            color: white;
            border: none;
            border-radius: 30px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
        }
        
        .newsletter-btn:hover {
            background-color: var(--accent-color);
            transform: translateY(-3px);
        }
        
        /* التذييل */
        footer {
            background-color: var(--dark-color);
            color: var(--light-text);
            padding: 60px 0 0;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-column h3 {
            font-size: 1.3rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-column h3::after {
            content: "";
            position: absolute;
            bottom: 0;
            right: 0;
            width: 50px;
            height: 3px;
            background-color: var(--secondary-color);
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-link {
            margin-bottom: 10px;
        }
        
        .footer-link a {
            color: rgba(255, 255, 255, 0.7);
            text-decoration: none;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .footer-link a:hover {
            color: white;
            transform: translateX(5px);
        }
        
        .footer-link i {
            font-size: 0.8rem;
        }
        
        .contact-info-item {
            display: flex;
            align-items: flex-start;
            gap: 15px;
            margin-bottom: 15px;
        }
        
        .contact-info-item i {
            margin-top: 3px;
        }
        
        .footer-bottom {
            background-color: rgba(0, 0, 0, 0.2);
            padding: 20px 0;
            text-align: center;
            font-size: 0.9rem;
        }
        
        /* تأثيرات التحميل */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .animate-fade {
            animation: fadeIn 0.6s ease-out forwards;
        }
        
        .delay-1 { animation-delay: 0.2s; }
        .delay-2 { animation-delay: 0.4s; }
        .delay-3 { animation-delay: 0.6s; }
        
        /* تصميم متجاوب */
        @media (max-width: 1200px) {
            .hero-title {
                font-size: 2.5rem;
            }
            
            .offer-title {
                font-size: 2rem;
            }
        }
        
        @media (max-width: 992px) {
            .header-content {
                flex-wrap: wrap;
                gap: 20px;
            }
            
            .search-bar {
                order: 3;
                width: 100%;
                max-width: 100%;
                margin: 0;
            }
            
            .hero-content {
                text-align: center;
            }
            
            .hero-text {
                margin: 0 auto;
            }
            
            .hero-image {
                display: none;
            }
            
            .offer-content {
                flex-direction: column;
                text-align: center;
            }
            
            .offer-text {
                margin-bottom: 30px;
            }
        }
        
        @media (max-width: 768px) {
            .top-bar-content {
                flex-direction: column;
                gap: 10px;
            }
            
            .nav-links {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .nav-link a {
                padding: 10px 15px;
            }
            
            .hero-title {
                font-size: 2rem;
            }
            
            .hero-subtitle {
                font-size: 1rem;
            }
            
            .section-title h2 {
                font-size: 1.8rem;
            }
            
            .newsletter-form {
                flex-direction: column;
            }
        }
        
        @media (max-width: 576px) {
            .products-tabs {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .products-grid {
                grid-template-columns: 1fr;
            }
            
            .blog-grid {
                grid-template-columns: 1fr;
            }
        }
 </style>
</head>

<body>
 <!-- الشريط العلوي -->
 <div class="top-bar">
  <div class="container top-bar-content">
   <div class="contact-info">
    <a href="tel:+213561194538"><i class="fas fa-phone"></i> +213 561194538</a>
    <a href="ahmedshuahmedshu@gmail.com"><i class="fas fa-envelope"></i>ahmedshuahmedshu@gmail.com</a>
   </div>
   <div class="social-links">
    <a href="https://www.facebook.com/profile.php?id=100092551502942"><i class="fab fa-facebook-f"></i></a>
    <a href="#"><i class="fab fa-twitter"></i></a>
    <a href="#"><i class="fab fa-instagram"></i></a>
    <a href="#"><i class="fab fa-youtube"></i></a>
   </div>
  </div>
 </div>

 <!-- رأس الصفحة -->
 <header>
  <div class="container header-content">
   <a href="#" class="logo">
    <img src="https://b.top4top.io/p_34798ndw30.png" alt="TASWIQINALUKUM Logo">
    <div class="logo-text">
     <span class="logo-main">تسويقنا</span>
     <span class="logo-sub">لكم</span>
    </div>
   </a>

   <div class="search-bar">
    <input type="text" class="search-input" placeholder="ابحث عن منتجات...">
    <button class="search-btn"><i class="fas fa-search"></i></button>
   </div>

   <div class="user-tools">
    <a href="#" class="user-tool">
     <i class="far fa-user"></i>
     <span>حسابي</span>
    </a>
    <a href="#" class="user-tool">
     <i class="far fa-heart"></i>
     <span>المفضلة</span>
    </a>
    <a href="#" class="user-tool">
     <i class="fas fa-shopping-cart"></i>
     <span>السلة</span>
     <span class="cart-count">0</span>
    </a>
   </div>
  </div>

  <nav>
   <div class="container">
    <ul class="nav-links">
     <li class="nav-link active"><a href="#">الرئيسية</a></li>
     <li class="nav-link">
      <a href="#">المنتجات <i class="fas fa-chevron-down"></i></a>
      <div class="dropdown-menu">
       <a href="#">إلكترونيات</a>
       <a href="#">أزياء</a>
       <a href="#">منزلية</a>
       <a href="#">رياضية</a>
      </div>
     </li>
     <li class="nav-link"><a href="#">العروض</a></li>
     <li class="nav-link"><a href="#">المتجر</a></li>
     <li class="nav-link"><a href="#">المدونة</a></li>
     <li class="nav-link"><a href="#">اتصل بنا</a></li>
    </ul>
   </div>
  </nav>
 </header>

 <!-- قسم الهيرو -->
 <section class="hero">
  <div class="container hero-content animate-fade">
   <div class="hero-text">
    <h1 class="hero-title">أحدث المنتجات بأسعار تنافسية</h1>
    <p class="hero-subtitle">اكتشف تشكيلتنا الواسعة من المنتجات عالية الجودة التي تلبي جميع احتياجاتك</p>
    <div class="hero-buttons">
     <a href="#" class="btn btn-outline">تصفح المنتجات</a>
     <a href="#" class="btn">تسوق الآن</a>
    </div>
   </div>
   <img src="https://via.placeholder.com/500x500" alt="Hero Product" class="hero-image">
  </div>
 </section>
 <img src="https://b.top4top.io/p_34798ndw30.png" width="350" height="350">

 <!-- قسم المميزات -->
 <section class="features">
  <div class="container">
   <div class="section-title animate-fade">
    <h2>لماذا تختار متجر تسويقنالكم؟</h2>
    <p>نقدم لكم أفضل تجربة تسوق إلكتروني مع ضمان الجودة والسرعة في التوصيل</p>
   </div>

   <div class="features-grid">
    <div class="feature-card animate-fade delay-1">
     <div class="feature-icon">
      <i class="fas fa-truck"></i>
     </div>
     <h3 class="feature-title">توصيل سريع</h3>
     <p>توصيل خلال 24-48 ساعة لجميع أنحاء المملكة مع إمكانية التتبع المباشر</p>
    </div>

    <div class="feature-card animate-fade delay-2">
     <div class="feature-icon">
      <i class="fas fa-shield-alt"></i>
     </div>
     <h3 class="feature-title">دفع آمن</h3>
     <p>أنظمة دفع متعددة وآمنة مع حماية كاملة لبياناتك المالية</p>
    </div>

    <div class="feature-card animate-fade delay-3">
     <div class="feature-icon">
      <i class="fas fa-headset"></i>
     </div>
     <h3 class="feature-title">دعم فني 24/7</h3>
     <p>فريق دعم فني متاح على مدار الساعة لمساعدتك في أي استفسار</p>
    </div>
   </div>
  </div>
 </section>
 <!-- this script is provided by www.htmlfreecode.com coded by: Kerixa Inc. -->
 <!-- This Script is from www.htmlfreecode.com, Coded by: Krishna Eydat-->

 <div align="center">
  <FONT color="#ffd700" size="+1">
   <MARQUEE bgcolor="#00ebff" direction="right" loop="20" width="75%">
    <STRONG></STRONG>💛🩵🛍️🛒📦منتجاتكم👠🥿👟👞بيع👡👢🥾🩴🥼🧥🩳👚شراء🎽👕👖👔تسوق💄🪭🧼🪥🧴💍👄💅🧳💼👜👛👝🎒مع تسويقنالكم</STRONG>
   </MARQUEE>
  </FONT>
 </DIV>

 <font face="TASWIQINALUKUM"><a target="_blank" href="http://www.htmlfreecode.com/"><span style="font-size: 8pt; text-decoration: none"></span></a></font>
 <a target='_blank' href='www.htmlfreecode.com' style='font-size: 8pt; text-decoration: none'></a>
 <!-- قسم المنتجات -->
 <section class="products">
  <div class="container">
   <div class="products-header animate-fade">
    <h2 class="section-title">أحدث المنتجات</h2>
    <div class="products-tabs">
     <button class="tab-btn active">الكل</button>
     <button class="tab-btn">إلكترونيات</button>
     <button class="tab-btn">أزياء</button>
     <button class="tab-btn">منزلية</button>
    </div>
   </div>

   <div class="products-grid">
    <!-- المنتج 1 -->
    <div class="product-card animate-fade delay-1">
     <span class="product-badge">جديد</span>
     <div class="product-image" style="background-image: url('https://images.unsplash.com/photo-1546868871-7041f2a55e12?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')">
      <div class="product-actions">
       <button class="action-btn"><i class="far fa-heart"></i></button>
       <button class="action-btn"><i class="fas fa-search"></i></button>
       <button class="action-btn"><i class="fas fa-share-alt"></i></button>
      </div>
     </div>
     <div class="product-info">
      <span class="product-category">إلكترونيات</span>
      <h3 class="product-title">سماعات لاسلكية عالية الجودة</h3>
      <div class="product-rating">
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star-half-alt"></i>
       <span>(24)</span>
      </div>
      <div class="product-price">
       <div>
        <span class="price">399 د.ج</span>
        <span class="original-price">499 د.ج</span>
       </div>
       <button class="add-to-cart"><i class="fas fa-plus"></i></button>
      </div>
     </div>
    </div>

    <!-- المنتج 2 -->
    <div class="product-card animate-fade delay-2">
     <span class="product-badge">الأكثر مبيعاً</span>
     <div class="product-image" style="background-image: url('https://images.unsplash.com/photo-1523275335684-37898b6baf30?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')">
      <div class="product-actions">
       <button class="action-btn"><i class="far fa-heart"></i></button>
       <button class="action-btn"><i class="fas fa-search"></i></button>
       <button class="action-btn"><i class="fas fa-share-alt"></i></button>
      </div>
     </div>
     <div class="product-info">
      <span class="product-category">إلكترونيات</span>
      <h3 class="product-title">ساعة ذكية متطورة بشاشة لمس</h3>
      <div class="product-rating">
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="far fa-star"></i>
       <span>(18)</span>
      </div>
      <div class="product-price">
       <div>
        <span class="price">799 د.ج</span>
        <span class="original-price">999 د.ج</span>
       </div>
       <button class="add-to-cart"><i class="fas fa-plus"></i></button>
      </div>
     </div>
    </div>

    <!-- المنتج 3 -->
    <div class="product-card animate-fade delay-1">
     <div class="product-image" style="background-image: url('https://images.unsplash.com/photo-1491553895911-0055eca6402d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')">
      <div class="product-actions">
       <button class="action-btn"><i class="far fa-heart"></i></button>
       <button class="action-btn"><i class="fas fa-search"></i></button>
       <button class="action-btn"><i class="fas fa-share-alt"></i></button>
      </div>
     </div>
     <div class="product-info">
      <span class="product-category">أزياء</span>
      <h3 class="product-title">حذاء رياضي مريح للجري</h3>
      <div class="product-rating">
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <span>(32)</span>
      </div>
      <div class="product-price">
       <div>
        <span class="price">249 د.ج</span>
       </div>
       <button class="add-to-cart"><i class="fas fa-plus"></i></button>
      </div>
     </div>
    </div>

    <!-- المنتج 4 -->
    <div class="product-card animate-fade delay-2">
     <span class="product-badge">خصم 30%</span>
     <div class="product-image" style="background-image: url('https://images.unsplash.com/photo-1542291026-7eec264c27ff?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')">
      <div class="product-actions">
       <button class="action-btn"><i class="far fa-heart"></i></button>
       <button class="action-btn"><i class="fas fa-search"></i></button>
       <button class="action-btn"><i class="fas fa-share-alt"></i></button>
      </div>
     </div>
     <div class="product-info">
      <span class="product-category">أزياء</span>
      <h3 class="product-title">حقيبة ظهر أنيقة متعددة الاستخدامات</h3>
      <div class="product-rating">
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star-half-alt"></i>
       <i class="far fa-star"></i>
       <span>(12)</span>
      </div>
      <div class="product-price">
       <div>
        <span class="price">179 د.ج</span>
        <span class="original-price">259 د.ج</span>
       </div>
       <button class="add-to-cart"><i class="fas fa-plus"></i></button>
      </div>
     </div>
    </div>

    <!-- المنتج 5 -->
    <div class="product-card animate-fade delay-1">
     <div class="product-image" style="background-image: url('https://images.unsplash.com/photo-1556228453-efd6c1ff04f6?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')">
      <div class="product-actions">
       <button class="action-btn"><i class="far fa-heart"></i></button>
       <button class="action-btn"><i class="fas fa-search"></i></button>
       <button class="action-btn"><i class="fas fa-share-alt"></i></button>
      </div>
     </div>
     <div class="product-info">
      <span class="product-category">منزلية</span>
      <h3 class="product-title">طقم أدوات مطبخ فاخرة</h3>
      <div class="product-rating">
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <span>(45)</span>
      </div>
      <div class="product-price">
       <div>
        <span class="price">599 د.ج
                            </span>
       </div>
       <button class="add-to-cart"><i class="fas fa-plus"></i></button>
      </div>
     </div>
    </div>

    <!-- المنتج 6 -->
    <div class="product-card animate-fade delay-2">
     <span class="product-badge">جديد</span>
     <div class="product-image" style="background-image: url('https://images.unsplash.com/photo-1560343090-f0409e92791a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')">
      <div class="product-actions">
       <button class="action-btn"><i class="far fa-heart"></i></button>
       <button class="action-btn"><i class="fas fa-search"></i></button>
       <button class="action-btn"><i class="fas fa-share-alt"></i></button>
      </div>
     </div>
     <div class="product-info">
      <span class="product-category">منزلية</span>
      <h3 class="product-title">سجادة صلاة فاخرة</h3>
      <div class="product-rating">
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="fas fa-star"></i>
       <i class="far fa-star"></i>
       <span>(28)</span>
      </div>
      <div class="product-price">
       <div>
        <span class="price">129 د.ج</span>
        <span class="original-price">199 د.ج</span>
       </div>
       <button class="add-to-cart"><i class="fas fa-plus"></i></button>
      </div>
     </div>
    </div>
   </div>
  </div>
 </section>

 <!-- قسم العروض -->
 <section class="offer-banner">
  <div class="container">
   <div class="offer-content animate-fade">
    <div class="offer-text">
     <h2 class="offer-title">خصم يصل إلى 50% على تشكيلة الصيف</h2>
     <p class="offer-description">استمتع بأفضل العروض على المنتجات الموسمية لفترة محدودة فقط. تسوق الآن ووفر أكثر!</p>
     <a href="#" class="btn">استفد من العرض</a>
    </div>
    <img src="https://via.placeholder.com/400x300" alt="Summer Sale" class="offer-image">
    <div class="offer-shape shape-1"></div>
    <div class="offer-shape shape-2"></div>
   </div>
  </div>
 </section>

 <!-- قسم المدونة -->
 <section class="blog">
  <div class="container">
   <div class="section-title animate-fade">
    <h2>أحدث المقالات</h2>
    <p>اكتشف نصائح وأفكار مفيدة حول التسوق والمنتجات</p>
   </div>

   <div class="blog-grid">
    <!-- مقال 1 -->
    <div class="blog-card animate-fade delay-1">
     <div class="blog-image" style="background-image: url('https://images.unsplash.com/photo-1499750310107-5fef28a66643?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')"></div>
     <div class="blog-content">
      <span class="blog-date">15 يونيو 2023</span>
      <h3 class="blog-title">كيف تختار أفضل سماعات لاسلكية تناسب احتياجاتك</h3>
      <p class="blog-excerpt">دليل شامل لاختيار السماعات اللاسلكية المثالية بناءً على استخدامك اليومي وميزانيتك. تعرف على أهم المعايير التي يجب مراعاتها قبل الشراء.</p>
      <a href="#" class="read-more">اقرأ المزيد <i class="fas fa-chevron-left"></i></a>
     </div>
    </div>

    <!-- مقال 2 -->
    <div class="blog-card animate-fade delay-2">
     <div class="blog-image" style="background-image: url('https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')"></div>
     <div class="blog-content">
      <span class="blog-date">10 يونيو 2023</span>
      <h3 class="blog-title">أحدث صيحات الموضة الصيفية لهذا العام</h3>
      <p class="blog-excerpt">اكتشف أحدث اتجاهات الموضة للرجال والنساء في فصل الصيف. نقدم لك نصائح لتنسيق الإطلالات الأنيقة مع الحفاظ على الراحة.</p>
      <a href="#" class="read-more">اقرأ المزيد <i class="fas fa-chevron-left"></i></a>
     </div>
    </div>

    <!-- مقال 3 -->
    <div class="blog-card animate-fade delay-3">
     <div class="blog-image" style="background-image: url('https://images.unsplash.com/photo-1556911220-bff31c812dba?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80')"></div>
     <div class="blog-content">
      <span class="blog-date">5 يونيو 2023</span>
      <h3 class="blog-title">10 نصائح لتنظيم المطبخ بطرق مبتكرة</h3>
      <p class="blog-excerpt">طرق ذكية لتنظيم المطبخ وتوفير المساحة باستخدام أدوات بسيطة. تعلم كيف تحول مطبخك إلى مساحة عملية وجميلة في نفس الوقت.</p>
      <a href="#" class="read-more">اقرأ المزيد <i class="fas fa-chevron-left"></i></a>
     </div>
    </div>
   </div>
  </div>
 </section>
 <!-- this script is provided by www.htmlfreecode.com coded by: Kerixa Inc. -->
 <!-- This Script is from www.htmlfreecode.com, Coded by: Krishna Eydat-->

 <div align="center">
  <FONT color="#ffd700" size="+1">
   <MARQUEE bgcolor="#00ebff" direction="right" loop="20" width="75%">
    <STRONG>مرحبابكم في موقع تسويقنالكم ونشكركم على زيارتكم</STRONG>
   </MARQUEE>
  </FONT>
 </DIV>

 <font face="TASWIQINALUKUM"><a target="_blank" href="http://www.htmlfreecode.com/"><span style="font-size: 8pt; text-decoration: none"></span></a></font>
 <a target='_blank' href='www.htmlfreecode.com' style='font-size: 8pt; text-decoration: none'></a>
 <!-- النشرة البريدية -->
 <section class="newsletter">
  <div class="container">
   <div class="section-title animate-fade">
    <h2>اشترك في نشرتنا البريدية</h2>
    <p>احصل على آخر العروض والتخفيضات مباشرة إلى بريدك الإلكتروني</p>
   </div>

   <form class="newsletter-form animate-fade delay-1">
    <input type="email" class="newsletter-input" placeholder="أدخل بريدك الإلكتروني">
    <button type="submit" class="newsletter-btn">اشترك الآن</button>
   </form>
  </div>
 </section>

 <!-- التذييل -->
 <footer>
  <div class="container">
   <div class="footer-content">
    <div class="footer-column">
     <h3>عن المتجر</h3>
     <p>متجر تسويقنالكم هو وجهتك الأولى للتسوق الإلكتروني في الوطن العربي، نقدم منتجات عالية الجودة بأسعار تنافسية.</p>
     <div class="social-links" style="margin-top: 20px;">
      <a href="#"><i class="fab fa-facebook-f"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
      <a href="#"><i class="fab fa-youtube"></i></a>
     </div>
    </div>

    <div class="footer-column">
     <h3>روابط سريعة</h3>
     <ul class="footer-links">
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> الرئيسية</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> المنتجات</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> العروض</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> المدونة</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> اتصل بنا</a></li>
     </ul>
    </div>

    <div class="footer-column">
     <h3>خدمة العملاء</h3>
     <ul class="footer-links">
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> حسابي</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> تتبع الطلب</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> سياسة الإرجاع</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> الأسئلة الشائعة</a></li>
      <li class="footer-link"><a href="#"><i class="fas fa-chevron-left"></i> الشروط والأحكام</a></li>
     </ul>
    </div>

    <div class="footer-column">
     <h3>اتصل بنا</h3>
     <div class="contact-info-item">
      <i class="fas fa-map-marker-alt"></i>
      <span>الجزائر ولاية المنتدبة مسعد </span>
     </div>
     <div class="contact-info-item">
      <i class="fas fa-phone"></i>
      <span>+213 561194538</span>
     </div>
     <div class="contact-info-item">
      <i class="fas fa-envelope"></i>
      <span>ahmedshuahmedshu@gmail.com</span>
     </div>
     <div class="contact-info-item">
      <i class="fas fa-clock"></i>
      <span>الأحد - الخميس: 8 صباحاً - 10 مساءً</span>
     </div>
    </div>
   </div>
  </div>

  <div class="footer-bottom">
   <div class="container">
    <p>&copy; 2025 متجر تسويقنالكم . جميع الحقوق محفوظة.</p>
   </div>
  </div>
 </footer>

 <script>
  // كود جافاسكريبت بسيط للتفاعلية
        document.addEventListener('DOMContentLoaded', function() {
            // تغيير لون الشريط العلوي عند التمرير
            window.addEventListener('scroll', function() {
                const topBar = document.querySelector('.top-bar');
                if (window.scrollY > 50) {
                    topBar.style.backgroundColor = 'rgba(94, 53, 177, 0.9)';
                } else {
                    topBar.style.backgroundColor = 'var(--primary-color)';
                }
            });
            
            // تبديل علامات التبويب للمنتجات
            const tabBtns = document.querySelectorAll('.tab-btn');
            tabBtns.forEach(btn => {
                btn.addEventListener('click', function() {
                    tabBtns.forEach(b => b.classList.remove('active'));
                    this.classList.add('active');
