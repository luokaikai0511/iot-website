<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>物聯網網站</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Microsoft JhengHei', sans-serif;
            min-height: 100vh;
            background: linear-gradient(135deg, #0a1628, #1a3a5c);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
        }
        .container {
            text-align: center;
            background: rgba(255,255,255,0.08);
            border-radius: 20px;
            padding: 50px 40px;
            max-width: 500px;
        }
        .logo {
            width: 150px;
            height: 150px;
            margin: 0 auto 25px;
        }
        .logo img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
        h1 { font-size: 1.8em; margin-bottom: 8px; }
        .subtitle { color: #8ab4f8; margin-bottom: 25px; }
        .info {
            background: rgba(255,255,255,0.1);
            border-radius: 12px;
            padding: 20px;
            margin: 20px 0;
        }
        .label {
            font-size: 0.85em;
            color: #aaa;
            margin-bottom: 5px;
        }
        .value {
            font-size: 1.5em;
            font-weight: 700;
            letter-spacing: 2px;
        }
        .footer {
            font-size: 0.8em;
            color: #666;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="https://secretary.lhu.edu.tw/var/file/35/1035/img/586481327.png" alt="龍華科技大學校徽">
        </div>
        <h1>龍華科技大學</h1>
        <p class="subtitle">物聯網實習網站</p>
        <div class="info">
            <p class="label">學號</p>
            <p class="value">D1134141050</p>
        </div>
        <p class="footer">本網站使用 GitHub Pages 建置</p>
    </div>
</body>
</html>
