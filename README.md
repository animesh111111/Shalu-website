<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shalu</title>
  <style>
    body {
      margin: 0;
      background-color: #f8f9fa;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .heart {
      position: relative;
      width: 200px;
      height: 180px;
      background-color: red;
      transform: rotate(-45deg);
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 200px;
      height: 180px;
      background-color: red;
      border-radius: 50%;
    }
    .heart::before {
      top: -100px;
      left: 0;
    }
    .heart::after {
      left: 100px;
      top: 0;
    }
    .name {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) rotate(45deg);
      font-size: 24px;
      color: white;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="heart">
    <div class="name">shalu</div>
  </div>
</body>
</html>
