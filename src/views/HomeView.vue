<script setup>
</script>

<template>
  <head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  </head>
  <!--Encabezado-->
    <header>
        <div class="logo">
            <!--<img src="A3.png">-->
            <a href="" class="libro-colorear">Libro Para Colorear</a>
        </div>
        <nav>
            <a href="" class="nav-link">Sobre Nosotros</a>
        </nav>
    </header>
  <!--Tarjetas-->
    <div class="container">
        <div class="card">
            <div class="contenido">
              <h3>¿Cómo Funciona?</h3>
              <p>Texto complementario</p>
            </div>
        </div>
        <div class="card">
          <div class="contenido">
            <h3>Tutorial</h3>
            <p>Texto complementario</p>
          </div>
        </div>
        <div class="card">
          <div class="contenido">
            <h3>Galería</h3>
            <p>Texto Complementario</p>
          </div>
        </div>
    </div>

  <!--Carrusel-->
  <div class="slideshow-container">
  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 16</div>
    <img src="@/assets/01.jpg" style="width:100%">
    <div class="text">Caption Text</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">2 / 16</div>
    <img src="@/assets/02.jpg" style="width:100%">
    <div class="text">Caption Two</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">3 / 16</div>
    <img src="@/assets/03.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">4 / 16</div>
    <img src="@/assets/04.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">5 / 16</div>
    <img src="@/assets/05.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">6 / 16</div>
    <img src="@/assets/06.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">7 / 16</div>
    <img src="@/assets/07.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">8 / 16</div>
    <img src="@/assets/08.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">9 / 16</div>
    <img src="@/assets/09.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">10 / 16</div>
    <img src="@/assets/10.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">11 / 16</div>
    <img src="@/assets/11.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">12 / 16</div>
    <img src="@/assets/12.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">13 / 16</div>
    <img src="@/assets/13.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">14 / 16</div>
    <img src="@/assets/14.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">15 / 16</div>
    <img src="@/assets/15.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext">16 / 16</div>
    <img src="@/assets/16.jpg" style="width:100%">
    <div class="text">Caption Three</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>

  <!--Tutorial-->
  <div class="tutorial">
    <div class="txt">
      <h1>Tutorial</h1>
      <p>Mira el video explicativo y aprende cómo usar la tecnología de realidad aumentada</p>
    </div>
    <img class="imgtutorial" src="@/assets/imgtutorial.png" alt="">
  </div>
  <!--   <button @click="$router.push('/book')">ir al libro</button> -->

  <footer>
    <div class="footerContainer">
        <div class="socialIcons">
            <a href="https://www.instagram.com/isab_elacl/"><i class="fa-brands fa-instagram"></i></a>
            <a href="https://www.youtube.com/@isabelacuartaslopez9056"><i class="fa-brands fa-youtube"></i></a>
        </div>
        <div class="footerNav">
            <ul><li><a href="">Inicio</a></li>
                <li><a href="">Sobre Nosotros</a></li>
            </ul>
        </div>
        
    </div>
  </footer>

</template>

<style scoped>
* {
    font-family: Georgia, 'Times New Roman', Times, serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
a{
    text-decoration: none;
    color:ghostwhite
}

header{
    display:flex;
    height:60px;
    background-color: darkblue;
    align-items:center;
    padding:10px;
    justify-content:space-between;
    box-shadow:5px 5px 20px rgba(0, 0, 0, 0.4);
}
.logo{
    display:flex;
    align-items:center;
}
.logo img{
    height:50px;
    margin-right:10px;
}
.libro-colorear{
  color: white;
  font-weight: 800;
  font-size: larger;
}
nav a:hover{
  color: gray;
}

.container{
  padding-top: 50px;
    width:100%;
    display:flex;
}
.card{
    width:100%;
    margin:20px;
    overflow: hidden;
    background: whitesmoke;
}
.card:hover{
    box-shadow:5px 5px 20px rgba(0, 0, 0, 0.4);
}
.card img{
    width:100%;
    height:210px;
}
.card .contenido{
  text-align: center;
    padding:15px;
}
.card .contenido h3{
    font-weight:400;
    margin-bottom:15px;
}
.card .contenido p{
    color:black;
}

.titulo{
  text-align: center;
  font-size: large;
  font-weight: 400;
  padding-top: 50px;
  color: black;
}
* {box-sizing:border-box}
/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}
/* Hide the images by default */
.mySlides {
  display: none;
}
/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}
/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}
/* Caption text */
.text {
  color: white;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}
/* Number text (1/3 etc) */
.numbertext {
  color: white;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}
/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}
@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

/*Tutorial*/
.tutorial{
  display: flex;
  align-items: center
}
.txt{
  margin-right: 20px;
}
.imgtutorial{
  width: 540;
  height: auto;
}

/*Pie de página*/
footer{
    background-color: darkblue;
}
.footerContainer{
    width: 100%;
    padding: 20px 30px 20px ;
}
.socialIcons{
    display: flex;
    justify-content: center;
}
.socialIcons a{
    text-decoration: none;
    padding:  10px;
    margin: 10px;
    border-radius: 50%;
}
.socialIcons a i{
    font-size: 2em;
    color: white;
    opacity: 0,9;
}
.socialIcons a:hover{
    background-color: white;
    transition: 0.5s;
}
.socialIcons a:hover i{
    color: darkblue;
    transition: 0.5s;
}
.footerNav{
    margin: 10px 0;
}
.footerNav ul{
    display: flex;
    justify-content: center;
    list-style-type: none;
}
.footerNav ul li a{
    color:white;
    margin: 20px;
    text-decoration: none;
    font-size: 1.3em;
    opacity: 0.7;
    transition: 0.5s;

}
.footerNav ul li a:hover{
    opacity: 1;
}
@media (max-width: 700px){
    .footerNav ul{
        flex-direction: column;
    } 
    .footerNav ul li{
        width:100%;
        text-align: center;
        margin: 10px;
    }
    .socialIcons a{
        padding: 8px;
        margin: 4px;
    }
}
</style>
