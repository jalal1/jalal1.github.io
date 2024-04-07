---
layout: page
title: ALMT
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Title in the Middle</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            background-image: url('background-image.jpg'); /* Replace 'background-image.jpg' with your own image */
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container {
            text-align: center;
        }
        .title {
            font-size: 2.5em;
            margin-bottom: 30px;
        }
        .work {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin-bottom: 20px;
            max-width: 400px;
            margin: auto;
        }
        .work h2 {
            margin-top: 0;
        }
        .work p {
            margin-bottom: 0;
        }
        .work a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="title">
        Title in the Middle
    </div>
    
    <div class="work" onclick="window.location.href='https://example.com/work1'">
        <h2>Work 1</h2>
        <p>Description of Work 1</p>
    </div>

    <div class="work" onclick="window.location.href='https://example.com/work2'">
        <h2>Work 2</h2>
        <p>Description of Work 2</p>
    </div>

    <div class="work" onclick="window.location.href='https://example.com/work3'">
        <h2>Work 3</h2>
        <p>Description of Work 3</p>
    </div>
</div>

</body>
</html>
