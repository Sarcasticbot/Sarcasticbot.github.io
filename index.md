<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarcastic Bot - Documentation</title>
    <style>
        /* Global styles */
        body {
            background-color: #1b1b1b;
            color: #fff;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Header styles */
        header {
            background-color: #272727;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
            color: #ff6b6b;
        }

        /* Container for the whole content */
        .container {
            display: flex;
            justify-content: space-between;
            margin: 20px;
        }

        /* Sidebar styles */
        .sidenav {
            width: 250px;
            background-color: #272727;
            padding: 20px 0;
        }

        .sidenav a {
            display: block;
            padding: 12px 16px;
            text-decoration: none;
            color: #fff;
            transition: all 0.3s;
        }

        .sidenav a:hover {
            background-color: #ff6b6b;
            color: #1b1b1b;
        }

        /* Main content styles */
        .content {
            flex-grow: 1;
            padding: 20px;
            animation: fadeIn 1s;
        }

        /* Dropdown styles */
        .dropdown-container {
            display: none;
            padding-left: 16px;
        }

        .dropdown-btn {
            background-color: #272727;
            color: #ff6b6b;
            border: none;
            padding: 12px;
            text-align: left;
            width: 100%;
            cursor: pointer;
        }

        /* Animation styles */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Sarcastic Bot Documentation</h1>
    </header>
    <div class="container">
        <div class="sidenav">
            <button class="dropdown-btn">Bot Info</button>
            <div class="dropdown-container">
                <p>Your bot is the coolest bot in town. It's sassy, witty, and ready to rock your Telegram groups.</p>
            </div>
            <button class="dropdown-btn">Add to Groups</button>
            <div class="dropdown-container">
                <p>Adding your bot to groups is easy. Just invite it, and watch the magic happen!</p>
            </div>
            <button class="dropdown-btn">Contact</button>
            <div class="dropdown-container">
                <p>Got questions, feedback, or just want to chat? Here's how to reach us:</p>
                <ul>
                    <li>Email: bot@example.com</li>
                    <li>Telegram: @SarcasticBotSupport</li>
                </ul>
            </div>
            <button class="dropdown-btn">Donation</button>
            <div class="dropdown-container">
                <p>Love our bot? Consider supporting us. Your contributions help keep the sarcasm flowing!</p>
            </div>
            <button class="dropdown-btn">Contributors</button>
            <div class="dropdown-container">
                <p>We're grateful for the talented contributors who made Sarcastic Bot a reality.</p>
            </div>
            <button class="dropdown-btn">Group Management Features</button>
            <div class="dropdown-container">
                <p>Group Management Features:</p>
                <ul>
                    <li>Ban Users</li>
                    <li>Mute Users</li>
                    <li>Kick Users</li>
                    <li>Group Stats</li>
                </ul>
            </div>
            <button class="dropdown-btn">Music Features</button>
            <div class="dropdown-container">
                <p>Music Features:</p>
                <ul>
                    <li>Play Music</li>
                    <li>Skip Tracks</li>
                    <li>Create Playlists</li>
                </ul>
            </div>
        </div>
        <div class="content">
            <p>Welcome to the documentation of the Sarcastic Bot. This bot is your ultimate Telegram companion.</p>
        </div>
    </div>
    <script>
        // JavaScript for dropdown functionality
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
