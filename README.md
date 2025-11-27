index.html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>我的超酷项目</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      text-align: center;
      padding: 100px 20px;
      min-height: 100vh;
      margin: 0;
    }
    h1 {
      font-size: 3.5rem;
      margin-bottom: 20px;
      text-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    p {
      font-size: 1.3rem;
      opacity: 0.9;
    }
    .button {
      margin-top: 40px;
      padding: 15px 40px;
      font-size: 1.2rem;
      background: #fff;
      color: #667eea;
      border: none;
      border-radius: 50px;
      cursor: pointer;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      transition: all 0.3s;
    }
    .button:hover {
      transform: translateY(-5px);
      box-shadow: 0 15px 40px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>
  <h1>欢迎来到我的项目 🚀</h1>
  <p>一个用爱发电的前端页面～</p>
  <button class="button" onclick="alert('你点到我了！😍')">点我一下</button>
</body>
</html>
