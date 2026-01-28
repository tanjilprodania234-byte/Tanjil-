<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Propose Day</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #ffdde1, #ee9ca7);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .card {
      background: #ffffff;
      max-width: 420px;
      width: 90%;
      padding: 30px 25px;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      text-align: center;
    }
    h1 {
      color: #e63946;
      margin-bottom: 10px;
    }
    p {
      color: #444;
      line-height: 1.6;
      font-size: 16px;
    }
    .heart {
      font-size: 48px;
      margin: 15px 0;
      animation: beat 1.5s infinite;
    }
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.15); }
    }
    button {
      margin-top: 20px;
      padding: 12px 22px;
      border: none;
      border-radius: 25px;
      background: #e63946;
      color: #fff;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #d62839;
    }
    footer {
      margin-top: 20px;
      font-size: 13px;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Happy Propose Day</h1>
    <div class="heart">❤</div>
    <p>
      From the moment I met you, my days became brighter and my smiles became real.
      I just want you to know that you are very special to me.
    </p>
    <p>
      Today, I want to ask you something simple but meaningful.
      Will you be a part of my journey and make life more beautiful together?
    </p>
    <button onclick="alert('No pressure. Just wanted to share my feelings 😊')">
      A Small Question
    </button>
    <footer>
      Made with honesty and respect
    </footer>
  </div>
</body>
</html>
