<!DOCTYPE html>
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
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <div class="reason" id="reason"></div>

    <script>
        // Array of reasons
        const reasons = [
            "Your smile brightens my day.",
            "You listen to me without judgment.",
            "I feel at peace when I'm with you.",
            "You make me laugh.",
            "We share common interests.",
            "You support my dreams.",
            "You are kind to everyone.",
            "Your presence is comforting.",
            "I trust you completely.",
            "You encourage me to be my best self."
        ];

        // Function to display a random reason
        function displayRandomReason() {
            const randomIndex = Math.floor(Math.random() * reasons.length);
            document.getElementById('reason').innerHTML = reasons[randomIndex];
        }

        // Call the function when the page loads
        window.onload = displayRandomReason;
    </script>
</body>
</html>
