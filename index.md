<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    h1 {
      font-size: 36px;
    }

    img {
      border-radius: 50%;
    }

    .animated-text {
      color: #4772F7;
      font-size: 24px;
      animation: typing 2s steps(25) infinite;
    }

    @keyframes typing {
      0% {
        width: 0;
      }
      100% {
        width: 100%;
      }
    }

    .profile-img {
      width: 300px;
      height: 300px;
      border-radius: 50%;
      animation: spin 5s linear infinite;
    }

    @keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }

    .group-info {
      font-size: 20px;
    }

    .music-player {
      width: 150px;
      height: 150px;
      animation: bounce 2s ease infinite;
    }

    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
      }
      40% {
        transform: translateY(-30px);
      }
      60% {
        transform: translateY(-15px);
      }
    }

    .donation {
      font-size: 20px;
      color: #F74772;
    }

    .status-button {
      background: transparent;
      border: none;
      cursor: pointer;
      transition: transform 0.2s;
    }

    .status-button:hover {
      transform: scale(1.1);
    }

    .status-icon {
      width: 50px;
    }

    .features-list {
      font-size: 24px;
    }

    .bio-data {
      font-size: 18px;
    }

    .source-code-button {
      background: #4772F7;
      border: none;
      color: #fff;
      padding: 10px 20px;
      border-radius: 5px;
      font-size: 20px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .source-code-button:hover {
      background: #2C3E50;
    }

    .contact-links {
      font-size: 20px;
      margin: 10px;
    }
  </style>
</head>
<body>
  <h1> <img src="https://te.legra.ph/file/90124a5be58c0f1812203.jpg" width="100px" class="profile-img"> Hello World....</h1>

  <div class="animated-text">
    I am Sarcastic, a Telegram bot ✨✌️
  </div>

  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" class="group-info">

  <h2>About me <img height="60" src="https://raw.githubusercontent.com/Sarcasticbot/Sarcasticbot.github.io/main/assets/Jai shree ram bro.gif"></h2>
  <div class="group-info">
    ➲ A powerful and awesome Telegram group management and music player that gives you a spam-free and fun environment for your groups.
    <br>
    ➲ Written in Python and uses MongoDB as a database 🥀
    <br>
    ➲ Uptime: May be always full time
    <br>
    ➲ Users: 13k+
    <br>
    ➲ Chats: 350+ (still growing)
  </div>

</body>
</html>
