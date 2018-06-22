#Pre-Maquetado Página Acerca De Tía Tomate#
____

#### Tía Tomate es una empresa productora de tomates organicos que requiere maqueta para página "Acerca de"


####Los requerimientos visuales son:

- Que se muestre a sus clientes una pequeña reseña historica.
- Procedencia de sus productos.
- Mostrar personas que trabajan cosechando.
- Mostrar la pasión que sienten por sus productos.
- Mostrar logo.
- Enfocar la compra de productos.

###Los requerimientos tecnícos son:

- Que sea responsiva
 
###Sketch Página Acerca de:


![Acerca de](assets/img/maqueta-acerca-de.jpeg)

###Estructura:

la pagina tendra la siguiente estructura:

se usara bootstrap





		<!DOCTYPE html>
		<html>
		<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1 shrink-to-fit=no">
		<title>TIATOMATE | Acerca De</title>
	
		<!-- Bootstrap CSS -->
    	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB" crossorigin="anonymous">

		<!-- Main Styles -->
		<link rel="stylesheet" href="assets/css/style.css">
		</head>

		<body>
			<!-- Navbar -->
			
			<nav class="navbar navbar-expand-lg navbar_tia-tomate fixed-top">
			
				<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
				</button>

			<!-- Just Image-->

				<a class="navbar-brand" href="index.html">
    			<img src="../img/logo-navbar.png" width="30" height="30" alt="Tía Tomate">
				</a>
				
			<!-- Responsive Nav -->

				<div class="collapse navbar-collapse" id="navbarTogglerDemo03">
					<ul class="navbar-nav navbar__navigation mr-auto">
						<li class="nav-item active">
							<a class="nav-link" href="acerca de.html">Acerca de<span class="sr-only">(current)</span></a>
						</li>
						<li class="nav-item active">
							<a class="nav-link" href="Productos.html">Productos<span class="sr-only">(current)</span></a>
						</li>
						<li class="nav-item active">
							<a class="nav-link" href="Blog.html">Blog</a>
						</li>
						<li class="nav-item active">
							<a class="nav-link" href="Contacto.html">Contacto</a>
						</li>
					</ul>
				</div> <!--End items-->
			</nav>
			
			<!--Header-->
				<header class="container-fluid header_tia-tomate"
				<h1>Nosotros</h1>
				</header>
			
				<main>

			<!--Blog-->
			
				<section class="container-fluid blog">
				    <div class="row">
				      <div class="blog__inner col-lg-6 col-md-6 col-sm-12">
				        <h3>Historia </h3>
				        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ultrices accumsan ornare. Phasellus tristique ullamcorper luctus.</p>
				        
				     </div>
				     <div class="blog__inner blog__inner_background col-lg-6 col-md-6 col-sm-12">
						<div class="blog__content"><h3>Un Gusto Conocerte!</h3></div>
					</div>
				    </div>
				</section>
				
				<!--about us section-->


				</main>

			<!-- Optional JavaScript -->
		    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
		    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
		    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
		    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T" crossorigin="anonymous"></script>
		</body>
		</html>  


