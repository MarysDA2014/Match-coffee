<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Match Coffee</title>

    <link rel="shortcut icon" href="images/favicon.ico">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.css" />
    <link rel="stylesheet" href="css/style.css">

    
</head>

<body>
    <header>
        <div class="container">
            <div class="cabezote">
                <img class="logo" src="images/logo.svg" alt="Logo Match Coffee" title="Match Coffee">
                <nav class="menu">
                    <ul>
                        <li><a id="toBanner">Inicio</a></li>
                        <li><a id="toMatch">Match</a></li>
                        <li><a id="toApp">Descarga la app</a></li>
                        <li><a id="toContacto">Contacto</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
    <section id="banner" class="banner relative">
        <!-- Slider main container -->
        <div class="swiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper">
                <!-- Slides -->
                <div class="swiper-slide"><img src="images/banner.jpg" alt="Banner 1"></div>
                <div class="swiper-slide"><img src="images/banner 2.png" alt="Banner 2"></div>
                <div class="swiper-slide"><img src="images/banner.jpg" alt="Banner 3"></div>
            </div>

            <!-- If we need navigation buttons -->
            <div class="swiper-button-prev flechas"></div>
            <div class="swiper-button-next flechas"></div>
        </div>
        <div class="scrollDown" id="toDown">
            <p>Descubre más</p>
            <img src="images/flecha.svg" alt="Flecha">
        </div>
        <img src="images/separador.png" alt="separador" class="separador">
    </section>
	
	
	
	
	
	
    <section id="match" class="section">
		<div class="container" >
            <h2 class="subtitulo">¿CÓMO HAGO MATCH?</h2>
            <div class="cont-flex-icons" style="display: flex;">
              <div class="conticons">
                 <img src="images/icono celular.png" alt="">
                <h3>REGÍSTRATE</h3>
                <p>Descarga la app, regístrate y conoce personas</p>
               </div>

               <div class="conticons">
                <img src="images/icono casa.png" alt="">
                <h3>ESCOGE</h3>
                <p>El establecimiento de tu agrado para tu primera cita</p>
               </div>

               <div class="conticons">
                <img src="images/icono taza.png" alt="">
                <h3>DISFRUTA</h3>
                <p>La experiencia Match Coffee en el establecimiento</p>
               </div>

               <div class="conticons">
                <img src="images/icono estrella.png" alt="">
                <h3>CALIFICA</h3>
                <p>La experiencia en nuestra app y haz que más personas nos conozcan</p>
               </div>
            </div>
			       
    </section>
	
	

	
    <section id="app" class="section">
        
     <div class="botonesDescarga">
            <h3>Descarga la app Match Coffee y vive la experiencia</h3>
            <a href="#">
                <img class="appstore" src="images/appstore.png" alt="">
            </a>
            <a href="#">
                <img class="playstore" src="images/playstore.png" alt="">
            </a>
        </div>
    </div>
	
    </section>
	
	
    <section id="contacto" class="section">
        Contacto
    </section>
    <footer>
        <div class="container contFooter">
            <div class="columnfooter">
                <div class="cont-logo">
                    <img src="images/logo-footer.png" alt="LogoFooter">
                </div>
                <div class="cont-direccion">
                    <h3>Encuentranos</h3>
                    <p>Carrera 48 B 123 -09 Medllín, colombia</p>
                    <p>312 687 4565</p>
                </div>
                <div class="cont-redes">
                    <h3>Síguenos</h3>
                    <div class="redes">
                        <a href="#"><img src="images/facebook.svg" alt="Facebook"></a>
                        <a href="#"><img src="images/instagram.svg" alt="Instagram"></a>
                    </div>
                </div>
            </div>
        </div>
        <div class="copyright">
                <p>Copyright - Todos los derechos reservados</p>
            </div>
    </footer>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.js"></script>
    <script src="js/scripts.js"></script>
</body>

</html>
