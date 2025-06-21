<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NightlifeDR Tour & Travel</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #e0f7fa;
      color: #003c5e;
    }
    header {
      background-color: #0288d1;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      background-color: #03a9f4;
      text-align: center;
      padding: 1rem;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .services, .contact {
      background: #b3e5fc;
      margin-bottom: 2rem;
      border-radius: 8px;
      padding: 1.5rem;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .gallery img {
      width: calc(50% - 10px);
      border-radius: 8px;
    }
    footer {
      background-color: #0288d1;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .social-buttons {
      position: fixed;
      bottom: 20px;
      right: 20px;
      display: flex;
      flex-direction: column;
      gap: 10px;
      z-index: 1000;
    }
    .social-buttons a {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      color: white;
      font-size: 24px;
      text-decoration: none;
    }
    .whatsapp { background-color: #25D366; }
    .facebook { background-color: #3b5998; }
    .instagram {
      background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fd5949 45%, #d6249f 60%, #285AEB 90%);
    }
    @media (max-width: 768px) {
      header, nav, section, footer {
        padding: 1rem;
      }
      nav a {
        display: block;
        margin: 0.5rem 0;
      }
      .gallery img {
        width: 100%;
      }
    }
    input, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    input[type="submit"] {
      background: #0288d1;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <header>
    <h1>NightlifeDR Tour & Travel</h1>
    <p>Tu agencia de viajes confiable en Santo Domingo</p>
  </header>

  <nav>
    <a href="#servicios">Servicios</a>
    <a href="#productos">Productos</a>
    <a href="#galeria">Galería</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="servicios" class="services">
    <h2>Servicios</h2>
    <ul>
      <li>Transporte</li>
      <li>Traslado al aeropuerto</li>
      <li>Hoteles</li>
      <li>Cruceros</li>
      <li>Boletería</li>
      <li>Alquiler de villas y apartamentos (Airbnb)</li>
      <li>Traducción de documentos</li>
      <li>Asesoría para USA y Canadá</li>
    </ul>
  </section>

  <section id="productos" class="services">
    <h2>Productos</h2>
    <p>Ofrecemos paquetes turísticos personalizados, escapadas a destinos paradisíacos, reservas exclusivas en hoteles y más.</p>
  </section>

  <section id="galeria" class="services">
    <h2>Galería de Imágenes</h2>
    <div class="gallery">
      <img src="https://cdn.pixabay.com/photo/2016/10/06/22/16/beach-1721626_1280.jpg" alt="Playa en República Dominicana">
      <img src="https://cdn.pixabay.com/photo/2021/01/28/10/21/dominican-republic-5956862_1280.jpg" alt="Tour por la ciudad">
      <img src="https://cdn.pixabay.com/photo/2020/01/03/21/04/santo-domingo-4738343_1280.jpg" alt="Santo Domingo histórico">
      <img src="https://cdn.pixabay.com/photo/2022/08/02/14/32/island-7360782_1280.jpg" alt="Isla tropical">
      <img src="https://cdn.pixabay.com/photo/2016/11/18/17/20/plane-1838709_1280.jpg" alt="Vuelo aéreo">
      <img src="https://cdn.pixabay.com/photo/2016/11/19/14/00/beach-1836335_1280.jpg" alt="Resort en RD">
      <img src="https://cdn.pixabay.com/photo/2021/11/22/22/03/colombia-6815226_1280.jpg" alt="Colombia">
      <img src="https://cdn.pixabay.com/photo/2020/03/03/03/06/punta-cana-4896724_1280.jpg" alt="Punta Cana">
    </div>
  </section>

  <section id="contacto" class="contact">
    <h2>Contacto</h2>
    <p><strong>Teléfonos:</strong> 829-384-3299 / 809-232-5787</p>
    <p><strong>Dirección:</strong> Av. DR. Delgado, No.36, Gazcue, Santo Domingo, República Dominicana</p>
    <p><strong>Email:</strong> info@nightlifedr.com</p>

    <h3>Formulario de Contacto</h3>
    <form action="mailto:info@nightlifedr.com" method="post" enctype="text/plain">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="email">Correo electrónico:</label>
      <input type="email" id="email" name="email" required>

      <label for="mensaje">Mensaje:</label>
      <textarea id="mensaje" name="mensaje" rows="5" required></textarea>

      <input type="submit" value="Enviar mensaje">
    </form>
  </section>

  <div class="social-buttons">
    <a class="whatsapp" href="https://wa.me/18293843299" target="_blank" title="WhatsApp">
      <i class="fab fa-whatsapp"></i>
    </a>
    <a class="facebook" href="https://facebook.com/nightlifedrtour" target="_blank" title="Facebook">
      <i class="fab fa-facebook-f"></i>
    </a>
    <a class="instagram" href="https://instagram.com/nightlifedrtour" target="_blank" title="Instagram">
      <i class="fab fa-instagram"></i>
    </a>
  </div>

  <footer>
    <p>&copy; 2025 NightlifeDR Tour & Travel. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
Travel Agency
