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
            margin: 0;
            padding: 0;
        }
        .container {
            text-align: center;
            width: 100%;
            position: absolute;
            top: 10%;
        }
        .title {
            font-size: 36px; /* Increased font size */
            color: #333;
            margin: 0 0 20px 0; /* Adjusted to remove bottom margin */
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
     <div class="container">
    <div class="title">100 Reasons Why I Love You</div>
    <div class="reason" id="reason"></div>

    <script>
        // Array of reasons
        const reasons = [
            "your smile brightens my day", 
            " you listen to me without judgment",
            " I feel at peace when you're with me",
            " you make me laugh",
            " I share common interests with you",
            " you support my dreams",
            " you are kind to everyone",
            " your presence is comforting",
            " I trust you completely",
            " you encourage me to be my best self",
            " you understand me like no one else",
            " I share great chemistry with you",
            " you respect my boundaries",
            " I can be myself around you",
            " you're intelligent and I learn from you",
            " you're creative and you inspire me",
            " you show your love in the way I need",
            " you remember small details about me",
            " you're loyal to me",
            " you handle conflicts with maturity",
            " you're generous with your time and attention",
            " you make me feel wanted and loved",
            " you're patient with me",
            " you motivate me to achieve my goals",
            " you share my values and beliefs",
            " you make sacrifices for my happiness",
            " you're emotionally available",
            " you make mundane tasks enjoyable when we are together",
            " you apologize and admit when you're wrong",
            " you celebrate my achievements",
            " you share your fears and vulnerabilities with me",
            " you make you feel safe",
            " you're passionate about my interests",
            " you respect my opinions, even when differing",
            " We have fun together, no matter what we are doing",
            " you're humble and can laugh at yourself",
            " you're optimistic and uplift my spirits",
            " you're reliable; you can always count on you",
            " you cherish the time spent with me",
            " you make an effort with my friends and family",
            " you're thoughtful and surprise me with small gestures",
            " you communicate openly and honestly",
            " you're strong and resilient",
            " you have a great sense of humor that matches mine",
            " you encourage me to try new things",
            " you're attentive to my needs and desires",
            " you're respectful to all",
            " you have a beautiful soul",
            " you help me grow as a person",
            " you're my best friend",
            " you love you unconditionally",
            " you make me feel confident",
            " you're dedicated to making the relationship work",
            " you give me space when you need it",
            " you share your joys and sorrows with me",
            " you make me want to be a better person",
            " you're beautiful to me in every way",
            " you make a great team with me",
            " you accept my flaws",
            " you make my heart skip a beat",
            " you're passionate about life",
            " you help you overcome challenges",
            " you make me feel young and alive",
            " you're my rock during hard times",
            " you make me feel important and valued",
            " you have a good heart",
            " you're ambitious and hardworking",
            " you inspire me with your achievements",
            " you're caring and empathetic",
            " you make every moment special",
            " you give me your undivided attention",
            " you're warm and welcoming to everyone",
            // Add other reasons here, ensure to use straight quotes
        ];

        // Array of background colors as strings
        const colors = [
            "#6E238A", "#0640C5", "#F31810", "#406854", "#86DCC6", "#8304B3", "#52ABC0", "#A4CA04", "#73D99F", "#8245EA","#D87D5B", "#FB05BE", "#9D1384", "#11CCFC", "#60590F", "#B4C1A2", "#58E707", "#B692F8", "#898E50", "#A53149",
            "#A7257C", "#08BB15", "#F18EA0", "#EF951A", "#BAB769", "#C4F38C", "#9CF760", "#9222C8", "#78496F", "#F16F3D", "#622490",
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
