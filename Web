<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Club de Lectura con Propósito</title>
  <style>
    /* Fuentes y reset ligero */
    *, *::before, *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #fafafa;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    img {
      max-width: 100%;
      display: block;
    }

    /* Encabezado */
    header {
      background: linear-gradient(135deg, #4b6cb7 0%, #182848 100%);
      color: white;
      text-align: center;
      padding: 4rem 1rem;
    }
    header h1 {
      font-size: 2.8rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    /* Navegación */
    nav {
      background-color: #fff;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav .container {
      max-width: 1200px;
      margin: auto;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0.8rem 1rem;
    }
    nav a {
      margin: 0 1.2rem;
      font-weight: 600;
      color: #4b6cb7;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #182848;
    }

    /* Sección genérica */
    section {
      padding: 4rem 1rem;
    }
    section .container {
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      font-size: 2rem;
      color: #4b6cb7;
      margin-bottom: 1rem;
      text-align: center;
    }
    p {
      margin-bottom: 1.4rem;
    }

    /* Sobre nosotros */
    #nosotros p {
      font-size: 1.1rem;
      color: #555;
    }

    /* Libros recomendados */
    #libros .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .libro {
      background-color: #fff;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .libro:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.08);
    }
    .libro img {
      height: 180px;
      object-fit: cover;
      width: 100%;
    }
    .libro .info {
      padding: 1.2rem;
    }
    .libro .info h3 {
      margin-bottom: 0.5rem;
      color: #182848;
    }
    .libro .info p {
      font-size: 0.95rem;
      color: #666;
      line-height: 1.4;
    }

    /* Eventos */
    #eventos .evento {
      margin-bottom: 2.5rem;
      padding-bottom: 2.5rem;
      border-bottom: 1px solid #eee;
    }
    #eventos .evento:last-child {
      border-bottom: none;
    }
    #eventos .evento h3 {
      color: #182848;
      font-size: 1.4rem;
      margin-bottom: 0.5rem;
    }
    #eventos .evento span {
      display: block;
      color: #888;
      font-size: 0.9rem;
      margin-bottom: 1rem;
    }

    /* Contacto */
    #contacto form {
      max-width: 600px;
      margin: auto;
      display: grid;
      gap: 1.2rem;
    }
    #contacto input, #contacto textarea {
      width: 100%;
      padding: 0.9rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }
    #contacto button {
      padding: 1rem 2rem;
      background-color: #4b6cb7;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    #contacto button:hover {
      background-color: #3a5095;
    }

    /* Pie de página */
    footer {
      background-color: #182848;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
    }

    /* Adaptabilidad (responsive) */
    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }
      section {
        padding: 3rem 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Club de Lectura con Propósito</h1>
    <p>Leer con intención. Crecer con cada página.</p>
  </header>

  <nav>
    <div class="container">
      <a href="#inicio">Inicio</a>
      <a href="#nosotros">Sobre nosotros</a>
      <a href="#libros">Libros recomendados</a>
      <a href="#eventos">Eventos</a>
      <a href="#contacto">Contacto</a>
    </div>
  </nav>

  <section id="inicio">
    <div class="container">
      <h2>Bienvenido</h2>
      <p>En nuestro club, creemos que la lectura va más allá del entretenimiento. Es una herramienta de transformación personal, de descubrimiento y de conexión. Si estás buscando un espacio donde compartir lecturas que inspiran y motivan, estás en el lugar adecuado.</p>
    </div>
  </section>

  <section id="nosotros" style="background-color:#fff;">
    <div class="container">
      <h2>Sobre Nosotros</h2>
      <p>Somos un grupo diverso de lectores que se unen con un propósito común: crecer, aprender y compartir. Nos reunimos una vez al mes para comentar libros que no solo entretienen, sino que también invitan a la reflexión y al cambio. Aquí encontrarás un ambiente acogedor, respetuoso y entusiasta.</p>
    </div>
  </section>

  <section id="libros">
    <div class="container">
      <h2>Libros Recomendados</h2>
      <div class="grid">
        <div class="libro">
          <img src="https://via.placeholder.com/400x180?text=Los+Cuatro+Acuerdos" alt="Los Cuatro Acuerdos">
          <div class="info">
            <h3>Los Cuatro Acuerdos</h3>
            <p>Autor: Don Miguel Ruiz. Sabiduría tolteca para vivir con libertad, amor y paz.</p>
          </div>
        </div>
        <div class="libro">
          <img src="https://via.placeholder.com/400x180?text=El+Poder+del+Ahora" alt="El Poder del Ahora">
          <div class="info">
            <h3>El Poder del Ahora</h3>
            <p>Autor: Eckhart Tolle. Una guía para vivir en el momento presente y encontrar la plenitud.</p>
          </div>
        </div>
        <div class="libro">
          <img src="https://via.placeholder.com/400x180?text=El+Alquimista" alt="El Alquimista">
          <div class="info">
            <h3>El Alquimista</h3>
            <p>Autor: Paulo Coelho. Una historia sobre sueños, búsqueda y descubrimiento personal.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="eventos" style="background-color:#fff;">
    <div class="container">
      <h2>Eventos Próximos</h2>
      <div class="evento">
        <h3>Reunión Mensual – Mayo</h3>
        <span>Fecha: 15 de mayo · Hora: 18:00 · Lugar: Biblioteca Central</span>
        <p>Nos reuniremos para comentar el libro del mes, compartir reflexiones y escoger la lectura del mes siguiente. ¡Te esperamos!</p>
      </div>
      <div class="evento">
        <h3>Taller de Lectura Creativa</h3>
        <span>Fecha: 30 de mayo · Hora: 10:00 · Lugar: Sala de eventos</span>
        <p>Un encuentro especial para explorar técnicas de lectura activa, compartir recomendaciones y fomentar nuestra comunidad lectora.</p>
      </div>
    </div>
  </section>

  <section id="contacto">
    <div class="container">
      <h2>Contacto</h2>
      <p>¿Te gustaría unirte al club o tienes alguna sugerencia? Contáctanos.</p>
      <form action="#" method="post">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo electrónico" required>
        <textarea name="mensaje" rows="4" placeholder="Tu mensaje"></textarea>
        <button type="submit">Enviar</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Club de Lectura con Propósito. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
