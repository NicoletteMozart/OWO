<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>Practica Final</title>
	<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale1.0, minimum-scale=1.0">
	<link rel="stylesheet" href="css/bootstrap.min.css">
</head>
<body>
     <!-- NAVBAR-->
	<nav class="navbar navbar-expand-md navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
         <img src="imagenes/bootstrap-logo.svg" alt="" width="30" height="24">
         Navbar
         </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav m-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <span class="navbar-text">
         14488-2 Nicole Valdez
    </span>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
</div> <!-- NAVBAR-->

<!--SLIDER-->
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="imagenes/2.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="imagenes/1.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="imagenes/3.jpg" class="d-block w-100" alt="...">
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
</div><!--SLIDER-->


<!--SECTION UNO-->
<section class="container my-5">
	<H2 class="display-4 text-center">BOKU NO HERO ACADEMIA</H2>
	<p class="lead my-4">My Hero Academia (????????????????????????????????? Boku no H??r?? Akademia ?) es una serie de anime producida por el estudio BONES, basada en el manga del mismo nombre, escrito e ilustrado por Kohei Horikoshi. Fue anunciado en la edici??n 49 de la revista Weekly Shonen Jump en 2015. En marzo de 2016, Funimation anunci?? que hab??a licenciado la serie para Am??rica, mientras que en Espa??a la serie fue licenciada por Selecta Visi??n.</p>
	<H2 class="display-4 text-center">Personajes</H2>
	<!--CARD-->
	<div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/deku.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Izuku Midoriya</h5>
        <p class="card-text">Izuku Midoriya tambi??n conocido como Deku, es un estudiante de la Clase 1-A de la Academia U.A. Es el protagonista principal de la serie.
        Aunque originalmente naci?? sin un Don, logra captar la atenci??n del legendario h??roe All Might y desde entonces se ha convertido en su alumno cercano y estudiante en la Academia U.A., convirti??ndolo en el noveno usuario del Don One For All.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Deku</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/bakugou.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Katsuki Bakugou</h5>
        <p class="card-text">Katsuki Bakugou, tambi??n conocido como Kacchan por sus amigos, y por su nombre de h??roe Dynamight, es un estudiante de la Clase 1-A de la Academia U.A., que est?? entrenando para convertirse en un H??roe. Es el deuteragonista de la serie y amigo de la infancia convertido en rival de Izuku Midoriya.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Kacchan</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/todoroki.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Shoto Todoroki</h5>
        <p class="card-text">Shoto Todoroki es un estudiante de la Clase 1-A de la Academia U.A, donde ingres?? a trav??s de recomendaciones oficiales y est?? entrenando para convertirse en un H??roe. Es el hijo m??s joven de Endeavor, el h??roe n??mero 1; y Rei Todoroki, es uno de los principales protagonistas de la serie.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Todoroki</small>
      </div>
    </div>
  </div>
</div>
<!--CARD-->
<div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/momo.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Momo Yaoyorozu</h5>
        <p class="card-text">Momo Yaoyorozu, tambi??n conocida como Hero??na para todo: Creati, es una estudiante y la vicepresidenta de la Clase 1-A de la Academia U.A. donde ingres?? a trav??s de recomendaciones oficiales y est?? entrenando para convertirse en un H??roe.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Yaoyorozu</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/uraraka.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Ochako Uraraka</h5>
        <p class="card-text">Ochaco Uraraka, tambi??n conocida como Uravity, es una estudiante de la Clase 1-A de la Academia U.A. que est?? entrenando para convertirse en un Hero??na profesional. Es una de los protagonistas de la serie.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Ochako</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/mina.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Mina Ashido	</h5>
        <p class="card-text">Mina Ashido tambi??n conocida como Pinky, es una estudiante de la Clase 1-A de la Academia U.A. Esta entrenando para convertirse en una Hero??na.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Mina</small>
      </div>
    </div>
  </div>
</div>

<div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/kirishima.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Eijiro Kirishima</h5>
        <p class="card-text">Eijiro Kirishima, tambi??n conocido como H??roe resistente: Red Riot, es un estudiante de la Clase 1-A de la Academia U.A., el cual est?? entrenando para convertirse en un h??roe profesional.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Kirishima</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/kaminari.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Denki Kaminari</h5>
        <p class="card-text">Denki Kaminari, tambi??n conocido como Stun Gun Hero: Chargebolt, es un estudiante de la Clase 1-A de la Academia U.A. que est?? entrenando para convertirse en un h??roe profesional.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Kaminari</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="imagenes2/jiro.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Kyoka Jiro</h5>
        <p class="card-text">Kyoka Jiro tambi??n conocida como Hero??na auditiva: Earphone Jack, es una estudiante de la Clase 1-A de la Academia U.A. Esta entrenando para convertirse en una Hero??na.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Jiro</small>
      </div>
    </div>
  </div>
</div><!--CARD-->


</section><!--SECTION UNO-->

<!-- Jumbotron -->
<div class="jumbotron">
	<div class="container">
		<h1 class="display-4"></h1>
        <p class="lead">Espero te este gustando la pagina</p>
        <hr class="my-4">
        <p>??Puedes ver la serie en una de estas paginas: Anime flv, Anime JK</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Leer mas sobre la serie</a>
  
</div><!-- Jumbotron -->
<!-- SECTION2 -->
<section class="container">
	<H2 class="display-4 text-center">BOKU NO HERO ACADEMIA</H2>
	<p class="lead my-4">My Hero Academia (????????????????????????????????? Boku no H??r?? Akademia ?) es una serie de anime producida por el estudio BONES, basada en el manga del mismo nombre, escrito e ilustrado por Kohei Horikoshi. Fue anunciado en la edici??n 49 de la revista Weekly Shonen Jump en 2015. En marzo de 2016, Funimation anunci?? que hab??a licenciado la serie para Am??rica, mientras que en Espa??a la serie fue licenciada por Selecta Visi??n.</p>
<div class="row">
	<div class="col-md-6">
<!--ACORDION -->
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>Sh??eisha anunci?? el lanzamiento el 20 de agosto de 2016 en la revista Sh??kan Sh??nen Jump de un spin-off de la obra original llamado My Hero Academia:Vigilantes-. El autor fue Hideyuki Furuhashi, mientras que Betten Court estuvo a cargo de los dibujos. La historia trata sobre h??roes ilegales a los que se llama "Vigilantes".8??? A partir de la edici??n del 17 de diciembre del mismo a??o las publicaciones pasaron a la aplicaci??n Sh??nen Jump+.9???
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>TMy Hero Academia (????????????????????????????????? Boku no H??r?? Akademia?) es una serie de manga escrita e ilustrada por K??hei Horikoshi. Se basa en un one-shot realizado por el mismo autor y publicado en el quinto volumen del manga ??magadoki D??butsuen bajo el nombre de My Hero.1???2??? El 11 de enero de 2015, fue lanzado un VOMIC basado en el manga.3???
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>El 2 de noviembre de 2015, comenz?? a publicarse un manga spin-off llamado My Hero Academia Smash!! y escrito por Hirofumi Neda.4??? Una adaptaci??n del manga original al anime comenz?? a transmitirse el 3 de abril de 2016.5??? Unas historias extra han sido adaptadas por Anri Takahashi en formato de novela ligera.6??? Adem??s, se han desarrollado dos videojuegos por las empresas Bandai Namco Games y Takara Tomy.7???
      </div><!--ACORDION -->
    </div>
  </div>
</div>
   </div>
</section>

<!-- SECTION2 -->
<footer class="bg-dark text-white">
	
<center>?? Derechos reservados Nicole Valdez 14488-2 </center>

</footer>
</body>
<script type="js/jquery"></script>
<script type="js/bootstrap.min.js"></script>
</html>
