<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Para Thamy ❤️</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;600&display=swap');

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      overflow: hidden;
      background:
        radial-gradient(circle at center, #250014 0%, #0b0006 65%, #000 100%);
      color: white;
      font-family: 'Poppins', sans-serif;
    }

    /* =========================
       PANTALLA DE ENTRADA
    ========================= */

    #login {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    .login-box {
      position: relative;
      z-index: 10;
      width: 90%;
      max-width: 380px;
      padding: 40px 28px;

      background: rgba(255, 255, 255, 0.06);
      border: 1px solid rgba(255, 105, 180, 0.25);
      border-radius: 30px;

      backdrop-filter: blur(15px);

      box-shadow:
        0 0 40px rgba(255, 20, 120, 0.15),
        inset 0 0 30px rgba(255, 20, 120, 0.03);
    }

    .login-heart {
      font-size: 70px;
      animation: latido 1.5s infinite;
      filter: drop-shadow(0 0 20px #ff4f9a);
    }

    .login-box h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 45px;
      font-weight: normal;
      margin: 15px 0 5px;
      color: #ff8fbd;
    }

    .login-box p {
      color: #ddd;
      font-size: 14px;
      margin-bottom: 25px;
    }

    input {
      width: 100%;
      padding: 15px;
      margin: 7px 0;

      border: 1px solid rgba(255, 105, 180, 0.2);
      border-radius: 15px;
      outline: none;

      background: rgba(255,255,255,0.07);
      color: white;

      text-align: center;
      font-size: 15px;
      font-family: 'Poppins', sans-serif;
    }

    input::placeholder {
      color: #aaa;
    }

    input:focus {
      border-color: #ff65a8;
      box-shadow: 0 0 15px rgba(255, 65, 150, 0.2);
    }

    button {
      width: 100%;
      padding: 15px;
      margin-top: 15px;

      border: none;
      border-radius: 15px;

      background: linear-gradient(
        90deg,
        #d91668,
        #ff4f96,
        #d91668
      );

      color: white;
      font-size: 16px;
      font-weight: 600;

      font-family: 'Poppins', sans-serif;

      cursor: pointer;

      box-shadow: 0 0 20px rgba(255, 50, 140, 0.25);
    }

    button:active {
      transform: scale(0.97);
    }

    #error {
      display: none;
      margin-top: 15px;
      color: #ff7aaa;
      font-size: 13px;
    }


    /* =========================
       SORPRESA
    ========================= */

    #sorpresa {
      display: none;
      height: 100vh;
      position: relative;
      overflow: hidden;

      justify-content: center;
      align-items: center;

      text-align: center;
      padding: 25px;
    }

    /* Fecha gigante de fondo */

    .fecha-fondo {
      position: absolute;
      top: 50%;
      left: 50%;

      transform: translate(-50%, -50%);

      width: 100%;

      font-size: clamp(55px, 15vw, 180px);
      font-weight: 600;

      color: rgba(255, 100, 170, 0.035);

      white-space: nowrap;

      z-index: 0;

      user-select: none;
    }

    /* Contenido */

    .contenido {
      position: relative;
      z-index: 5;

      max-width: 850px;

      animation: aparecer 2.5s ease;
    }

    .dedicatoria {
      font-size: 14px;
      letter-spacing: 5px;
      text-transform: uppercase;

      color: #ff82b5;

      margin-bottom: 20px;
    }

    .titulo {
      font-family: 'Great Vibes', cursive;

      font-size: clamp(55px, 12vw, 100px);

      font-weight: normal;

      color: #ff8fbd;

      text-shadow:
        0 0 10px rgba(255, 70, 150, 0.5),
        0 0 35px rgba(255, 20, 120, 0.25);

      margin: 0 0 25px;
    }

    .mensaje {
      font-size: clamp(15px, 2.2vw, 20px);

      line-height: 1.9;

      color: #f5f5f5;

      font-weight: 300;

      text-shadow: 0 2px 10px black;

      animation: textoAparecer 3s ease;
    }

    .fecha {
      margin-top: 30px;

      font-size: 18px;

      letter-spacing: 7px;

      color: #ff7eb1;

      opacity: 0.8;
    }


    /* =========================
       CORAZONES
    ========================= */

    .corazon {
      position: absolute;

      top: -50px;

      color: #ff4f9a;

      font-size: 20px;

      pointer-events: none;

      z-index: 2;

      animation: caer linear forwards;

      filter:
        drop-shadow(0 0 6px rgba(255, 50, 150, 0.8));
    }

    @keyframes caer {

      0% {
        transform:
          translateY(-50px)
          translateX(0)
          rotate(0deg);

        opacity: 0;
      }

      10% {
        opacity: 0.9;
      }

      50% {
        transform:
          translateY(50vh)
          translateX(40px)
          rotate(180deg);
      }

      100% {
        transform:
          translateY(110vh)
          translateX(-40px)
          rotate(360deg);

        opacity: 0;
      }
    }


    /* =========================
       ANIMACIONES
    ========================= */

    @keyframes latido {

      0%, 100% {
        transform: scale(1);
      }

      50% {
        transform: scale(1.18);
      }
    }

    @keyframes aparecer {

      from {
        opacity: 0;
        transform: translateY(40px) scale(0.95);
      }

      to {
        opacity: 1;
        transform: translateY(0) scale(1);
      }
    }

    @keyframes textoAparecer {

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


  <!-- =========================
       ENTRADA
  ========================= -->

  <div id="login">

    <div class="login-box">

      <div class="login-heart">
        ❤️
      </div>

      <h1>Para alguien especial</h1>

      <p>
        Hay algo que quiero que leas...
      </p>

      <input
        type="text"
        id="usuario"
        placeholder="Usuario"
      >

      <input
        type="password"
        id="password"
        placeholder="Contraseña"
      >

      <button onclick="entrar()">
        Abrir mi sorpresa ❤️
      </button>

      <div id="error">
        Mmm... parece que esos datos no son 👀
      </div>

    </div>

  </div>



  <!-- =========================
       SORPRESA
  ========================= -->

  <div id="sorpresa">

    <div class="fecha-fondo">
      29/06/2024
    </div>


    <div class="contenido">

      <div class="dedicatoria">
        Para ti, Thamy
      </div>

      <h1 class="titulo">
        Thamy ❤️
      </h1>

      <div class="mensaje">

        Te amo desde el primer día en que nos conocimos.
        <br>

        Eres el amor de mi vida y lo supe con el tiempo.
        <br>

        Llevamos 2 años y quiero que sean muchos más
        de historia.
        <br>

        Quiero seguir haciendo historia a tu lado.
        <br>

        Siempre estaré para ti.
        <br>

        Te amo y quiero estar siempre a tu lado,
        hasta el final de mi vida. ❤️

      </div>

      <div class="fecha">
        29 · 06 · 2024
      </div>

    </div>

  </div>



  <script>

    /* =========================
       DATOS DE ENTRADA
    ========================= */

    function entrar() {

      const usuario =
        document.getElementById("usuario").value;

      const password =
        document.getElementById("password").value;


      /*
        USUARIO:
        thamy

        CONTRASEÑA:
        29062024
      */

      if (
        usuario.toLowerCase() === "thamy" &&
        password === "29062024"
      ) {

        document.getElementById("login").style.display =
          "none";

        document.getElementById("sorpresa").style.display =
          "flex";

        comenzarCorazones();

      } else {

        document.getElementById("error").style.display =
          "block";

      }

    }



    /* =========================
       CORAZONES CAYENDO
    ========================= */

    function comenzarCorazones() {

      setInterval(() => {

        const corazon =
          document.createElement("div");

        corazon.className = "corazon";

        const corazones = [
          "♥",
          "♡",
          "❤",
          "💕",
          "💗"
        ];

        corazon.innerHTML =
          corazones[
            Math.floor(
              Math.random() * corazones.length
            )
          ];


        corazon.style.left =
          Math.random() * 100 + "vw";


        corazon.style.fontSize =
          (12 + Math.random() * 28) + "px";


        corazon.style.animationDuration =
          (4 + Math.random() * 5) + "s";


        document
          .getElementById("sorpresa")
          .appendChild(corazon);


        setTimeout(() => {

          corazon.remove();

        }, 10000);


      }, 280);

    }

  </script>

</body>
</html>