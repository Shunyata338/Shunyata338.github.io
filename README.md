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
            " your smile brightens my day"
            " you listen to you without judgment"
            " I feel at peace when you're with them"
            " you make you laugh"
            " I share common interests"
            " you support my dreams"
            " you are kind to everyone"
            " your presence is comforting"
            " I trust them completely"
            " you encourage me to be my best self"
            " you understand you like no one else"
            " I share great chemistry"
            " you respect my boundaries"
            " I can be myself around them"
            " you're intelligent and you learn from them"
            " you're creative and inspire you"
            " you show your love in the way you need"
            " you remember small details about you"
            " you're loyal to you"
            " you handle conflicts with maturity"
            " you're generous with your time and attention"
            " you make you feel wanted and loved"
            " you're patient with you"
            " you motivate me to achieve my goals"
            " you share my values and beliefs"
            " you make sacrifices for my happiness"
            " you're emotionally available"
            " you make mundane tasks enjoyable when you're together"
            " you apologize and admit when you're wrong"
            " you celebrate my achievements"
            " you share your fears and vulnerabilities with you"
            " you make you feel safe"
            " you're passionate about your interests"
            " you respect my opinions, even when differing"
            " I have fun together, no matter what you're doing"
            " you're humble and can laugh at yourself"
            " you're optimistic and uplift my spirits"
            " you're reliable; you can always count on them"
            " you cherish the time spent with you"
            " you make an effort with my friends and family"
            " you're thoughtful and surprise you with small gestures"
            " you communicate openly and honestly"
            " you're strong and resilient"
            " you have a great sense of humor that matches mine"
            " you encourage you to try new things"
            " you're attentive to my needs and desires"
            " you're respectful to all"
            " you have a beautiful soul"
            " you help you grow as a person"
            " you're my best friend"
            " you love you unconditionally"
            " you make you feel confident"
            " you're dedicated to making the relationship work"
            " you give yourself space when you need it"
            " you share your joys and sorrows with you"
            " you make you want to be a better person"
            " you're beautiful to you in every way"
            " you make a great team with you"
            " you accept my flaws"
            " you make my heart skip a beat"
            " you're passionate about life"
            " you help you overcome challenges"
            " you make you feel young and alive"
            " you're my rock during hard times"
            " you make you feel important and valued"
            " you have a good heart"
            " you're ambitious and hardworking"
            " you inspire you with your achievements"
            " you're caring and empathetic"
            " you make every moment special"
            " you give you your undivided attention"
            " you're warm and welcoming to everyone"
            " you keep your promises"
            " you have an amazing voice you could listen to forever"
            " you make you feel like you're home"
            " you share your life with you"
            " you make an effort to understand my passions"
            " you're spontaneous and adventurous"
            “ you're disciplined and organized"
            " you always look for ways to make you happy"
            " you're fair and just"
            " you're confident and self-assured"
            " you bring out the best in you"
            " you're always there to comfort you"
            " you have a unique perspective on life"
            " you're good with children"
            " you make you feel secure in my future together"
            “ you're honest and forthright"
            " you have a calming presence"
            " you're responsible and dependable"
            " you make you feel like the most attractive person"
            " you're insightful and wise"
            " you have a great relationship with your family"
            " you're open-minded and willing to learn"
            " you have a zest for life"
            " you're protective of me in a loving way"
            " you make you a priority in your life"
            " you have a beautiful smile that melts my heart"
            " you make you feel loved in ways no one else has"
            " you're my soulmate, and with them, you feel complete"
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
