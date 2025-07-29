# Capitech
<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tienda TecnoExpress</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #00c6ff, #0072ff);
      color: white;
      text-align: center;
    }header {
  padding: 40px 20px;
  background-color: #00000090;
}

h1 {
  font-size: 3em;
  margin-bottom: 10px;
}

p {
  font-size: 1.2em;
}

.productos {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 40px auto;
  gap: 20px;
  max-width: 1000px;
}

.producto {
  background: white;
  color: black;
  border-radius: 10px;
  width: 250px;
  padding: 20px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

.producto img {
  width: 100%;
  border-radius: 10px;
}

.producto h3 {
  margin: 10px 0 5px;
  font-size: 1.2em;
}

.producto p {
  font-size: 1em;
}

.btn-whatsapp {
  display: inline-block;
  margin-top: 30px;
  padding: 15px 25px;
  background-color: #25D366;
  color: white;
  border-radius: 50px;
  text-decoration: none;
  font-weight: bold;
  font-size: 1.2em;
  transition: transform 0.2s;
}

.btn-whatsapp:hover {
  transform: scale(1.05);
}

footer {
  padding: 20px;
  background-color: #00000090;
  font-size: 0.9em;
}

  </style>
</head>
<body>
  <header>
    <h1>🔥 TecnoExpress 🔥</h1>
    <p>Los mejores productos tecnológicos, ¡al mejor precio!</p>
  </header>  <section class="productos">
    <div class="producto">
      <img src="https://via.placeholder.com/250x150" alt="Producto 1">
      <h3>Audífonos Bluetooth</h3>
      <p>Sonido de alta calidad y conexión estable.</p>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/250x150" alt="Producto 2">
      <h3>Smartwatch Fitness</h3>
      <p>Monitorea tu salud y tu actividad diaria.</p>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/250x150" alt="Producto 3">
      <h3>Mini proyector LED</h3>
      <p>Convierte cualquier espacio en un cine en casa.</p>
    </div>
  </section><a class="btn-whatsapp" href="https://wa.me/573001112222" target="_blank">💬 Comprar por WhatsApp</a>

  <footer>
    © 2025 TecnoExpress. Todos los derechos reservados.
  </footer>
</body>
</html>
