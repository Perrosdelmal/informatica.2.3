<!DOCTYPE html>
<html lang="es">
<head>
    <script>
        alert("¡Hola!, para empezar a explorar la página selecciona el apartado de tu interes, gracias.");
    </script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INFORMÁTICA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #ffcc00;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: #5152DD;
            padding: 8px;
            text-align: center;
        }

        nav a {
            color: #ffcc00;
            text-decoration: none;
            margin: 0 8px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            margin-top: 20px;
            background-color: #f0f0f0;
            border-radius: 5px;
            display: none;
        }

        footer {
            background-color: #ffcc00;
            color: #fff;
            text-align: center;
            padding: .3px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .contenedor-imagen-texto {
            display: flex;
            flex-direction: row;
        }

        .imagen-materia {
            width: 50%;
            height: auto;
        }

        .texto-materia {
            width: 50%;
            padding-left: 20px;
        }

        .cuadro {
            width: 1240px;
            height: 200px;
            background-color: #f0f0f0; /* Color de fondo original */
            border: 2px solid #ccc;
            padding: 20px;
            box-sizing: border-box;
            margin-bottom: 20px; /* Espacio entre cuadros */
        }

        .cuadro5 {
            width: 1240px;
            height: 700px;
            background-color: #f0f0f0; /* Color de fondo original */
            border: 2px solid #ccc;
            padding: 20px;
            box-sizing: border-box;
            margin-bottom: 20px; /* Espacio entre cuadros */

        }
    </style>
</head>
<body>

<header>
    <h1>INFORMÁTICA</h1>
</header>

<nav>
    <a href="#inicio" onclick="mostrarSeccion('inicio')">Inicio</a>
    <a href="#parcial1" onclick="mostrarSeccion('parcial1')">1er Parcial</a>
    <a href="#parcial2" onclick="mostrarSeccion('parcial2')">2do Parcial</a>
    <a href="#parcial3" onclick="mostrarSeccion('parcial3')">3er Parcial</a>
    <a href="#parcial4" onclick="mostrarSeccion('parcial4')">4to Parcial</a>
    <a href="#materia" onclick="mostrarSeccion('materia')">FILOSOFIA</a>
    <a href="#integrantes" onclick="mostrarSeccion('integrantes')">Integrantes</a>
    <a href="#contacto" onclick="mostrarSeccion('contacto')">Contacto</a>
</nav>

<section id="inicio">
    <div class="contenedor-imagen-texto">
        <img src="logo.jpg" class="imagen-materia">
        <div class="texto-materia">
            <h2>¡Hola!</h2>
            <p>Bienvenido a nuestra página de Informática. Aquí podrás encontrar información sobre los diferentes parciales, la materia de Filosofía, los integrantes del equipo y cómo contactarnos. ¡Disfruta explorando!</p>
        </div>
    </div>
</section>

<section id="parcial1" class="seccion-parcial">
    <h2>1er Parcial</h2>
    <div class="cuadro">
        <p>En el primer parcial de informática vimos el sistema operativo, con sus subtemas que son tipos de sistemas operativos, partes de un sistema operativo, hardware y software, dispositivos de entrada salida, almacenamiento y programa, sistema aplicación y programación, que es el sistema operativo, plataforma de recursos administración de recursos, interfaz de la computadora, componentes y función de los sistemas operativos.</p>
    </div>
</section>

<section id="parcial2" class="seccion-parcial">
    <h2>2do Parcial</h2>
    <div class="cuadro">
        <p>Internet: servicios de internet, virus y antivirus, tipos de redes, buscadores y navegadores, estructura básica del HTML</p>
    </div>
</section>

<section id="parcial3" class="seccion-parcial">
    <h2>3er Parcial</h2>
    <div class="cuadro">
        <p>Procesadores de texto, editor de texto, historia y evolución de los procesadores de texto, conceptos básicos, características y ventajas de los procesadores de texto, introducción a la elaboración de documentos sobre informática, herramientas del procesador de texto, tablas y columnas, gráficas e imágenes.</p>
    </div>
</section>

<section id="parcial4" class="seccion-parcial">
    <h2>4to Parcial</h2>
    <div class="cuadro">
        <p>Por último, vimos los programas de diseño, lo que es power point y como proyecto final hacer una página web.</p>
    </div>
</section>

<section id="materia">
    <h2>Materia</h2>
    <div class="cuadro5">
        <p>La filosofía abarca diversas ramas que exploran aspectos fundamentales del conocimiento humano y la realidad:<br><br>
            Metafísica: Se ocupa de la naturaleza fundamental de la realidad y las preguntas sobre el ser, la existencia y la causalidad.<br><br>
            Epistemología: Examina la naturaleza, el alcance y los límites del conocimiento, así como los métodos para adquirirlo y validarlos.<br><br>
            Ética: Se centra en cuestiones de moralidad y valores, explorando qué es lo correcto o bueno y los principios que guían el comportamiento humano.<br><br>
            Lógica: Estudia los principios del razonamiento válido y la inferencia correcta para evaluar argumentos y estructurar el pensamiento de manera coherente.<br><br>
            Estética: Analiza la naturaleza del arte, la belleza y la apreciación estética, tanto desde perspectivas subjetivas como objetivas.<br><br>
            Filosofía de la mente: Investiga la naturaleza de la mente, la conciencia y la cognición, así como la relación entre la mente y el cuerpo.<br><br>
            Filosofía de la ciencia: Examina los fundamentos, métodos y presupuestos de la ciencia, así como sus límites y su relación con otras formas de conocimiento.<br><br>
            Filosofía política: Se ocupa de cuestiones relacionadas con el gobierno, la justicia, el poder y la organización de la sociedad.<br><br>
            Por otro lado, se pueden distinguir entre mito, religión, ciencia y filosofía:<br><br>
            Mito: Narrativas tradicionales que explican el origen del mundo y fenómenos naturales, transmitidas oralmente y con elementos sobrenaturales.<br><br>
            Religión: Sistemas de creencias y prácticas que abordan preguntas sobre lo divino, lo trascendental y la moralidad, con rituales y comunidades organizadas.<br><br>
            Ciencia: Enfoque sistemático basado en la evidencia para entender el mundo natural a través de observación, experimentación y formulación de teorías, buscando la objetividad y la verificación.<br><br>
            Filosofía: Disciplina que se ocupa de preguntas fundamentales sobre la realidad, el conocimiento, la moralidad y la existencia humana, basada en la reflexión crítica y el razonamiento lógico.<br><br>
            Las diferencias entre estos campos se pueden ilustrar con ejemplos como el "Mito de la Caverna" de Platón, que explora la naturaleza del conocimiento, y las obras de Aristóteles, que abordan temas como la metafísica y la ética.<br><br><br><br><br>
        </p> <br><br><br><br>
    </div>
</section>

<section id="integrantes">
    <h2>Integrantes</h2>
    <p>Diego Ismael Marfileño Mata<br><br> Diego Rocha Aguirre <br><br> Victoria</p>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p>Puedes contactarnos a través de la siguiente información de contacto.</p>
</section>

<footer>
    <p>Derechos de autor © 2024 - Mi Página Web</p>
</footer>

<script>
    function mostrarSeccion(id) {
        var secciones = document.querySelectorAll('.seccion-parcial, section[id="materia"], section[id="integrantes"], section[id="contacto"]');
        secciones.forEach(function(seccion) {
            seccion.style.display = 'none';
        });
        document.getElementById(id).style.display = 'block';
        if (id !== "inicio") {
            document.getElementById("inicio").style.display = 'none';
        } else {
            document.getElementById("inicio").style.display = 'flex';
        }
    }
</script>

</body>
</html>

