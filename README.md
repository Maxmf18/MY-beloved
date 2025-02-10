# MY-beloved
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botón de Halago</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            font-family: Arial, sans-serif;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
        }
        #mensaje {
            margin-top: 20px;
            font-size: 24px;
            font-weight: bold;
            color: #e91e63;
            display: none;
        }
        img {
            margin-top: 20px;
            width: 300px;
            border-radius: 10px;
        }
        .heart {
            font-size: 50px;
            color: red;
            display: none;
        }
    </style>
</head>
<body>
    <button onclick="mostrarMensaje()">Pulsa el botón</button>
    <div id="mensaje">¡ESTÁS HERMOS@! ❤️</div>
    <div class="heart" id="corazon">❤️</div>
    <img id="imagen" src="WhatsApp Image 2025-02-06 at 09.44.54 (1).jpeg" alt="Imagen de halago" style="display: none;">

    <script>
        function mostrarMensaje() {
            document.getElementById('mensaje').style.display = 'block';
            document.getElementById('imagen').style.display = 'block';
            document.getElementById('corazon').style.display = 'block';
        }
    </script>
</body>
</html>
