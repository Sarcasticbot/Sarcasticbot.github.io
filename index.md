<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarcastic Bot - Documentation</title>
    <style>
        /* CSS for side navigation bar */
        .sidenav {
            height: 100%;
            width: 250px;
            position: fixed;
            z-index: 1;
            top: 0;
            left: 0;
            background-color: #333;
            overflow-x: hidden;
            padding-top: 20px;
        }

        .sidenav a {
            padding: 8px 8px 8px 32px;
            text-decoration: none;
            font-size: 20px;
            color: #f1f1f1;
            display: block;
        }

        .sidenav a:hover {
            color: #ff0066;
        }

        /* CSS for dropdown container */
        .dropdown-container {
            display: none;
            padding-left: 8px;
        }

        /* CSS for expanding the dropdown */
        .dropdown-btn {
            width: 100%;
            padding: 12px;
            text-align: left;
            background-color: #333;
            color: #f1f1f1;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="sidenav">
        <button class="dropdown-btn">Home</button>
        <div class="dropdown-container">
            <a href="#home">Introduction</a>
        </div>
        <button class="dropdown-btn">About</button>
        <div class="dropdown-container">
            <a href="#about">Bot Details</a>
            <a href="#usage">How to Use</a>
        </div>
        <button class="dropdown-btn">Donation</button>
        <div class="dropdown-container">
            <a href="#donation">Support Us</a>
        </div>
        <button class="dropdown-btn">Contact</button>
        <div class="dropdown-container">
            <a href="#contact">Support Channels</a>
        </div>
        <button class="dropdown-btn">Features</button>
        <div class="dropdown-container">
            <a href="#features">Bot Features</a>
        </div>
    </div>

    <div class="content">
        <section id="home">
            <h1>Hello cuties ✨</h1>
        </section>

        <section id="about">
            <!-- About content here -->
        </section>

        <section id="donation">
            <!-- Donation content here -->
        </section>

        <section id="contact">
            <!-- Contact content here -->
        </section>

        <section id="features">
            <!-- Features content here -->
        </section>
    </div>

    <footer>
        <p>&copy; Sarcastic Bot 2023-24</p>
    </footer>

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
