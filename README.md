https://andersonandre-csi.neocities.org/Bootstrap/home.html


# Bootstrap
Trabalho em grupo

<h1>Sejam Bem vindos.</h1>

<!doctype html>
<html lang="pt-br">
  <head>
    <title>Minha primeira página com Bootstrap 5</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
   
   
   
   
   <Style>
  
   body {box-sizing:border-box;
        
   }
   
   #demo{
     
     background-color:#FF8C00;
     
     }
   </style>
   
    
      


  </head>
  <body  >
  
     <header>
    <nav class="navbar navbar-expand-sm bg-warning fixed-top">
    <div class="container-fluid">
        <img src="dudule.jpg" class="rounded-circle" alt="Logo do Brownie Duledu" style="width:50px;">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="collapsibleNavbar">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="https://andersonandre-csi.neocities.org/Bootstrap/home.html" style="color:saddlebrown; margin-left: 10px; font-weight:bold; font-family:georgia">Inicio</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" style="color:saddlebrown; font-weight:bold; font-family:georgia">Produtos</a>
          <ul class="dropdown-menu bg-warning">
              <li><a class="dropdown-item" href="https://rodrigo-franca.neocities.org/HTML/Trabalho/1Brownie.html" style="color:saddlebrown; font-weight:bold; font-family:georgia">Brownies</a></li>
              <li><a class="dropdown-item" href="https://rodrigo-franca.neocities.org/HTML/Trabalho/2PizzadeBrownie.html" style="color:saddlebrown; font-weight:bold; font-family:georgia">Pizza de brownie</a></li>
              <li><a class="dropdown-item" href="#" style="color:saddlebrown; font-weight:bold; font-family:georgia">Pizza Brownie gourmet</a></li>
          </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://gisellasilva.neocities.org/duleDu/contatoDuleDu.html" style="color:saddlebrown; font-weight:bold; font-family:georgia">Contato</a>
          </li> 
          <li class="nav-item">
            <a class="nav-link" href="https://andersonandre-csi.neocities.org/Bootstrap/sobre.html" style="color:saddlebrown; font-weight:bold; font-family:georgia">Sobre</a>
          </li>
        </ul>
      </div>
          <a href="https://www.ifood.com.br/delivery/rio-de-janeiro-rj/duledu---brownies---doces-e-presentes-botafogo/c6bd2f0d-3358-42c8-9ffb-01912eee5184" target="_blank"><button style="color:chocolate;">COMPRE AQUI<svg xmlns="http://www.w3.org/2000/svg" width="35" height="30" fill="currentColor" class="bi bi-cart3" viewBox="0 0 16 16">
  <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .49.598l-1 5a.5.5 0 0 1-.465.401l-9.397.472L4.415 11H13a.5.5 0 0 1 0 1H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5zM3.102 4l.84 4.479 9.144-.459L13.89 4H3.102zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2zm7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"/>
</svg></button></a>
    </div>
    </nav>
  </header>
  
   <section style="background-color:#D2691E;">
 
  
   <!-- Aqui começa o conteúdo -->
    <div class="container" style="margin-top:80px">
    <h1 style= "color:#8B4513;  font-family: Garamond;  font-size: 97px; text-align:center">Brownie Duledu</h1>
    
    <!-- ************ -->
    <!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
  </div>
  
  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="pizzabrownie.jpg" alt="Restaurante Aprazivel" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3 style=color:black;><strong>Brownie Duledu</strong></h3>
        <p style=color:black;><strong>Pizza de Brownie</strong></p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="brownetone.jpg" alt="Arpoador" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3 style=color:black;><strong>Brownie Duledu</strong></h3>
        <p style=color:black;><strong>Brownitone de Leite Ninho</strong></p>
      </div> 
    </div>
    <div class="carousel-item">
      <img src="docedeleite.jpg" alt="Mureta da Urca" class="d-block" style="width:100%">
      <div class="carousel-caption">
        <h3 style=color:black;><Strong>Brownie Duledu</strong></h3>
        <p style=color:black;><Strong>Brownitone de Doce de Leite</strong></p>
      </div> 
    </div>
  </div>
  
  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>
</div>
<br>

<h1 style="color:#8B4513;  font-family: Garamond;  font-size: 97px; text-align:center"></h1>
<p style= "text-align: justify; width:500px; margin: 0 auto; "><strong>.</strong>

</section>
<!-- Footer -->
 
         <div class="container-fluid">
  <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top bg-light  ">
    <div class="col-md-4 d-flex align-items-center">
      <a href="/" class="mb-3 me-2 mb-md-0 text-muted text-decoration-none lh-1">
        <svg class="bi" width="30" height="24"><use xlink:href="#bootstrap"/></svg>
      </a>
      <span class="mb-3 mb-md-0 text-muted">&copy; 2022 Company, Brownie Duledu</span>
      
    </div>

    <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
      <li class="ms-1"><a class="text-muted" href=""><svg class="bi" width="24" height="24"><img src="https://andersonandre-csi.neocities.org/Bootstrap/twitter.svg"></a></li>
      <li class="ms-1"><a class="text-muted" href="https://www.facebook.com/brownieduledu"><svg class="bi" width="24" height="24"><img src="https://andersonandre-csi.neocities.org/Bootstrap/facebook.svg"></a></li>
       <li class="ms-1"><a class="text-muted" href="https://www.youtube.com/channel/UCxvc4loe7RPRDIJo0LRt1Qg"><svg class="bi" width="24" height="24"><img src="https://andersonandre-csi.neocities.org/Bootstrap/youtube.svg"></a></li>
      
      <li class="ms-1"><a class="text-muted" href="https://www.instagram.com/brownieduledu/"><svg class="bi" width="24" height="24"><img src="https://andersonandre-csi.neocities.org/Bootstrap/instagram.svg"></a></li>
    </ul>
  </footer>
</div>
 
  <!-- Footer -->
  
 
     
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
   
  </body>
</html>
