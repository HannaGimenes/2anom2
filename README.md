<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Alura MIDI</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;600&display=swap" rel="stylesheet">

    <link rel="icon" type="image/png" href="images/bateria.png">
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/estilos.css">

</head>

<body>

   <h1>DJ Freitas</h1>

   <section class="teclado">
      <button class="tecla tecla_pom">
            <span class="tecla_title">Pom</span>
            <span class="tecla_number">7</span>
        </button>

  <button class="tecla tecla_clap">
            <span class="tecla_title">Clap</span>
            <span class="tecla_number">8</span>
  </button>     
 <button class="tecla tecla_tim">
          <span class="tecla_title">Tim</span>
            <span class="tecla_number">9</span>
        </button>
       <button class="tecla tecla_puff">
            <span class="tecla_title">Puff</span>
            <span class="tecla_number">4</span>
        </button>
        <button class="tecla tecla_splash">
            <span class="tecla_title">Splash</span>
            <span class="tecla_number">5</span>
        </button>
        <button class="tecla tecla_toim">
            <span class="tecla_title">Toim</span>
            <span class="tecla_number">6</span>
        </button>
        <button class="tecla tecla_psh">
            <span class="tecla_title">Psh</span>
            <span class="tecla_number">1</span>
        </button>
        <button class="tecla tecla_tic">
            <span class="tecla_title">Tic</span>
            <span class="tecla_number">2</span>
        </button>
        <button class="tecla tecla_tom">
            <span class="tecla_title">Tom</span>
            <span class="tecla_number">3</span>
        </button>
    </section
    <audio src="sounds/keyq.wav" id="som_tecla_pom"></audio>
    <audio src="sounds/keyw.wav" id="som_tecla_clap"></audio>
    <audio src="sounds/keye.wav" id="som_tecla_tim"></audio>
    <audio src="sounds/keya.wav" id="som_tecla_puff"></audio>
    <audio src="sounds/keys.wav" id="som_tecla_splash"></audio>
    <audio src="sounds/keyd.wav" id="som_tecla_toim"></audio>
    <audio src="sounds/keyz.wav" id="som_tecla_psh"></audio>
    <audio src="sounds/keyx.wav" id="som_tecla_tic"></audio>
    <audio src="sounds/keyc.wav" id="som_tecla_tom"></audio>

    <script src="main.js"></script>
</body>

</html>
