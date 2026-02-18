# -
بن الكيف علي كيف كيفك 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>الكيف - Ghasaq cafe</title>
    <style>
        /* الخطوط والألوان */
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');

        body {
            margin: 0;
            font-family: 'Cairo', sans-serif;
            background-color: #243314; /* أخضر داكن من الشعار */
            color: #b3ac9c; /* لون فاتح قريب من الشعار */
            line-height: 1.6;
        }
        a {
            color: #b3ac9c;
            text-decoration: none;
        }
        a:hover {
            color: #d9d6ca;
        }

        /* الحاوية الرئيسية */
        .container {
            width: 90%;
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px 0;
        }

        /* الهيدر والشعار */
        header {
            background-color: #2b3a19;
            padding: 30px 0;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 40px;
        }
        .logo {
            font-size: 4rem;
            font-weight: 700;
            letter-spacing: 8px;
            margin-bottom: 8px;
            user-select: none;
        }
        .logo-sub {
            font-size: 1.5rem;
            font-style: italic;
            letter-spacing: 3px;
            color: #9e997f;
        }

        /* التنقل (القائمة) */
        nav {
            display: flex;
            justify-content: center;
            gap: 35px;
            margin-bottom: 50px;
            flex-wrap: wrap;
        }
        nav a {
            font-size: 1.2rem;
            padding: 8px 20px;
            border: 2px solid transparent;
            border-radius: 20px;
            transition: all 0.3s ease;
        }
        nav a:hover {
            border-color: #b3ac9c;
            background-color: #465527;
        }

        /* الأقسام */
        section {
            margin-bottom: 60px;
        }

        /* قسم التعريف */
        #about {
            font-size: 1.25rem;
            max-width: 900px;
            margin: 0 auto;
            text-align: center;
            color: #cdc8b1;
        }

        /* قسم المنتجات */
        #products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 30px;
        }
        .product-card {
            background-color: #3f4b23;
            border-radius: 15px;
            padding: 20px;
            color: #d9d6ca;
            box-shadow: 0 6px 15px rgba(15, 15, 15, 0.4);
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-10px);
        }
        .product-title {
            font-size: 1.6rem;
            margin-bottom: 12px;
            font-weight: 700;
        }
        .product-desc {
            font-size: 1.05rem;
            margin-bottom: 15px;
            color: #c3bda7;
        }
        .product-price {
            font-weight: bold;
            font-size: 1.3rem;
            color: #e6d8ac;
        }

        /* قسم التواصل */
        #contact {
            text-align: center;
            color: #cdc8b1;
        }
        #contact h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        #contact p {
            font-size: 1.1rem;
            margin: 5px 0;
        }
        #contact a {
            display: inline-block;
            margin-top: 10px;
            background-color: #465527;
            padding: 10px 25px;
            border-radius: 30px;
            color: #b3ac9c;
            font-weight: 600;
            box-shadow: 0 4px 10px rgba(70,85,39,0.6);
            transition: background-color 0.3s ease;
        }
        #contact a:hover {
            background-color: #6e7f3c;
        }

        /* الفوتر */
        footer {
            background-color: #2b3a19;
            text-align: center;
            padding: 20px 10px;
            font-size: 0.9rem;
            color: #999574;
            user-select: none;
        }

        /* Responsive */
        @media (max-width: 600px) {
            nav {
                gap: 15px;
            }
            .logo {
                font-size: 3rem;
                letter-spacing: 5px;
            }
            .product-card {
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">الكيف</div>
        <div class="logo-sub">على كيفك - Ghasaq cafe</div>
    </header>

    <nav>
        <a href="#about">من نحن</a>
        <a href="#products">منتجاتنا</a>
        <a href="#contact">تواصل معنا</a>
    </nav>

    <div class="container">
        
        <section id="about">
            <h2>مرحبا بكم في الكيف</h2>
            <p>محل الكيف هو مقصد عشاق البن الأصيل، حيث نقدم أجود أنواع القهوة المختارة يدوياً بدقة عالية. نحرص على تقديم تجربة فريدة من نوعها تمنحكم طعماً لا يُنسى ورائحة تأسر الحواس.</p>
        </section>

        <section id="products">
            <div class="product-card">
                <div class="product-title">بن عربي فاخر</div>
                <div class="product-desc">حبات البن المختارة بعناية من مزارع البن العربية الأصيلة، نكهة غنية وقوية.</div>
                <div class="product-price">120 جنيه / 250 جرام</div>
            </div>

            <div class="product-card">
                <div class="product-title">خليط الكيف الخاص</div>
                <div class="product-desc">مزيج متوازن من عدة أنواع بن يمنحك نكهة متفردة ومميزة.</div>
                <div class="product-price">150 جنيه / 250 جرام</div>
            </div>

            <div class="product-card">
                <div class="product-title">قهوة منزوعة الكافيين</div>
                <div class="product-desc">نكهة القهوة الكاملة بدون الكافيين، مثالية لمن يحب طعم القهوة بلا تأثير.</div>
                <div class="product-price">130 جنيه / 250 جرام</div>
            </div>
        </section>

        <section id="contact">
            <h2>تواصل معنا</h2>
            <p>العنوان: شارع البن، القاهرة، مصر</p>
            <p>الهاتف: 01234567890</p>
            <p>البريد الإلكتروني: info@ghasaqcafe.com</p>
            <a href="mailto:info@ghasaqcafe.com">ارسال بريد إلكتروني</a>
        </section>

    </div>

    <footer>
        جميع الحقوق محفوظة © 2024 الكيف - Ghasaq cafe.
    </footer>

</body>
</html>![Screenshot_20260212_181701_com android chrome_edit_297570167431152](https://github.com/user-attachments/assets/09ee5f13-291a-41b5-a8b1-1013ffe2b28e)
