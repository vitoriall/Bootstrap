# Bootstrap
/*Aprendendo a usar o Bootstrap*/
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="sonacozinha.css">
    <link rel="stylesheet" href="carousel.css">
    <link rel="shortcut icon" href="egg.svg" type="image/x-icon">
    <title>Só na Cozinha</title>
    <!--Bootstrap-->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">

    <!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</head>
<body>
  <header class="blog-header py-3">
    <div class="row flex-nowrap justify-content-between align-items-center">
      <div class="col-4 d-flex justify-content-end align-items-center">  
      </div>
    </div>
    <div class="py-5 text-center">
      <img class="d-block mx-auto mb-4" src="logo sónacozinha.jpg" alt="" width="150" height="100" style="margin-top: -50px;">
      <h2 style="font-family: 'Praise', cursive;">Só Na Cozinha</h2>
      <p class="lead" style="font-family: sans-serif; font-size: small;"> Melhor site de comida nordestinha que você poderá encontrar.</p>
      <a class="btn btn-light" href="Sobremesas.html" role="button">Receitas Doces</a>
      <a class="btn btn-light" href="PratosSalgados.html" role="button">Receitas Salgadas</a>
    </div>
  </header>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

  
  <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="arroz com carne suína.jpeg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Aprenda a receita de arroz de costela suína com aspargos e farofa de macadâmia.</h5>
          <p><a href="PratosSalgados.html">Clique aqui</a></p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="bolo pé de moleque.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Aprenda a receita do bolo pé de moleque.</h5>
          <p><a href="Sobremesas.html">Clique aqui</a></p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="canjica.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Aprenda a fazer a receita da canjica nordestina.</h5>
          <p><a href="Sobremesas.html">Clique aqui</a></p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-target="#carouselExampleCaptions" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-target="#carouselExampleCaptions" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </button>
  </div>

<!---Nunca mexer nisso aqui-->
<div class="Somos">
 <div class="row">
    <div class="col-lg-4"></div>
    <div class="col-lg-4">
      <h2>Quem nós somos?</h2>
     <p>        <i>“Nós somos nutricionistas formados pela Universidade de Fortaleza (UNIFOR), e inicialmente, criamos o “Só na cozinha” apenas com o objetivo de fazer um experimento social. Mas aí, o projeto foi se expandindo e descobrimos que há nele um grande potencial de apresentar ao público em geral a riqueza presente na comida regional nordestina, em especial a cearense.” </i></p>
     - Maria Soares , sócia do projeto.<cite title="Source Title"></cite>  </p>
    </div>
    <div class="col-lg-4"></div>
  </div>
</div>
<hr>


<footer class="container">
  <p class="float-right"><a href="#">Voltar ao topo</a></p>
  <p>&copy; As narrativas presentes no site são fictícias. As imagens e os textos das receitas foram retiradas do site G1: &middot; <a href="https://g1.globo.com/economia/agronegocios/globo-rural/receitas/"> Clique para entrar no site oficial</a></p>
</footer>


  <!--JS-->
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.min.js" integrity="sha384-VHvPCCyXqtD5DqJeNxl2dtTyhF78xXNXdkwX1CZeRusQfRKp+tA7hAShOK/B/fQ2" crossorigin="anonymous"></script>
</body>
         
</html>
