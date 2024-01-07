<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <DE ALEXITO>¿PARA EL AMOR DE MI VIDA </MI NIÑA>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f3f3f3;
      font-family: Arial, sans-serif;
    }
    #container {
      text-align: center; 
    }
    h1 {
      font-size: 32px;
      color: #333;
    }
    #buttons {
      margin-top: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    button {
      margin: 10px;
      padding: 10px 20px;
      font-size: 18px;
      color: #fff;
      background-color: #4CAF50;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #45a049;
    }
    #btnNo {
      background-color: #f44336;
    }
    #btnNo:hover {
      background-color: #d32f2f;
    }
    img {
      margin-top: 30px;
      max-width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
  </style>
  <script>
    function CARTA CUANDO LA LEA() {
      alert("¡Nunca me imaginé estar enamorado y mucho menos escribiendo cartas ni mensajes románticos, pero ha cambiado tanto dentro de mí, que ahora parezco un hombre nuevo; y es que eso hace el amor cuando es puro y sincero, cambia a las personas y las hace mucho mejores de lo que un día creyeron poder ser.

Hoy, tengo la suerte de decir que estoy enamorado y que me siento muy afortunado por tenerte a mi lado, pues contigo he sentido algo que jamás me había ocurrido, y ahora me encuentro escribiendo este texto, lleno de romance y de amor eterno.

Gracias por ser mi motivo para ser mejor y para abrirle al amor las puertas de mi corazón.

Te amo.");
    }

    function mueveElBoton() {
      const width = window.innerWidth;
      const height = window.innerHeight;

      const newWidth = Math.random() * width;
      const newHeight = Math.random() * height;

      const btnNo = document.getElementById("btnNo");
      btnNo.style.position = "absolute";
      btnNo.style.left = newWidth + "px";
      btnNo.style.top = newHeight + "px";
    }
  </script>
</head>
<body>
    <div id="container">
      <h1>¿QUIERES TENER UN FUTURO CONMIGO?</h1>
      <div id="buttons">
        <button onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi">Sí</button>
        <button id="btnNo" onmouseover="mueveElBoton()">NO</button>
      </div>
      <img src="img/2.jpeg" alt="" width="200">
    </div>
  
    <script>
      function accionParaCuandoEllaDigaQueSi() {
        const respuesta = confirm("¿Estás segura de querer pasar una vida conmigo?");
        if (respuesta) {
          // Redireccionar a la nueva página si responde "Sí"
          window.location.href = "opcionsi.html";
        } else {
          alert("Espero que puedas reconsiderarlo 😊");
        }
      }
  
      function mueveElBoton() {
        const width = window.innerWidth;
        const height = window.innerHeight;
  
        const newWidth = Math.random() * width;
        const newHeight = Math.random() * height;
  
        const btnNo = document.getElementById("btnNo");
        btnNo.style.position = "absolute";
        btnNo.style.left = newWidth + "px";
        btnNo.style.top = newHeight + "px";
      }
    </script>
  </body>
  </html>
