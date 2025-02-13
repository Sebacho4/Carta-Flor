<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carta de Amor</title>
    <style>
        /* Estilos generales */
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            font-family: "Indie Flower", cursive;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        /* Contenedor principal */
        .container {
            text-align: center;
            position: relative;
        }

        /* Estilo para el mensaje */
        .message {
            font-size: 40px;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            margin-bottom: 20px;
        }

        /* Estilo para el girasol */
        .sunflower {
            font-size: 100px;
            animation: float 3s ease-in-out infinite;
        }

        /* Animación para el girasol */
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
    </style>
    <!-- Enlace a la fuente de Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Contenedor principal -->
    <div class="container">
        <!-- Mensaje de amor -->
        <div class="message">
            ¡Hola mi amor! 🌻<br>
            Eres mi luz y mi inspiración.
        </div>

        <!-- Girasol animado -->
        <div class="sunflower">🌻</div>

        <!-- Botón para descargar la carta -->
        <a href="Documento A4 carta de amor moderna blanco.pdf" download="Carta_de_Amor_Moderna.pdf">
            <button class="download-button">Descargar Carta</button>
        </a>
    </div>
</body>
</html>
