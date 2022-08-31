# ST12.github.io
HTML CSS JavaScript 
<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/html" xmlns="http://www.w3.org/1999/html">
<head>
    <meta charset="UTF-8">
    <title>WELCOME TO MY FIRD PAGE</title>
    <link rel="stylesheet" href="Style.css">
    <script src="main.js"> </script>
    <style>
        h1{
            color:brown;
        }
    </style>
</head>

<p>
    <h1 style="text-align:center"><strong>AMISTAD</strong></h1>
    <p class="text-blanco">La amistad no se me dado fácilmente, es decir que me cuesta
        un poco en socializar con gente desconisa. A pesar que hay
        un dicho de una serie animada que:
    </p>
    <p class="text-white"><strong>"Un extraño es un amigo a Conocer"</strong></p>
    <p class="text-blanco">La amistad de escuela o de colegio es innegable, de decir que marca tu vida
        de las cueles puedes encontrar amistades buenas y malas, pero muy pocas son duraderas.
        La vida estudiantil me ha demostrado que una buena amistad no se busca, solo llega a ti
        sin saberlo, conocí muchas personas siguiendo el concejo de alguien que decía:
    </p>
    <p class="text-white" style="text-align: center">
        <storng>"Las mejores amistades surgen en la Universidad, porque esas amistades son verdaderas
     que pueden ayudarte de una u otra forma a tu carrera profesional y personal" </storng>
    </p>
    <p></p>
    <p class="text-blanco">El ingreso a la universidad fue lo mejor que me ha sucedido en mi vida,
        sin saberlo conocí a mi amigo, hermano, una amistad verdadera que solo pueden pasar cada siglo,
        luchando por el ten apreciado título de Ingeniero, navegando en los mares de las malas
        notas, riéndonos de lo que alguna vez una nota nos derrumbó. Deseo con tan profunda de mi corazón,
        llegar a graduarnos y mejor aún montar un negocio para progresar y cumplir metas y sueños.
    </p>
    <p class="text-white" style="text-align: center"><strong>"Gracias por ser mi amigo sin tener nada a cambio."</strong></p>
    <br>
    <a href="https://www.youtube.com/watch?v=P2rUuv1EQhQ" >
        Cancion de la amistad
    </a>

</div>
</body>
<body>
<div style="text-align:center">
    <img src="https://i.pinimg.com/originals/ea/3f/6c/ea3f6cad9e31fa46cb1fc350e0076a28.gif" alt="Imagen">
</div>
<body style="text-align:center">
    <h1 style="text-align:center">EL VALOR DE LA AMISTAD</h1>
    <video  width="720" height="540" id="video_1">
        <source  src="EL VALOR DEL COMPAÑERISMO.mp4" type="video/mp4">
        <source src="EL VALOR DEL COMPAÑERISMO.webm" type="vdeo/webm">
    </video>
    <div>
        <button onclick="playPause()">&#9658;/||</button>
        <button onclick="stop()">&#9726;</button>
        <button onclick="skip(-10)">&lt;&lt;</button>
        <button onclick="skip(10)">&gt;&gt;</button>
    </div>
    <script>
        var video= document.getElementById("video_1")
        function playPause(){
            if(video.paused)
             video.play();
            else
             video.pause();
        }
        function stop(){
            video.pause();
            video.currentTime = 0
        }
        function skip(value){
            video.currentTime += value
        }

    </script>
</body>
</body>
</html>
