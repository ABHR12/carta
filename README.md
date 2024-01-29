<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carta Motivadora</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 50px;
        }

        #carta {
            max-width: 600px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            animation: aparecer 1s ease-out;
        }

        h1 {
            color: #4A90E2;
        }

        p {
            font-size: 1.2em;
            margin: 20px 0;
            line-height: 1.5;
        }

        button {
            background-color: #4A90E2;
            color: #fff;
            font-size: 1em;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #3461a4;
        }

        @keyframes aparecer {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div id="carta">
        <h1>Querida Futura Licenciada en Psicología,</h1>
        <p>¡Feliz regreso a clases! Este nuevo semestre es una oportunidad para aprender, crecer y alcanzar nuevos logros. Recuerda que cada desafío es una oportunidad para fortalecerte y avanzar hacia tus metas.</p>
        <p>Tu dedicación y pasión por la psicología son inspiradoras. No dudes en enfrentar cada día con confianza y amor por lo que haces. Estoy seguro de que lograrás grandes cosas en tu camino hacia la licenciatura.</p>
        <p>Siempre recuerda que el amor y la dedicación que pones en tu trabajo marcan la diferencia. ¡Estoy emocionado de ver todo lo increíble que lograrás!</p>
        <button onclick="mostrarMensaje()">¡Vamos por ello!</button>
        <p id="mensaje" style="display: none;">Eres increíble y estoy orgulloso de ti amor.</p>
    </div>

    <script>
        function mostrarMensaje() {
            document.getElementById('mensaje').style.display = 'block';
        }
    </script>
</body>
</html>
