# Portafolio-Ramiro-Oyola
Proyectos 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ramiro Oyola | Diseñador Gráfico</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 3rem 1rem 2rem;
    }

    .perfil {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #fff;
      margin-bottom: 1rem;
    }

    h1 {
      margin: 0;
      font-size: 2rem;
    }

    h2 {
      margin: 0.2rem 0 0.5rem;
      font-weight: normal;
      font-size: 1.2rem;
      color: #ccc;
    }

    .frase {
      font-style: italic;
      font-size: 1rem;
      color: #aaa;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }

    .item {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s;
    }

    .item:hover {
      transform: scale(1.03);
    }

    .item img {
      width: 100%;
      height: auto;
      display: block;
    }

    .desc {
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="foto-perfil.jpg" alt="Foto de perfil de Ramiro" class="perfil" />
    <h1>Ramiro Oyola</h1>
    <h2>Diseñador gráfico</h2>
    <p class="frase">“Visualizo lo invisible”</p>
  </header>

  <section class="grid">
    <div class="item">
      <img src="proyecto1.jpg" alt="Proyecto 1" />
      <div class="desc">
        <h3>Proyecto 1</h3>
        <p>Descripción breve del proyecto.</p>
      </div>
    </div>

    <div class="item">
      <img src="proyecto2.jpg" alt="Proyecto 2" />
      <div class="desc">
        <h3>Proyecto 2</h3>
        <p>Descripción breve del proyecto.</p>
      </div>
    </div>
    <!-- Agrega más proyectos aquí -->
  </section>
</body>
</html>
