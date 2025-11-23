<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>朔州市一轩化工有限公司 | 聚丙烯酰胺专业供应商</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="朔州市一轩化工有限公司，专注阴离子聚丙烯酰胺(APAM)与阳离子聚丙烯酰胺(CPAM)水处理絮凝剂，服务工业废水和污泥脱水等应用场景。">
    <style>
        :root {
            --primary: #0080ff;
            --primary-dark: #0050b3;
            --accent: #00d2a0;
            --bg-dark: #050b1a;
            --bg-light: #f4f7ff;
            --card-bg: #ffffff;
            --text-main: #1a1a1a;
            --text-muted: #8088a0;
            --border-soft: rgba(255,255,255,.18);
            --shadow-soft: 0 18px 45px rgba(15, 35, 80, 0.35);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "PingFang SC",
                         "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
            color: var(--text-main);
            background: #050816;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* 顶部导航栏（Navigation 导航栏） */

        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 50;
            backdrop-filter: blur(14px);
            background: linear-gradient(to bottom, rgba(5,11,26,.92), rgba(5,11,26,.60));
            border-bottom: 1px solid rgba(255,255,255,.08);
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .nav {
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 64px;
        }

        .logo-wrap {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo-mark {
            width: 32px;
            height: 32px;
            border-radius: 12px;
            background: radial-gradient(circle at 20% 0%, #4df1ff, #0080ff 45%, #050816);
            box-shadow: 0 0 18px rgba(77, 241, 255, .7);
            position: relative;
            overflow: hidden;
        }

        .logo-mark::after {
            content: "";
            position: absolute;
            inset: 6px;
            border-radius: 8px;
            border: 1px solid rgba(255,255,255,.35);
        }

        .logo-text {
            color: #ffffff;
        }

        .logo-text strong {
            font-size: 16px;
            letter-spacing: .03em;
        }

        .logo-text span {
            display: block;
            font-size: 11px;
            opacity: .75;
        }

        .nav-links {
            display: flex;
            gap: 20px;
            font-size: 13px;
            color: #e4e8ff;
        }

        .nav-links a {
            position: relative;
            padding-bottom: 3px;
        }

        .nav-links a::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            width: 0;
            height: 2px;
            transform: translateX(-50%);
            background: linear-gradient(90deg, #4df1ff, #00ffb8);
            transition: width .25s ease;
        }

        .nav-links a:hover::after {
            width: 80%;
        }

        /* Hero 首屏大图 */

        .hero {
            min-height: 100vh;
            padding-top: 72px; /* 留给导航栏 */
            background-image:
                radial-gradient(circle at 0% 0%, rgba(0,255,184,.25), transparent 55%),
                radial-gradient(circle at 100% 100%, rgba(77,241,255,.22), transparent 60%),
                linear-gradient(135deg, #050816 0%, #021326 40%, #031a30 100%),
                url("images/hero-water.jpg");
            background-size: cover;
            background-position: center;
            background-blend-mode: overlay, overlay, normal, normal;
            color: #ffffff;
        }

        .hero-inner {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px 40px;
            display: grid;
            grid-template-columns: minmax(0, 3fr) minmax(0, 2.4fr);
            gap: 36px;
            align-items: center;
        }

        .hero-kicker {
            font-size: 12px;
            letter-spacing: .16em;
            text-transform: uppercase;
            color: #9fb4ff;
            margin-bottom: 10px;
        }

        .hero-title {
            font-size: 32px;
            line-height: 1.2;
            margin-bottom: 12px;
        }

        .hero-title span {
            background: linear-gradient(120deg, #4df1ff, #00ffb8);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }

        .hero-sub {
            font-size: 13px;
            color: #bcc5ff;
            max-width: 520px;
            margin-bottom: 22px;
        }

        .hero-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 24px;
        }

        .badge {
            font-size: 11px;
            padding: 4px 10px;
            border-radius: 999px;
            border: 1px solid rgba(255,255,255,.26);
            background: rgba(3, 12, 32, .85);
        }

        .badge.primary {
            border-color: transparent;
            background: linear-gradient(120deg, #4df1ff, #00ffb8);
            color: #020716;
            font-weight: 600;
        }

        .hero-actions {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 26px;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 8px 18px;
            border-radius: 999px;
            font-size: 13px;
            border: 1px solid transparent;
            cursor: pointer;
            transition: all .22s ease;
            white-space: nowrap;
        }

        .btn-primary {
            background: linear-gradient(120deg, #4df1ff, #00ffb8);
            color: #050816;
            font-weight: 600;
            box-shadow: 0 12px 30px rgba(0,255,184,.4);
        }

        .btn-primary:hover {
            transform: translateY(-1px);
            box-shadow: 0 16px 40px rgba(0,255,184,.6);
        }

        .btn-ghost {
            background: rgba(5,11,26,.7);
            border-color: rgba(255,255,255,.35);
            color: #e4e8ff;
        }

        .btn-ghost:hover {
            background: rgba(11,23,54,.9);
        }

        .hero-strip {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            font-size: 11px;
            color: #9aa5ff;
        }

        .hero-strip-item {
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .dot {
            width: 7px;
            height: 7px;
            border-radius: 999px;
            background: #4df1ff;
            box-shadow: 0 0 10px rgba(77,241,255,.9);
        }

        /* Hero 右侧 “玻璃卡片 + 产品图片” */

        .hero-right {
            position: relative;
        }

        .glass-panel {
            position: relative;
            border-radius: 22px;
            border: 1px solid var(--border-soft);
            background: linear-gradient(135deg, rgba(10,18,55,.92), rgba(5,11,26,.96));
            box-shadow: var(--shadow-soft);
            padding: 18px 18px 14px;
            overflow: hidden;
        }

        .panel-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
        }

        .panel-title {
            font-size: 13px;
            color: #e4e8ff;
        }

        .panel-title span {
            display: block;
            font-size: 11px;
            color: #9aa5ff;
        }

        .status-dot {
            width: 9px;
            height: 9px;
            border-radius: 50%;
            background: #00ffb8;
            box-shadow: 0 0 10px rgba(0,255,184,.9);
        }

        .panel-grid {
            display: grid;
            grid-template-columns: 1.2fr 1.2fr;
            gap: 10px;
        }

        .mini-card {
            border-radius: 14px;
            background: radial-gradient(circle at 0 0, rgba(77,241,255,.4), transparent 60%),
                        rgba(5,16,56,.9);
            border: 1px solid rgba(255,255,255,.14);
            padding: 10px;
            font-size: 11px;
            color: #dfe5ff;
        }

        .mini-tag {
            display: inline-flex;
            align-items: center;
            padding: 2px 7px;
            border-radius: 999px;
            border: 1px solid rgba(255,255,255,.4);
            font-size: 10px;
            margin-bottom: 6px;
        }

        .mini-num {
            font-size: 17px;
            font-weight: 600;
            margin-bottom: 2px;
        }

        .mini-label {
            opacity: .7;
        }

        .mini-img-card {
            position: relative;
            border-radius: 16px;
            overflow: hidden;
            border: 1px solid rgba(255,255,255,.18);
            background: #020615;
        }

        .mini-img-card img {
            width: 100%;
            height: 120px;
            object-fit: cover;
            display: block;
            filter: saturate(1.2) contrast(1.05);
            transform: scale(1.02);
        }

        .mini-img-caption {
            position: absolute;
            left: 8px;
            bottom: 8px;
            right: 8px;
            font-size: 11px;
            color: #f5f7ff;
            text-shadow: 0 2px 6px rgba(0,0,0,.9);
        }

        .mini-img-caption span {
            display: block;
            font-size: 10px;
            color: #9af5ff;
        }

        .panel-footer {
            margin-top: 10px;
            padding-top: 8px;
            border-top: 1px solid rgba(255,255,255,.12);
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 10px;
            color: #9aa5ff;
        }

        .chips {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
        }

        .chip {
            padding: 3px 7px;
            border-radius: 999px;
            background: rgba(5,15,40,.92);
            border: 1px solid rgba(255,255,255,.16);
        }

        /* 主体内容 */

        main {
            background: radial-gradient(circle at 10% -10%, #071a3a, #050816 45%, #020712 100%);
            color: #f5f7ff;
        }

        section {
            padding: 48px 0 40px;
        }

        .section-head {
            max-width: 1200px;
            margin: 0 auto 18px;
            padding: 0 20px;
        }

        .section-kicker {
            font-size: 11px;
            letter-spacing: .18em;
            text-transform: uppercase;
            color: #8ca0ff;
            margin-bottom: 6px;
        }

        .section-title {
            font-size: 20px;
            margin-bottom: 6px;
        }

        .section-sub {
            font-size: 12px;
            color: #a8b3ff;
        }

        /* 产品区（Product Showcase 产品展示区） */

        .products-wrap {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px 10px;
            display: grid;
            grid-template-columns: minmax(0, 3fr) minmax(0, 2fr);
            gap: 24px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 18px;
        }

        .product-card {
            background: radial-gradient(circle at 0 0, rgba(77,241,255,.18), transparent 60%),
                        rgba(7, 14, 42, .98);
            border-radius: 18px;
            border: 1px solid rgba(137,167,255,.45);
            padding: 14px 14px 12px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 14px 35px rgba(7,18,50,.65);
            transition: transform .22s ease, box-shadow .22s ease, border-color .22s ease;
        }

        .product-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 20px 45px rgba(7,18,50,.9);
            border-color: #4df1ff;
        }

        .product-badge {
            font-size: 10px;
            padding: 2px 7px;
            border-radius: 999px;
            background: rgba(5,15,40,.82);
            border: 1px solid rgba(255,255,255,.3);
            color: #b9c5ff;
            display: inline-block;
            margin-bottom: 6px;
        }

        .product-title {
            font-size: 14px;
            margin-bottom: 4px;
        }

        .product-sub {
            font-size: 11px;
            color: #b9c5ff;
            margin-bottom: 8px;
        }

        .product-meta {
            font-size: 11px;
            color: #c4d0ff;
            margin-bottom: 6px;
        }

        .product-meta span {
            color: #4df1ff;
        }

        .product-list {
            font-size: 11px;
            color: #dfe5ff;
            margin-left: 16px;
            margin-bottom: 8px;
        }

        .product-list li {
            margin-bottom: 2px;
        }

        .product-tag-row {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
            margin-top: 4px;
        }

        .product-tag {
            font-size: 10px;
            padding: 3px 7px;
            border-radius: 999px;
            border: 1px dashed rgba(160,183,255,.6);
            color: #a9b9ff;
        }

        .products-images {
            display: grid;
            grid-template-rows: 1.4fr 1fr;
            gap: 14px;
        }

        .large-img-card,
        .small-img-card {
            position: relative;
            border-radius: 18px;
            overflow: hidden;
            border: 1px solid rgba(163,192,255,.5);
            background: #020615;
            box-shadow: 0 14px 35px rgba(7,18,50,.7);
        }

        .large-img-card img,
        .small-img-card img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
            filter: saturate(1.1) contrast(1.06);
        }

        .img-caption {
            position: absolute;
            left: 10px;
            bottom: 9px;
            right: 10px;
            font-size: 11px;
            color: #f5f7ff;
            text-shadow: 0 2px 6px rgba(0,0,0,.95);
        }

        .img-caption span {
            display: block;
            font-size: 10px;
            color: #9af5ff;
        }

        /* 技术资料区（Technical Docs 技术资料） */

        .docs-wrap {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px 10px;
            display: grid;
            grid-template-columns: minmax(0, 1.6fr) minmax(0, 2.4fr);
            gap: 22px;
            align-items: start;
        }

        .doc-card {
            background: rgba(7,14,42,.92);
            border-radius: 16px;
            border: 1px solid rgba(146,171,255,.55);
            padding: 14px 14px 12px;
        }

        .doc-card h3 {
            font-size: 14px;
            margin-bottom: 6px;
        }

        .doc-card p {
            font-size: 11px;
            color: #b9c5ff;
            margin-bottom: 6px;
        }

        .doc-list {
            list-style: none;
            font-size: 11px;
            color: #dfe5ff;
        }

        .doc-list li {
            display: flex;
            justify-content: space-between;
            gap: 12px;
            align-items: center;
            padding: 7px 0;
            border-bottom: 1px dashed rgba(130,154,255,.5);
        }

        .doc-meta span {
            display: block;
            color: #9aa5ff;
            font-size: 10px;
        }

        .doc-link {
            font-size: 11px;
            padding: 4px 10px;
            border-radius: 999px;
            border: 1px solid #4df1ff;
            color: #4df1ff;
            white-space: nowrap;
        }

        .doc-link:hover {
            background: #4df1ff;
            color: #021021;
        }

        .doc-hint-list {
            margin-left: 16px;
            margin-top: 6px;
            font-size: 11px;
            color: #c5d2ff;
        }

        .doc-hint-list li {
            margin-bottom: 3px;
        }

        /* 联系我们（Contact 联系方式） */

        .contact-wrap {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px 14px;
            display: grid;
            grid-template-columns: minmax(0, 2fr) minmax(0, 3fr);
            gap: 22px;
        }

        .contact-card {
            background: rgba(7,14,42,.92);
            border-radius: 16px;
            border: 1px solid rgba(146,171,255,.55);
            padding: 14px 14px 12px;
            font-size: 11px;
            color: #dfe5ff;
        }

        .contact-card h3 {
            font-size: 14px;
            margin-bottom: 6px;
        }

        .contact-card p {
            margin-bottom: 4px;
        }

        .contact-list {
            margin-left: 16px;
            margin-top: 6px;
        }

        .contact-list li {
            margin-bottom: 3px;
        }

        footer {
            border-top: 1px solid rgba(111,131,188,.5);
            padding: 12px 0 14px;
            font-size: 11px;
            color: #909ccb;
            text-align: center;
            background: #050816;
        }

        /* 响应式（Responsive 自适应） */

        @media (max-width: 960px) {
            .hero-inner {
                grid-template-columns: 1fr;
            }
            .hero-right {
                order: -1;
            }
            .products-wrap,
            .docs-wrap,
            .contact-wrap {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 720px) {
            .nav {
                flex-direction: column;
                align-items: flex-start;
                gap: 6px;
                height: auto;
                padding: 6px 0;
            }
            .nav-links {
                flex-wrap: wrap;
            }
            .hero-title {
                font-size: 26px;
            }
        }

    </style>
</head>
<body>

<header>
    <div class="container">
        <nav class="nav">
            <div class="logo-wrap">
                <div class="logo-mark"></div>
                <div class="logo-text">
                    <strong>一轩化工</strong>
                    <span>Shuozhou Yixuan Chemical</span>
                </div>
            </div>
            <div class="nav-links">
                <a href="#home">首页 Home</a>
                <a href="#products">产品 Products</a>
                <a href="#docs">技术资料 Docs</a>
                <a href="#contact">联系我们 Contact</a>
            </div>
        </nav>
    </div>
</header>

<!-- Hero 首屏 -->

<section class="hero" id="home">
    <div class="hero-inner">
        <div>
            <div class="hero-kicker">WATER TREATMENT FLOCCULANTS 水处理絮凝剂</div>
            <h1 class="hero-title">
                聚丙烯酰胺<span> · APAM / CPAM</span><br>
                工业废水与污泥脱水整体解决方案
            </h1>
            <p class="hero-sub">
                朔州市一轩化工有限公司专注阴离子聚丙烯酰胺（Anionic Polyacrylamide 阴离子聚丙烯酰胺, APAM）
                与阳离子聚丙烯酰胺（Cationic Polyacrylamide 阳离子聚丙烯酰胺, CPAM），
                覆盖工业废水、市政污水、选矿洗煤、造纸、油田等多行业水处理应用。
            </p>

            <div class="hero-badges">
                <div class="badge primary">高效絮凝 (High-Efficiency Flocculation 高效絮凝)</div>
                <div class="badge">低投加量 (Low Dosage 低投加量)</div>
                <div class="badge">适用行业广泛 (Wide Applications 行业广泛)</div>
            </div>

            <div class="hero-actions">
                <a href="#products" class="btn btn-primary">查看产品 Products</a>
                <a href="#docs" class="btn btn-ghost">下载说明书 Manuals</a>
            </div>

            <div class="hero-strip">
                <div class="hero-strip-item">
                    <div class="dot"></div> 高浊度水澄清处理 (High-Turbidity Water Clarification 高浊度水澄清)
                </div>
                <div class="hero-strip-item">
                    <div class="dot"></div> 污泥脱水、污水深度处理 (Sludge Dewatering & Advanced Treatment 污泥脱水)
                </div>
                <div class="hero-strip-item">
                    <div class="dot"></div> APAM / CPAM 技术支持 (Technical Support 技术支持)
                </div>
            </div>
        </div>

        <div class="hero-right">
            <div class="glass-panel">
                <div class="panel-header">
                    <div class="panel-title">
                        聚丙烯酰胺核心参数
                        <span>Key Performance Data 关键性能数据</span>
                    </div>
                    <div class="status-dot"></div>
                </div>

                <div class="panel-grid">
                    <div class="mini-card">
                        <div class="mini-tag">APAM 阴离子聚丙烯酰胺</div>
                        <div class="mini-num">6–30 × 10⁶</div>
                        <div class="mini-label">分子量 (Molecular Weight 分子量)</div>
                        <div style="margin-top:6px;font-size:10px;">
                            固含量 (Solids 固含量) ≥ 88%<br>
                            水解度 (Hydrolysis Degree 水解度) 10–50%
                        </div>
                    </div>
                    <div class="mini-card">
                        <div class="mini-tag">CPAM 阳离子聚丙烯酰胺</div>
                        <div class="mini-num">6–13 × 10⁶</div>
                        <div class="mini-label">分子量 (Molecular Weight 分子量)</div>
                        <div style="margin-top:6px;font-size:10px;">
                            固含量 (Solids 固含量) ≥ 88%<br>
                            离子度 (Charge Density 离子度) 5–90%
                        </div>
                    </div>
                    <div class="mini-img-card">
                        <img src="images/product-apam.jpg" alt="APAM 阴离子聚丙烯酰胺">
                        <div class="mini-img-caption">
                            APAM 用于高浊度工业废水澄清与沉降处理
                            <span>Industrial Wastewater Clarification 工业废水澄清</span>
                        </div>
                    </div>
                    <div class="mini-img-card">
                        <img src="images/product-cpam.jpg" alt="CPAM 阳离子聚丙烯酰胺">
                        <div class="mini-img-caption">
                            CPAM 专注市政污泥与造纸污泥脱水应用
                            <span>Sludge Dewatering 污泥脱水</span>
                        </div>
                    </div>
                </div>

                <div class="panel-footer">
                    <div>溶解时间 (Dissolving Time 溶解时间)：APAM ≤ 30 min · CPAM ≤ 60 min</div>
                    <div class="chips">
                        <div class="chip">水处理 Water Treatment</div>
                        <div class="chip">污泥脱水 Sludge Dewatering</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<main>

    <!-- 产品展示区 Products -->

    <section id="products">
        <div class="section-head">
            <div class="section-kicker">PRODUCT SHOWCASE 产品展示</div>
            <div class="section-title">APAM & CPAM 水处理核心产品</div>
            <div class="section-sub">
                通过不同分子量与离子度组合，为钢铁、电镀、冶金、洗煤、市政污水、造纸等工况提供针对性的聚丙烯酰胺解决方案。
            </div>
        </div>

        <div class="products-wrap">
            <div class="product-grid">
                <!-- APAM Card -->
                <article class="product-card">
                    <div class="product-badge">APAM · 阴离子聚丙烯酰胺 (Anionic Polyacrylamide 阴离子聚丙烯酰胺)</div>
                    <h3 class="product-title">APAM 工业废水澄清与沉降</h3>
                    <div class="product-sub">
                        适用于钢铁厂、电镀厂、冶金、洗煤等工业废水，以及部分饮用水高浊度水澄清。具备良好的絮凝、沉降、过滤促进与增稠作用。
                    </div>
                    <div class="product-meta">
                        分子量 (Molecular Weight 分子量)：<span>6–30 × 10⁶</span> ·
                        固含量 (Solids 固含量)：<span>≥ 88%</span>
                    </div>
                    <ul class="product-list">
                        <li>工业废水澄清与固液分离 (Industrial Wastewater Clarification 工业废水澄清)</li>
                        <li>污泥浓缩与脱水 (Sludge Thickening & Dewatering 污泥浓缩脱水)</li>
                        <li>选矿、洗煤过程沉降 (Mineral Processing & Coal Washing 选矿洗煤沉降)</li>
                        <li>饮用水高浊度水处理 (High-Turbidity Potable Water 高浊度水处理)</li>
                    </ul>
                    <div class="product-tag-row">
                        <div class="product-tag">澄清 Clarification 澄清</div>
                        <div class="product-tag">絮凝 Flocculation 絮凝</div>
                        <div class="product-tag">沉降 Settling 沉降</div>
                    </div>
                </article>

                <!-- CPAM Card -->
                <article class="product-card">
                    <div class="product-badge">CPAM · 阳离子聚丙烯酰胺 (Cationic Polyacrylamide 阳离子聚丙烯酰胺)</div>
                    <h3 class="product-title">CPAM 市政污水与污泥脱水</h3>
                    <div class="product-sub">
                        针对有机胶体含量较高废水及污泥脱水，如城市污水、城市污泥、造纸污泥等，具有优异的吸附架桥、脱水与粘合作用。
                    </div>
                    <div class="product-meta">
                        分子量 (Molecular Weight 分子量)：<span>6–13 × 10⁶</span> ·
                        离子度 (Charge Density 离子度)：<span>5–90%</span>
                    </div>
                    <ul class="product-list">
                        <li>城市污水与污泥脱水 (Municipal Sewage & Sludge Dewatering 城市污泥脱水)</li>
                        <li>造纸污泥脱水 (Papermaking Sludge Dewatering 造纸污泥脱水)</li>
                        <li>染色、食品、建筑、冶金等有机废水 (Organic-Rich Effluents 有机废水)</li>
                    </ul>
                    <div class="product-tag-row">
                        <div class="product-tag">脱水 Dewatering 脱水</div>
                        <div class="product-tag">吸附 Adsorption 吸附</div>
                        <div class="product-tag">粘合 Binding 粘合</div>
                    </div>
                </article>
            </div>

            <div class="products-images">
                <div class="large-img-card">
                    <img src="images/factory.jpg" alt="生产线及工厂环境">
                    <div class="img-caption">
                        现代化生产线与严格质量控制，为聚丙烯酰胺产品提供稳定性能与可靠供货能力。
                        <span>Manufacturing & QC 生产与质量控制</span>
                    </div>
                </div>
                <div class="small-img-card">
                    <img src="images/hero-water.jpg" alt="水处理现场应用">
                    <div class="img-caption">
                        工业废水与市政污水处理现场应用，兼顾出水水质与运行成本。
                        <span>On-Site Water Treatment 水处理现场</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 技术资料 Technical Docs -->

    <section id="docs">
        <div class="section-head">
            <div class="section-kicker">TECHNICAL DOCUMENTS 技术资料</div>
            <div class="section-title">产品说明书下载与应用指引</div>
            <div class="section-sub">
                通过下载产品说明书（Product Manuals 产品说明书），可获取完整技术指标、使用方法、溶解配置要求以及安全与储存建议。
            </div>
        </div>

        <div class="docs-wrap">
            <div class="doc-card">
                <h3>如何合理选择聚丙烯酰胺型号？</h3>
                <p>
                    不同水质和工艺条件下，需根据分子量（Molecular Weight 分子量）、离子度（Charge Density 离子度）、
                    粘度与溶解性能进行产品匹配。建议配合现场小试（Jar Test 小试试验）优化投加剂量。
                </p>
                <ul class="doc-hint-list">
                    <li>提供进水水质（pH、浊度、SS、COD 等）与处理规模 (Flowrate 流量)</li>
                    <li>说明现有加药点和工艺流程 (Process Flow 工艺流程)</li>
                    <li>我们可协助推荐 APAM / CPAM 型号及参考投加范围 (Dosage Range 投加范围)</li>
                </ul>
            </div>

            <div class="doc-card">
                <ul class="doc-list">
                    <li>
                        <div class="doc-meta">
                            阴离子聚丙烯酰胺产品说明书
                            <span>Anionic Polyacrylamide Manual 阴离子聚丙烯酰胺说明书</span>
                        </div>
                        <!-- 实际部署时，请把 href 换成你服务器上的真实路径 -->
                        <a class="doc-link" href="阴离子聚丙烯酰胺说明书.doc" download>下载 Download</a>
                    </li>
                    <li>
                        <div class="doc-meta">
                            阳离子聚丙烯酰胺产品说明书
                            <span>Cationic Polyacrylamide Manual 阳离子聚丙烯酰胺说明书</span>
                        </div>
                        <!-- 实际部署时，请把 href 换成你服务器上的真实路径 -->
                        <a class="doc-link" href="阳离子聚丙烯酰胺说明书.doc" download>下载 Download</a>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- 联系我们 Contact -->

    <section id="contact">
        <div class="section-head">
            <div class="section-kicker">CONTACT US 联系我们</div>
            <div class="section-title">一站式水处理絮凝方案合作</div>
            <div class="section-sub">
                欢迎就工业废水、市政污水、污泥脱水等工况的聚丙烯酰胺应用与我们联系，我们将根据您的实际工况提供产品选型与技术建议。
            </div>
        </div>

        <div class="contact-wrap">
            <div class="contact-card">
                <h3>公司信息 Company Info</h3>
                <p>公司名称：朔州市一轩化工有限公司 (Shuozhou Yixuan Chemical Co., Ltd.)</p>
                <p>电话 / Tel：<strong>+86-000-00000000</strong></p>
                <p>邮箱 / Email：<strong>info@example.com</strong></p>
                <p>地址 / Address：<strong>中国 山西省朔州市（示例，可替换）</strong></p>
            </div>
            <div class="contact-card">
                <h3>技术与商务询盘内容建议</h3>
                <ul class="contact-list">
                    <li>使用行业与工艺简介 (Industry & Process 使用工艺)</li>
                    <li>废水/污泥基本水质参数 (Basic Water / Sludge Parameters 基本参数)</li>
                    <li>处理规模与运行工况 (Treatment Capacity 处理规模)</li>
                    <li>现有加药点与工艺流程 (Existing Dosing & Process 现有工艺)</li>
                    <li>期望解决的问题：如出水水质、污泥含水率、药剂成本等 (Key Pain Points 关键问题)</li>
                </ul>
                <p>我们将根据以上信息，推荐适用的 APAM / CPAM 型号和参考投加方案。</p>
            </div>
        </div>
    </section>

</main>

<footer>
    © 朔州市一轩化工有限公司 Shuozhou Yixuan Chemical Co., Ltd. All rights reserved.
</footer>

</body>
</html>
