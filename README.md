<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0, user-scalable=yes">
    <title>MuMaCodes المجتمع</title>
     
    <meta name="description" content="انضم مجتمع عربي للمبرمجين والطلاب: +1200 عضو، 8 مجموعات تخصصية، دعم يومي، كروب نقاشات ومساعدة برمجية. مكانك الصحيح لتعلم البرمجة.">
    <meta name="keywords" content="مجتمع مبرمجين عرب, تعلم البرمجة, برمجة عربي, طلاب برمجة, مساعدة برمجية, واتساب برمجة, MuMaCodes, مبرمجين مبتدئين">
    <meta name="author" content="MuMaCodes Community">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://mumacodes.online">
    <meta property="og:title" content="MuMaCodes · مجتمع المبرمجين والطلاب">
    <meta property="og:description" content="+1200 مبرمج وطالب، 8 مجموعات تخصصية، كروب نقاشات ومساعدة. انضم الآن مجاناً">
    <meta property="og:image" content="/1.png">
    <meta property="og:url" content="https://mumacodes.online">
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="MuMaCodes">
    <meta property="og:locale" content="ar_AR">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="MuMaCodes · مجتمع المبرمجين والطلاب">
    <meta name="twitter:description" content="انضم لأكبر مجتمع عربي للمبرمجين والطلاب: دعم يومي، 8 مجموعات، +1200 عضو">
    <meta name="twitter:image" content="/2.png">
    <link rel="icon" type="image/png" href="/1.png">
    <link rel="apple-touch-icon" href="/2.png">
    <link rel="alternate" href="https://mumacodes.online" hreflang="ar">    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"><style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --black: #0a0a0a;
            --black-light: #1a1a1a;
            --black-lighter: #2a2a2a;
            --gold: #FFD700;
            --gold-dark: #e6c300;
            --gold-light: #fff0b3;
            --gold-glow: rgba(255, 215, 0, 0.5);
            --text-light: #f5f5f5;
            --text-dim: #cccccc;
        }

        body {
            font-family: 'Tahoma', 'Segoe UI', system-ui, sans-serif;
            background: var(--black);
            color: var(--text-light);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            direction: rtl;
            line-height: 1;
        }

        /* خلفية سوداء مع تموجات ذهبية خفيفة */
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 30% 40%, rgba(255, 215, 0, 0.05) 0%, transparent 40%),
                radial-gradient(circle at 70% 60%, rgba(255, 215, 0, 0.05) 0%, transparent 40%),
                linear-gradient(145deg, #000000 0%, #0f0f0f 100%);
            z-index: -2;
        }

        /* شبكة دقيقة ذهبية */
        .grid-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(255, 215, 0, 0.02) 1px, transparent 1px),
                linear-gradient(90deg, rgba(255, 215, 0, 0.02) 1px, transparent 1px);
            background-size: 60px 60px;
            pointer-events: none;
            z-index: -1;
        }

        .container {
            width: 100%;
            max-width: 800px;
            margin: 1rem auto;
            padding: clamp(0.5rem, 2vw, 1.5rem);
            position: relative;
            z-index: 10;
        }

        /* البطاقة الرئيسية - تصميم أسود مع ذهبي */
        .gold-black-card {
            background: rgba(10, 10, 10, 0.85);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid var(--gold);
            border-radius: 60px;
            padding: clamp(1rem, 4vw, 2rem);
            box-shadow: 
                0 40px 80px -20px rgba(0, 0, 0, 0.9),
                0 0 0 1px var(--gold) inset,
                0 0 40px rgba(255, 215, 0, 0.3);
            text-align: center;
            transition: all 0.4s ease;
            
        }

        .gold-black-card:hover {
            box-shadow: 
                0 50px 100px -20px #000,
                0 0 0 2px var(--gold-light) inset,
                0 0 60px rgba(255, 215, 0, 0.5);
            border-color: var(--gold-light);
        }

        /* الشعار */
        .logo {
            margin-bottom: 2rem;
        }

        .logo h1 {
            font-size: 5rem;
            font-weight: 900;
            color: var(--gold);
            text-shadow: 
                0 0 30px var(--gold-glow),
                3px 3px 0 rgba(0, 0, 0, 0.8);
            letter-spacing: 2px;
            line-height: 1.1;
        }

        .logo-sub {
            font-size: clamp(1.2rem, 4vw, 1.8rem);
            color: var(--text-dim);
            margin-top: 0.5rem;
            position: relative;
            display: inline-block;
            padding: 0.5rem 2rem;
            background: rgba(255, 215, 0, 0.1);
            border-radius: 60px;
            border: 1px dashed var(--gold);
        }

    
        .description .main-text {
            font-size: 1.7rem;
            font-weight: 600;
            color: white;
            margin-bottom: 0.5rem;
        }

        .description .sub-text {
            font-size: clamp(1.1rem, 4vw, 1.5rem);
            color: var(--text-dim);
            max-width: 500px;
            margin: 0 auto;
        }

        .highlight {
            color: var(--gold);
            font-weight: bold;
        }

        /* إحصائيات سريعة */
        .quick-stats {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
            margin: 1.5rem 0;
        }

        .stat-item {
            background: rgba(255, 215, 0, 0.05);
            border: 1px solid var(--gold);
            border-radius: 60px;
            padding: 0.8rem 2rem;
            font-size: clamp(1.1rem, 3.5vw, 1.3rem);
            display: flex;
            align-items: center;
            gap: 12px;
            color: var(--gold);
            transition: 0.3s;
        }

        .stat-item:hover {
            background: rgba(255, 215, 0, 0.15);
            transform: translateY(-3px);
            box-shadow: 0 10px 20px -10px var(--gold);
        }

        .stat-item i {
            color: white;
        }

        /* الزر الرئيسي - ضخم وفي الوسط */
        .join-section {
            margin: 2rem 0 1rem;
        }

        .join-button {
            background: var(--gold);
            border: none;
            border-radius: 120px;
            padding: clamp(1rem, 3vw, 1rem) clamp(1rem, 7vw, 3rem);
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: clamp(1rem, 3vw, 2rem);
            font-size: clamp(1.5rem, 4vw, 2rem);
            font-weight: 900;
            color: var(--black);
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.2, 0.9, 0.4, 1.2);
            border: 3px solid white;
            box-shadow: 
                0 12px 20px -10px rgba(114, 97, 2, 0.5),
                0 0 40px var(--gold-glow);
            text-decoration: none;
            width: fit-content;
            margin: 0 auto;
        }

        .join-button:hover {
            background: var(--gold-dark);
            transform: scale(0.9) translateY(-5px);
            box-shadow: 
                0 20px 20px -15px rgba(255, 215, 0, 0.7),
                0 0 20px var(--gold);
            border-color: var(--gold-light);
        }

        .join-button i {
            font-size: 1em;
            color: var(--black);}

        

        /* روابط المجتمع */
        .social-links {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
            margin: 2rem 0 1rem;
        }

        .social-link {
            background: rgba(255, 215, 0, 0.05);
            border: 1px solid var(--gold);
            border-radius: 60px;
            padding: 0.8rem 2rem;
            color: white;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 12px;
            font-size: clamp(1rem, 3.5vw, 1.2rem);
            transition: 0.3s;
        }

        .social-link:hover {
            background: rgba(255, 215, 0, 0.15);
            color: var(--gold);
            transform: translateY(-3px);
            box-shadow: 0 10px 20px -10px var(--gold);
        }

        .social-link i {
            color: var(--gold);
        }

        /* الفوتر */
        .footer {
            margin-top: 2rem;
            padding-top: 1rem;
            border-top: 1px solid rgba(255, 215, 0, 0.3);
            color: var(--text-dim);
            font-size: clamp(0.9rem, 1vw, 1rem);
        }

        .footer .crown {
            color: var(--gold);
            margin-left: 5px;
        }

        /* شارة المشاركة */
        .share-badge {
            position: fixed;
            bottom: 20px;
            left: 20px;
            background: var(--black-lighter);
            backdrop-filter: blur(10px);
            padding: 0.8rem 1.8rem;
            border-radius: 60px;
            border: 1px solid var(--gold);
            color: var(--gold);
            display: flex;
            align-items: center;
            gap: 10px;
            z-index: 1000;
            font-size: clamp(0.8rem, 3vw, 1rem);
            cursor: pointer;
            transition: 0.3s;
        }

        .share-badge:hover {
            background: var(--gold);
            color: var(--black);
        }

        .share-badge:hover i {
            color: var(--black);
        }

        /* تحسينات للشاشات الصغيرة */
        @media (max-width: 600px) {
            .gold-black-card {
                padding: 1.8rem;
                border-radius: 40px;
            }
            .logo h1 {
                font-size: 3rem;
            }
            .description .main-text {
            font-size: 0.8rem;
        }
            
            .join-button {
                padding: 1.5rem 2.5rem;
                font-size: 1.8rem;
                width: 100%;
            }
            
            .stat-item {
                width: 100%;
                justify-content: center;
            }
            
            .social-link {
                width: 100%;
                justify-content: center;
            }
        }

        @media (max-width: 380px) {
            .logo h1 {
                font-size: 2rem;
            }
             .description .main-text {
            font-size: 0.6rem;
        }
            .join-button {
                font-size: 1.5rem;
                padding: 1.2rem 1.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="grid-overlay"></div>

    <!-- شارة المشاركة -->
    <div class="share-badge" onclick="navigator.share? navigator.share({title:'MuMaCodes', url:window.location.href}) : alert('انسخ الرابط وشاركه')">
        <i class="fas fa-share-alt"></i>
        <span>شارك </span>
    </div>

    <div class="container">
        <div class="gold-black-card">
            <!-- الشعار -->
            <div class="logo">
                <h1>MuMaCodes</h1>
                <div class="logo-sub">
                    <i class="fas fa-code"></i>  مجتمع للمبرمجين <i class="fas fa-laptop "></i>
                </div>
            </div>

            <!-- الوصف المختصر -->
            <div class="description">
                <div class="main-text">
                    مكانك الصحيح إذا كنت <span class="highlight">مبرمجاً</span> أو <span class="highlight">طالباً</span> تتعلم البرمجة
                </div>
                <div class="sub-text">
                    مجتمع يضم <span class="highlight">+1200</span> مبرمج وطالب، <span class="highlight">8</span> مجموعات تخصصية، ودعم يومي
                </div>
            </div>

            <!-- إحصائيات سريعة -->
            <div class="quick-stats">
                <div class="stat-item">
                    <i class="fas fa-users"></i> +١٢٠٠ عضو
                </div>
                <div class="stat-item">
                    <i class="fas fa-layer-group"></i> ٨ مجموعات
                </div>
                <div class="stat-item">
                    <i class="fas fa-comments"></i> تفاعل يومي
                </div>
            </div>

            <!-- الزر الرئيسي - في منتصف الصفحة (التركيز الأكبر) -->
            <div class="join-section">
                <a href="https://chat.whatsapp.com/EN7sspWSSDqDk3tBVqtHk2" target="_blank" style="text-decoration: none;">
                    <button class="join-button">
                        <i class="fab fa-whatsapp"></i> انضم الآن
                    </button>
                </a>
            </div>

            <!-- روابط سريعة -->
            <div class="social-links">
                <a href="https://github.com/MuMaCodes" target="_blank" class="social-link"><i class="fab fa-github"></i> GitHub</a>
                <a href="https://mumacodes.online" target="_blank" class="social-link"><i class="fas fa-globe"></i> الموقع قريباً ..</a>
                <a href="https://chat.whatsapp.com/G9ZR5G4IlFZ4shxiupmhRd" class="social-link"><i class="fas fa-heart"></i> للجميع</a>
            </div>

            <!-- الفوتر -->
            <div class="footer">
                <i class="fas fa-code crown"></i> MuMaCodes · حيث المستقبل يُكتب بكود
                
            </div>
        </div>
    </div>

    <!-- إضافة خاصية النقر على زر المشاركة إن أمكن -->
    <script>
        // تحسين تجربة المشاركة
        document.querySelector('.share-badge').addEventListener('click', function() {
            if (navigator.share) {
                navigator.share({
                    title: 'MuMaCodes',
                    text: 'انضم لأكبر مجتمع مبرمجين وطلاب عربي',
                    url: window.location.href
                });
            } else {
                alert('انسخ الرابط: ' + window.location.href);
            }
        });
    </script>
</body>
</html>
