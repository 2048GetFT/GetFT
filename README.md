
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>GetFT!</title>

  <link href="style/main.css" rel="stylesheet" type="text/css">
  <link rel="shortcut icon" href="favicon.ico">
  <link rel="apple-touch-icon" href="meta/apple-touch-icon.png">
  <meta name="apple-mobile-web-app-capable" content="yes">

  <meta name="HandheldFriendly" content="True">
  <meta name="MobileOptimized" content="320">
  <meta name="viewport" content="width=device-width, target-densitydpi=160dpi, initial-scale=1.0, maximum-scale=1, user-scalable=no, minimal-ui">
</head>
<body>

  <div class="container">
    <div class="heading">
      <h1 class="title">GetFT</h1>
      <div class="scores-container">
        <div class="score-container">0</div>
        <div class="best-container">0</div>
      </div>
    </div>
    <p class="game-intro">Veja quantas faculdades da Unicamp são necessárias para atingir a tão <span onclick="document.body.style.background='url(img/petey.jpeg)';">desejada <strong>Faculdade de Tecnologia!</strong></span></p>

    <div class="game-container">
      <div class="game-message">
        <p></p>
        <div class="lower">
	        <a class="keep-playing-button">Siga jogando</a>
          <a class="retry-button">Tente novamente</a>
        </div>
      </div>

      <div class="grid-container">
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
      </div>

      <div class="tile-container">

      </div>
    </div>

    <p class="game-explanation">
      <strong class="important">Como jogar:</strong> Use as <strong>setas</strong> para mover as figuras. Quando duas figuras da mesma faculdade se tocam, elas se <strong>combinam em uma só!</strong>
      <br><strong class="important">Nota:</strong> A ordem das faculdades não indica algum ranking, mas fique à vontade para entender como quiser.
    </p>
    <hr>
    <p>
    Criado por <a href="https://www.ft.unicamp.br/pt-br/noticias/engenharia-de-telecomunica%C3%A7%C3%B5es-escolhido-como-o-melhor-curso-p%C3%BAblico-no-pa%C3%ADs-pelo-guia-da#:~:text=O%20curso%20de%20Engenharia%20de,pelo%20Guia%20da%20Faculdade%202020.">Telecom bom bom</a>.
    </p>
    <hr>
    <p>
    Inspired by <a href="https://mitchgu.github.io/GetMIT/">GetMIT by Mitchell Gu</a>.
    </p>
  </div>

  <script src="js/animframe_polyfill.js"></script>
  <script src="js/keyboard_input_manager.js"></script>
  <script src="js/html_actuator.js"></script>
  <script src="js/grid.js"></script>
  <script src="js/tile.js"></script>
  <script src="js/local_score_manager.js"></script>
  <script src="js/game_manager.js"></script>
  <script src="js/application.js"></script>
</body>
</html>
