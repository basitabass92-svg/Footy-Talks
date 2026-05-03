<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>FOOTY TALKS ⚽✨</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
    }

    header {
      background: #0b6623;
      color: white;
      text-align: center;
      padding: 25px;
    }

    header h1 {
      margin: 0;
      font-size: 28px;
    }

    header p {
      margin-top: 5px;
      font-size: 14px;
    }

    .container {
      padding: 15px;
    }

    .btn {
      width: 100%;
      padding: 15px;
      margin-top: 10px;
      background: #222;
      color: white;
      border: none;
      font-size: 16px;
      text-align: left;
      cursor: pointer;
      border-radius: 6px;
    }

    .content {
      display: none;
      background: white;
      padding: 12px;
      border-radius: 6px;
      margin-bottom: 10px;
      border: 1px solid #ddd;
    }

    .whatsapp {
      display: block;
      text-align: center;
      background: #25D366;
      color: white;
      padding: 15px;
      margin-top: 20px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
    }

    .admin {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>

<body>

<header>
  <h1>FOOTY TALKS ⚽✨</h1>
  <p>Your Home for Football News, Talks & Updates</p>
</header>

<div class="container">

  <button class="btn" onclick="toggle('about')">
    ⚽ About FOOTY TALKS
  </button>
  <div id="about" class="content">
    FOOTY TALKS ⚽✨ is a growing football community created to bring fans together.
    We share football news, match discussions, transfer updates, opinions, and analysis in one place.
  </div>

  <button class="btn" onclick="toggle('mission')">
    🎯 Our Mission
  </button>
  <div id="mission" class="content">
    Our mission is to build a strong football community where fans can stay updated,
    share opinions, and enjoy the beautiful game together without limits.
  </div>

  <button class="btn" onclick="toggle('vision')">
    🚀 Our Vision
  </button>
  <div id="vision" class="content">
    Our vision is to grow FOOTY TALKS into a global football media platform,
    inspiring young sports lovers and becoming a trusted source for football content.
  </div>

  <button class="btn" onclick="toggle('offer')">
    📢 What We Offer
  </button>
  <div id="offer" class="content">
    - Daily football updates ⚽  
    - Match analysis 🧠  
    - Transfer news 🔁  
    - Player discussions 👑  
    - Fan opinions & debates 🗣️  
  </div>

  <button class="btn" onclick="toggle('admin')">
    👑 Admin Info
  </button>
  <div id="admin" class="content">
    Admin Name: <b>BIG JAYCEE 😎</b><br>
    Founder & Vision Driver of FOOTY TALKS ⚽✨
  </div>

  <!-- WhatsApp Button -->
  <a class="whatsapp"
     href="https://chat.whatsapp.com/DVDoD7a99QTEarxqR9XXJB"
     target="_blank">
     👉 Join FOOTY TALKS WhatsApp Community
  </a>

  <div class="admin">
    Built with passion for football lovers ⚽🔥
  </div>

</div>

<script>
function toggle(id) {
  var content = document.getElementById(id);

  if (content.style.display === "block") {
    content.style.display = "none";
  } else {
    content.style.display = "block";
  }
}
</script>

</body>
</html>
