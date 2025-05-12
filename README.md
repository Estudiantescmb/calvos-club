</head>
<body>
  <form>
    <label>Nombre: <input type="text" name="nombre"></label><br><br>

    <label>Apellido: <input type="text" name="apellido"></label><br><br>

    <label>Edad: <input type="text" name="edad"></label><br><br>

    Sexo:<br>
    <input type="radio" name="sexo" value="mujer"> Mujer<br>
    <input type="radio" name="sexo" value="hombre"> Hombre<br><br>

    <label>Nivel de estudios:
      <select name="nivel_estudios">
        <option value="primaria">primaria</option>
        <option value="secundaria">secundaria</option>
        <option value="preparatoria">preparatoria</option>
        <option value="universidad">universidad</option>
      </select>
    </label><br><br>

    <label>Usuario: <input type="text" name="usuario"></label><br><br>

    <label>Contraseña: <input type="password" name="contrasena"></label><br><br>

    <label>Confirmacion de contraseña: <input type="password" name="confirmacion"></label><br><br>

    <input type="submit" value="enviar">
  </form>
</body>
</html>
