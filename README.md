<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>I'm Sorry</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #ff9a9e, #fad0c4);
      font-family: 'Open Sans', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      color: #fff;
      overflow: hidden;
    }
    .card {
      background: rgba(255, 255, 255, 0.15);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
      text-align: center;
      max-width: 700px;
      animation: fadeIn 2s ease-out;
      backdrop-filter: blur(12px);
    }
    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      margin-bottom: 10px;
      animation: slideDown 1s ease-out;
    }
    p {
      font-size: 1.3em;
      line-height: 1.8;
      margin-top: 20px;
      animation: fadeIn 2.5s ease-out;
    }
    footer {
      margin-top: 40px;
      font-size: 1em;
      opacity: 0.8;
      animation: fadeIn 3s ease-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>I'm Truly Sorry</h1>
    <p>
      I never intended to hurt you, and I carry a deep sense of regret for the pain I’ve caused.<br>
      You matter to me more than words can express.<br>
      Whenever youre good id love to talk to you irl just even once. i deserve a chance perhaps
    </p>
    <footer>With all my heart — please forgive me brother</footer>
  </div>
</body>
</html>
