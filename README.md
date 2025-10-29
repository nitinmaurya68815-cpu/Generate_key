# Generate_key
Free fire mod key generator 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nitin_Modz</title>
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #000;
    font-family: 'Courier New', monospace;
    color: white;
    text-align: center;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 30px 10px;
  }

  .logo img {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    box-shadow: 0 0 40px #ff004c;
    border: 2px solid #111;
    animation: pulse 2s infinite alternate;
  }

  @keyframes pulse {
    from { box-shadow: 0 0 25px #ff004c; }
    to { box-shadow: 0 0 50px #00ffff; }
  }

  h1 {
    color: #ff00cc;
    font-size: 26px;
    margin-top: 20px;
  }

  h2 {
    color: #00bfff;
    font-size: 20px;
    margin-bottom: 25px;
  }

  .generate-box {
    border: 1px solid #00ffff55;
    padding: 10px;
    margin: 10px auto;
    width: 80%;
    max-width: 320px;
    border-radius: 10px;
    font-size: 16px;
    color: #ccc;
  }

  .btn {
    background-color: transparent;
    border: 2px solid #00ffff;
    color: #00ffff;
    padding: 12px 28px;
    margin-top: 10px;
    border-radius: 10px;
    font-size: 18px;
    cursor: pointer;
    transition: 0.3s;
  }

  .btn:hover {
    background-color: #00ffff;
    color: #000;
    box-shadow: 0 0 15px #00ffff;
  }

  .telegram-box {
    margin-top: 30px;
    border: 1px solid #ff00ff55;
    padding: 20px;
    border-radius: 12px;
    max-width: 340px;
    margin-left: auto;
    margin-right: auto;
  }

  .telegram-box p {
    color: #ff00ff;
    font-size: 15px;
    margin-bottom: 12px;
  }

  .telegram-btn {
    background: linear-gradient(90deg, #ff00cc, #00ffff);
    color: #000;
    font-weight: bold;
    padding: 10px 25px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: 0.3s;
  }

  .telegram-btn:hover {
    transform: scale(1.05);
  }

  .key-box {
    margin-top: 20px;
    font-size: 15px;
    color: #00ffcc;
  }
</style>
</head>
<body>

<div class="container">
  <div class="logo">
    <img src="<a href="<a href="https://ibb.co/xSrtFDVk"><img src="https://i.ibb.co/xSrtFDVk/file-000000007e9c620689dae05d6a981593.png" alt="file-000000007e9c620689dae05d6a981593" border="0"></a
  </div>

  <h1>Nitin_modz</h1>
  <h2>V1-AIMKILL</h2>

  <div class="generate-box">– Press Generate –</div>
  <button class="btn" onclick="generateKey()">GENERATE KEY</button>
  <button class="btn" onclick="copyKey()">COPY KEY</button>

  <div class="key-box" id="keyBox"></div>

  <div class="telegram-box">
    <p>❤️ Any Problem? Join Telegram!</p>
    <button class="telegram-btn" onclick="window.open('https://t.me/+MVN6iStjmxIxNTBl', '_blank')">Join Now</button>
  </div>
</div>

<script>
  function generateKey() {
    const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789";
    let key = "";
    for (let i = 0; i < 16; i++) {
      key += chars.charAt(Math.floor(Math.random() * chars.length));
      if ((i + 1) % 4 === 0 && i < 15) key += "-";
    }
    document.getElementById("keyBox").innerHTML = "🔑 Your Key: <b>" + key + "</b>";
  }

  function copyKey() {
    const keyText = document.getElementById("keyBox").innerText.replace("🔑 Your Key: ", "");
    if (keyText.trim() !== "") {
      navigator.clipboard.writeText(keyText);
      alert("✅ Key copied to clipboard!");
    } else {
      alert("⚠️ Please generate a key first!");
    }
  }
</script>

</body>
</html>
