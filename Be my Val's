<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>To My ❤️ [Tominia]</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
      color: #333;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
    }

    .container {
      text-align: center;
      padding: 30px;
      max-width: 90%;
      background: rgba(255, 255, 255, 0.92);
      border-radius: 20px;
      box-shadow: 0 10px 40px rgba(0,0,0,0.15);
      animation: fadeIn 2s ease;
    }

    h1 {
      color: #e91e63;
      font-size: 3.2rem;
      margin: 0.4em 0;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.1);
    }

    .nickname {
      font-size: 1.9rem;
      color: #c2185b;
      margin: 0.3em 0 0.8em;
    }

    p {
      font-size: 1.35rem;
      line-height: 1.6;
      margin: 1.2em auto;
      max-width: 700px;
    }

    .heart {
      color: #e91e63;
      font-size: 2.8rem;
      animation: beat 1.4s infinite;
      display: inline-block;
    }

    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.25); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .floating-hearts {
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      pointer-events: none;
      z-index: -1;
    }

    .heart-float {
      position: absolute;
      font-size: 1.8rem;
      color: rgba(233, 30, 99, 0.7);
      animation: float 12s linear infinite;
      user-select: none;
    }

    @keyframes float {
      0%   { transform: translateY(100vh) rotate(0deg); opacity: 0.6; }
      100% { transform: translateY(-15vh) rotate(360deg); opacity: 0; }
    }

    /* Make it mobile friendly */
    @media (max-width: 600px) {
      h1 { font-size: 2.6rem; }
      .nickname { font-size: 1.7rem; }
      p { font-size: 1.2rem; }
    }
  </style>
</head>
<body>

  <div class="floating-hearts" id="hearts"></div>

  <div class="container">
    <h1>Happy Valentine's Day ❤️</h1>
    <div class="nickname">To My Beautiful [Wife Tominia Maame Aba Eshun ]</div>

    <p>Every time I look at you, my heart does this silly little flip.<br>
       You make ordinary days feel like magic,<br>
       and every laugh we share becomes my favorite sound in the world.</p>

    <p>I just wanted to say...<br>
       <strong>I love you more than words can ever show</strong><br>
       and I'm so lucky you're mine. 💕</p>

    <p class="heart">♡ Forever yours ♡</p>

    <p style="font-size:1.1rem; margin-top:2em;">
      Made with lots of love just for you<br>
      — [Iceberg]
    </p>
  </div>

  <script>
    // Floating hearts animation
    function createHeart() {
      const heart = document.createElement("div");
      heart.className = "heart-float";
      heart.innerHTML = "❤️";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (Math.random() * 8 + 8) + "s"; // 8-16s
      heart.style.opacity = Math.random() * 0.5 + 0.4;
      document.getElementById("hearts").appendChild(heart);

      setTimeout(() => heart.remove(), 16000);
    }

    // Create hearts every ~400-900ms
    setInterval(createHeart, Math.random() * 500 + 400);
  </script>

</body>
</html>