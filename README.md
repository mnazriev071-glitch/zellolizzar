<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Экзотические куртки из кожи</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      margin: 0; padding: 0;
      color: #333;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-weight: 400;
    }
    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }
    .cards {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .card {
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px #ccc;
      width: 280px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-body {
      padding: 15px;
      flex-grow: 1;
    }
    .card-title {
      font-size: 1.2em;
      margin: 0 0 10px;
      font-weight: bold;
      color: #111;
    }
    .card-text {
      font-size: 0.9em;
      margin-bottom: 15px;
      color: #555;
      line-height: 1.3;
    }
    .btn-contact {
      background-color: #25D366;
      color: white;
      text-decoration: none;
      padding: 12px 20px;
      text-align: center;
      border-radius: 5px;
      font-weight: bold;
      display: block;
      margin: 0 15px 15px 15px;
      transition: background-color 0.3s ease;
    }
    .btn-contact:hover {
      background-color: #1ebe57;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.8em;
      color: #777;
      border-top: 1px solid #ddd;
      margin-top: 40px;
    }
    @media(max-width: 600px) {
      .cards {
        flex-direction: column;
        align-items: center;
      }
      .card {
        width: 90%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Экзотические куртки из кожи</h1>
    <p>Крокодил, Питон, Страус — роскошь и стиль</p>
  </header>
  <div class="container">
    <div class="cards">

      <div class="card">
        <img src="https://cdn.reggenza.co/media/wysiwyg/biker-jacket-crocodile-leather_1.jpg" alt="Кожаная куртка из крокодила" />
        <div class="card-body">
          <h2 class="card-title">Кожаная куртка из крокодила</h2>
          <p class="card-text">Роскошная куртка из натуральной кожи крокодила. Эксклюзивный дизайн, идеальна для стильных и смелых.</p>
          <a href="https://wa.me/1234567890" target="_blank" class="btn-contact">Связаться в WhatsApp</a>
        </div>
      </div>

      <div class="card">
        <img src="https://cdn.reggenza.co/media/wysiwyg/snake-skin-jacket_1.jpg" alt="Кожаная куртка из питона" />
        <div class="card-body">
          <h2 class="card-title">Кожаная куртка из питона</h2>
          <p class="card-text">Экзотическая куртка из кожи питона. Уникальный узор и долговечность, выделись из толпы.</p>
          <a href="https://wa.me/1234567890" target="_blank" class="btn-contact">Связаться в WhatsApp</a>
        </div>
      </div>

      <div class="card">
        <img src="https://cdn.reggenza.co/media/wysiwyg/ostrich-leather-jacket_1.jpg" alt="Кожаная куртка из страуса" />
        <div class="card-body">
          <h2 class="card-title">Кожаная куртка из страуса</h2>
          <p class="card-text">Стильная куртка из кожи страуса. Легкая и прочная, с уникальной текстурой и шикарным видом.</p>
          <a href="https://wa.me/1234567890" target="_blank" class="btn-contact">Связаться в WhatsApp</a>
        </div>
      </div>

    </div>
  </div>

  <footer>
    &copy; 2025 Экзотические куртки. Все права защищены.
  </footer>
</body>
</html>
