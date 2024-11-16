<html lang="en">
<head>
    <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Reloj Maestro - Tienda de Relojes</title>
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
<body>
       <style>
        .card-img-top {
          height: 200px;
          object-fit: cover;
        }

        body {
            font-family: 'Arial', sans-serif;
            overflow-x: hidden;
            background: linear-gradient(45deg,rgba(255, 255, 255, 0.1) , black);;
      }

      .navbar-brand img{ max-height: 500px;
      }
      .navbar-brand {
            font-size: 1.5rem;
            font-weight: bold;
            color: #fff;
            text-shadow: 0 0 20px rgba(0, 255, 255, 0.5);
        }


        /* Tablets */
        @media screen and (max-width: 768px) {
            .menu {
                display: none;
                width: 100%;
                position: absolute;
                top: 60px;
                left: 0;
                background: var(--primary-color);
                flex-direction: column;
                text-align: center;
            }

            .menu.active {
                display: flex;
            }

            .menu li {
                padding: 1rem;
                border-top: 100px solid rgba(255,255,255,0.1);
            }

            .menu-toggle {
                display: block;
            }

            .grid-container {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        /* Móviles */
        @media screen and (max-width: 480px) {
            .grid-container {
                grid-template-columns: 1fr;
            }
        }

      </style>
    <body>
      <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
          <a class="navbar-brand" href="#">Reloj Maestro</a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item active">
                <a class="nav-link" href="#">Inicio <span class="sr-only"></span></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Productos</a>
              </li>
              <li class="nav-item">
            <a class="nav-link" href="https://jd-354.github.io/SOBRE-NOSOTROS-/">Sobre Nosotros</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="https://jd-354.github.io/CONTATANOS-/">Contacto</a>
              </li>
            </ul>
          </div>
        </nav>

        <img src="https://blog-inolvidable.joyeriasbizzarro.com/hubfs/2024_MIDO_Blog_BannerHome_Desk.jpg"  class="d-block w-100" width="350" height="350">
      </header>
    
      <main>
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
        </div>
            <div class="carousel-item">
              <img src="#" class="d-block w-100" alt="Reloj 2"width="0" height="0">
            </div>
            <div class="carousel-item">
              <img src="#" class="d-block w-100" alt="Reloj 3" width="0" height="0">
            </div>
          </div>
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
    <main>
        <div class="container my-5"></div>
        <section id="contacto" class="contact-section">
            <div class="container">
                <h3 class="mb-3"></h3>
                <div class="row">
                    <!-- Información de Contacto -->
                    <div class="mb-3">
                <div class=".contact-info">
                    <li>
              <strong>Somos una empresa dedicada a la venta de relojes exclusivos de las marcas más prestigiosas del mundo. Nuestra pasión por los relojes de alta calidad nos ha llevado a crear esta colección, que hemos cuidado con gran esmero para ofrecerte los mejores productos.</strong>
              <strong>Nuestro equipo de expertos en relojería ha seleccionado cada uno de estos modelos, asegurándose de que cumplan con los más altos estándares de calidad y diseño. Nos enorgullece poder compartir esta colección contigo y esperamos que encuentres el reloj perfecto para complementar tu estilo de vida.</strong>
              <strong>Si tienes alguna pregunta o necesitas más información, no dudes en contactarnos. Estaremos encantados de asistirte.</strong >
            </li>
            </div>
          </div>
