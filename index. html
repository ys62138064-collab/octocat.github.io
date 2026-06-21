<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>艺术家 · 郑雨丝</title>
    <style>
        /* 全局重置与字体 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #faf8f5;          /* 柔和米白底，更显雅致 */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 2rem 1rem;
            font-family: 'Georgia', 'Times New Roman', '宋体', 'KaiTi', serif;
            line-height: 1.7;
            color: #2c2c2c;
        }

        .art-card {
            max-width: 880px;
            width: 100%;
            background: #ffffff;
            padding: 2.5rem 2.8rem;
            border-radius: 32px;
            box-shadow: 0 12px 28px rgba(0, 0, 0, 0.06), 0 4px 12px rgba(0, 0, 0, 0.03);
            transition: all 0.2s ease;
            text-align: center;            /* 关键：所有内联块级文字、图片居中 */
        }

        /* 艺术家简介标题 — 优雅小标题 */
        .intro-label {
            display: inline-block;
            font-size: 0.9rem;
            letter-spacing: 4px;
            color: #a58b7a;
            border-bottom: 1px solid #e2d6cc;
            padding-bottom: 6px;
            margin-bottom: 1.2rem;
            text-transform: uppercase;
            font-weight: 400;
        }

        /* 简介文字段落 — 居中 + 舒适间距 */
        .bio-text {
            font-size: 1.05rem;
            text-align: center;            /* 强制居中 */
            margin: 0 auto 2.2rem auto;
            max-width: 760px;
            word-break: break-word;
            letter-spacing: 0.02em;
            color: #1e1e1e;
        }

        /* 姓名与年份保留一点层次 */
        .bio-text strong {
            font-weight: 600;
            color: #3d2c21;
        }

        .bio-text .highlight {
            display: inline-block;
            background: #f3ede8;
            padding: 0.1rem 0.6rem;
            border-radius: 20px;
            font-size: 0.95rem;
            color: #5f4a3a;
        }

        /* 图片容器 — 完全居中 */
        .image-wrapper {
            text-align: center;
            margin: 0 auto;
            width: 100%;
        }

        .image-wrapper img {
            display: block;
            max-width: 100%;
            height: auto;
            width: 800px;                /* 保留原宽度，自适应 */
            max-height: 1200px;
            object-fit: contain;
            margin: 0 auto;              /* 水平居中 */
            border-radius: 18px;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.06);
            transition: transform 0.2s;
            background-color: #f6f2ed;   /* 加载占位柔色 */
        }

        /* 图片说明（可选），但保留干净 */
        .image-caption {
            margin-top: 0.8rem;
            font-size: 0.9rem;
            color: #9b8a7c;
            letter-spacing: 1px;
        }

        /* 移动端适配 */
        @media (max-width: 600px) {
            .art-card {
                padding: 1.8rem 1.2rem;
            }
            .bio-text {
                font-size: 0.98rem;
                text-align: center;
            }
            .image-wrapper img {
                width: 100%;
                max-width: 600px;
            }
        }

        /* 给文字中的换行保留，但用段落包裹更具语义，同时保持居中 */
        .bio-text p {
            margin-bottom: 0.8rem;
            text-align: center;
        }

        .bio-text p:last-of-type {
            margin-bottom: 0;
        }

        /* 小细节：姓名突出 */
        .artist-name {
            font-size: 1.4rem;
            font-weight: 500;
            letter-spacing: 3px;
            color: #3d2c21;
            display: block;
            margin: 0.2rem 0 0.6rem 0;
        }

        /* 分割装饰 */
        .divider-light {
            width: 60px;
            height: 2px;
            background: #dacfc6;
            margin: 0.8rem auto 1.6rem auto;
            border-radius: 4px;
        }

    </style>
</head>
<body>
    <div class="art-card">
        <!-- 小标签：艺术家简介 -->
        <span class="intro-label">✦ 艺 术 家 简 介 ✦</span>

        <!-- 文字部分：完全居中，保留原内容，细化结构 -->
        <div class="bio-text">
            <span class="artist-name">郑雨丝</span>
            <div class="divider-light"></div>

            <p>
                <strong>2023年</strong>毕业于暨南大学本科，<strong>2024年</strong>在香港大学专业进修学院修读设计课程，<br>
                <strong>2026年</strong>入读香港教育大学研究生。
            </p>
            <p>
                现生活于香港并从事艺术教育工作，曾获得伦敦英国绘画比赛奖项，<br>
                画作曾在英国伦敦与香港展出。曾被深圳万达广场邀请个展<br>
                <span class="highlight">「山有扶苏，隰有荷华」</span> 个展。
            </p>
            <p>
                擅长运用工笔绘画生活中的静物、所见所闻及研究古代仕女，<br>
                在传统风格里面加入一些现代元素，赋予其美好的思想感情。<br>
                用细腻的线条勾勒出物体的整体轮廓，用墨水晕染出不同的层次感和厚度，<br>
                用色彩赋予其情感的完美释放。最后将美融于画作事物之中，<br>
                以水墨的方式彰显「美学」韵味，塑造出富有现代人性的画面感，<br>
                又能产生一种恬静淡雅，又不失风韵的现代水墨画作。
            </p>
        </div>

        <!-- 图片部分：完全居中，宽度保持800px，高度自适应 -->
        <div class="image-wrapper">
            <img src="图片8.jpg" alt="郑雨丝作品 · 水墨意境" width="800" height="1200" loading="lazy">
            <!-- 可选小字说明，保留干净则注释掉 -->
            <!-- <div class="image-caption">—— 工笔 · 现代水墨 ——</div> -->
        </div>
    </div>
</body>
</html>
