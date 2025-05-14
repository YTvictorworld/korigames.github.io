<!DOCTYPE HTML>
<html>
<head>
<title>Kori Games</title>
<link rel="icon" type="image/png" href="images/logo1-removebg-preview.png">
<link href="css/bootstrap.css" rel='stylesheet' type='text/css' />
<link href="css/style.css" rel='stylesheet' type='text/css' />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<link href='http://fonts.googleapis.com/css?family=Open+Sans:400,300,600,700,800' rel='stylesheet' type='text/css'>
<script type="application/x-javascript"> addEventListener("load", function() { setTimeout(hideURLbar, 0); }, false); function hideURLbar(){ window.scrollTo(0,1); } </script>
<script src="js/jquery.min.js"></script>
<!--<script src="js/jquery.easydropdown.js"></script>-->
<!--start slider -->
<link rel="stylesheet" href="css/fwslider.css" media="all">
<script src="js/jquery-ui.min.js"></script>
<script src="js/fwslider.js"></script>
<!--end slider -->
<script type="text/javascript">
        $(document).ready(function() {
            $(".dropdown img.flag").addClass("flagvisibility");

            $(".dropdown dt a").click(function() {
                $(".dropdown dd ul").toggle();
            });
                        
            $(".dropdown dd ul li a").click(function() {
                var text = $(this).html();
                $(".dropdown dt a span").html(text);
                $(".dropdown dd ul").hide();
                $("#result").html("Selected value is: " + getSelectedValue("sample"));
            });
                        
            function getSelectedValue(id) {
                return $("#" + id).find("dt a span.value").html();
            }

            $(document).bind('click', function(e) {
                var $clicked = $(e.target);
                if (! $clicked.parents().hasClass("dropdown"))
                    $(".dropdown dd ul").hide();
            });


            $("#flagSwitcher").click(function() {
                $(".dropdown img.flag").toggleClass("flagvisibility");
            });
        });
     </script>
</head>
<body>
	<div class="header">
		<div class="container">
			<div class="row">
			  <div class="col-md-12">
				 <div class="header-left">
					 <div class="logo">
						<a href="index.html"><img src="images/kori logo.png" alt=""/></a>
					 </div>
					 <div class="menu">
						  <a class="toggleMenu" href="#"><img src="images/nav.png" alt="" /></a>
						    <ul class="nav" id="nav">					
								<div class="clear"></div>	
							</ul>
							<script type="text/javascript" src="js/responsive-nav.js"></script>
				    </div>							
	    		    <div class="clear"></div>
	    	    </div>
	            <div class="header_right">
	    		  <!-- start search-->
				      <div class="search-box">
							<div id="sb-search" class="sb-search">
								<form>
									<input class="sb-search-input" placeholder="Enter your search term..." type="search" name="search" id="search">
									<input class="sb-search-submit" type="submit" value="">
									<span class="sb-icon-search"> </span>
								</form>
							</div>
						</div>
						<!----search-scripts---->
						<script src="js/classie.js"></script>
						<script src="js/uisearch.js"></script>
						<script>
							new UISearch( document.getElementById( 'sb-search' ) );
						</script>
						<!----//search-scripts---->
				    <ul class="icon1 sub-icon1 profile_img">
					 <li>
						<ul class="sub-icon1 list">
						  <div class="product_control_buttons">
						  	<a href="#"><img src="images/edit.png" alt=""/></a>
						  		<a href="#"><img src="images/close_edit.png" alt=""/></a>
						  </div>
						   <div class="clear"></div>
						  <li class="list_img"><img src="images/1.jpg" alt=""/></li>
						  <li class="list_desc"><h4><a href="#">velit esse molestie</a></h4><span class="actual">1 x
                          $12.00</span></li>
						  <div class="login_buttons">
							 <div class="check_button"><a href="checkout.html">Check out</a></div>
							 <div class="login_button"><a href="login.html">Login</a></div>
							 <div class="clear"></div>
						  </div>
						  <div class="clear"></div>
						</ul>
					 </li>
				   </ul>
		           <div class="clear"></div>
	       </div>
	      </div>
		 </div>
	    </div>
	</div>
	<div class="banner">
	<!-- start slider -->
       <div id="fwslider">
         <div class="slider_container">
            <div class="slide"> 
                <!-- Slide image -->
               <img src="images/slider1.jpg" class="img-responsive" alt=""/>
                <!-- /Slide image -->
                <!-- Texts container -->
                <div class="slide_content">
                    <div class="slide_content_wrap">
                        <!-- Text title -->	
                        <!-- /Text title -->
                    </div>
                </div>
               <!-- /Texts container -->
            </div>
            <!-- /Duplicate to create more slides -->
            <div class="slide">
               <img src="images/slider2.jpg" class="img-responsive" alt=""/>
                <div class="slide_content">
                    <div class="slide_content_wrap">
                    </div>
                </div>
            </div>
            <!--/slide -->
        </div>
        <div class="timers"></div>
        <div class="slidePrev"><span></span></div>
        <div class="slideNext"><span></span></div>
       </div>
	<!--/slider -->
      </div>
	  <div class="main">
		
	</div>
	<!--/Juegos  -->
	<div class="features">
		<div class="container">
			<h3 class="m_3">Nuestros juegos</h3>
			<div class="close_but"></div>
			  <div class="row">
				<div class="col-md-3 top_box">
				  <div class="view view-ninth"><a href="single.html">
                    <img src="images/lescaball.jpg" class="img-responsive" alt=""/>
                    <div class="mask mask-1"> </div>
                    <div class="mask mask-2"> </div>
                      <div class="content">
                        <h2>LESCABALL</h2>
                        <p>¡Goku y Vegeta se enfrentan como nunca antes en este combate retro 2D!
							<br>
							¡La batalla comienza ya!
						</p>
                      </div>
                   </a> </div
                  </div>
                  <h4 class="m_4"><a href="#">LESCABALL</a></h4>
                  <p class="m_5">Peleas al estilo antiguo, poderes clásicos y pura adrenalina. 
					Elige tu guerrero, domina sus técnicas y demuestra quién es el verdadero saiyajin legendario.</p>
                </div>
                <div class="col-md-3 top_box">
					<div class="view view-ninth"><a href="single.html">
                    <img src="images/la mina del tesoro.jpg" class="img-responsive" alt=""/>
                    <div class="mask mask-1"> </div>
                    <div class="mask mask-2"> </div>
                      <div class="content">
                        <h2>LA MINA DEL TESORO</h2>
                        <p>Adéntrate en una mina oscura llena de secretos y peligros.</p>
                      </div>
                    </a> </div>
                   <h4 class="m_4"><a href="#">LA MINA DEL TESORO</a></h4>
                   <p class="m_5">Tu misión: encontrar el cofre escondido y hacerte rico... 
					¡antes de que la cueva se derrumbe! Cada rincón puede tener una pista, un tesoro o una trampa.
					 ¿Lograrás escapar con el oro a tiempo?</p>
				</div>

				<!--/estilos -->
				<div class="col-md-3 top_box">
					<div class="view view-ninth"><a href="single.html">
                    <img src="images/midnightblitz.png" class="img-responsive" alt=""/>
                    <div class="mask mask-1"> </div>
                    <div class="mask mask-2"> </div>
                      <div class="content">
                        <h2>MIDNIGHTBLITZ</h2>
                        <p>TEl mundo ha caído bajo el control de los robots, y tú eres el último humano sobreviviente.</p>
                      </div>
                    </a> </div>
                   <h4 class="m_4"><a href="#">MIDNIGHTBLITZ</h4>
                   <p class="m_5"> El mundo ha caído bajo el control de los robots, y tú eres el último humano sobreviviente.
					 Armado solo con ingenio y pocos recursos, debes explorar las ruinas en busca de tecnología que te ayude a enfrentarlos,
					 mientras evitas ser cazado por las máquinas que patrullan sin descanso.</p>
				</div>
				<div class="col-md-3 top_box1">
					<div class="view view-ninth"><a href="single.html">
                    <img src="images/planta vs zombie.jpg" class="img-responsive" alt=""/>
                    <div class="mask mask-1"> </div>
                    <div class="mask mask-2"> </div>
                      <div class="content">
                        <h2>PLANTA VS ZOMBIE</h2>
                        <p>¿Te suena el clásico Plants vs. Zombies? Pues aquí está mi versión, con un toque único. </p>
                      </div>
                     </a> </div>
                   <h4 class="m_4"><a href="#">PLANTA VS ZOMBIE</a></h4>
                   <p class="m_5">Defiende tu jardín de oleadas de zombis usando plantas estratégicas, 
					poderes especiales y nuevas sorpresas. Mantén a los no-muertos a raya mientras desbloqueas niveles cada vez más desafiantes.
					¿Podrás proteger tu casa hasta el final?</p>
				</div>
			</div>
		 </div>
	    </div>

    <div class="company-info">
        <div class="container">
            <div class="row">
                <div class="col-md-12 text-center">
                    <h2>Kori Games</h2>
                    <p>Somos una empresa dedicada a la creación y desarrollo de páginas web y videojuegos, 
						combinando innovación y calidad en cada proyecto. Nos especializamos en ofrecer experiencias digitales únicas, 
						adaptadas a las necesidades de cada cliente, desde sitios web funcionales y modernos hasta videojuegos que abarcan una amplia gama de géneros y estilos.</p>
						<br>
<p>En el ámbito de los videojuegos, destacamos por nuestra diversidad y excelencia, 
entregando títulos que van desde emocionantes aventuras hasta juegos casuales,
 todos diseñados con un alto estándar de calidad. Nuestro compromiso es crear productos que no solo entretengan, 
 sino que también impacten y perduren en la memoria de los jugadores.</p>
 <br>

<p>Con un enfoque innovador y un tono formal, buscamos posicionarnos como líderes en el sector,
 impulsando experiencias digitales que combinan creatividad, tecnología y diseño impecable..</p>
                </div>
            </div>
        </div>
    </div>


		<div class="footer">
			<div class="container">
				<div class="row">
					<div class="col-md-3">
						<ul class="footer_box">
							<h4>Juegos</h4>
							<li><a href="#">LESCABALL</a></li>
							<li><a href="#">PURGATORIO</a></li>
							<li><a href="#">MIDNIGHTBLITZ</a></li>
							<li><a href="#">PLANTA VS ZOMBIE</a></li>

						</ul>
					</div>
					<div class="col-md-3">
						<ul class="footer_box">
							<h4>contacto</h4>
							<li><a href="#">midnightgames195@gmail.com</a></li>
							<li><a href="#">midnight_games_</a></li>
						</ul>
					</div>
					<div class="col-md-3">
						<ul class="footer_box">
							<h4>ubicacion </h4>
							<li><a href="#">C/Cristo Rey, Esq. 6 de Noviembre, Lava Pies, San Cristóbal.</a></li>
						</ul>
					</div>
					<div class="col-md-3">
						<ul class="">
					        </div>
							<ul class="social">	
							  <li class="facebook"><a href="https://www.facebook.com/profile.php?id=61559291321818"><span> </span></a></li>
							  <li class="twitter"><a href="#"><span> </span></a></li>
							  <li class="instagram"><a href="https://www.instagram.com/midnight_games__/"><span> </span></a></li>											  				
						    </ul>
						</ul>
						
					</div>
				</div>
				<marquee><p>© 2025 by kōri Games</p> </marquee>`
				<div class="row footer_bottom">

					 
   				</div>
			</div>
		</div>
</body>	
</html>
