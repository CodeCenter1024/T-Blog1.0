----------说明-------------
日期：2024年5月8日 • #Hanzhe T-Blog
Hello，大家好，欢迎来到我的个人blog。如果你未经允许访问我的Blog，请自觉退出（网警除外）。
我是Hanzhe，来自六年级一班，热爱电脑，网络，曾获得编程大赛国家二等奖，贵州省一等奖，不幸的是，作者Hanzhe左脚踝骨骨折，无法上课，于是闷在家制作了这个Blog。
如果你也喜欢我的博客，我可以分享制作方式和源代码（仅供参考）。
Update：之前的“Hanzhe Workstation”不稳定也无参与性，于是，我在网上买了这个服务器（缺点：只支持电脑端访问，手机端和iPad端要“威皮n”，电脑访问也没有多快）。
将沿用HanzheWorkstation的引用等内容，部分代码参考如下：
    </style>
</head>
<body class="bg-light">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">技术日志</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#articles">最新文章</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">项目作品</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">关于作者</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container mt-5 pt-4">
        <section id="featured-post" class="row g-4 mb-5 p-4">
            <div class="col-md-8">
                <h2 class="display-5 mb-3">最新技术分享</h2>
                <div id="article-content" class="code-block">
                    <!-- Markdown内容将通过JavaScript动态加载 -->
                </div>
            </div>
            <div class="col-md-4">
                <div class="bg-white p-4 rounded shadow-sm">
                    <h5>热门标签</h5>
                    <div class="tag-cloud mt-3" id="tags">
                        <a href="#" class="badge bg-secondary me-1 mb-1">Python</a>
                        <a href="#" class="badge bg-secondary me-1 mb-1">算法</a>
                        <a href="#" class="badge bg-secondary me-1 mb-1">Web开发</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="article-list" class="row row-cols-1 row-cols-md-2 g-4">
            <!-- 文章卡片将通过JavaScript动态加载 -->
        </section>
    </main>

    <footer class="bg-dark text-white mt-5 py-4">
        <div class="container text-center">
            <p class="mb-1">© 2024-2025 Hanzhe的技术博客</p>
            <div class="social-links">
                <a href="#" class="text-white me-3">GitHub</a>
                <a href="#" class="text-white me-3">LinkedIn</a>
                <a href="#" class="text-white">Email</a>
            </div>
        </div>
    </footer>

    <script src="https://cdn.bootcdn.net/ajax/libs/marked/4.3.0/marked.min.js"></script>
    <script src="https://cdn.bootcdn.net/ajax/libs/highlight.js/11.5.0/highlight.min.js"></script>
    <script src="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdn.bootcdn.net/ajax/libs/marked/12.0.2/marked.min.js"></script>
    <script>
        // 初始化Markdown渲染和代码高亮
        marked.setOptions({
            highlight: function(code, lang) {
                return hljs.highlightAuto(code).value;
            }
        });
部分注释能更好的帮助我写代码时保持思路。


最后：之前的“Hanzhe Workstation”两周后将停止支持，请各位转到此网站。
©2024-2025 Hanzhe Blog 1.0 版权所有。
