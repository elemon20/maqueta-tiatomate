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
			
			<nav class="navbar navbar-expand-lg navbar-light navbar__tia-tomate fixed-top">
				<div class="container-fluid">
			
				<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
				</button>

			<!-- Just Image-->

				<a class="navbar-brand" href="index.html">
    			<img src="assets/img/logo-navbar.png" alt="Tía Tomate">
				</a>
				
			<!-- Responsive Nav -->

				<div class="collapse navbar-collapse justify-content-end" id="navbarTogglerDemo03">
					<ul class="nav navbar-nav navbar-right navbar__navigation">
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
				</div> <!--End container-fluid"
			</nav>
			
			<!--Header-->
			<header class="container-fluid header__tia-tomate"
				<h1>Nosotros</h1>
			</header>
			
			<main>

			<!--Blog-->
			
				<section class="container-fluid blog">
				    <div class="row">
				      <div class="blog__inner col-lg-6 col-md-6 col-sm-12">
				        <h3>Historia </h3>
				        <p>Esta historia nace hace unos años cuando la vida me brindó la oportunidad de recuperar los sabores a campo, olores a ciruelas y tierra mojada que consiguieron trasladarme a mi niñez. Volví a disfrutar del tomate. Si, ese que sabe y huele a tomate, ése tomate de vida tranquila que por su sabor sabes al comerlo que tiene su propia historia y, sin pretenderlo, pasas a formar parte de ella.</p>
				        
				     </div>
				     <div class="blog__inner blog__inner_background col-lg-6 col-md-6 col-sm-12">
						<div class="blog__content"><h3>Un Gusto Conocerte!</h3></div>
					</div>
				    </div>
				</section>
				
				<!--about us section-->

				<section class="container-fluid about-us">
					<div class="row">
						<div class="col-sm-12"><h2>Quienes Somos</h2></div>
					</div>
					<div class="row">
						<div class="col-sm-12">
						<p>Fue así como nos adentramos en el fabuloso mundo del sabor. Miles de variedades, infinidad de cultivos desconocidos y un sinfín de maneras de cultivar. Nos propusimos recuperar variedades y buscar el sabor. Tomates de siempre, esos que “viajan mal” pero que mantienen el sabor a tradición, a las cosas bien hechas, a su ritmo y al del calor del sol que lo madura en la mata.</p>
					</div>
					</div>
					<div class="row">
						<div class="col-sm about-us__inner about-us__inner_image-left"></div>
						<div class="col-sm about-us__inner">
						<h5>Javiera Kunstmann</h5>
						<p>Defensores de lo auténtico, lo de siempre, lo natural y la sabiduría tradicional, buscamos la variedad y el sabor. Investigamos, probamos, compartimos y escuchamos.</p>
						</div>
						<div class="col-sm about-us__inner about-us__inner_image-right"></div>
						<div class="col-sm about-us__inner">
						<h5>Roberto Pacheco</h5>
						<p>Todo con un único objetivo, conseguir cultivos sanos, naturales y orgánicos. Cultivos que nos beneficien a nosotros por salud, nos hagan disfrutar por sabor y que cuiden a la madre naturaleza, respetando sus ciclos de una forma natural. Sin olvidar nunca que el ritmo lo marca el campo.</p>
						</div>
					</div>
				</section>

				<section>
					<h4>!Te invitamos a vivir una nueva experiencia¡</h4>
					<a class="btn button_tia-tomate" href="#">CLICK AQUÍ</a>
				</section>

			</main>

			<!-- footer -->

			<footer class="footer_tia-tomate">
				<div class="row">
					<div class="col-sm footer__tia-tomate_image">
						<a href="#">
	    				<img src="assets/img/logo-footer.png" alt="Tía Tomate">
						</a>
					</div>
					<div class="col-sm">
						<div class="footer__tia-tomate_icon">
							<i class="fab fa-facebook fa-3x"></i>
							<i class="fab fa-instagram fa-3x"></i>
							<i class="fab fa-twitter fa-3x"></i>
						</div>
					</div>
					<div class="col-sm justify-content-end">
						<ul class="nav flex-column">
							<li class="nav-item">
								<a class="nav-link active" href="#">Acerca de</a>
							</li>
							<li class="nav-item">
								<a class="nav-link" href="#">Productos</a>
							</li>
							<li class="nav-item">
								<a class="nav-link" href="#">Blog</a>
							</li>
							<li class="nav-item">
								<a class="nav-link" href="#">Contacto</a>
							</li>
						</ul>
					</div>
				</div>
				 <small>Tía Tomate 2018. Todos los derechos reservados.</small>
			</footer>

			<!-- Optional JavaScript -->

		    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
		    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>

		    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>

		    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T" crossorigin="anonymous"></script>

			<!-- font Awesome 5.1 -->
			<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.1.0/css/all.css" integrity="sha384-lKuwvrZot6UHsBSfcMvOkWwlCMgc0TaWr+30HWe3a4ltaBwTZhyTEggF5tJv8tbt" crossorigin="anonymous">

			<!-- main script -->
			<script scr="assets/js/script.js></script>
		</body>
		</html>  


