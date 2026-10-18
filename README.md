# my-love-question
A special question for someone I love ❤️
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Question for You ❤️</title>

<style>
body {
  background: #ffe6f0;
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 60px 15px;
}
.box {
  background: white;
  padding: 25px;
  border-radius: 20px;
  max-width: 350px;
  margin: auto;
  box-shadow: 0 5px 20px pink;
}
h1 { color: #ff3377; }
button {
  padding: 12px 24px;
  border: none;
  border-radius: 12px;
  margin: 8px;
  font-size: 18px;
}
#yes { background: #ff3377; color: white; }
#no { background: #ddd; color: black; }
#message {
  color: #ff3377;
  font-size: 18px;
  margin-top: 20px;
}
</style>
</head>

<body>
<div class="box">
  <h1>Hey, Beautiful ❤️🥰</h1>

  <p>You've brought smiles to my face, and I have something special to ask you. 💕</p>

  <h2>Will you be my girlfriend? ❤️</h2>

  <button id="yes" onclick="sayYes()">YES ❤️</button>
  <button id="no" onclick="sayNo()">NO 🙈</button>

  <div id="message"></div>
</div>

<script>
function sayYes() {
  document.getElementById("message").innerHTML =
    "Yaaay! 🥹❤️ I'm so happy! Let's make beautiful memories together. 😘💕";
}

function sayNo() {
  document.getElementById("message").innerHTML =
    "It's okay, beautiful ❤️. I'll respect your decision.";
}
</script>
</body>
</html>
