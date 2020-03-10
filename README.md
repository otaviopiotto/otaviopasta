<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>teste</title>
</head>
<body>
	
	<link href='https://fonts.googleapis.com/css?family=Raleway' rel='stylesheet'/>
	
	
	<nav role="navigation">
  <div id="menuToggle">
 
    <input type="checkbox" />
    
    <span id="menu-h"></span>
    <span id="menu-h"></span>
    <span id="menu-h"></span>
    
    <ul id="menu">
		
		<texto class="home">Home</texto>
		
      <li><a href="#">Sobre</a></li>
      <li><a href="#">Atuação</a></li>
      <li><tst></tst><a href="#">Sócios</a></li>
      <li><a href="#">Contato</a></li>
	  <br/><br/><br/><br/><br/>
		<li><text class="home-mos">MOS Advocacia</text></li>
		<li><text class="home-mattos">Mattos, Osna & Sirena Sociedade de Advogados</text></li>
		
		<li><text class="home-end">Av. Presidente Getúlio Vargas, 2932, salas 604-605, 
Curitiba, Paraná.
80.240-040 </text></li>
		
		<text class="home-tel ">41 3013 7775</text>
		<br/>
		<text class="home-email ">contato@mosadvocacia.com.br</text>
    </ul>
  </div>
</nav>
	
	
	
	
	<div class="principal">
		
	
		
		<div id="retangulo" class="slider">
			<img src="Imagens/scroll.png" class="scroll" />	
		
	<img src="logo/backgorund.png" class="bg-logo">
	<img src="logo/logo.png" class="logo">
			
			<div id="botoes">
				
			<a href="#slide-1" id="slider-image-1" class="slider-change-1">01</a>
				
			<br/><br/>
				
			<a href="#slide-2" id="slider-image-2" class="slider-change-2">02</a>
				
				<br/><br/>
				
			<a href="#slide-3" id="slider-image-3" class="slider-change-2">03</a></div>
			
			<div class="linha-botoes"></div>
			
		 <h2 class="titulo" > Sobre</h2>
			
			
	<div class="imagens-slider">
			
		    <div id="slide-1"><img src="Imagens/Escritorio.jpg" class="fundo-1 imagem-1" style="opacity: 0.2;"/>
		</div>
			
			<div id="slide-2">
			<img src="Imagens/home-office-1867761.jpg" class="fundo-1 imagem-2" style="z-index:2;"/>
			</div>
			
			
			<div id="slide-3">
			<img src="Imagens/computer-1245714.jpg" class="fundo-1 imagem-3" />
			</div>
		
			</div>
			
		</div>
	</div>

	
	<div class="mos">
			
		<h1 class="mos-titulo left"> <span>MOS Advocacia</span></h1>
				
		<div class="texto-1"> 
			Fundada em Curitiba em 2012, a Mattos, Osna & Sirena Sociedade de Advogados presta serviços diferenciados a investidores e empresas nacionais e internacionais na realização de negócios no Brasil, oferecendo aos seus clientes uma visão distinta a respeito da função da advocacia na concretização de negócios.</div>
			
			</div>
	
	
	<div>
	
		<h3 class="left conheca"> <span> Conheça algumas de nossas áreas de atuação:</span></h3>
	
	</div>
	
	<div class="outros-serv">
		
		
		
		<img src="Imagens/coffee-break-1177540.jpg" class="imagem-outros-servico "/> 
	    <texto class="texto-2">Contecioso cível e empresarial</texto>
		<text class="ver-mais-1">Ver mais</text>
		
	
		<texto class="texto-3">Família e planejamento sucessório</texto>
		<text class="ver-mais-2">Ver mais</text>
		<img src="Imagens/family-2810999.jpg" class="imagem-outros-servico " /> 

	   
		<texto class="texto-4">Reestruturação e insolvência</texto>
		<text class="ver-mais-3">Ver mais</text>
		<img src="Imagens/student-849821.jpg" class="imagem-outros-servico "/> 
	
	
	
	</div>
	
	
	
	
</body>
	
	<style>
	 
		html, body{
  width: 100%;
  max-width: 100%;		
  margin: 0;
  padding: 0;		
  height: 2724px;
  background-color: #121212;}
		
		
		
		.logo{ 
  width: 90px;
  position:absolute;
  display: block;
  z-index: 3;
  left: 3%;
  top:4%;
			
  }
		.bg-logo{ 
  width: 180px;
  position:absolute;
  display: block;	
  z-index: 3;
  left: 0;
  top:0;
  opacity: 0.6;
  z-index: 3;		}
		
		
	 #botoes{
	 display: inline-block;
     position: absolute;
	 left:91%;
     top:43em;
     z-index: 3; 
		}
		
		a{ text-decoration: none;}
		
	.linha-botoes{  
  height: 150px;
  width: 1px;
  border: solid 0.5px #f05a28;
  position:absolute;
  left:94%;
  top:46.7em;
  display: block;
  z-index: 3;}
		
		
	#slide-2{opacity: 0; }
	.imagem-3{opacity:0;}
		
	
		
	.scroll{
	 position:absolute;
	 left: 50%;
     top:52.8em;
     z-index: 3;}
		
		
	#retangulo{
  
  width: 100%;
  object-fit: contain;
  height: 900px;
  background-color: #000000;
		}
			
		
#slider-image-1:active .imagem-1{opacity:100;}
       
#slider-image-2:hover + #slide-2{opacity:100;}
		
#slider-image-3:target ~ .imagens-slider{left: -1600px;}
       
     
		
		
        
		.slider-change-1{
  width: 50px;
  height: 59px;
  font-family: Raleway ;
  font-size: 50px;
  font-weight: 500;
  color: #ffffff;
  z-index: 3;}
		
		.slider-change-2{ 
  width: 20px;
  height: 21px;
  font-family: Raleway;
  font-size: 18px;
  font-weight: 200;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: normal;
  color: #ffffff;
  z-index: 3;}
		

	.fundo-1{
  width:96%;
  max-width: 100%;
  max-height: 100%;
  padding:20px;
  position: absolute;
  display:block;
  object-fit:cover;
  z-index: 1; }
		
	.titulo{ 
  font-family: Raleway;			
  font-size: 2em;
  font-weight: 200;
  color: #fff; 
  border-left:solid 1px white ;	
  padding: 15px;
  position:absolute;
  display:block;			
  left:50%;
  top:10em;
  z-index: 3;
  }
		

		.mos-titulo { color:white; 
			font-family:raleway; 
			font-weight:200; 
			font-size:3em; 
			text-align:center;
			margin: 20% 0 20px;}
		
		.texto-1{ 
			text-align: center;
			font-family:raleway;
			font-weight: 200;
			font-size:18px;
            line-height: 1.33;
            text-align: center;
			color:#ffffff;
			margin-left:10%;
			margin-right:10%;
		}
		
		
		
		.ver-mais-1{ 
			font-family:raleway;
			width:160px;
			font-weight:200;
			font-size:12px;
            position:absolute;
			left:18%;
			margin-top:30%;
			text-align:center;
			color:#ffffff;
		    z-index:2;}
		
		.ver-mais-2{ 
			font-family:raleway;
			width:160px;
			font-weight: 200;
			font-size:12px;
            position: absolute;
			left:45%;
			margin-top:30% ;
			text-align: center;
			color:#ffffff;
		    z-index:2;}
		
		.ver-mais-3{ 
			 font-family:raleway;
			width:160px;
			font-weight: 200;
			font-size:12px;
            position: absolute;
			left:76%;	
			margin-top:30% ;
			text-align: center;
			color:#ffffff;
		    z-index:2;}
		
		
		.texto-2{ 
			font-family:raleway;
			width:160px;
			font-weight:200;
			font-size:22px;
            position:absolute;
			left:18%;
			margin-top:17%;
			text-align:center;
			color:#ffffff;
		    z-index:2;}
		
		
		.texto-3{ 
			      font-family:raleway;
			width:160px;
			font-weight: 200;
			font-size:22px;
            position: absolute;
			left:45%;
			margin-top:18% ;
			text-align: center;
			color:#ffffff;
		    z-index:2;}
		
		
		
		.texto-4{ 
			      font-family:raleway;
			width:160px;
			font-weight: 200;
			font-size:22px;
            position: absolute;
			left:76%;	
			margin-top:18% ;
			text-align: center;
			color:#ffffff;
		    z-index:2;}
		
		  	
		
		.conheca{  
	        font-family:raleway;
			font-weight: 100;
			font-size:18px;
            margin-top: 28%;
            line-height: 1.33;
			color:#f05a28;
			text-align: center;
		}
		
		
		
		.imagem-outros-servico{ 
		width:31%;
		height:31%;
		max-width: 100%;
		opacity: 0.3;
		text-align: center;
		margin-top:90px ;
		object-fit:cover;}
		
		
	
		
		
		.outros-serv{
		display:flex;
		max-width: 100%;	
		margin-top: 2%;
		margin-left: 5%;
		}
		
		
		

#menuToggle
{
  display: block;
  position: fixed;
  top: 50px;
  left: 50px;
  z-index: 4;
  -webkit-user-select: none;
  user-select: none;
}

#menuToggle a
{
  text-decoration: none;
  color: white;
  font-family: raleway;	
  transition: color 0.3s ease;
}

#menuToggle a:hover
{
  color: tomato;
}


#menuToggle input
{
  display: block;
  width: 38px;
  height: 30px;
  position: absolute;
  top: -5px;
  left: 105em;
  
  cursor: pointer;
  
  opacity: 0; 
  z-index: 5; 
  
  -webkit-touch-callout: none;
}


 
#menuToggle #menu-h
{
  display: block;
  width: 33px;
  height: 3px;
  margin-bottom: 5px;
  position: relative;
  left:88em;	
  top: 10%;	 
  background: #cdcdcd;
  border-radius: 3px;
  
  z-index: 4;
  
  transform-origin: 4px 0px;
  
  transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
              background 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
              opacity 0.55s ease;
}

#menuToggle #menu-h :first-child
{
  transform-origin: 0% 0%;
}

#menuToggle #menu-h :nth-last-child(2)
{
  transform-origin: 0% 100%;
}

#menuToggle input:checked ~ span
{
  opacity: 1;
  transform: rotate(45deg); translate:(-2px, -1px);
  background: white;
}


#menuToggle input:checked ~ span:nth-last-child(3)
{
  opacity: 0;
  transform: rotate(0deg) scale(0.2, 0.2);
}

#menuToggle input:checked ~ span:nth-last-child(2)
{
  transform: rotate(-45deg); translate:(0, -1px);
}


#menu
{
  position: fixed;
  width: 100%;
  height: 750px;
  margin: -100px 0 0 -50px;
  padding: 70px;
  padding-top: 120px;
  background: #121212;
  list-style-type: none;
  -webkit-font-smoothing: antialiased;
  transform-origin: 0% 0%;
  transform: translate(-100%, 0);
  transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0);
}
#menu li		
		
{
  padding: 10px 0;
  font-size: 22px;
}

#menuToggle input:checked ~ ul
{
  transform: none;
}
		
		
		
		
		.home{ font-size:45px;
			   font-family: raleway;
			   color:tomato;
		z-index:7;}
		
		.home-mos{
			   font-size:38px;
			   font-family: raleway;
			   color:white;
		       margin-top: 50px;
		z-index:7;}
		
		.home-mattos, .home-end{
			font-size:18px;
			width:10px;
			font-family: raleway;
			color:white;
			font-weight: 200;
		z-index:7;}
		
		
		.home-tel{font-size:38px;
			   font-family: raleway;
			   color:white;
			   margin-left: 75%;
			z-index:7;
		       }
		
		.home-email{ font-size:12px;
			width:10px;
			font-family: raleway;
			color:white;
			margin-left: 75%;
			font-weight: 200;
		z-index:7;}
		
		
		
		
		
		
h1 {
  display: flex;
  align-items: center;
  justify-content: center;
}
h1 span {
  background: #121212;
  margin: 0 15px;
}
h1:before,
h1:after {
  background: #f05a28;
  height: 1px;
  flex: 1;
  content: '';
}
h1.left:after {
  background: none;
}
		
		h3 {
  display: flex;
  align-items:center;
  margin-left: ;
  
			
}
		h3 span{
  background: #121212;
  margin:  0 10px;}
h3:before,
h3:after {
  background: #f05a28;
  height: 1px;
  flex: 1 ;
  content: '';
}
h3.left:after {
  background: none;

}

	
	</style>
	
	<script src="js/vendor/jquery.js"></script>
    <script src="js/vendor/what-input.js"></script>
    <script src="js/vendor/foundation.min.js"></script>
    <script>
      $(document).foundation();
    </script>
	
</html>
