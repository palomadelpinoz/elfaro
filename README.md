# elfaro
periodico
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EL FARO</title>
    <link rel="stylesheet" href="./css/bootstrap.min.css">
    <link rel="stylesheet" href="archivoprueba.css">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">
    
<link  rel="icon"   href="faroimg.png" type="image/png" />
</head>
<body> 

  <!-- Navbar content -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <a class="navbar-brand" href="#">EL FARO</a>
          <img src="./faroimg.png" alt="logo" style= "max-height:60px; max-width: 60px;" >
          <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Inicio</a>
              </li>
              
              <li class="nav-item">
                <a class="nav-link" href="#">Negocios</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Deportes</a>
              </li>
              
              
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="..." aria-label="...">
              <button class="btn btn-outline-success" style= "border: red; color: rgb(165, 77, 77);" type="submit">Buscar</button> 
            </form>
          </div>
        </div>
      </nav>
    <!-- Navbar content -->

<!-- header content -->
    <div class="card">
      
      <div class="card-header">
        <em>Las noticias de hoy, para ti.</em>
      </div>
      <div class="card-body">
        <h5 class="card-title">Recibe nuestras noticas diariamente</h5>
        <a href="#" class="btn btn-light">Registrarse</a>
        <a href="#" class="btn btn-light">Iniciar sesión</a>
      </div>
    </div>
    <!-- header end content -->

    

<!-- articulo inicio content -->
    <div class="accordion accordion-flush" id="accordionFlushExample">
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              Proceso de vacunación
            </button>
          </h2>
          <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Infórmese sobre las fechas y centros de vacunación aquí.</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
              Beneficios estatales
            </button>
          </h2>
          <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Infórmese sobre  beneficios, bonos y subsidios de los distintos organismos aquí.</div>
          </div>
        </div>
        
      </div>
      <!-- articulo acordeonend content -->
<hr>
      <!-- grid inicio 2content -->
  <div class="container">

    <div class="row">

      <div class="col">
        <h5>Por atraso en 5G se pierden negocios en América Latina</h5>
        <h4> <img src=https://www.arenapublica.com/sites/default/files/2021/08/27/pexels-thisisengineering-38619691.jpg class="card-img-top" alt="...">
          <h6>28 agosto 2021</h6>
          <p>El Instituto Federal de Telecomunicaciones (IFT) subastará este año 41 bloques de espectro radioeléctrico, incluidos algunos en bandas necesarias para las redes 5G.</p>
      </div>
      <div class="col">
        <h5>El día que Tiger Woods abrió una nueva dimensión</h5>
        <h4> <img src= https://imagenes.elpais.com/resizer/LHAia25AHI1o7HO1-pe7hz0TkNI=/1960x0/cloudfront-eu-central-1.images.arcpublishing.com/prisa/O7HC2K5AZ5H3DMS4KLX4RPTVVY.jpg class="card-img-top" alt="...">
          <h6>28 agosto 2021</h6>
          <p>Este domingo se cumplen 25 años del debut profesional del estadounidense, ahora recuperándose de una pierna rota </p>
      </div>
      <div class="col">
        <h5>Cuarta presea para Chile: Mariana Zúñiga consiguió medalla de plata en los Juegos Paralímpicos de Tokio en tiro con arco</h5>
        <h4> <img src=https://media.elmostrador.cl/2021/08/E-CL2-MWQAARZPk-700x468.jpg class="card-img-top" alt="...">
        <h6>28 agosto 2021</h6>
        <p>  Con esto, la santiaguina se sumó a las medallas de Alberto Abarza (oro y plata en natación) y el oro de la lanzadora de bala, Francisca Mardones.

        </p>

      </div>
      <div class="col">
        <h5>Sichel justifica sus fotos de campaña abrazado a Moreira, uno de los casos de platas negras en la política: “Me saqué con todos los candidatos a senadores de esa región”</h5>
        <h4> <img src=https://media.elmostrador.cl/2021/08/Captura-de-Pantalla-2021-08-28-a-las-13.35.40-700x334.png class="card-img-top" alt="...">
          <h6>28 agosto 2021</h6>
         
          <p> El candidato habló tras posar junto a parlamentarios involucrados en casos de cohecho y financiamiento irregular de la política, y sostuvo que <b>"son los partidos los que arman sus listas, sino esto sería una dictadura y no un proyecto político". </b></p>
      </div>

    </div>
<hr>
    <div class="row">
      <div class="col-5">
        <h5>¿Por qué las enfermedades cardiovasculares son la principal causa de muerte en Chile?</h5>
        <img src=https://media.elmostrador.cl/2021/08/cardiovasculares-700x395.jpeg class="card-img-top" alt="...">
        <h6>28 agosto 2021</h6>
        <p>Especialista se refirió a los factores que influyen en que hoy las afecciones cardíacas alcancen el 27,1% del total de defunciones del país y explicó en qué consiste la medicina hemodinámica y los beneficios de este tipo de tratamiento y control de enfermedades.</p>
      </div>
      
      <div class="col-7">
        <h5>Cargamento con 2 millones de dosis de la vacuna Sinovac fue recibido por el ministro Enrique Paris y la subsecretaria Paula Daza en el aeropuerto de Santiago</h5>
        <iframe width='600' height='338' src='https://rudo.video/vod/bMtFbt' frameborder='0' allowfullscreen allow='autoplay; fullscreen'></iframe>
        <h6>28 agosto 2021</h6>
        
        <p>Un nuevo cargamento de vacunas llegó al país. En esta oportunidad, el ministro de Salud, Enrique Paris, junto a la subsecretaria Paula Daza, recibieron <b>dos millones de dosis de la vacuna Sinovac, sumándose al arribo del día miércoles de la compañía Pfizer-BioNTech. Con esto, se alcanzaron 34.663 millones de dosis en Chile a lo largo de la pandemia. En cuanto a las inoculaciones provenientes de la compañía Sinovac, se llegó a la suma de 23.671.476 vacunas.</b></p>
      </div>
    </div>

  </div>
<!-- grid 2 end content -->
<hr>

      <!--  articulo con imagen inicio content -->
      <div class="clearfix">
        <img src=https://d500.epimg.net/cincodias/imagenes/2021/08/25/emprendedores/1629927824_128572_1630304503_noticia_normal_recorte1.jpg class="col-md-6 float-md-end mb-3 ms-md-3" alt="..." style= "max-height:450px; max-width: 450px;">
      <h4>Aumenta el emprendimiento a causa de la pandemia</h4>
      <h6>28 agosto 2021</h6>
        <h5>La creación de empresas creció en un 57,6% durante el primer semestre de 2021.</h5>
        <p>El emprendimiento vuelve a crecer. Datos del Instituto Nacional de Estadística (INE) muestran que la creación de empresas en el primer semestre de 2021 ha sido un 57,6% mayor a la de 2020.</p>
        <p>La creación de riqueza, obtener rentas altas o ganarse la vida son algunas de las motivaciones de los emprendedores para montar un negocio. Por otra parte, la mayoría de los emprendedores tiene una media de edad de 37 años, aunque su edad media consolidada suele situarse entre los 40 y los 50 años, mientras que aquellos que deciden abandonar tienen de media los 48 años.</p>
          
          <p>Se ha advertido una reducción de un 6% de la diferencia entre sexos a la hora de emprender. La diferencia se ha reducido debido a una “estabilización del índice de los hombres, y a un aumento del índice de las mujeres”, según el informe de EAE Business School.</p> 
       

        
        
      </div>
<!-- articulo con imagen content -->
<hr>


<!-- grid inicio 2content -->
  <div class="container">

    <div class="row">

      <div class="col">
        <h5>Con asistencia de Vidal, Inter de Milán triunfa 3-1 sobre Hellas Verona</h5>
        <h4> <img src=https://media.elmostrador.cl/2021/08/E90wFM_XMAQr_1i-700x467.jpg class="card-img-top" alt="...">
          <h6>27 agosto 2021</h6>
          <p>El Inter de Milán triunfó 3-1 en el campo de Hellas Verona, manteniendo el pleno de victorias tras dos jornadas de la Serie A italiana. La conquista de la "Nerazzurri" contó con una participación activa de Arturo Vidal.</p>
      </div>
      <div class="col">
        <h5>Cuánto dinero tiene Gerard Piqué: estos son todos sus millonarios negocios</h5>
        <h4> <img src=https://imagenes.lainformacion.com/files/image_606_387/uploads/imagenes/2021/08/26/gerard-pique.jpeg class="card-img-top" alt="...">
          <h6>28 agosto 2021</h6>
          <p> La última adquisición del futbolista del FC Barcelona son los derechos de la Ligue 1 tras la llegada de Leo Messi al PSG. </p>
      </div>
      <div class="col">
        <h5>La OPS alerta de que "la terrible situación” que vive Brasil por el COVID-19 “también está afectando a los países vecinos".</h5>
        <h4> <audio controls>
          <source src="https://news.un.org/es/sites/news.un.org.es/files/audio/2021/03/230321min.mp3" type="audio/mp3"> 
          </audio>
        <h6>30 agosto 2021</h6>
        <h6><em>Audio: Beatriz Barral</em></h6>
        <p> La variante del coronavirus inicialmente detectada en Brasil, ya <b>se encuentra al menos en 15 paises cercanos.</b></p>
     

      </div>
      <div class="col">
        <h5>Adiós a la Segunda B, esta es la nueva pirámide del fútbol español</h5>
        <h4> <img src=https://imagenes.elpais.com/resizer/t6P-Sloknz0kTL_k9wYmHK48Gis=/1960x0/cloudfront-eu-central-1.images.arcpublishing.com/prisa/BG775T6NMZA6ROPEZ3CAEQ6ZOQ.Jpg class="card-img-top" alt="...">
          <h6>27 agosto 2021</h6>
          <p>La Federación estrena tres nuevas categorías y añade un escalón más, la 1ª RFEF, en la antesala de las competiciones profesionales</p>
      </div>

    </div>
<hr> 
    <div class="row">
      <div class="col-7">
        <h5>Chile acogerá a cerca de 300 personas que buscan escapar de Afganistán</h5>
        <img src=https://media.elmostrador.cl/2021/08/Aton_507589-700x467.jpg class="card-img-top" alt="...">
        <h6>28 agosto 2021</h6>
        <p>Así lo informó este jueves el Ministerio de Relaciones Exteriores en un documento en el que detalló las gestiones que está realizando para facilitar el desplazamiento y la acogida de afganos que corren peligro debido al rápido avance talibán en Afganistán.</p>
      </div>
      <div class="col-5">
        <h5>ISIS-K, el grupo de Estado Islámico enemigo de los talibanes detrás de los ataques al aeropuerto de Kabul</h5>
        <img src=https://media.elmostrador.cl/2021/08/120297347_mediaitem120297344-700x394.jpg class="card-img-top" alt="...">
        <h6>28 agosto 2021</h6>
        <h6>Luego de que la Casa Blanca y países aliados alertaran de potenciales ataques en el aeropuerto de la capital afgana, dos explosiones dejaron este jueves al menos 60 muertos, incluidos niños, mujeres y personal militar de EE.UU. <b>Detrás de ellos, según las agencias de inteligencia de Estados Unidos, estuvo EI-K (ISIS-K, por sus siglas en inglés) o Provincia del Estado Islámico de Khorasan, la filial regional del autodenominado Estado Islámico (EI) que está activo en Afganistán y Pakistán, y que es enemigo de los talibanes.</b></h6>
        
      </div>
    </div>

  </div>
<!-- grid 2 end content -->
<hr>


<!-- footer inicio content -->
<div class="card">
  <div class="card-header">
    <em> Cuidarnos, es tarea de todos. Manten la distancia.</em>
  </div>
  <div class="card-body">
    <blockquote class="blockquote mb-0">
      <h3>EL FARO <img src="faroimg.png" alt="logo" style= "max-height:45px; max-width: 45px;"></h3>
      
      <footer class="blockquote-footer">Las noticias de hoy para ti. <cite title="Source Title">Todos los derechos reservados.</cite></footer>
    </blockquote>
  </div>
</div>
<!-- footer end content -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="./js/bootstrap.min.js"></script>
    
</body>
</html>
