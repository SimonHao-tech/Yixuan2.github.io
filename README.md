<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>朔州市一轩化工有限公司 | 聚丙烯酰胺专业供应商</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="朔州市一轩化工有限公司，专注阴离子聚丙烯酰胺(APAM)与阳离子聚丙烯酰胺(CPAM)的生产与销售，用于工业废水处理、污泥脱水及多行业水处理应用。">
    <style>
        :root {
            --primary: #005bac;
            --primary-dark: #00407b;
            --accent: #00b894;
            --bg-light: #f5f7fb;
            --text-main: #333333;
            --text-muted: #666666;
            --border-light: #e3e6f0;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "PingFang SC",
                         "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
            color: var(--text-main);
            background-color: #ffffff;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        header {
            position: sticky;
            top: 0;
            z-index: 100;
            background: #ffffff;
            border-bottom: 1px solid var(--border-light);
        }

        .container {
            width: 100%;
            max-width: 1180px;
            margin: 0 auto;
            padding: 0 16px;
        }

        .nav {
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 64px;
        }

        .logo {
            font-size: 18px;
            font-weight: 700;
            color: var(--primary-dark);
        }

        .logo span {
            display: block;
            font-size: 11px;
            font-weight: 400;
            color: var(--text-muted);
        }

        .nav-links {
            display: flex;
            gap: 24px;
            font-size: 14px;
        }

        .nav-links a {
            position: relative;
            padding-bottom: 4px;
        }

        .nav-links a:hover::after {
            content: "";
            position: absolute;
            left: 0;
            bottom: 0;
            width: 100%;
            height: 2px;
            background: var(--primary);
        }

        .hero {
            background: linear-gradient(135deg, #e8f1ff, #ffffff);
            border-bottom: 1px solid var(--border-light);
        }

        .hero-inner {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            padding: 48px 0 40px;
            gap: 32px;
        }

        .hero-text {
            flex: 1 1 320px;
        }

        .hero-text h1 {
            font-size: 28px;
            margin-bottom: 12px;
            color: var(--primary-dark);
        }

        .hero-text p {
            font-size: 14px;
            color: var(--text-muted);
            margin-bottom: 18px;
        }

        .hero-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 18px;
        }

        .badge {
            font-size: 11px;
            padding: 4px 10px;
            border-radius: 999px;
            border: 1px solid var(--border-light);
            background-color: #ffffff;
        }

        .badge.primary {
            border-color: var(--primary);
            color: var(--primary-dark);
        }

        .hero-actions {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
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
        }

        .btn-primary {
            background: var(--primary);
            color: #ffffff;
            border-color: var(--primary);
        }

        .btn-primary:hover {
            background: var(--primary-dark);
        }

        .btn-outline {
            background: transparent;
            color: var(--primary-dark);
            border-color: var(--primary);
        }

        .hero-stats {
            flex: 1 1 260px;
            background: #ffffff;
            border-radius: 16px;
            padding: 18px 20px;
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.04);
        }

        .hero-stats h2 {
            font-size: 16px;
            margin-bottom: 10px;
        }

        .stat-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 12px;
            margin-top: 8px;
        }

        .stat-item {
            padding: 8px 10px;
            border-radius: 10px;
            border: 1px solid var(--border-light);
            background-color: var(--bg-light);
        }

        .stat-label {
            font-size: 11px;
            color: var(--text-muted);
        }

        .stat-value {
            font-size: 14px;
            font-weight: 600;
            margin-top: 3px;
        }

        section {
            padding: 40px 0 32px;
        }

        section h2 {
            font-size: 20px;
            margin-bottom: 8px;
            color: var(--primary-dark);
        }

        section .subtitle {
            font-size: 13px;
            color: var(--text-muted);
            margin-bottom: 18px;
        }

        .two-col {
            display: grid;
            grid-template-columns: minmax(0, 2fr) minmax(0, 3fr);
            gap: 24px;
        }

        .about-box {
            background-color: var(--bg-light);
            border-radius: 14px;
            padding: 16px 18px;
            border: 1px solid var(--border-light);
            font-size: 13px;
        }

        .about-box h3 {
            font-size: 14px;
            margin-bottom: 6px;
        }

        .about-box ul {
            margin-left: 18px;
            margin-top: 4px;
        }

        .about-box li {
            margin-bottom: 4px;
        }

        .tag-row {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
            margin-top: 8px;
        }

        .tag {
            padding: 3px 8px;
            border-radius: 999px;
            border: 1px dashed var(--border-light);
            font-size: 11px;
            color: var(--text-muted);
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
            margin-top: 8px;
        }

        .card {
            border-radius: 16px;
            border: 1px solid var(--border-light);
            background-color: #ffffff;
            padding: 16px 18px;
            font-size: 13px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.02);
        }

        .card h3 {
            font-size: 15px;
            margin-bottom: 4px;
        }

        .card small {
            display: block;
            font-size: 11px;
            color: var(--text-muted);
            margin-bottom: 8px;
        }

        .kv {
            display: grid;
            grid-template-columns: 110px 1fr;
            gap: 4px 12px;
            margin-top: 6px;
        }

        .kv-label {
            font-size: 11px;
            color: var(--text-muted);
        }

        .kv-value {
            font-size: 13px;
        }

        .card ul {
            margin-left: 18px;
            margin-top: 4px;
        }

        .card li {
            margin-bottom: 3px;
        }

        .pill {
            display: inline-block;
            padding: 3px 8px;
            border-radius: 999px;
            font-size: 11px;
            background-color: var(--bg-light);
            border: 1px solid var(--border-light);
            margin-top: 4px;
        }

        .apps-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 16px;
            font-size: 13px;
        }

        .apps-grid h3 {
            font-size: 14px;
            margin-bottom: 4px;
        }

        .apps-grid ul {
            margin-left: 18px;
            margin-top: 4px;
        }

        .docs-list {
            list-style: none;
            font-size: 13px;
        }

        .docs-list li {
            padding: 8px 0;
            border-bottom: 1px dashed var(--border-light);
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 12px;
        }

        .docs-list span {
            font-size: 12px;
            color: var(--text-muted);
        }

        .docs-list a {
            font-size: 12px;
            padding: 4px 10px;
            border-radius: 999px;
            border: 1px solid var(--primary);
            color: var(--primary-dark);
        }

        .contact-box {
            display: grid;
            grid-template-columns: minmax(0, 2fr) minmax(0, 3fr);
            gap: 20px;
            font-size: 13px;
        }

        .contact-card {
            border-radius: 14px;
            border: 1px solid var(--border-light);
            padding: 14px 16px;
            background-color: var(--bg-light);
        }

        .contact-card h3 {
            font-size: 14px;
            margin-bottom: 6px;
        }

        .contact-card p {
            margin-bottom: 4px;
        }

        footer {
            border-top: 1px solid var(--border-light);
            padding: 14px 0;
            font-size: 11px;
            color: var(--text-muted);
        }

        @media (max-width: 768px) {
            .nav {
                flex-direction: column;
                align-items: flex-start;
                height: auto;
                padding: 8px 0;
                gap: 6px;
            }
            .nav-links {
                flex-wrap: wrap;
                gap: 12px;
            }
            .hero-inner {
                padding: 28px 0 22px;
            }
            .two-col,
            .contact-box {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <nav class="nav">
            <div class="logo">
                朔州市一轩化工有限公司
                <span>Shuozhou Yixuan Chemical Co., Ltd.</span>
            </div>
            <div class="nav-links">
                <a href="#home">首页 Home</a>
                <a href="#about">关于我们 About</a>
                <a href="#products">产品中心 Products</a>
                <a href="#applications">应用领域 Applications</a>
                <a href="#docs">技术资料 Docs</a>
                <a href="#contact">联系我们 Contact</a>
            </div>
        </nav>
    </div>
</header>

<main>

    <!-- Hero -->
    <section class="hero" id="home">
        <div class="container hero-inner">
            <div class="hero-text">
                <h1>聚丙烯酰胺专业生产供应商<br>Professional Polyacrylamide Supplier</h1>
                <p>
                    专注阴离子聚丙烯酰胺 (Anionic Polyacrylamide, APAM 阴离子聚丙烯酰胺) 与
                    阳离子聚丙烯酰胺 (Cationic Polyacrylamide, CPAM 阳离子聚丙烯酰胺)，
                    服务工业废水处理、污泥脱水及多行业水处理应用。
                </p>
                <div class="hero-badges">
                    <div class="badge primary">水处理絮凝剂 (Water Treatment Flocculants)</div>
                    <div class="badge">工业废水 (Industrial Wastewater 工业废水)</div>
                    <div class="badge">污泥脱水 (Sludge Dewatering 污泥脱水)</div>
                </div>
                <div class="hero-actions">
                    <a href="#products" class="btn btn-primary">查看产品 Products</a>
                    <a href="#docs" class="btn btn-outline">下载说明书 Manuals</a>
                </div>
            </div>
            <div class="hero-stats">
                <h2>核心产品参数 (Key Product Parameters)</h2>
                <div class="stat-list">
                    <div class="stat-item">
                        <div class="stat-label">APAM 固含量 (Solids Content 固含量)</div>
                        <div class="stat-value">&ge; 88%</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-label">APAM 分子量 (Molecular Weight 分子量)</div>
                        <div class="stat-value">6–30 × 10<sup>6</sup></div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-label">CPAM 固含量 (Solids Content 固含量)</div>
                        <div class="stat-value">&ge; 88%</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-label">CPAM 分子量 (Molecular Weight 分子量)</div>
                        <div class="stat-value">6–13 × 10<sup>6</sup></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About -->
    <section id="about">
        <div class="container">
            <h2>关于我们 (About Us)</h2>
            <p class="subtitle">
                朔州市一轩化工有限公司专注聚丙烯酰胺 (Polyacrylamide 聚丙烯酰胺, PAM) 研发与应用，
                为钢铁、电镀、冶金、洗煤、市政水务等行业提供稳定可靠的水处理解决方案。
            </p>
            <div class="two-col">
                <div class="about-box">
                    <h3>公司定位 (Positioning 公司定位)</h3>
                    <ul>
                        <li>专业聚丙烯酰胺絮凝剂供应商 (Professional PAM Flocculant Supplier 专业聚丙烯酰胺供应商)</li>
                        <li>面向工业废水及污泥处理 (Industrial & Municipal Water Treatment 工业与市政水处理)</li>
                        <li>提供产品选择、小试优化及技术支持 (Technical Support 技术支持)</li>
                    </ul>
                    <div class="tag-row">
                        <div class="tag">废水处理 (Wastewater Treatment 废水处理)</div>
                        <div class="tag">污泥脱水 (Sludge Dewatering 污泥脱水)</div>
                        <div class="tag">造纸 (Papermaking 造纸)</div>
                        <div class="tag">选矿洗煤 (Mineral Processing & Coal Washing 选矿洗煤)</div>
                    </div>
                </div>
                <div class="about-box">
                    <h3>产品优势 (Advantages 产品优势)</h3>
                    <ul>
                        <li>水溶性好 (Good Water Solubility 水溶性好)，易于配置和投加</li>
                        <li>投加量低 (Low Dosage 投加量低)，絮凝效果显著</li>
                        <li>可与无机絮凝剂 (Inorganic Coagulants 无机絮凝剂) 联用，提高处理效率</li>
                        <li>适用行业广泛 (Wide Industry Coverage 行业覆盖广)</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Products -->
    <section id="products">
        <div class="container">
            <h2>产品中心 (Products)</h2>
            <p class="subtitle">
                阴离子聚丙烯酰胺 (Anionic Polyacrylamide, APAM 阴离子聚丙烯酰胺) 与
                阳离子聚丙烯酰胺 (Cationic Polyacrylamide, CPAM 阳离子聚丙烯酰胺)，
                覆盖高浊度水处理、工业废水及污泥脱水等多种应用场景。
            </p>

            <div class="product-grid">
                <!-- APAM -->
                <div class="card">
                    <h3>阴离子聚丙烯酰胺 APAM</h3>
                    <small>Anionic Polyacrylamide 阴离子聚丙烯酰胺</small>
                    <p>
                        主要用于工业废水絮凝沉降及澄清处理，如钢铁厂、电镀厂、冶金、洗煤废水
                        以及污泥脱水、饮用水澄清等。:contentReference[oaicite:2]{index=2}
                    </p>

                    <div class="kv">
                        <div class="kv-label">外观 (Appearance 外观)</div>
                        <div class="kv-value">白色颗粒 (White Granules 白色颗粒)</div>

                        <div class="kv-label">固含量 (Solids Content 固含量)</div>
                        <div class="kv-value">&ge; 88%</div>

                        <div class="kv-label">分子量 (Molecular Weight 分子量)</div>
                        <div class="kv-value">6–30 × 10<sup>6</sup></div>

                        <div class="kv-label">水解度 (Degree of Hydrolysis 水解度)</div>
                        <div class="kv-value">10–50 %</div>

                        <div class="kv-label">溶解时间 (Dissolving Time 溶解时间)</div>
                        <div class="kv-value">&le; 30 min</div>
                    </div>

                    <p class="pill">主要功能 Functions: 澄清净化、沉降促进、过滤促进、增稠</p>

                    <ul>
                        <li>工业废水处理 (Industrial Wastewater Treatment 工业废水处理)</li>
                        <li>污泥浓缩及脱水 (Sludge Thickening & Dewatering 污泥脱水)</li>
                        <li>选矿、洗煤、造纸 (Mineral Processing, Coal Washing & Papermaking 选矿洗煤造纸)</li>
                        <li>饮用水澄清净化 (Potable Water Clarification 饮用水澄清)</li>
                    </ul>
                </div>

                <!-- CPAM -->
                <div class="card">
                    <h3>阳离子聚丙烯酰胺 CPAM</h3>
                    <small>Cationic Polyacrylamide 阳离子聚丙烯酰胺</small>
                    <p>
                        适用于有机胶体含量较高的废水及污泥脱水，特别是城市污水、城市污泥、
                        造纸污泥等脱水处理，也适用于染色、食品加工、冶金、选矿、油田等行业。:contentReference[oaicite:3]{index=3}
                    </p>

                    <div class="kv">
                        <div class="kv-label">外观 (Appearance 外观)</div>
                        <div class="kv-value">白色颗粒 (White Granules 白色颗粒)</div>

                        <div class="kv-label">固含量 (Solids Content 固含量)</div>
                        <div class="kv-value">&
