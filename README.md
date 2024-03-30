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
            " your smile brightens my day",
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
            " you're creative and inspire you",
            " you show your love in the way you need",
            " you remember small details about you",
            " you're loyal to you",
            " you handle conflicts with maturity",
            " you're generous with your time and attention",
            " you make you feel wanted and loved",
            " you're patient with you",
            " you motivate me to achieve my goals",
            " you share my values and beliefs",
            " you make sacrifices for my happiness",
            " you're emotionally available",
            " you make mundane tasks enjoyable when you're together",
            " you apologize and admit when you're wrong",
            " you celebrate my achievements",
            " you share your fears and vulnerabilities with you",
            " you make you feel safe",
            " you're passionate about your interests",
            " you respect my opinions, even when differing",
            " I have fun together, no matter what you're doing",
            " you're humble and can laugh at yourself",
            " you're optimistic and uplift my spirits",
            " you're reliable; you can always count on them",
            " you cherish the time spent with you",
            " you make an effort with my friends and family",
            " you're thoughtful and surprise you with small gestures",
            " you communicate openly and honestly",
            " you're strong and resilient",
            " you have a great sense of humor that matches mine",
            " you encourage you to try new things",
            " you're attentive to my needs and desires",
            " you're respectful to all",
            " you have a beautiful soul",
            " you help you grow as a person",
            " you're my best friend",
            " you love you unconditionally",
            " you make you feel confident",
            " you're dedicated to making the relationship work",
            " you give yourself space when you need it",
            " you share your joys and sorrows with you",
            " you make you want to be a better person",
            " you're beautiful to you in every way",
            " you make a great team with you",
            " you accept my flaws",
            " you make my heart skip a beat",
            " you're passionate about life",
            " you help you overcome challenges",
            " you make you feel young and alive",
            " you're my rock during hard times",
            " you make you feel important and valued",
            " you have a good heart",
            " you're ambitious and hardworking",
            " you inspire you with your achievements",
            " you're caring and empathetic",
            " you make every moment special",
            " you give you your undivided attention",
            " you're warm and welcoming to everyone",
            " you keep your promises",
            " you have an amazing voice you could listen to forever",
            " you make you feel like you're home",
            " you share your life with you",
            " you make an effort to understand my passions",
            " you're spontaneous and adventurous",
            “ you're disciplined and organized",
            " you always look for ways to make you happy",
            " you're fair and just",
            " you're confident and self-assured",
            " you bring out the best in you",
            " you're always there to comfort you",
            " you have a unique perspective on life",
            " you're good with children",
            " you make you feel secure in my future together",
            “ you're honest and forthright",
            " you have a calming presence",
            " you're responsible and dependable",
            " you make you feel like the most attractive person",
            " you're insightful and wise",
            " you have a great relationship with your family",
            " you're open-minded and willing to learn",
            " you have a zest for life",
            " you're protective of me in a loving way",
            " you make you a priority in your life",
            " you have a beautiful smile that melts my heart",
            " you make you feel loved in ways no one else has",
            " you're my soulmate, and with them, you feel complete",
        ];
         // Array of background colors
        const colors = [
               #6E238A, #0640C5, #F31810, #406854, #86DCC6, #8304B3, #52ABC0, #A4CA04, #73D99F, #8245EA,
            #D87D5B, #FB05BE, #9D1384, #11CCFC, #60590F, #B4C1A2, #58E707, #B692F8, #898E50, #A53149,
            #A7257C, #08BB15, #F18EA0, #EF951A, #BAB769, #C4F38C, #9CF760, #9222C8, #FCF938, #F16F3D,
            #622490, #8FD52B, #8FB8B1, #5B5AEE, #660068, #277538, #8572C4, #3E1166, #21C3A9, #6F9296,
            #763A82, #333B67, #143844, #5141D2, #2AE02E, #EAE499, #FE5CF2, #E06413, #E6AC97, #AFE09F,
            #BDF6AB, #F9E348, #80227B, #64C590, #572629, #3F24ED, #6BC53E, #AF5BA5, #4C050B, #A63982,
            #603FE7, #D496D6, #02B954, #A2E31D, #E14BDA, #6A0F59, #CB0B71, #E62F52, #7A9E34, #D1AF8A,
            #085802, #1BFB2F, #5FD538, #7349DD, #AFF4F3, #352642, #4532D3, #916BB3, #B041FA, #F63F6A,
            #73358E, #60316B, #78496F, #2ED28C, #093364, #1EF79D, #0C8490, #F49DBB, #2212DB, #E5952F,
            #F12EBE, #DF1259, #26C588, #ABB736, #179DFC, #327978, #7566EC, #E0660E, #AA418A, #3029C9

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
