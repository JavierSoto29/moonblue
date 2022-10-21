<!DOCTYPE html>
<html lang="es">
   <head>
    <title>Gato Azul Ruso</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;600&family=Pacifico&display=swap" rel="stylesheet">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;600&family=Fredoka+One&family=Orbitron:wght@700&family=Pacifico&display=swap" rel="stylesheet">
    
    <link href="style.css" rel="stylesheet">
   </head>

   <body><h1>Gato Azul Russo</h1>
       <main>  
        <h2>Imagenes de gatos:</h2>
         <!--TODO: Agregar enlace a imagenes de michis-->
        
         <p> Haz click aqui para ver mas <a href="#">imagenes de gatos.</a></p>
         
         <a href="https://es.wikipedia.org/wiki/Azul_ruso"target="_blank" rel="noopener noreferrer"><img src="https://www.dogalize.com/wp-content/uploads/2017/12/cat-1846101_640.jpg" class="bordes-redondeados" alt="Un lindo gato azul Ruso."></a>
         
         <hr>
         <h3>Listas de Gatos</h3>

         <div>
          <p>Cosas que los gatos <strong><em>aman:</em></strong></p>
          <!--ul / Unordered List-->

          <ul class="lista-de-gatos">
            <li>Menta gatuna</li>
            <li><s>Apuntadores</s></li>
            <li>Lasagna</li>
          </ul>
          <img src="imagenes/Nepeta.jpg" class="bordes-redondeados" alt="Nepeta">
          <img src="imagenes/Gato Laser.jpg" class="bordes-redondeados" alt="Láser">
          <img src="imagenes/lasana.jpg" class="bordes-redondeados" alt="Lasaña">
         
          <hr>
          <p>Cosas que los gatos <strong>odian:</strong></p>
          <ol class="lista-de-gatos">
            <li>Tratamientos antipulgas</li>
            <li>Truenos</li>
            <li>Otros gatos</li>
          </ol>
                   <img src="imagenes/Gatos.jpg"alt="Otros gatos">
         </div>
         <form action="/enviar-respuesta">
            
            <!--Botones de Radio-->
            <label for="interior">
               <input id="interior" type="radio" value="interior" name="interior-exterior" checked>Interior</label><br>

            <label for="exterior"><input id="exterior" type="radio" value="exterior" name="interior-exterior">Exterior</label><br><br>

            <!--Casillas de Verificación-->
            <label for="jugueton">
               <input id="jugueton" type="checkbox" name="personalidad" checked>Jugueton
            </label><br>
            <label for="peresoso">
               <input id="peresoso" type="checkbox" name="personalidad">Peresoso 
            </label><br>
            <label for="ariscopez">
               <input id="ariscopez" type="checkbox" name="personalidad">AriscoPez

            <!--Texto y Botón Enviar-->
            <input type="text" placeholder="URL de la foto de tu gato" required>
            <button type="submit">Enviar</button>





         </form>
       </main>
       <footer>
         <z> <small> Todos los derechos reservados - <a href="https://www.youtube.com/channel/UC4BbxNXiFpbBnuWsFhDcSJQ/videos"target="_blank" rel="noopener noreferrer">Luzyciencia.org</a></small></z>
       </footer>
    </body>
</html>
