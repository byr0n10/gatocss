<html lang="es">
  <head>
    <title>AppDeGatos</title>
    <style>
     <style>
      /* Modificar el color del fondo del body */
      body {
     
        font-family: Arial, sans-serif;
      }

      /* Modificar el color del texto de los encabezados */
      h1, h2, h3, h4, h5, h6 {
        color: #8E44AD;
      }

      /* Agregar un borde a las imágenes */
      img {
        border: 3px solid #8E44AD;
        border-radius: 10px;
        box-shadow: 5px 5px 5px #ccc;
      }

      /* Modificar el tamaño del texto de los enlaces */
      a {
        font-size: 18px;
        color: #8E44AD;
        text-decoration: none;
      }

      /* Cambiar el color de los enlaces al pasar el mouse sobre ellos */
      a:hover {
        color: #FFF;
        background-color: #8E44AD;
      }

      /* Estilos para las listas de gatos */
      ul, ol {
        margin-left: 30px;
      }

      ul li {
        list-style-image: url('https://image.flaticon.com/icons/png/128/2109/2109140.png');
        margin: 5px 0;
      }

      ol li {
        list-style-type: decimal;
        margin: 5px 0;
      }

      /* Estilos para el formulario */
      form {
        margin: 20px auto;
        width: 60%;
        padding: 20px;
        background-color: #FFF;
        border-radius: 10px;
        box-shadow: 5px 5px 5px #ccc;
      }

      label {
        display: block;
        margin: 10px 0;
      }

      input[type="text"] {
        width: 100%;
        padding: 10px;
        border-radius: 5px;
        border: 1px solid #ccc;
        box-sizing: border-box;
        font-size: 16px;
        margin: 10px 0;
      }

      button[type="submit"], button[type="reset"] {
        background-color: #8E44AD;
        color: #FFF;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        font-size: 16px;
        cursor: pointer;
        margin: 10px 5px;
      }

      button[type="submit"]:hover, button[type="reset"]:hover {
        background-color: #FFF;
        color: #8E44AD;
        border: 1px solid #8E44AD;
      }
      </style>
    <link href="style.css" rel="stylesheet">
  </head>
  <body  background="jj.gif">
    <center><h2>AppDeGatos</h2></center>
    <main>
      <h1>Imágenes de Gatos:</h1>
      <!-- TODO: Agregar enlace a imágenes de gatos -->
      <p>Haz click aquí para ver más <a href="https://unsplash.com/es/images/animals/kitten" target="_blank" rel="noopener noreferrer">imágenes de gatos.</a></p>

      <a href="#" target="_blank" rel="noopener noreferrer"><img src="https://bit.ly/fcc-relaxing-cat" alt="Un lindo gato naranja recostado sobre su espalda."></a>

      <hr color="black">

      <h3>Listas de Gatos</h3>

      <div>
        <h6><p>Cosas que los gatos aman:</p><h6></h6>
        <ul>
          <li>Menta gatuna</li>
          <li>Apuntadores Láser</li>
          <li><s>Lasaña</s></li>
        </ul>
        <img src="https://i.pinimg.com/736x/6c/ea/10/6cea10d5c69931deabf891a3c6ec7821.jpg" width="300" height="200" alt="Lasaña">
        <h6><p>Cosas que los gatos <strong>odian</strong>:</p></h6>
        <ol>
          <li>Tratamientos antipulgas</li>
          <li>Truenos</li>
          <li>Otros gatos</li>
        </ol>
      </div>
      <img src="https://i.pinimg.com/736x/b5/e4/73/b5e473a80d8e350c2487ad30f3aae27b.jpg" width="300" height="200" alt="Gatos">

      <form action="/enviar-respuesta">
        <!-- Botones de Radio -->
        <label for="interior">
          <input id="interior" type="radio" value="interior" name="interior-exterior">Interior
        </label>
        <br>
        <label for="exterior">
          <input id="exterior" type="radio" value="exterior" name="interior-exterior">Exterior
        </label>
        <br>
        <main class="main">
            <div class="card">
        <h2>Ingrese su nombre</h2>
        <input type="text" placeholder="Ingrese su nombre"></label>
        <h2>Ingrese su apellido</h2>
            </div>
        <input type="text" placeholder="Ingrese su apellido"></label>
        <form action="/uno/juan.txt">
          <h3>¿Como es ser un  gato?</h3>
          <input type="checkbox">Amoroso
          <input type="checkbox">Peresoso
          <input type="checkbox">Amargado
        <br>
        
        <input type="text" placeholder="URL de la foto de su gato" required><br>
        <button type="submit">Enviar</button>
        <button type="reset">Limpiar</button>
      </form>
    </main>
    <br>
    <footer>
      <p><small>Sin Derechos de Autor - <a href="https://www.freecodecamp.org/espanol/">freeCodeCamp.org</a></small></p>
    </footer>
  </body>
</html>
