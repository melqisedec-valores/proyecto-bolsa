<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IA para Bolsa de Valores</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f3f4f6;
      color: #111827;
    }
    header {
      background-color: #111827;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      background-color: #1f2937;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 0.5rem;
    }
    main {
      padding: 2rem;
    }
    .card {
      background-color: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      margin-bottom: 2rem;
    }
    footer {
      background-color: #111827;
      color: white;
      text-align: center;
      padding: 1rem;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Analizador Bursátil con IA</h1>
    <p>Predicciones y recomendaciones en tiempo real</p>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="#">Datos de Acciones</a>
    <a href="#">Recomendaciones</a>
    <a href="#">Contacto</a>
  </nav>

  <main>
    <section class="card" id="stock-data">
      <h2>📈 Datos en tiempo real</h2>
      <p>Conectando con la API...</p>
    </section>

    <section class="card" id="ai-prediction">
      <h2>🤖 Recomendaciones con IA</h2>
      <p>Predicciones aparecerán aquí...</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 - Proyecto de IA para Bolsa de Valores</p>
  </footer>

  <script>
    // Aquí más adelante vamos a conectar con una API real
    document.getElementById("stock-data").innerHTML += "<p>Ejemplo: AAPL $173.45</p>";
  </script>
</body>
</html>
