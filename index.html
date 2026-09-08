<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

  <meta
    name="viewport"
    content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no"
  >

  <title>AURIONS UNLEASHED</title>

  <style>

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      touch-action: none;
    }

    body {
      overflow: hidden;
      background: #020b12;
      font-family: Arial, Helvetica, sans-serif;
      color: white;
    }

    /* =========================
       MAIN GAME WORLD
       ========================= */

    #game {
      position: relative;
      width: 100vw;
      height: 100vh;
      overflow: hidden;

      background:
        radial-gradient(
          circle at 50% 20%,
          rgba(38, 132, 155, 0.65),
          transparent 35%
        ),

        linear-gradient(
          to bottom,
          #082d3c 0%,
          #064052 35%,
          #032633 70%,
          #01151e 100%
        );
    }

    /* =========================
       GAME TITLE
       ========================= */

    #title {
      position: absolute;

      top: 22px;
      left: 0;
      width: 100%;

      text-align: center;

      font-size: clamp(25px, 7vw, 42px);
      font-weight: 900;

      letter-spacing: 4px;

      color: #d9fbff;

      text-shadow:
        0 2px 0 #17495c,
        0 5px 12px rgba(0, 0, 0, 0.7),
        0 0 10px rgba(105, 238, 255, 0.9),
        0 0 25px rgba(55, 206, 255, 0.65);

      animation: titleGlow 3s ease-in-out infinite;
    }

    @keyframes titleGlow {

      0%, 100% {
        transform: scale(1);
        text-shadow:
          0 2px 0 #17495c,
          0 5px 12px rgba(0, 0, 0, 0.7),
          0 0 10px rgba(105, 238, 255, 0.9),
          0 0 25px rgba(55, 206, 255, 0.65);
      }

      50% {
        transform: scale(1.025);
        text-shadow:
          0 2px 0 #17495c,
          0 5px 12px rgba(0, 0, 0, 0.7),
          0 0 18px rgba(145, 248, 255, 1),
          0 0 40px rgba(55, 206, 255, 0.9);
      }

    }

    /* =========================
       PLAYER
       ========================= */

    #player {
      position: absolute;

      width: 48px;
      height: 48px;

      left: 50%;
      bottom: 145px;

      transform: translateX(-50%);

      border-radius: 50%;

      background:
        radial-gradient(
          circle at 32% 25%,
          #ffffff 0%,
          #b9f7ff 15%,
          #54dff7 35%,
          #1686b0 65%,
          #062f43 100%
        );

      border: 2px solid rgba(190, 250, 255, 0.8);

      box-shadow:
        0 0 10px rgba(116, 239, 255, 0.9),
        0 0 25px rgba(54, 205, 255, 0.75),
        0 0 45px rgba(31, 154, 207, 0.45);

      z-index: 10;

      transition: transform 0.08s linear;
    }

    /* Aura around player */

    #player::before {

      content: "";

      position: absolute;

      width: 70px;
      height: 70px;

      left: 50%;
      top: 50%;

      transform: translate(-50%, -50%);

      border-radius: 50%;

      border: 1px solid rgba(117, 239, 255, 0.45);

      box-shadow:
        0 0 15px rgba(83, 226, 255, 0.5),
        inset 0 0 15px rgba(83, 226, 255, 0.25);

      animation: auraPulse 2s ease-in-out infinite;

      pointer-events: none;
    }

    @keyframes auraPulse {

      0%, 100% {
        transform: translate(-50%, -50%) scale(0.85);
        opacity: 0.35;
      }

      50% {
        transform: translate(-50%, -50%) scale(1.15);
        opacity: 0.8;
      }

    }

    /* =========================
       INFORMATION HUD
       ========================= */

    #info {

      position: absolute;

      top: 82px;
      left: 18px;

      padding: 9px 13px;

      border-radius: 12px;

      background: rgba(0, 12, 20, 0.45);

      border: 1px solid rgba(167, 241, 255, 0.2);

      backdrop-filter: blur(5px);

      font-size: 15px;

      z-index: 20;
    }

    #score {
      font-weight: bold;
      color: #aaf4ff;
    }

    /* =========================
       JOYSTICK
       ========================= */

    #joystick {

      position: absolute;

      left: 25px;
      bottom: 28px;

      width: 115px;
      height: 115px;

      border-radius: 50%;

      border: 2px solid rgba(210, 250, 255, 0.3);

      background:
        radial-gradient(
          circle,
          rgba(130, 235, 255, 0.14),
          rgba(255, 255, 255, 0.03)
        );

      box-shadow:
        inset 0 0 20px rgba(80, 220, 255, 0.08),
        0 0 15px rgba(40, 190, 220, 0.15);

      z-index: 30;
    }

    #stick {

      position: absolute;

      width: 52px;
      height: 52px;

      left: 29px;
      top: 29px;

      border-radius: 50%;

      background:
        radial-gradient(
          circle at 35% 30%,
          #dfffff,
          #73e8ff 35%,
          #229fc4 80%
        );

      border: 2px solid rgba(220, 253, 255, 0.55);

      box-shadow:
        0 0 15px rgba(85, 225, 255, 0.8),
        0 0 30px rgba(50, 190, 230, 0.4);

      z-index: 31;
    }

    /* =========================
       BUBBLES
       ========================= */

    .bubble {

      position: absolute;

      bottom: -30px;

      width: 8px;
      height: 8px;

      border-radius: 50%;

      border: 1px solid rgba(220, 250, 255, 0.55);

      background: rgba(190, 245, 255, 0.06);

      animation: bubbleRise linear infinite;

      pointer-events: none;
    }

    @keyframes bubbleRise {

      0% {
        transform: translateY(0) translateX(0);
        opacity: 0;
      }

      15% {
        opacity: 0.7;
      }

      50% {
        transform: translateY(-50vh) translateX(20px);
      }

      100% {
        transform: translateY(-115vh) translateX(-20px);
        opacity: 0;
      }

    }

    /* Different bubble sizes and positions */

    .b1 {
      left: 8%;
      width: 7px;
      height: 7px;
      animation-duration: 7s;
    }

    .b2 {
      left: 22%;
      width: 11px;
      height: 11px;
      animation-duration: 9s;
      animation-delay: 2s;
    }

    .b3 {
      left: 42%;
      width: 6px;
      height: 6px;
      animation-duration: 6s;
      animation-delay: 1s;
    }

    .b4 {
      left: 63%;
      width: 13px;
      height: 13px;
      animation-duration: 10s;
      animation-delay: 3s;
    }

    .b5 {
      left: 82%;
      width: 8px;
      height: 8px;
      animation-duration: 8s;
      animation-delay: 1.5s;
    }

    /* =========================
       LIGHT RAYS
       ========================= */

    .light-ray {

      position: absolute;

      top: -20%;

      width: 120px;
      height: 140%;

      background: linear-gradient(
        to bottom,
        rgba(180, 250, 255, 0.08),
        rgba(180, 250, 255, 0)
      );

      transform: rotate(12deg);

      filter: blur(8px);

      pointer-events: none;
    }

    .ray1 {
      left: 12%;
    }

    .ray2 {
      left: 55%;
      transform: rotate(-9deg);
    }

    /* =========================
       JAVASCRIPT-GENERATED
       ========================= */

    .particle {

      position: absolute;

      width: 3px;
      height: 3px;

      border-radius: 50%;

      background: rgba(190, 250, 255, 0.5);

      animation: particleFloat 5s linear infinite;

      pointer-events: none;
    }

    @keyframes particleFloat {

      from {
        transform: translateY(0);
        opacity: 0;
      }

      20% {
        opacity: 0.7;
      }

      to {
        transform: translateY(-100vh);
        opacity: 0;
      }

    }

  </style>
</head>

<body>

  <div id="game">

    <!-- Atmospheric light -->

    <div class="light-ray ray1"></div>
    <div class="light-ray ray2"></div>

    <!-- Game title -->

    <div id="title">
      AURIONS UNLEASHED
    </div>

    <!-- Game information -->

    <div id="info">
      ⭐ Score:
      <span id="score">0</span>
    </div>

    <!-- Player -->

    <div id="player"></div>

    <!-- Virtual joystick -->

    <div id="joystick">
      <div id="stick"></div>
    </div>

    <!-- Bubbles -->

    <div class="bubble b1"></div>
    <div class="bubble b2"></div>
    <div class="bubble b3"></div>
    <div class="bubble b4"></div>
    <div class="bubble b5"></div>

  </div>


  <script>

    /* =================================
       GAME STATE
       ================================= */

    let score = 0;

    let playerX = window.innerWidth / 2;
    let playerY = window.innerHeight - 145;

    const player = document.getElementById("player");
    const scoreDisplay = document.getElementById("score");

    /* =================================
       PLAYER POSITION
       ================================= */

    function updatePlayer() {

      player.style.left = playerX + "px";

      player.style.top = playerY + "px";

    }

    updatePlayer();


    /* =================================
       CREATE ATMOSPHERIC PARTICLES
       ================================= */

    function createParticles() {

      for (let i = 0; i < 30; i++) {

        const particle = document.createElement("div");

        particle.className = "particle";

        particle.style.left =
          Math.random() * 100 + "%";

        particle.style.top =
          Math.random() * 100 + "%";

        particle.style.animationDuration =
          (4 + Math.random() * 6) + "s";

        particle.style.animationDelay =
          Math.random() * 5 + "s";

        document
          .getElementById("game")
          .appendChild(particle);
      }
    }

    createParticles();


    /* =================================
       GAME LOOP
       ================================= */

    function gameLoop() {

      updatePlayer();

      requestAnimationFrame(gameLoop);

    }

    gameLoop();


    /* =================================
       SCREEN RESIZE
       ================================= */

    window.addEventListener("resize", () => {

      playerX =
        Math.min(playerX, window.innerWidth - 25);

      playerY =
        Math.min(playerY, window.innerHeight - 25);

      updatePlayer();

    });

  </script>

</body>
</html>
