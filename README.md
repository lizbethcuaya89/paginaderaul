# paginaderaul
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .nav {
            display: flex;
            justify-content: flex-end;
            background-color: #222;
            padding: 15px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .container {
            display: flex;
            padding: 20px;
        }
        .column {
            flex: 1;
            padding: 20px;
            border: 1px solid white;
        }
    </style>
</head>
<body>
    <nav class="nav">
        <a href="#">Inicio</a>
        <a href="#">Servicios</a>
        <a href="#">Acerca de</a>
        <a href="#">Contacto</a>
    </nav>

    <div class="container">
        <div class="column">
            <h2>Columna 1</h2>
            <p>Contenido de la primera columna.</p>
        </div>
        <div class="column">
            <h2>Columna 2</h2>
            <p>Contenido de la segunda columna.</p>
        </div>
    </div>
</body>
</html>
