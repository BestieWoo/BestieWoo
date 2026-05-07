<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BestieWoo - 我的作品集</title>
    <style>
        /* ----- 基础样式 ----- */
        * { margin:0; padding:0; box-sizing: border-box; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;}
        body { background: #fffaf0; color: #333; line-height: 1.6;}
        a { color: #ff6f61; text-decoration: none;}
        a:hover { text-decoration: underline;}
        img { max-width: 100%; display: block;}
        h1, h2, h3 { margin-bottom: 0.5em;}
        p { margin-bottom: 1em;}

        /* ----- 容器 ----- */
        .container { max-width: 1000px; margin: 0 auto; padding: 20px;}

        /* ----- 导航 ----- */
        nav { display: flex; justify-content: space-between; align-items: center; padding: 20px 0;}
        nav a { margin-left: 20px; font-weight: bold;}

        /* ----- 首页Banner ----- */
        .banner { text-align: center; padding: 100px 20px; background: #ffe4e1;}
        .banner h1 { font-size: 3em; margin-bottom: 20px;}
        .banner p { font-size: 1.2em; color: #555;}

        /* ----- 作品集 ----- */
        .portfolio { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 20px; margin: 50px 0;}
        .portfolio-item { background: #fff; border-radius: 10px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1); transition: transform 0.3s;}
        .portfolio-item:hover { transform: translateY(-5px);}
        .portfolio-item img { width: 100%; height: 200px; object-fit: cover;}
        .portfolio-item .info { padding: 15px;}
        .portfolio-item .info h3 { margin-bottom: 10px;}
        .portfolio-item .info p { font-size: 0.9em; color: #666;}

        /* ----- 关于我 ----- */
        .about { margin: 50px 0;}
        .about img { border-radius: 50%; width: 150px; margin-bottom: 20px;}
        .about p { max-width: 700px; margin: 0 auto;}

        /* ----- 联系 ----- */
        .contact { margin: 50px 0;}
        .contact form { max-width: 600px; margin: 0 auto; display: flex; flex-direction: column; gap: 15px;}
        .contact input, .contact textarea { padding: 10px; border-radius: 5px; border: 1px solid #ccc;}
        .contact button { padding: 10px; border: none; border-radius: 5px; background: #ff6f61; color: #fff; font-weight: bold; cursor: pointer;}
        .contact button:hover { background: #ff3b2e;}

        /* ----- 页脚 ----- */
        footer { text-align: center; padding: 20px; color: #aaa; font-size: 0.9em;}
    </style>
</head>
<body>

    <!-- 导航 -->
    <nav class="container">
        <div class="logo"><a href="#">BestieWoo</a></div>
        <div class="nav-links">
            <a href="#portfolio">作品集</a>
            <a href="#about">关于我</a>
            <a href="#contact">联系我</a>
        </div>
    </nav>

    <!-- 首页 Banner -->
    <section class="banner">
        <h1>欢迎来到 BestieWoo</h1>
        <p>我是外星人，讲故事的人，创意与研究的探索者</p>
    </section>

    <!-- 作品集 -->
    <section class="container" id="portfolio">
        <h2>作品集</h2>
        <div class="portfolio">
            <div class="portfolio-item">
                <img src="作品1.jpg" alt="作品1">
                <div class="info">
                    <h3>作品名称1</h3>
                    <p>简短介绍作品背景和创作思路</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="作品2.jpg" alt="作品2">
                <div class="info">
                    <h3>作品名称2</h3>
                    <p>简短介绍作品背景和创作思路</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="作品3.jpg" alt="作品3">
                <div class="info">
                    <h3>作品名称3</h3>
                    <p>简短介绍作品背景和创作思路</p>
                </div>
            </div>
            <!-- 可继续添加更多作品 -->
        </div>
    </section>

    <!-- 关于我 -->
    <section class="container about" id="about">
        <h2>关于我</h2>
        <div style="text-align:center;">
            <img src="头像.jpg" alt="我的头像">
        </div>
        <p>我是外星人，从事创意和研究工作。热爱探索生活中的点滴美好，喜欢用作品记录世界，也希望通过作品与更多人产生共鸣。这里展示我的部分作品，希望你喜欢！</p>
    </section>

    <!-- 联系我 -->
    <section class="container contact" id="contact">
        <h2>联系我</h2>
        <form>
            <input type="text" placeholder="你的姓名" required>
            <input type="email" placeholder="你的邮箱" required>
            <textarea placeholder="你的留言" rows="5" required></textarea>
            <button type="submit">发送</button>
        </form>
    </section>

    <!-- 页脚 -->
    <footer>
        &copy; 2026 BestieWoo. 版权所有.
    </footer>

</body>
</html>
