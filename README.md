<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SkillMint Pro</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: #fff;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    header {
      padding: 20px;
      background: rgba(0,0,0,0.2);
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 1px;
    }
    .container {
      margin-top: 40px;
      padding: 20px;
    }
    .card {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      padding: 20px;
      margin: 15px auto;
      width: 90%;
      max-width: 350px;
      transition: 0.3s;
    }
    .card:hover {
      background: rgba(255,255,255,0.2);
      transform: scale(1.03);
    }
    button {
      background: #fff;
      color: #2575fc;
      border: none;
      padding: 10px 18px;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 10px;
      font-weight: 600;
      transition: 0.3s;
    }
    button:hover {
      background: #2575fc;
      color: #fff;
    }
    footer {
      margin-top: 40px;
      padding: 15px;
      font-size: 13px;
      opacity: 0.8;
    }
  </style>
</head>
<body>
  <header>🎓 SkillMint Pro</header>
  
  <div class="container">
    <div class="card">
      <h2>📚 Daily Quiz</h2>
      <p>Test your knowledge & earn coins!</p>
      <button onclick="alert('Coming Soon!')">Start Quiz</button>
    </div>

    <div class="card">
      <h2>🏆 Leaderboard</h2>
      <p>Compete with others & climb ranks.</p>
      <button onclick="alert('Leaderboard launching soon!')">View</button>
    </div>

    <div class="card">
      <h2>💰 Redeem Rewards</h2>
      <p>Convert your points into rewards.</p>
      <button onclick="alert('Redeem system coming soon!')">Redeem</button>
    </div>

    <div class="card">
      <h2>👥 Invite Friends</h2>
      <p>Invite & earn bonus coins.</p>
      <button onclick="alert('Share feature launching soon!')">Invite</button>
    </div>
  </div>

  <footer>Made with ❤️ by Jaheen</footer>
</body>
</html>
