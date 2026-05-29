<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="XL空间 - 个人主页，展示我的技能和经历">
    <title>XL的空间 - 个人主页</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar">
        <div class="container">
            <a href="index.html" class="logo">
                <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="50" cy="50" r="45" fill="none" stroke="#0984e3" stroke-width="3"/>
                    <path d="M30 70 L50 25 L70 70" fill="none" stroke="#2d3436" stroke-width="4" stroke-linecap="round"/>
                    <path d="M38 55 L62 55" fill="none" stroke="#2d3436" stroke-width="3" stroke-linecap="round"/>
                </svg>
                <span>XL的空间</span>
            </a>
            <ul class="nav-links">
                <li><a href="index.html" class="active">首页</a></li>
                <li><a href="about.html">关于我</a></li>
                <li><a href="portfolio.html">作品集</a></li>
                <li><a href="skills.html">技能</a></li>
                <li><a href="blog.html">爱好</a></li>
                <li><a href="contact.html">联系我</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-avatar">
                    <img src="https://api.dicebear.com/7.x/avataaars/svg?seed=moyan&backgroundColor=0984e3" alt="XL头像">
                </div>
                <h1>您好，我是<span>XL</span></h1>
                <p>一名毕业于商科与计算机交叉专业的学生</p>
                <p>喜欢突破自我挑战“不可能”</p>
                <div style="display: flex; gap: 15px; justify-content: center; margin-top: 30px;">
                    <a href="portfolio.html" class="btn btn-primary">查看作品</a>
                    <a href="contact.html" class="btn btn-outline">联系我</a>
                </div>
            </div>
        </div>
    </section>

    <section class="section" style="background: var(--light-bg);">
        <div class="container">
            <div class="section-title">
                <h2>近期作品</h2>
                <p>快来瞧瞧我最近在干什么</p>
            </div>
            <div class="grid grid-3">
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=600&h=400&fit=crop" alt="电商平台项目" loading="lazy">
                    <div class="card-content">
                        <h3>电商平台系统</h3>
                        <p>基于现代技术栈构建的全功能电商解决方案，包含商品管理、订单处理和支付集成。</p>
                    </div>
                </div>
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1551650975-87deedd944c3?w=600&h=400&fit=crop" alt="移动应用项目" loading="lazy">
                    <div class="card-content">
                        <h3>健康管理应用</h3>
                        <p>帮助用户追踪健康数据的移动应用，支持运动记录、饮食管理和睡眠分析。</p>
                    </div>
                </div>
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?w=600&h=400&fit=crop" alt="数据可视化项目" loading="lazy">
                    <div class="card-content">
                        <h3>数据分析仪表盘</h3>
                        <p>交互式数据可视化平台，将复杂数据转化为直观的图表和洞察报告。</p>
                    </div>
                </div>
            </div>
            <div style="text-align: center; margin-top: 40px;">
                <a href="portfolio.html" class="btn btn-outline">查看全部作品</a>
            </div>
        </div>
    </section>

    <section class="section">
        <div class="container">
            <div class="section-title">
                <h2>核心技能</h2>
                <p>我在学习与工作中积累的专业能力</p>
            </div>
            <div class="grid grid-4" style="grid-template-columns: repeat(4, 1fr);">
                <div class="skill-item">
                    <i class="fab fa-html5"></i>
                    <h4>前端开发</h4>
                    <p>HTML5 / CSS3 / JavaScript</p>
                </div>
                <div class="skill-item">
                    <i class="fab fa-react"></i>
                    <h4>框架应用</h4>
                    <p>React / Vue / Node.js</p>
                </div>
                <div class="skill-item">
                    <i class="fas fa-database"></i>
                    <h4>后端开发</h4>
                    <p>Python / Java / MySQL</p>
                </div>
                <div class="skill-item">
                    <i class="fas fa-paint-brush"></i>
                    <h4>UI设计</h4>
                    <p>Figma / Sketch / PS</p>
                </div>
            </div>
        </div>
    </section>

    <section class="section" style="background: var(--light-bg);">
        <div class="container">
            <div class="section-title">
                <h2>我的爱好</h2>
                <p>来看看我的生活碎片</p>
            </div>
            <div class="blog-card">
                <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=600&h=400&fit=crop" alt="编程效率提升" loading="lazy">
                <div class="blog-content">
                    <h3>握紧方向盘去遇见未知的风景</h3>
                    <p>对我而言，自驾不仅是简单的出行方式，更是一场关于自由与探索的浪漫奔赴...</p>
                    <div class="blog-meta">
                        <span><i class="far fa-calendar"></i> 2026年5月30日</span>
                    </div>
                </div>
            </div>
            <div class="blog-card">
                <img src="https://images.unsplash.com/photo-1504639725590-34d0984388bd?w=600&h=400&fit=crop" alt="代码重构心得" loading="lazy">
                <div class="blog-content">
                    <h3>在呼吸与心跳的间隙里雕刻更好的自己</h3>
                    <p>健身不仅是肌肉与重量的对抗，更是一场身体与灵魂的深度对话。当汗水洗去日常的浮躁与疲惫，我在每一次坚持与力竭中，重新找回了对生活的掌控感与内在的秩序。</p>
                    <div class="blog-meta">
                        <span><i class="far fa-calendar"></i> 2026年5月30日</span>
                    </div>
                </div>
            </div>
            <div style="text-align: center; margin-top: 30px;">
                <a href="blog.html" class="btn btn-outline">了解更多我的爱好</a>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h4>再次介绍一下XL</h4>
                    <p>一名毕业于商科与计算机交叉专业的学生</p>
                    <p>喜欢突破自我挑战“不可能”</p>
                    <div class="social-links" style="margin-top: 15px;">
                        <a href="#"><i class="fab fa-github"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-weixin"></i></a>
                    </div>
                </div>
                <div class="footer-section">
                    <h4>快速链接</h4>
                    <p><a href="about.html">关于我</a></p>
                    <p><a href="portfolio.html">作品集</a></p>
                    <p><a href="contact.html">联系我</a></p>
                </div>
                <div class="footer-section">
                    <h4>联系方式</h4>
                    <p><i class="fas fa-envelope"></i> xuan246163@163.com</p>
                    <p><i class="fas fa-map-marker-alt"></i> 中国 · 成都</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2026 XL空间. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script src="js/main.js"></script>
</body>
</html>
