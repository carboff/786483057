

<头>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>北京卡伯夫国际贸易有限公司 | 可降解环保包装解决方案</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <样式>
        *  {
            边距：0;
            
            盒模型：边框盒;
            字体家族：'Segoe UI'，'Microsoft YaHei'，无衬线;
        }
        
        :root {
            --主要绿色: #1a936f;
            --浅绿色: #88d498;
            --深绿色: #114b5f;
            --奶油色: #f3e9d2;
            --light-gray: #f8f9fa;
            --深灰色: #333;
        }
        
        body {
            行高: 1.6;
            颜色: var(--深灰色);
            背景颜色: #fff;
        }
        
        容器 {
            宽度：100%；
            最大宽度：1200像素；
            margin: 0 auto;
            填充: 0 20px;
        }
        
        /* 头部样式 */
        标题 {
            背景颜色：白色；
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.05);
            position: 粘性;
            顶部：0；
            z-index: 1000;
        }
        
        .header-container {
            显示: 弹性布局;
            项目对齐方式: 两端对齐;
            对齐项目：居中；
            内边距：15px 0;
        }
        
        .logo {
            显示: 弹性布局;
            对齐项目：居中；
        }
        
        .logo h1 {
            字体大小: 1.8rem;
            颜色: var(--深绿色);
            字体粗细：700；
        }
        
        .logo span {
            color: var(--primary-green);
            font-weight: 300;
            font-size: 1rem;
            margin-left: 5px;
        }
        
        .logo .carboff {
            font-size: 0.9rem;
            background-color: var(--light-green);
            color: white;
            padding: 3px 8px;
            border-radius: 4px;
            margin-left: 10px;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 30px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: var(--dark-gray);
            font-weight: 500;
            transition: color 0.3s;
            font-size: 1.05rem;
        }
        
        nav ul li a:hover {
            color: var(--primary-green);
        }
        
        .mobile-menu-btn {
            display: none;
            font-size: 1.5rem;
            background: none;
            border: none;
            cursor: pointer;
            color: var(--dark-green);
        }
        
        /* 英雄区域 */
        .hero {
            background: linear-gradient(rgba(26, 147, 111, 0.9), rgba(17, 75, 95, 0.85)), url('https://images.unsplash.com/photo-1604871000636-074fa5117945?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 120px 0;
            text-align: center;
        }
        
        .hero h2 {
            font-size: 3rem;
            margin-bottom: 20px;
            font-weight: 700;
        }
        
        .hero p {
            font-size: 1.3rem;
            max-width: 800px;
            margin: 0 auto 30px;
            line-height: 1.8;
        }
        
        .cta-button {
            display: inline-block;
            background-color: white;
            color: var(--primary-green);
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .cta-button:hover {
            background-color: var(--light-green);
            color: white;
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }
        
        /* 公司理念 */
        .mission {
            padding: 100px 0;
            background-color: var(--light-gray);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            color: var(--dark-green);
            margin-bottom: 15px;
        }
        
        .section-title p {
            color: #666;
            max-width: 700px;
            margin: 0 auto;
            font-size: 1.1rem;
        }
        
        .mission-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        
        .mission-text {
            flex: 1;
            min-width: 300px;
            padding-right: 40px;
        }
        
        .mission-text h3 {
            font-size: 1.8rem;
            color: var(--primary-green);
            margin-bottom: 20px;
        }
        
        .mission-text p {
            margin-bottom: 20px;
            font-size: 1.1rem;
        }
        
        .mission-image {
            flex: 1;
            min-width: 300px;
        }
        
        .mission-image img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }
        
        /* 产品展示 */
        .products {
            padding: 100px 0;
        }
        
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 40px;
        }
        
        .product-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.12);
        }
        
        .product-img {
            height: 220px;
            background-color: #f5f5f5;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #aaa;
        }
        
        .product-img i {
            font-size: 4rem;
            color: var(--light-green);
        }
        
        .product-info {
            padding: 25px;
        }
        
        .product-info h3 {
            font-size: 1.4rem;
            margin-bottom: 10px;
            color: var(--dark-green);
        }
        
        .product-info p {
            color: #666;
            margin-bottom: 20px;
        }
        
        /* 认证区域 */
        .certifications {
            padding: 100px 0;
            background-color: var(--light-gray);
        }
        
        .cert-grid {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 40px;
        }
        
        .cert-item {
            background: white;
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            min-width: 250px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .cert-item i {
            font-size: 3rem;
            color: var(--primary-green);
            margin-bottom: 20px;
        }
        
        .cert-item h3 {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: var(--dark-green);
        }
        
        .cert-status {
            display: inline-block;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
        }
        
        .status-active {
            background-color: #e7f6ef;
            color: var(--primary-green);
        }
        
        .status-pending {
            background-color: #fff8e1;
            color: #ff9800;
        }
        
        /* 公司优势 */
        .advantages {
            padding: 100px 0;
        }
        
        .advantage-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .advantage-item {
            text-align: center;
            padding: 30px 20px;
        }
        
        .advantage-item i {
            font-size: 2.5rem;
            color: var(--primary-green);
            margin-bottom: 20px;
        }
        
        .advantage-item h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: var(--dark-green);
        }
        
        /* 页脚 */
        footer {
            background-color: var(--dark-green);
            color: white;
            padding: 70px 0 30px;
        }
        
        .footer-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-bottom: 50px;
        }
        
        .footer-column {
            flex: 1;
            min-width: 250px;
            margin-bottom: 30px;
        }
        
        .footer-column h3 {
            font-size: 1.3rem;
            margin-bottom: 25px;
            color: var(--light-green);
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 12px;
        }
        
        .footer-column ul li a {
            color: #ddd;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-column ul li a:hover {
            color: var(--light-green);
        }
        
        .contact-info p {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }
        
        .contact-info i {
            margin-right: 10px;
            color: var(--light-green);
        }
        
        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            color: #aaa;
        }
        
        /* 响应式设计 */
        @media (max-width: 992px) {
            .hero h2 {
                font-size: 2.5rem;
            }
            
            .mission-content {
                flex-direction: column;
            }
            
            .mission-text {
                padding-right: 0;
                margin-bottom: 40px;
            }
        }
        
        @media (max-width: 768px) {
            nav ul {
                display: none;
                position: absolute;
                top: 100%;
                left: 0;
                width: 100%;
                background-color: white;
                flex-direction: column;
                padding: 20px;
                box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            }
            
            nav ul.active {
                display: flex;
            }
            
            nav ul li {
                margin: 10px 0;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            .hero h2 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .section-title h2 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- 头部导航 -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <h1>卡伯夫<span>CARBOFF</span></h1>
                <div class="carboff">零碳排 · 环保</div>
            </div>
            
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
            
            <nav>
                <ul id="mainMenu">
                    <li><a href="#home">首页</a></li>
                    <li><a href="#about">公司理念</a></li>
                    <li><a href="#products">产品中心</a></li>
                    <li><a href="#certifications">资质认证</a></li>
                    <li><a href="#advantages">公司优势</a></li>
                    <li><a href="#contact">联系我们</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- 英雄区域 -->
    <section class="hero" id="home">
        <div class="container">
            <h2>北京卡伯夫国际贸易有限公司</h2>
            <p>卡伯夫(CARBOFF) = 零碳排(Carbon Offset)，我们致力于提供环保可降解包装解决方案，助力企业实现可持续发展目标。我们提供可降解包装、杯托、育苗杯等全系列产品，支持多规格定制，已获得FSC认证，正在申请BPI和OK认证。</p>
            <a href="#contact" class="cta-button">获取定制方案</a>
        </div>
    </section>

    <!-- 公司理念 -->
    <section class="mission" id="about">
        <div class="container">
            <div class="section-title">
                <h2>公司理念</h2>
                <p>卡伯夫(CARBOFF) 源自"零碳排(Carbon Offset)"，我们致力于通过环保可降解产品，减少塑料污染，推动循环经济发展。</p>
            </div>
            
            <div class="mission-content">
                <div class="mission-text">
                    <h3>环保使命，可持续未来</h3>
                    <p>北京卡伯夫国际贸易有限公司专注于可降解环保包装产品的研发、生产与销售。我们的产品包括可降解包装、可降解杯托、可降解育苗杯等，覆盖多种规格型号，并提供定制化服务。</p>
                    <p>我们相信，商业成功与环境保护可以并行不悖。通过提供高品质的可降解产品，我们帮助客户减少碳足迹，实现环保目标，同时满足市场对可持续产品的需求。</p>
                    <p>我们的产品采用环保材料制成，可在自然环境中分解，不会对环境造成持久污染。从原材料采购到生产过程，我们都严格遵循环保标准，确保产品真正符合可持续发展的要求。</p>
                </div>
                <div class="mission-image">
                    <div class="product-img">
                        <i class="fas fa-leaf"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 产品中心 -->
    <section class="products" id="products">
        <div class="container">
            <div class="section-title">
                <h2>产品中心</h2>
                <p>我们提供全系列可降解环保产品，规格多样，支持定制，满足不同行业需求</p>
            </div>
            
            <div class="product-grid">
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-box-open"></i>
                    </div>
                    <div class="product-info">
                        <h3>可降解包装</h3>
                        <p>采用PLA、PBAT等生物基材料制成，可在自然环境中完全分解。适用于食品包装、电子产品包装、礼品包装等多种场景。</p>
                        <p><strong>规格:</strong> 多种尺寸、厚度可选，支持印刷定制</p>
                    </div>
                </div>
                
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-mug-hot"></i>
                    </div>
                    <div class="product-info">
                        <h3>可降解杯托</h3>
                        <p>适用于咖啡店、奶茶店、快餐店的环保杯托，承重力强，防水防油，使用后可完全生物降解。</p>
                        <p><strong>规格:</strong> 2杯位、4杯位、6杯位可选，支持品牌LOGO定制</p>
                    </div>
                </div>
                
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-seedling"></i>
                    </div>
                    <div class="product-info">
                        <h3>可降解育苗杯</h3>
                        <p>农业育苗专用可降解容器，可直接连同幼苗一起种植，在土壤中自然分解，减少移植伤害，提高成活率。</p>
                        <p><strong>规格:</strong> 多种口径、深度可选，支持不同作物需求</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 资质认证 -->
    <section class="certifications" id="certifications">
        <div class="container">
            <div class="section-title">
                <h2>资质认证</h2>
                <p>我们已获得国际权威认证，确保产品符合环保标准，质量可靠</p>
            </div>
            
            <div class="cert-grid">
                <div class="cert-item">
                    <i class="fas fa-certificate"></i>
                    <h3>FSC认证</h3>
                    <p>森林管理委员会认证</p>
                    <p>确保产品原材料来自可持续管理的森林</p>
                    <div class="cert-status status-active">已获得</div>
                </div>
                
                <div class="cert-item">
                    <i class="fas fa-award"></i>
                    <h3>BPI认证</h3>
                    <p>可生物降解产品研究所认证</p>
                    <p>证明产品可在工业堆肥设施中完全分解</p>
                    <div class="cert-status status-pending">申请中</div>
                </div>
                
                <div class="cert-item">
                    <i class="fas fa-globe-europe"></i>
                    <h3>OK compost认证</h3>
                    <p>欧盟可堆肥认证</p>
                    <p>符合欧盟EN13432标准的可堆肥认证</p>
                    <div class="cert-status status-pending">申请中</div>
                </div>
            </div>
        </div>
    </section>

    <!-- 公司优势 -->
    <section class="advantages" id="advantages">
        <div class="container">
            <div class="section-title">
                <h2>公司优势</h2>
                <p>选择卡伯夫，为您的企业提供可靠的环保解决方案</p>
            </div>
            
            <div class="advantage-list">
                <div class="advantage-item">
                    <i class="fas fa-cogs"></i>
                    <h3>规格齐全</h3>
                    <p>提供多种规格型号，满足不同行业需求</p>
                </div>
                
                <div class="advantage-item">
                    <i class="fas fa-edit"></i>
                    <h3>支持定制</h3>
                    <p>根据客户需求定制尺寸、厚度、印刷等</p>
                </div>
                
                <div class="advantage-item">
                    <i class="fas fa-certificate"></i>
                    <h3>认证齐全</h3>
                    <p>已获FSC认证，正在申请BPI、OK认证</p>
                </div>
                
                <div class="advantage-item">
                    <i class="fas fa-shipping-fast"></i>
                    <h3>快速交付</h3>
                    <p>拥有完善供应链，确保产品快速交付</p>
                </div>
                
                <div class="advantage-item">
                    <i class="fas fa-leaf"></i>
                    <h3>100%可降解</h3>
                    <p>产品可在自然环境中完全分解，环保无污染</p>
                </div>
                
                <div class="advantage-item">
                    <i class="fas fa-headset"></i>
                    <h3>专业服务</h3>
                    <p>提供专业咨询和技术支持，解决客户问题</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 页脚 -->
    <footer id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>北京卡伯夫国际贸易有限公司</h3>
                    <p>卡伯夫(CARBOFF) = 零碳排(Carbon Offset)</p>
                    <p>我们致力于提供环保可降解包装解决方案，助力企业实现可持续发展目标。</p>
                </div>
                
                <div class="footer-column">
                    <h3>产品中心</h3>
                    <ul>
                        <li><a href="#products">可降解包装</a></li>
                        <li><a href="#products">可降解杯托</a></li>
                        <li><a href="#products">可降解育苗杯</a></li>
                        <li><a href="#products">定制服务</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>资质认证</h3>
                    <ul>
                        <li>FSC认证（已获得）</li>
                        <li>BPI认证（申请中）</li>
                        <li>OK compost认证（申请中）</li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>联系我们</h3>
                    <div class="contact-info">
                        <p><i class="fas fa-building"></i> 北京卡伯夫国际贸易有限公司</p>
                        <p><i class="fas fa-map-marker-alt"></i> 北京市</p>
                        <p><i class="fas fa-phone"></i> 010-XXXX-XXXX</p>
                        <p><i class="fas fa-envelope"></i> info@carboff.com</p>
                    </div>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 北京卡伯夫国际贸易有限公司 版权所有 | 卡伯夫 - 零碳排环保解决方案</p>
            </div>
        </div>
    </footer>

    <script>
        // 移动端菜单切换
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mainMenu = document.getElementById('mainMenu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mainMenu.classList.toggle('active');
            
            // 切换菜单图标
            const icon = mobileMenuBtn.querySelector('i');
            if (icon.classList.contains('fa-bars')) {
                icon.classList.remove('fa-bars');
                icon.classList.add('fa-times');
            } else {
                icon.classList.remove('fa-times');
                icon.classList.add('fa-bars');
            }
        });
        
        // 点击菜单项后关闭移动菜单
        const menuItems = document.querySelectorAll('#mainMenu a');
        menuItems.forEach(item => {
            item.addEventListener('click', () => {
                mainMenu.classList.remove('active');
                const icon = mobileMenuBtn.querySelector('i');
                icon.classList.remove('fa-times');
                icon.classList.add('fa-bars');
            });
        });
        
        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // 页面滚动效果
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.style.boxShadow = '0 5px 20px rgba(0, 0, 0, 0.1)';
            } else {
                header.style.boxShadow = '0 2px 15px rgba(0, 0, 0, 0.05)';
            }
        });
    </script>
</body>
</html>
