<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feliz Aniversário Feh</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(to bottom, #d52d00, #ef7627, #ff9a56, #f9f9f9, #d162a4, #b55690, #a30262);
      font-family: 'Comic Sans MS', cursive, sans-serif;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      padding: 20px;
      gap: 20px;
      min-height: 100vh;
    }

    h1 {
      font-family: 'Pacifico', cursive;
      font-size: 3em;
      text-align: center;
      color: #800080;
      margin-bottom: 30px;
      text-shadow: -1px -1px 0 #fff, 1px -1px 0 #fff, -1px 1px 0 #fff, 1px 1px 0 #fff;
    }

    .main-content {
      display: flex;
      gap: 20px;
    }

    .menu {
      background-color: #ffffff;
      border-radius: 20px;
      padding: 20px;
      color: #800080;
    }

    .container {
      background-color: #ffffff;
      border: 2px solid #800080;
      border-radius: 20px;
      padding: 20px;
      width: 90%;
      max-width: 500px;
      display: flex;
      flex-direction: column;
      gap: 20px;
      box-shadow: 0 0 15px #cba2d3;
      color: #800080;
    }

    .item {
      background-color: #ffffff;
      border-radius: 15px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 0 10px #e6b0c8;
    }

    .item a {
      text-decoration: none;
      color: #d94f91;
      font-weight: bold;
    }

    .photo-banner {
      width: 250px;
      max-height: 100vh;
      position: sticky;
      top: 20px;
      border-radius: 20px;
      box-shadow: 0 0 15px #d184a3;
      object-fit: cover;
    }

    .qr-code {
      margin-top: 10px;
      display: flex;
      justify-content: center;
    }

    .qr-code img {
      width: 120px;
      height: 120px;
      border-radius: 10px;
      box-shadow: 0 0 8px #c79ec0;
    }
  </style>
</head>
<body>
  <div class="main-content">
    <img src="birtiday bunitin feh.jpg" alt="Foto da Feh" class="photo-banner">

    <div class="menu">
      <h1>Feliz aniversário Feh<3</h1>

      <div class="container">
        <div class="item">
          <p>📄 Clique aqui para abrir nossa cartinha:D!</p>
          <a href="Feh book.pdf" target="_blank">Ler Cartinha</a>
        </div>

        <div class="item">
          <p>🎶 Ouça a playlist que fizemos pra você <3!</p>
          <div class="qr-code">
            <img src="qrcode.jpg" alt="QR Code da Playlist Spotify">
          </div>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
