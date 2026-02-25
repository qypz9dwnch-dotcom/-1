<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>ساعات رولكس الفاخرة</title>

    <!-- خطوط Changa للعناوين + Tajawal للنصوص -->
    <link href="https://fonts.googleapis.com/css2?family=Changa:wght@500;600;700&family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">

    <style>
        /* النصوص العامة */
        body, p, span, button, div {
            font-family: 'Tajawal', sans-serif;
        }

        /* العناوين */
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Changa', sans-serif;
        }

        body {
            background-color: #f7f9fc;
            color: #222;
            margin: 0;
        }

        .topbar {
            background: #0a3d2e;
            color: #fff;
            padding: 14px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo-text {
            font-size: 22px;
            font-weight: bold;
            color: #f7d774;
        }
        .topbar-right span {
            margin-left: 18px;
            cursor: pointer;
        }

        .content {
            display: grid;
            grid-template-columns: 1fr 1.4fr;
            min-height: 100vh;
        }

        /* يسار */
        .left-panel {
            background: linear-gradient(135deg, #0a3d2e, #0f5f45);
            color: #fff;
            padding: 40px;
        }
        .left-panel h1 {
            color: #f7d774;
            font-size: 30px;
        }
        .left-panel p {
            line-height: 1.8;
            margin-top: 10px;
            max-width: 350px;
        }

        .watches-visual img {
            width: 100%;
            border-radius: 14px;
            margin-top: 25px;
        }

        .btn-main {
            margin-top: 20px;
            display: inline-block;
            padding: 10px 22px;
            background-color: #f7d774;
            color: #000;
            border-radius: 999px;
            font-weight: bold;
        }

        /* يمين */
        .right-panel {
            padding: 40px;
            background: #ffffff;
        }
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }
        .product-card {
            background: #f0f4f7;
            border-radius: 14px;
            padding: 15px;
            border: 1px solid #dcdcdc;
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
        }
        .product-name {
            font-size: 16px;
            margin-top: 10px;
        }
        .new-price {
            color: #0a3d2e;
            font-weight: bold;
        }
        .old-price {
            text-decoration: line-through;
            color: #777;
            margin-right: 6px;
        }
        .discount-tag {
            background: #f7d774;
            color: #000;
            padding: 4px 10px;
            border-radius: 999px;
            font-size: 12px;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 8px;
        }
        .btn-buy {
            margin-top: 10px;
            padding: 8px 14px;
            border-radius: 999px;
            border: 1px solid #0a3d2e;
            color: #0a3d2e;
            background: transparent;
            cursor: pointer;
        }
        .btn-buy:hover {
            background: #0a3d2e;
            color: #fff;
        }
    </style>
</head>
<body>

    <div class="topbar">
        <div class="logo-text">ROLEX</div>
        <div class="topbar-right">
            <span>البحث</span>
            <span>المفضلة</span>
            <span>حسابي</span>
            <span>السلة</span>
        </div>
    </div>

    <div class="content">

        <!-- يسار -->
        <div class="left-panel">
            <h1>ساعات رولكس الفاخرة</h1>
            <p>
                اكتشف الفخامة والأناقة مع أحدث موديلات رولكس الأصلية.
                تصميمات راقية، دقة سويسرية، وألوان منعشة تناسب كل الأذواق.
            </p>

            <div class="watches-visual">
                <img src="C:\Users\maria\Downloads\m279384rbr-0004.jpg" alt="Rolex Watches">
            </div>

            <a class="btn-main">اكتشف المزيد</a>
        </div>

        <!-- يمين -->
        <div class="right-panel">
            <h2>العروض المميزة</h2>

            <div class="products-grid">

                <div class="product-card">
                    <span class="discount-tag">20% OFF</span>
                    <img src="C:\Users\maria\Downloads\داي ديت.jpg">
                    <div class="product-name">داي ديت</div>
                    <div>
                        <span class="new-price">$151,000</span>
                        <span class="old-price">$281,000</span>
                    </div>
                    <button class="btn-buy">أضف للسلة</button>
                </div>

                <div class="product-card">
                    <span class="discount-tag">20% OFF</span>
                    <img src="C:\Users\maria\Downloads\دﻳﺖ ﺟﺴﺖ.jpg">
                    <div class="product-name">ديت جست</div>
                    <div>
                        <span class="new-price">$22,500</span>
                        <span class="old-price">$33,500</span>
                    </div>
                    <button class="btn-buy">أضف للسلة</button>
                </div>

                <div class="product-card">
                    <span class="discount-tag">20% OFF</span>
                    <img src="C:\Users\maria\Downloads\يدي ديت جست.jpg">
                    <div class="product-name">ليدي ديت جست</div>
                    <div>
                        <span class="new-price">$145,000</span>
                        <span class="old-price">$188,800</span>
                    </div>
                    <button class="btn-buy">أضف للسلة</button>
                </div>

                <div class="product-card">
                    <span class="discount-tag">20% OFF</span>
                    <img src="C:\Users\maria\Downloads\ﻛﻮزﻣﻮﻏﺮاف داﻳﺘﻮﻧﺎ.jpg">
                    <div class="product-name">كوزموغراف دايتونا</div>
                    <div>
                        <span class="new-price">$255,000</span>
                        <span class="old-price">$345,000</span>
                    </div>
                    <button class="btn-buy">أضف للسلة</button>
                </div>

            </div>
        </div>

    </div>

</body>
</html>
