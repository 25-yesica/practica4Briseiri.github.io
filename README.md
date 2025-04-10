# practica4Briseiri.github.io
briseiri León
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Página Web</title>
  <style>
    :root {
      --primary-color: #2c3e50;
      --secondary-color: #3498db;
      --font-color: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #ecf0f1;
      color: var(--primary-color);
    }

    header {
      background-color: var(--primary-color);
      color: var(--font-color);
      padding: 1rem 2rem;
      text-align: center;
    }

    nav {
      margin-top: 1rem;
      text-align: center;
    }

    nav a {
      color: var(--secondary-color);
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    main {
      max-width: 960px;
      margin: 2rem auto;
      padding: 1rem;
    }

    footer {
      background-color: var(--primary-color);
      color: var(--font-color);
      text-align: center;
      padding: 1rem;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    button {
      padding: 0.5rem 1rem;
      background-color: var(--secondary-color);
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>

  <header>
    <h1>Bienvenido a Mi Página Web</h1>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="#">Servicios</a>
    <a href="#">Contacto</a>
  </nav>

  <main>
    <section>
      <h2>Sobre mí</h2>
      <p>Soy un programador profesional creando soluciones web modernas y eficientes.</p>
    </section>

    <section>
      <h2>Interacción</h2>
      <p>Presiona el botón para ver una acción de JavaScript:</p>
      <button onclick="mostrarMensaje()">Haz clic aquí</button>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Mi Nombre. Todos los derechos reservados.</p>
  </footer>

 
</body>
</html>
