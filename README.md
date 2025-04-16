<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feliz Cumpleaños Alexander</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(#ffe0f0, #fff);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      overflow: hidden;
    }

    h1 {
      margin-top: 50px;
      font-size: 2.5rem;
      color: #d6336c;
    }

    p {
      font-size: 1.2rem;
      color: #333;
      max-width: 600px;
      margin: 0 auto 20px;
    }

    .cake {
      position: relative;
      margin: 50px auto;
      width: 200px;
      height: 200px;
      background: #ffc107;
      border-radius: 10px 10px 0 0;
      box-shadow: 0 10px 0 #d6336c;
    }

    .candle {
      width: 10px;
      height: 30px;
      background: #6c757d;
      position: absolute;
      top: -40px;
      left: 50%;
      transform: translateX(-50%);
      border-radius: 2px;
    }

    .flame {
      width: 10px;
      height: 20px;
      background: orange;
      border-radius: 50%;
      position: absolute;
      top: -25px;
      left: 50%;
      transform: translateX(-50%);
      animation: flicker 1s infinite;
    }

    @keyframes flicker {
      0% { transform: translateX(-50%) scale(1); opacity: 1; }
      50% { transform: translateX(-50%) scale(1.2); opacity: 0.7; }
      100% { transform: translateX(-50%) scale(1); opacity: 1; }
    }

    .message {
      animation: fadeIn 3s ease forwards;
      opacity: 0;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <h1>🎉 ¡Feliz Cumpleaños, Alexander! 🎉</h1>

  <div class="cake">
    <div class="candle">
      <div class="flame"></div>
    </div>
  </div>

  <div class="message">
    <p><strong>Buen día dormilón</strong></p>
    <p>Te deseo un año más lleno de minutos de amor,</p>
    <p>días de felicidad</p>
    <p>y meses de mucha alegría.</p>
    <p>¡Feliz cumpleaños, Alexander!</p>
  </div>
</body>
</html>
