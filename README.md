<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz San Valentín</title>
    <style>
        /* Estilos generales */
        body {
            margin: 0;
            padding: 0;
            font-family: "Indie Flower", cursive;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            background-image: url('https://i.pinimg.com/736x/4d/1d/f2/4d1df2e6309e1db525abc9176722487b.jpg'); /* Imagen de fondo */
            background-size: cover;
            background-position: center;
        }

        /* Contenedor principal */
        .container {
            text-align: center;
            position: relative;
            background: rgba(255, 255, 255, 0.7); /* Fondo semitransparente para que el texto sea legible */
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
        }

        /* Estilo para el mensaje */
        .message {
            font-size: 50px;
            color: #ff6f61;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            margin-bottom: 20px;
        }

        /* Estilo para el corazón flechado */
        .heart {
            font-size: 100px;
            color: #ff6f61;
            animation: float 3s ease-in-out infinite;
        }

        /* Animación para el corazón flechado */
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }

        /* Estilo para el botón */
        .download-button {
            padding: 15px 30px;
            font-size: 20px;
            font-family: "Arial", sans-serif;
            color: white;
            background-color: #ff6f61;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: background-color 0.3s ease;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
        }

        .download-button:hover {
            background-color: #ff3b2f;
        }

        /* Corazones flechados rebotando en el fondo */
        .hearts-background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

        .hearts-background span {
            position: absolute;
            color: #ff6f61;
            font-size: 30px;
            animation: bounce 5s linear infinite;
            bottom: -50px;
        }

        @keyframes bounce {
            0% {
                transform: translateY(0) rotate(0deg);
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) rotate(360deg);
                opacity: 0;
            }
        }

        /* Más corazones subiendo */
        .more-hearts {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

        .more-hearts span {
            position: absolute;
            color: #ff6f61;
            font-size: 30px;
            animation: rise 10s linear infinite;
            bottom: -50px;
        }

        @keyframes rise {
            0% {
                transform: translateY(0) rotate(0deg);
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) rotate(360deg);
                opacity: 0;
            }
        }
    </style>
    <!-- Enlace a la fuente de Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Corazones flechados rebotando en el fondo -->
    <div class="hearts-background">
        <span style="left: 10%;">💘</span>
        <span style="left: 20%;">💘</span>
        <span style="left: 30%;">💘</span>
        <span style="left: 40%;">💘</span>
        <span style="left: 50%;">💘</span>
        <span style="left: 60%;">💘</span>
        <span style="left: 70%;">💘</span>
        <span style="left: 80%;">💘</span>
        <span style="left: 90%;">💘</span>
        <span style="left: 100%;">💘</span>
    </div>

    <!-- Más corazones subiendo -->
    <div class="more-hearts">
        <span style="left: 5%;">💘</span>
        <span style="left: 15%;">💘</span>
        <span style="left: 25%;">💘</span>
        <span style="left: 35%;">💘</span>
        <span style="left: 45%;">💘</span>
        <span style="left: 55%;">💘</span>
        <span style="left: 65%;">💘</span>
        <span style="left: 75%;">💘</span>
        <span style="left: 85%;">💘</span>
        <span style="left: 95%;">💘</span>
    </div>

    <!-- Contenedor principal -->
    <div class="container">
        <!-- Mensaje de amor -->
        <div class="message">
            ¡Feliz San Valentín, mi amor! 💘
        </div>

        <!-- Corazón flechado animado -->
        <div class="heart">💘</div>

        <!-- Botón para descargar la carta -->
        <a href="Documento A4 carta de amor moderna blanco.pdf" download="carta_flor.pdf">
            <button class="download-button">Para ti</button>
        </a>
    </div>
</body>
</html>
