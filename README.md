<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday, Bhumi! 🎉</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #ffe3ec, #fff0f5);
      text-align: center;
      padding: 50px;
      color: #5a2d2d;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    .flowers {
      font-size: 2em;
      margin: 20px 0;
    }

    .message {
      font-size: 1.2em;
      margin-bottom: 30px;
    }

    .gift-box {
      background-color: #ffb6c1;
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      width: 250px;
      margin: 0 auto;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .gift-box:hover {
      background-color: #ff9eb2;
    }

    .gift-text {
      display: none;
      margin-top: 20px;
      font-size: 1.1em;
      background: #fff;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .reveal {
      display: block;
    }

    .credit {
      margin-top: 40px;
      font-size: 0.9em;
      color: #8b4a4a;
    }
  </style>
</head>
<body>

  <div class="flowers">🌸🌼🌺💐🌷</div>

  <h1>Happy Birthday, Bhumi! 🥳</h1>

  <div class="message">
    Wishing you a day full of joy, love, flowers, and sweet surprises!<br>
    There's something special waiting for you... 💝
  </div>

  <div class="gift-box" onclick="revealGift()">
    🎁 Tap to Reveal Your Gift!
  </div>

  <div class="gift-text" id="giftText">
    Surprise! 🎊<br><strong>Abhishek Sharma from SRH</strong> sends you a big birthday shoutout!<br>
    “Hey Bhumi, Happy Birthday! Keep shining and smashing through life just like I smash sixes! 💪🎂”
  </div>

  <div class="flowers">🌸🌼🌺💐🌷</div>

  <script>
    function revealGift() {
      document.getElementById("giftText").classList.add("reveal");
    }
  </script>

</body>
</html>
