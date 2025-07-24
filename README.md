<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <title>زرقني</title>
  <style>
    body {
      background: black;
      color: cyan;
      font-size: 3em;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    #name {
      transition: opacity 1s ease;
    }
  </style>
</head>
<body>
  <div id="name">آدم</div>

  <script>
    setTimeout(() => {
      document.getElementById("name").style.opacity = "0";
    }, 3000); // الاسم يختفي بعد 3 ثواني
  </script>
</body>
</html>
