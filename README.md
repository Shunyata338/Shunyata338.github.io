<html>
<head>
    <title>Random Slide Show</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            background-color: #f0f0f0;
        }
        .reason {
            text-align: center;
            max-width: 600px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            color: #fff; /* Ensure text color contrasts well */
        }
    </style>
</head>
<body>
    <div class="reason" id="reason"></div>

    <script>
        // Array of reasons
        const reasons = [
            "your smile brightens my day", 
            " you listen to you without judgment",
            " I feel at peace when you're with them",
            " you make you laugh",
            " I share common interests",
            " you support my dreams",
            " you are kind to everyone",
            " your presence is comforting",
            " I trust them completely",
            " you encourage me to be my best self",
            " you understand you like no one else",
            " I share great chemistry",
            " you respect my boundaries",
            " I can be myself around them",
            " you're intelligent and you learn from them",

            // Add other reasons here, ensure to use straight quotes
        ];

        // Array of background colors as strings
        const colors = [
            "#6E238A", "#0640C5", "#F31810", "#406854", "#86DCC6", "#8304B3", "#52ABC0", "#A4CA04", "#73D99F", "#8245EA",
         // Add the rest of the colors here, enclosed in quotes
        ];

        // Function to display a random reason with a random background color
        function displayRandomReason() {
            const randomIndex = Math.floor(Math.random() * reasons.length);
            const randomColorIndex = Math.floor(Math.random() * colors.length);
            const reasonElement = document.getElementById('reason');
            reasonElement.innerHTML = reasons[randomIndex];
            reasonElement.style.backgroundColor = colors[randomColorIndex];
        }

        // Call the function when the page loads
        window.onload = displayRandomReason;
    </script>
</body>
</html>
