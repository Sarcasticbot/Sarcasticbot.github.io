<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarcastic Bot - User Guide</title>
    <style>
        /* Updated CSS for a "sexy" look */
        body {
            background-color: #272727;
            color: #fff;
            font-family: 'Arial', sans-serif;
        }

        .sidenav {
            height: 100%;
            width: 250px;
            position: fixed;
            z-index: 1;
            top: 0;
            left: 0;
            background-color: #1b1b1b;
            overflow-x: hidden;
            padding-top: 20px;
        }

        .sidenav a {
            padding: 12px 16px;
            text-decoration: none;
            font-size: 20px;
            color: #fff;
            display: block;
            transition: all 0.3s;
        }

        .sidenav a:hover {
            color: #ff6b6b;
        }

        /* Updated styles for buttons and sections */
        .dropdown-btn {
            width: 100%;
            padding: 14px;
            text-align: left;
            background-color: #1b1b1b;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        .content {
            margin-left: 270px;
            padding: 20px;
        }

        .content h1 {
            font-size: 36px;
            color: #ff6b6b;
        }

        .content p {
            font-size: 18px;
            line-height: 1.6;
        }

        /* Stylish footer */
        footer {
            background-color: #1b1b1b;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <div class="sidenav">
        <button class="dropdown-btn">🤖 Home</button>
        <div class="dropdown-container">
            <a href="#home">Introduction</a>
        </div>
        <button class="dropdown-btn">🤓 About</button>
        <div class="dropdown-container">
            <a href="#about">Bot Details</a>
            <a href="#usage">How to Use</a>
        </div>
        <button class="dropdown-btn">💰 Donation</button>
        <div class="dropdown-container">
            <a href="#donation">Support Us</a>
        </div>
        <button class="dropdown-btn">📞 Contact</button>
        <div class="dropdown-container">
            <a href="#contact">Support Channels</a>
        </div>
        <button class="dropdown-btn">🚀 Features</button>
        <div class="dropdown-container">
            <a href="#features">Bot Features</a>
        </div>
    </div>

    <div class="content">
        <section id="home">
            <h1>Welcome to Sarcastic Bot! 🤖</h1>
            <p>Get ready to experience the world's sassiest Telegram bot. Sarcastic Bot is here to make your chats more entertaining and witty.</p>
        </section>

        <section id="about">
            <h1>About Our Bot 🤓</h1>
            <p>Sarcastic Bot is the brainchild of humor aficionados. Find out all about the bot's creators and its mischievous mission.</p>
        </section>

        <section id="donation">
            <h1>Donate and Support 💰</h1>
            <p>Love our bot's wit? Consider supporting us so that we can keep the sarcasm flowing. Your contributions mean the world to us!</p>
        </section>

        <section id="contact">
            <h1>Get in Touch 📞</h
