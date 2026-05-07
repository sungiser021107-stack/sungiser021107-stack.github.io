<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的深度学习笔记</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background: #f6f8fa;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
            line-height: 1.7;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
        }
        h1 {
            font-size: 32px;
            color: #24292e;
            margin-bottom: 10px;
        }
        .desc {
            color: #586069;
            font-size: 16px;
        }
        .article-list {
            background: white;
            border-radius: 12px;
            padding: 25px 30px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.06);
        }
        .article-list a {
            display: block;
            font-size: 18px;
            color: #0366d6;
            text-decoration: none;
            padding: 12px 0;
            border-bottom: 1px solid #f1f1f1;
        }
        .article-list a:last-child {
            border-bottom: none;
        }
        .article-list a:hover {
            color: #0550a3;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>我的深度学习笔记</h1>
        <p class="desc">记录 PyTorch / 目标检测 / 神经网络学习过程</p>
    </header>

    <div class="article-list">
        <a href="note1.html">📝 Pytorch 数据集加载</a>
        <a href="note2.html">📝 HWC 与 CHW 维度转换</a>
        <a href="note3.html">📝 单目标检测任务原理</a>
        <a href="note4.html">📝 神经网络输出层设计</a>
    </div>
</body>
</html>
