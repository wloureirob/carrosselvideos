<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Carrossel de Vídeos</title>
  <style>
    body {
      font-family: sans-serif;
      padding: 20px;
      background: #f0f0f0;
    }
    .carousel {
      display: flex;
      overflow-x: auto;
      gap: 20px;
      scroll-snap-type: x mandatory;
      -webkit-overflow-scrolling: touch;
    }
    .carousel iframe {
      flex: 0 0 auto;
      width: 300px;
      height: 180px;
      scroll-snap-align: center;
      border: none;
    }
  </style>
</head>
<body>
  <h1>Bem-vindo ao carrossel de vídeos!</h1>
  <p>Abaixo estão os vídeos do nosso módulo. Assista na ordem e anote os pontos principais.</p>

  <div class="carousel">
    <iframe src="https://www.youtube.com/embed/9THIw3wP7d4" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/aOFPZ7cfiTE" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/3aRkbKiL70Q" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/O37lD0-1OZk" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/iKTZEpxljoo" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/POJHqPjLnnY" allowfullscreen></iframe>
  </div>

  <p>Depois de assistir, acesse o fórum da turma para compartilhar suas reflexões.</p>
</body>
</html>

