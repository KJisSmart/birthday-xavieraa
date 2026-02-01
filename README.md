# birthday-xavieraa
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Xaviera ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #ffffff;
      text-align: center;
    }

    .container {
      max-width: 700px;
      margin: auto;
      padding: 40px 20px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    h2 {
      font-weight: normal;
      opacity: 0.9;
    }

    .heart {
      font-size: 40px;
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }

    .card {
      background: rgba(255,255,255,0.08);
      border-radius: 20px;
      padding: 30px;
      margin-top: 30px;
      line-height: 1.8;
      font-size: 1.05em;
    }

    button {
      margin-top: 30px;
      padding: 15px 25px;
      border: none;
      border-radius: 30px;
      background: #ff5e7e;
      color: white;
      font-size: 1em;
      cursor: pointer;
    }

    button:hover {
      background: #ff3f68;
    }

    .hidden {
      display: none;
      margin-top: 25px;
      font-style: italic;
      opacity: 0.95;
    }

    footer {
      margin-top: 50px;
      font-size: 0.9em;
      opacity: 0.7;
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="heart">❤️</div>

    <h1>Happy Birthday, Xaviera</h1>
    <h2>Today is all about you.</h2>

    <div class="card">
      <p>
        Even with distance between us, my heart somehow always knows where you are.
        On your birthday, I just want you to remember this:
        <br><br>
        You are deeply loved.  
        You are endlessly special.  
        And you make my world brighter just by being in it.
      </p>

      <p>
        I wish I could be right there with you today,
        but until that moment comes,
        let this page remind you how important you are to me.
      </p>
    </div>

    <button onclick="showMessage()">Click for your surprise 🎁</button>

    <div id="message" class="hidden">
      <p>
        No matter how many miles exist,
        no matter how much time passes,
        you will always have my heart.
        <br><br>
        Happy Birthday, my love 💕
      </p>
    </div>

    <footer>
      Forever yours, <br>
      your baby boii 💌
    </footer>
  </div>

  <script>
    function showMessage() {
      document.getElementById("message").style.display = "block";
    }
  </script>

</body>
</html>
