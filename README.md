<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Guardar Nombres</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>

  <h2>Ingresa tres nombres</h2>

  <input type="text" id="nombre1" placeholder="Nombre 1">
  <input type="text" id="nombre2" placeholder="Nombre 2">
  <input type="text" id="nombre3" placeholder="Nombre 3">

  <button onclick="guardarNombres()">Guardar</button>
  <button onclick="mostrarNombres()">Mostrar</button>

  <div id="resultado"></div>

  <script src="script.js"></script>
</body>
</html>
