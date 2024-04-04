<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Мій темний фіолетовий сайт</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #1f1632;
    color: #fff;
    margin: 0;
    padding: 0;
  }
  
  header {
    padding: 20px;
    text-align: center;
    margin-bottom: 20px;
    border-radius: 10px;
    background: linear-gradient(135deg, #45207e, #8e44ad);
  }

  header h1 {
    margin: 0;
  }

  .main-content {
    display: flex;
    justify-content: space-between;
    padding: 20px;
  }

  .sidebar {
    width: 30%;
    background-color: #2c3e50;
    padding: 20px;
    border-radius: 10px;
    margin-right: 20px;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    color: #fff;
  }

  table, th, td {
    border: 1px solid #fff;
    padding: 10px;
    text-align: left;
  }

  th {
    background-color: #45207e;
  }

  .sidebar a {
    color: #af7ac5;
    text-decoration: none;
    transition: background-color 0.3s;
    display: block;
    padding: 10px;
    margin-bottom: 10px;
    border-radius: 5px;
    text-align: center;
    border: 1px solid transparent;
    border-radius: 5px;
    background-image: linear-gradient(135deg, #45207e, #8e44ad);
    background-clip: padding-box;
    -webkit-background-clip: padding-box;
    animation: border-color-change 2s infinite alternate;
  }

  .sidebar a:hover {
    background-color: #5b2c83;
  }

  @keyframes border-color-change {
    0% {
      border-color: #45207e;
    }
    50% {
      border-color: #583b94;
    }
    100% {
      border-color: #8e44ad;
    }
  }
</style>
</head>
<body>

<header>
  <h1>PSYCHO STORM</h1>
</header>

<div class="main-content">
  <div class="sidebar">
    <h2>Мої соціальні мережі</h2>
    <a href="https://www.instagram.com/zxcpidarass?igshid=MXRwNnRpc3ZwOGluYg==" target="_blank">Instagram 𓆩𓆪</a>
    <a href="https://t.me/zxcstormikk" target="_blank">Telegram 𓆩𓆪</a>
    <a href="https://www.twitch.tv/psychostormik" target="_blank">Twitch 𓆩𓆪</a>
  </div>
  
  <div class="content">
    <h2>Основний вміст</h2>
    <p>Це основний вміст вашого сайту.</p>
    <p>Додайте сюди свій контент.</p>
  </div>
  
  <div class="sidebar">
    <img src="https://i.pinimg.com/originals/47/21/5a/47215a8d5879b407a8b9822ee860915d.gif" alt="GIF" style="width: 100%; border-radius: 10px;">
  </div>
</div>

<footer>
  <p>© 2024 Мій сайт. Усі права захищені.</p>
</footer>

</body>
</html>
