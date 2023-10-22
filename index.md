<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarcastic Bot - User Guide</title>
    <style>
        /* Updated CSS for a "sexy" and animated look */
        body {
            background-color: #1b1b1b;
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
            background-color: #272727;
            overflow-x: hidden;
            padding-top: 20px;
            transition: 0.3s;
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

        /* Animated styles for buttons and sections */
        .dropdown-btn {
            width: 100%;
            padding: 14px;
            text-align: left;
            background-color: #272727;
            color: #fff;
            border: none;
            cursor: pointer;
            transition: 0.3s;
        }

        .content {
            margin-left: 270px;
            padding: 20px;
            transition: 0.3s;
        }

        .content h1 {
            font-size: 36px;
            color: #ff6b6b;
            animation: fadeInUp 1s ease both;
        }

        .content p {
            font-size: 18px;
            line-height: 1.6;
            animation: fadeInUp 1s ease both;
        }

        /* Stylish footer with animation */
        footer {
            background-color: #272727;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        /* CSS animations */
        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
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
            <h1>Get in Touch 📞</h1>
            <p>Have questions, feedback, or just want to share a laugh? We're all ears. Reach us through various channels.</p>
        </section>

        <section id="features">
            <h1>Features Galore! 🚀</h1>
            <p>Discover the fantastic features that set Sarcastic Bot apart. From clever comebacks to hilarious one-liners, we've got it all.</p>
        </section>
    </div>

    <footer>
        <p>&copy; Sarcastic Bot 2023-24</p>
    </footer>

    <script>
        // JavaScript for dropdown functionality (same as before)
        var dropdownButtons = document.querySelectorAll(".dropdown-btn");

        dropdownButtons.forEach(function (button) {
            button.addEventListener("click", function () {
                var container = this.nextElementSibling;
                container.style.display = container.style.display === "block" ? "none" : "block";
            });
        });
    </script>
</body>
</html>
