<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Catálogo Sneakers Chile</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #f8f8f8;
    margin: 0; padding: 0;
  }
  header {
    background: #333;
    color: white;
    padding: 1rem;
    text-align: center;
  }
  h1 {
    margin: 0;
  }
  .catalogo {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 1rem;
  }
  .producto {
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgb(0 0 0 / 0.15);
    width: 280px;
    padding: 15px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .producto img {
    max-width: 100%;
    border-radius: 6px;
  }
  .nombre {
    font-weight: bold;
    margin: 10px 0 5px;
    font-size: 1.2rem;
    text-align: center;
  }
  .precio {
    color: #e53935;
    font-weight: bold;
    margin: 5px 0;
    font-size: 1.1rem;
  }
  .tallas {
    font-size: 0.9rem;
    color: #555;
    margin-bottom: 10px;
  }
  .boton-contacto {
    background: #25d366; /* WhatsApp green */
    color: white;
    border: none;
    padding: 10px 15px;
    border-radius: 5px;
    cursor: pointer;
    text-decoration: none;
    font-weight: bold;
    font-size: 1rem;
    text-align: center;
    width: 100%;
  }
  .boton-contacto:hover {
    background: #128c4a;
  }
  footer {
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
    color: #666;
  }
  @media(max-width:600px){
    .catalogo {
      flex-direction: column;
      align-items: center;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Catálogo Sneakers Chile</h1>
  <p>Encuentra tus zapatillas favoritas y contáctanos para comprar</p>
</header>

<section class="catalogo">

  <!-- Producto 1 -->
  <article class="producto">
    <img src="https://i.imgur.com/AzTgOVt.jpg" alt="Jordan 3 Retro White Cement" />
    <div class="nombre">Jordan 3 Retro White Cement</div>
    <div class="precio">$79.990</div>
    <div class="tallas">Tallas disponibles: 38 - 44</div>
    <a href="https://wa.me/569XXXXXXXX" target="_blank" class="boton-contacto">Comprar por WhatsApp</a>
  </article>

  <!-- Producto 2 -->
  <article class="producto">
    <img src="https://i.imgur.com/2zvRzTO.jpg" alt="Nike Air Max 90" />
    <div class="nombre">Nike Air Max 90</div>
    <div class="precio">$69.990</div>
    <div class="tallas">Tallas disponibles: 37 - 43</div>
    <a href="https://wa.me/569XXXXXXXX" target="_blank" class="boton-contacto">Comprar por WhatsApp</a>
  </article>

  <!-- Agrega más productos copiando el bloque de "producto" y cambiando datos -->

</section>

<footer>
  &copy; 2025 Sneakers Chile. Todos los derechos reservados.
</footer>

</body>
</html>

