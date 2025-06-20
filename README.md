<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bienvenid@</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .container {
      text-align: center;
      background: white;
      padding: 60px 40px;
      border-radius: 20px;
      box-shadow: 0 10px 40px rgba(0, 0, 0, 0.2);
      animation: fadeIn 2s ease-in-out;
    }

    h1 {
      font-size: 3em;
      color: #333;
      margin-bottom: 0.5em;
    }

    p {
      font-size: 1.2em;
      color: #555;
      margin-bottom: 1.5em;
    }

    .btn {
      padding: 12px 25px;
      font-size: 1em;
      background: #6c63ff;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
      text-decoration: none;
    }

    .btn:hover {
      background: #554ed6;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(-30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive */
    @media (max-width: 600px) {
      .container {
        width: 90%;
        padding: 40px 20px;
      }

      h1 {
        font-size: 2em;
      }

      p {
        font-size: 1em;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>¡Bienvenid@ a Mi Sitio Web!</h1>
    <p>Gracias por visitar. Aquí encontrarás contenido interesante, útil y hecho con mucho cariño. ¡Explora y disfruta!</p>
    <a href="#explorar" class="btn">Comenzar</a>
  </div>
</body>
</html>
