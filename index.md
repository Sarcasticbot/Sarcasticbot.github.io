<!DOCTYPE html>
<html>

<head>
    <style>
        /* Your existing CSS styles here */

        body {
            background-image: url('your-anime-background-image.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            font-family: 'Autour One';
        }

        /* Define animation for touch sensor */
        @keyframes touch-sensor {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
            100% {
                transform: scale(1);
            }
        }

        /* Create a button with three dots for sections */
        .section-button {
            background: transparent;
            border: none;
            cursor: pointer;
            font-size: 24px;
        }

        .section-button:hover {
            animation: touch-sensor 0.3s ease infinite;
        }

        /* Style for the categorized sections */
        .section {
            display: none;
        }

        .section.active {
            display: block;
        }
    </style>
</head>

<body>
    <p align="right">
        <h1> <img src="https://te.legra.ph/file/90124a5be58c0f1812203.jpg" width="100px"
                class="profile-pic"> Hello cuties ✨</h1>
    </p>

    <p align="center">
        <img src="https://readme-typing-svg.herokuapp.com?color=4772F7width=420&lines=I+am+Sarcastic+a+telegram+bot+✨%E2%9C%8C%EF%B8%8F;Created+with+❤+by+my+developers+⭐%E2%9D%A4%EF%B8%8F">
    </p>

    <!-- Anime background touch sensors -->
    <div id="anime-touch" style="position: fixed; width: 100%; height: 100%; z-index: -1;"></div>

    <!-- Section buttons for categorization -->
    <button class="section-button" onclick="toggleSection('about')">⋮</button>
    <button class="section-button" onclick="toggleSection('how-to-use')">⋮</button>
    <button class="section-button" onclick="toggleSection('features')">⋮</button>

    <div class="section" id="about">
        <h1>About me <img height="60"
                src="https://raw.githubusercontent.com/Sarcasticbot/Sarcasticbot.github.io/main/assets/Jai shree ram bro.gif">
        </h1>
        <!-- About me content here -->
    </div>

    <div class="section" id="how-to-use">
        <h2>How to use me...<img height="80"
                src="https://raw.githubusercontent.com/Sarcasticbot/Sarcasticbot.github.io/main/assets/emojibest_com_AnimatedSticker (2).gif">
        </h2>
        <!-- How to use me content here -->
    </div>

    <div class="section" id="features">
        <h2>Features <img height="50"
                src="https://raw.githubusercontent.com/Sarcasticbot/Sarcasticbot.github.io/main/assets/emojibest_com_AnimatedSticker.gif">
        </h2>
        <!-- Features content here -->
    </div>

    <!-- Other content -->

    <script>
        // JavaScript function to toggle sections
        function toggleSection(sectionId) {
            const sections = document.querySelectorAll('.section');
            sections.forEach((section) => section.classList.remove('active'));
            const section = document.getElementById(sectionId);
            section.classList.add('active');
        }

        // JavaScript function to create touch sensor animation
        document.addEventListener('mousemove', function (e) {
            const touchSensor = document.getElementById('anime-touch');
            touchSensor.style.left = e.pageX + 'px';
            touchSensor.style.top = e.pageY + 'px';
        });
    </script>
</body>

</html>
