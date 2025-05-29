<!DOCTYPE html>

<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Tienda de ropa urbana - [nombre de la marca]">
  <title>[nombre de la marca]</title>
  <style>
    body { margin: 0; font-family: sans-serif; background: #fff; color: #000; }
    header, footer { background: #111; color: white; padding: 1rem; position: sticky; top: 0; z-index: 10; }
    nav ul { list-style: none; display: flex; flex-wrap: wrap; gap: 1rem; padding: 0; }
    nav ul li a { color: white; text-decoration: none; }
    .hero { text-align: center; padding: 2rem; background: #333; color: white; }
    .hero img { max-width: 100%; height: auto; }
    .section { padding: 2rem; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; }
    .product { border: 1px solid #ccc; padding: 1rem; text-align: center; }
    .footer-links, .social, .newsletter { margin-top: 1rem; }
    input, textarea { width: 100%; padding: 0.5rem; margin-top: 0.5rem; }
    button { background: black; color: white; border: none; padding: 0.5rem 1rem; cursor: pointer; }
  </style>
</head>
<body>

<header>
  <div style="display: flex; justify-content: space-between; align-items: center;">
    <div><strong>[nombre de la marca]</strong></div>
    <nav>
      <ul>
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#ofertas">Ofertas</a></li>
        <li><a href="#destacados">Destacados</a></li>
        <li><a href="#drops">Drops</a></li>
        <li><a href="#pantalones">Pantalones</a></li>
        <li><a href="#remeras">Remeras</a></li>
        <li><a href="#zapatillas">Zapatillas</a></li>
        <li><a href="#contacto">Contactanos</a></li>
        <li><a href="#cliente">Atención al Cliente</a></li>
      </ul>
    </nav>
  </div>
</header>

<section class="hero" id="inicio">
  <h1>Vestí la calle con estilo</h1>
  <p>Nueva colección disponible ahora</p>
  <button>Ver Colección</button>
  <button>Ver Drops Exclusivos</button>
</section>

<section class="section" id="ofertas">
  <h2>Ofertas</h2>
  <div class="products">
    <div class="product">Producto 1 -30%</div>
    <div class="product">Producto 2 -20%</div>
  </div>
</section>

<section class="section" id="destacados">
  <h2>Productos Destacados</h2>
  <div class="products">
    <div class="product">Producto A</div>
    <div class="product">Producto B</div>
  </div>
</section>

<section class="section" id="drops">
  <h2>Drops Exclusivos</h2>
  <p>Próximo Drop en: 3 días 4 horas</p>
  <button>Unirse al Drop</button>
</section>

<section class="section" id="pantalones">
  <h2>Pantalones</h2>
  <div class="products">
    <div class="product">Pantalón 1</div>
  </div>
</section>

<section class="section" id="remeras">
  <h2>Remeras</h2>
  <div class="products">
    <div class="product">Remera 1</div>
  </div>
</section>

<section class="section" id="zapatillas">
  <h2>Zapatillas</h2>
  <div class="products">
    <div class="product">Zapatilla 1</div>
  </div>
</section>

<section class="section" id="contacto">
  <h2>Contactanos</h2>
  <form>
    <input type="text" placeholder="Nombre">
    <input type="email" placeholder="Email">
    <input type="text" placeholder="Asunto">
    <textarea placeholder="Mensaje"></textarea>
    <button type="submit">Enviar</button>
  </form>
</section>

<section class="section" id="cliente">
  <h2>Atención al Cliente</h2>
  <ul>
    <li>¿Cuánto tarda el envío?</li>
    <li>¿Cómo devuelvo un producto?</li>
  </ul>
  <button>Enviar una consulta</button>
</section>

<footer>
  <div>
    <div>[nombre de la marca]</div>
    <div class="footer-links">
      <a href="#">Política de privacidad</a> |
      <a href="#">Términos</a> |
      <a href="#">Devoluciones</a>
    </div>
    <div class="social">
      <p>Seguinos en: Instagram | TikTok</p>
    </div>
    <div class="newsletter">
      <p>Suscribite a nuestro newsletter</p>
      <input type="email" placeholder="Tu correo">
      <button>Suscribirse</button>
    </div>
  </div>
</footer>

</body>
</html>
