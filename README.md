# valentiness
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart to Love Letter</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&family=Playfair+Display:wght@500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Playfair Display', serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: linear-gradient(135deg, #f8cdda, #f5b2b8);
            color: #333;
            text-align: center;
        }

        .container {
            background: rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            max-width: 450px;
            width: 100%;
            animation: fadeIn 1s ease-in-out;
        }

        .password-prompt {
            font-size: 22px;
            color: #b22222;
            font-family: 'Dancing Script', cursive;
        }

        .password-input, .password-button {
            padding: 12px;
            font-size: 18px;
            border-radius: 10px;
            width: 100%;
            max-width: 300px;
            display: block;
            margin: 10px auto;
            text-align: center;
            outline: none;
        }

        .password-input {
            border: 2px solid #b22222;
            transition: all 0.3s ease;
        }

        .password-input:focus {
            border-color: #ff6347;
            box-shadow: 0 0 10px rgba(255, 99, 71, 0.5);
        }

        .password-button {
            background: linear-gradient(135deg, #b22222, #ff6347);
            color: white;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .password-button:hover {
            background: linear-gradient(135deg, #8b0000, #e63946);
            transform: scale(1.05);
        }

        .heart {
            font-size: 120px;
            color: #b22222;
            cursor: pointer;
            transition: transform 0.3s ease, color 0.3s ease;
            display: none;
            animation: heartPop 1s ease-out;
        }

        .heart:hover {
            transform: scale(1.2);
            color: #8b0000;
        }

        .love-letter {
            display: none;
            margin-top: 20px;
            background: rgba(255, 255, 255, 0.3);
            backdrop-filter: blur(12px);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            opacity: 0;
            transform: translateY(50px);
            transition: opacity 0.6s ease, transform 0.6s ease;
            max-width: 500px;
            height: 400px;
            overflow-y: auto;
            text-align: left;
        }

        .love-letter::-webkit-scrollbar {
            width: 8px;
        }

        .love-letter::-webkit-scrollbar-thumb {
            background: rgba(178, 34, 34, 0.7);
            border-radius: 10px;
        }

        .letter-title {
            font-size: 26px;
            font-family: 'Dancing Script', cursive;
            color: #b22222;
            margin-bottom: 10px;
            text-align: center;
        }

        .letter-content {
            font-size: 18px;
            line-height: 1.6;
            color: #333;
            font-style: italic;
            padding-right: 10px;
        }

        .surprise-button {
            display: none;
            margin-top: 20px;
        }

        .surprise-button button {
            padding: 10px 25px;
            font-size: 18px;
            background: #b22222;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: 0.3s;
        }

        .surprise-button button:hover {
            background: #8b0000;
            transform: scale(1.1);
        }

        @keyframes heartPop {
            0% { transform: scale(0); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="password-prompt">💖 Enter the secret password to reveal your surprise 💖</div>
        <input type="password" id="password" class="password-input" placeholder="Password">
        <button class="password-button" onclick="checkPassword()">Unlock</button>

        <div class="heart" id="heart" onclick="showLetterAndPlaySong()">❤️</div>

        <div class="love-letter" id="loveLetter">
            <div class="letter-title">To my beautiful, loving, and amazing babii,</div>
            <div class="letter-content">
                <!-- Your love letter content here -->
                To my beautiful, loving, and amazing babii,
                HAHAHA I know you love handwritten letters, and I wish I could give you one in person, but for now, this will have to do. It’s still handmade, just with my keyboard.

Babbii, I’ve been seeing so many TikTok vids where IT boyfriends create something special for their girlfriends, asking them to be their Valentine. But me? I didn’t need to ask because from the start, you were already my Valentine, my always, my forever. I made this on my own, and I’ve been working on it for almost two weeks now, making sure everything is perfect just for you. This whole project is for you, babbii, because you deserve nothing but the best. HAHAHA

So ayun, happy Valentine’s Day, babbiii! And now, mag start na me sa totoong message ko HAHAHA.
                Happy happy Valentine’s Day, my babiii!
                
                First of all, I just want to say thank you. Thank you for being the most wonderful person in my life. Thank you for loving me even from miles away, for making me feel like I’m never alone despite the distance. Alam mo, minsan ang hirap talaga ng LDR pero dahil ikaw yung kasama ko sa journey na to, everything becomes easier. You make it all worth it.
                
                I miss you every single day, babbii. I miss your voice, your laugh, your little stories about your day. I miss the way we joke around, the way we comfort each other when things get tough. Kahit hindi tayo magkasama physically, you still manage to make me feel so loved, so special. And I hope you know that I’m always trying my best to do the same for you.
                
                You are my safe place, my happiest hello, and my hardest goodbye. Alam mo ba, ang daming moments na gusto kitang yakapin ng mahigpit, gusto kitang titigan at sabihin kung gaano kita kamahal, but for now I’ll just have to pour everything into this letter and into the little things I do for you.
                
                Babbii, kahit malayo tayo sa isa’t isa, I want you to know that my love for you never fades. It only grows stronger every single day. Every good morning and good night message, every call, every small effort we do for each other, it all means so much to me. I appreciate you more than words can ever express.
                
                I know that someday all this waiting, all the longing, will be worth it. One day we won’t have to count the days apart. One day I won’t have to miss you anymore because I’ll be right there beside you, holding your hand, making up for all the time we spent apart. And when that day comes, I promise, babbii, I’ll love you just as much as I do now, if not even more.
                
                But for now let’s keep holding on, okay? Let’s keep dreaming about the future we’ll build together. No matter how far we are from each other, my heart is always with you. You are my person, my love, my always.
                
                I love you so so much, babbii. Today, tomorrow, and for every Valentine’s Day to come.
                
                Forever yours,
                BABBII
            </div>
        </div>

        <div class="surprise-button" id="surpriseButton">
            <button onclick="window.location.href='surprise_section.html'">More Surprises?</button>
        </div>
    </div>

    <!-- Add the audio player -->
    <audio id="loveSong" src="C:\Users\Pro 450 G5\Desktop\GT\thousand.mp3"></audio>

    <script>
        function checkPassword() {
            const password = document.getElementById("password").value;
            const correctPassword = "122524";

            if (password === correctPassword) {
                document.querySelector(".password-prompt").style.display = "none";
                document.getElementById("password").style.display = "none";
                document.querySelector(".password-button").style.display = "none";
                document.getElementById("heart").style.display = "block";
            } else {
                alert("Incorrect password, try again!");
            }
        }

        function showLetterAndPlaySong() {
            document.getElementById("loveLetter").style.display = "block";
            setTimeout(() => {
                document.getElementById("loveLetter").style.opacity = "1";
                document.getElementById("loveLetter").style.transform = "translateY(0)";
            }, 100);

            document.getElementById("surpriseButton").style.display = "block";

            // Play the love song
            var audio = document.getElementById("loveSong");
            audio.play().catch(error => {
                console.log("Autoplay blocked. Waiting for user interaction.");
            });
        }
    </script>
</body>
</html>
