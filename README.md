<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Biblioteca Virtual 6TO Ciclo</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(90deg, #6abf6a 0%, #f28a8a 100%);
      color: #000;
      position: relative;
      min-height: 100vh;
      padding-bottom: 3em;
    }
    header {
      background: linear-gradient(90deg, #6abf6a 0%, #f28a8a 100%);
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1em 2em;
    }
    header img {
      height: 240px;
      width: auto;
    }
    .banner {
      background: white;
      color: #000;
      text-align: center;
      padding: 2em;
      border: 8px solid transparent;
      border-image: linear-gradient(45deg, #600, #060, #600) 1;
      border-radius: 15px;
      margin: 1em 2em;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }
    .banner h1 {
      font-size: 2.2em;
      margin-bottom: 0.5em;
    }
    .banner h2 {
      font-size: 1.4em;
      margin-bottom: 0.3em;
    }
    .banner p {
      font-size: 1.3em;
      font-weight: bold;
    }
    .line-divider {
      border-top: 3px solid #fff;
      margin: 1em 2em;
    }
    main {
      padding: 2em;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2em;
    }
    section {
      background-color: white;
      border: 16px solid transparent;
      border-image: linear-gradient(45deg, #600, #060, #600) 1;
      padding: 1.5em;
      border-radius: 20px;
      transition: transform 0.3s ease;
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
      text-align: center;
    }
    section:hover {
      transform: scale(1.03);
    }
    section img {
      height: 200px;
      width: auto;
      margin-bottom: 1em;
      border-radius: 10px;
    }
    section.inclusion img {
      height: 180px;
    }
    section.programacion img {
      height: 150px;
    }
    section.redes img {
      height: 170px;
    }
    h3 {
      margin-bottom: 1em;
      color: #c00;
      border-bottom: 2px solid #000;
      padding-bottom: 0.5em;
      font-size: 1.3em;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    li {
      margin: 0.7em 0;
    }
    a {
      color: #060;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover {
      text-decoration: underline;
    }
    .author-fixed {
      position: fixed;
      bottom: 10px;
      right: 20px;
      color: white;
      font-weight: bold;
      font-size: 1.1em;
      background: rgba(0, 0, 0, 0.5);
      padding: 0.6em 1em;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <header>
    <img src="niñoestudia.png" alt="Niño estudia" />
    <img src="unl logo.png" alt="LOGO UNL" />
    <img src="biblioteca10.png" alt="Logo Biblioteca" />
  </header>

  <div class="banner">
    <h1>UNIVERSIDAD NACIONAL DE LOJA</h1>
    <h2>CARRERA DE PEDAGOGÍA DE LAS CIENCIAS EXPERIMENTALES - INFORMÁTICA</h2>
    <p>BIBLIOTECA VIRTUAL DE 6TO CICLO</p>
  </div>

  <div class="line-divider"></div>

  <main>
    <section>
      <img src="Evaluacioncurricular.png" alt="Evaluación Curricular">
      <h3>Evaluación Curricular</h3>
      <ul>
        <li><a href="https://drive.google.com/file/d/1JM_Eo1JEmLbgBN2tJCeRh9uVcilMiaml/view">Guía de Estudio</a></li>
        <li><a href="https://drive.google.com/file/d/11ajN1c_Q9504y8mFQ0nrqaJcCdq0QM3k/view">Sílabo</a></li>
        <li><a href="https://drive.google.com/file/d/1rqUKLJHQTS9QLJrKzVQDxjdQdCUzk-M4/view">Texto Base</a></li>
      </ul>
    </section>

    <section>
      <img src="Gestiondetecnologia.png" alt="Gestión de Tecnología Educativa">
      <h3>Gestión de Tecnología Educativa</h3>
      <ul>
        <li><a href="https://docs.google.com/document/d/1I1PXqtPxjEG3z4qT3y9q002U7N-pagyk/edit?rtpof=true&sd=true&tab=t.0">Guía de Estudio</a></li>
        <li><a href="https://docs.google.com/document/d/1MXALAEMwGLRr5tkKBsXtdQj0qAle4-yy/edit?tab=t.0">Sílabo</a></li>
        <li><a href="https://drive.google.com/file/d/1ekKt422QBbgX72P46PwQ-z_t86zzVkZJ/view">Texto Base</a></li>
      </ul>
    </section>

    <section class="inclusion">
      <img src="Inclusioneducativa.png" alt="Inclusión Educativa">
      <h3>Inclusión Educativa</h3>
      <ul>
        <li><a href="https://drive.google.com/file/d/1X5H1ZQmWsDZjykF-HeA2SzlEHP_QRMHE/view">Guía de Estudio</a></li>
        <li><a href="https://drive.google.com/file/d/13gRVBK4lN9R-yjAQX_Gok_oxKVfgfWlY/view">Sílabo</a></li>
        <li><a href="https://drive.google.com/file/d/1L1FTJb59lnKVambLrgghYFMnk0hAlaJW/view">Texto Base</a></li>
      </ul>
    </section>

    <section>
      <img src="Mantenimientodecomputadoras.png" alt="Mantenimiento de Computadoras">
      <h3>Mantenimiento de Computadoras</h3>
      <ul>
        <li><a href="https://drive.google.com/file/d/15t7yG8Kg_2155tX01KuD3CQMn1GdSg9G/view">Guía de Estudio</a></li>
        <li><a href="https://drive.google.com/file/d/1oF70N-ZDzVc0W6IXvZpBcDCOZiTJ1LYz/view">Sílabo</a></li>
        <li><a href="https://drive.google.com/file/d/1mC0BmJA1pWdwJPFe-svo6XYBElgbhZ2g/view">Texto Base</a></li>
      </ul>
    </section>

    <section class="programacion">
      <img src="Programacionweb.png" alt="Programación Web">
      <h3>Programación Web</h3>
      <ul>
        <li><a href="https://drive.google.com/file/d/1QcN106PUvuqj_yMkZMMqa9s7_MymuCpo/view">Guía de Estudio</a></li>
        <li><a href="https://drive.google.com/file/d/1lOZY2RM3sexn2IckW8MZm7xDj0eCqmKN/view">Sílabo</a></li>
        <li><a href="https://drive.google.com/file/d/1zxJiCIYhCg-gOF6S-S-Pepz8Y3u8Rw5U/view">Texto Base</a></li>
      </ul>
    </section>

    <section class="redes">
      <img src="Redesinformaticas.png" alt="Redes Informáticas">
      <h3>Redes Informáticas</h3>
      <ul>
        <li><a href="https://drive.google.com/file/d/1z0L95PX3VFFILh_6m-GsIGqWrqf6aDo6/view">Guía de Estudio</a></li>
        <li><a href="https://drive.google.com/file/d/1vGQIpQ4u41cfwTcH01xicNaJdnmhr1XM/view">Sílabo</a></li>
        <li><a href="https://drive.google.com/file/d/1ZXqPSB8glQECeS1KWNzMdjx1UZck2FH-/view">Texto Base</a></li>
      </ul>
    </section>
  </main>

  <div class="author-fixed">
    Biblioteca Virtual 1.0 | Autor: Jhoel Castillo | Edwinjhoelcastillojimenez@gmail.com
  </div>
</body>
</html>
