<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Best Friend ✨</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 25%, #f093fb 50%, #f5576c 75%, #4facfe 100%);
            background-size: 400% 400%;
            animation: gradientFlow 15s ease infinite;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }

        @keyframes gradientFlow {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="20" cy="20" r="2" fill="rgba(255,255,255,0.1)"/><circle cx="80" cy="80" r="2" fill="rgba(255,255,255,0.1)"/><circle cx="40" cy="60" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="90" cy="10" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="10" cy="90" r="1.5" fill="rgba(255,255,255,0.1)"/><circle cx="70" cy="30" r="1" fill="rgba(255,255,255,0.1)"/></svg>') repeat;
            animation: floatingStars 20s linear infinite;
            pointer-events: none;
            z-index: 1;
        }

        @keyframes floatingStars {
            0% { transform: translateY(0px) rotate(0deg); }
            100% { transform: translateY(-100px) rotate(360deg); }
        }

        .container {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(20px);
            border-radius: 30px;
            padding: 50px;
            box-shadow: 
                0 25px 50px rgba(0, 0, 0, 0.2),
                inset 0 1px 0 rgba(255, 255, 255, 0.3);
            max-width: 600px;
            width: 100%;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.2);
            position: relative;
            z-index: 2;
            overflow: hidden;
        }

        .container::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: conic-gradient(from 0deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            animation: rotate 10s linear infinite;
            z-index: -1;
        }

        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .header {
            margin-bottom: 30px;
        }

        .header h1 {
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4, #feca57);
            background-size: 300% 300%;
            animation: gradientText 4s ease infinite;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            font-size: 3em;
            margin-bottom: 10px;
            text-shadow: none;
            font-weight: bold;
            filter: drop-shadow(2px 2px 4px rgba(0, 0, 0, 0.3));
        }

        @keyframes gradientText {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .header p {
            color: rgba(255, 255, 255, 0.9);
            font-size: 1.3em;
            font-style: italic;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);
            margin-bottom: 20px;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 30px 0;
        }

        .extended-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin: 20px 0;
        }

        .extended-grid .feature-card {
            padding: 20px 15px;
        }

        .extended-grid .feature-card .icon {
            font-size: 2em;
            margin-bottom: 10px;
        }

        .extended-grid .feature-card .title {
            font-size: 0.9em;
        }

        .feature-card {
            background: linear-gradient(45deg, #ff9a9e, #fecfef, #fecfef, #f093fb);
            background-size: 300% 300%;
            animation: cardGradient 6s ease infinite;
            padding: 30px 20px;
            border-radius: 25px;
            cursor: pointer;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            border: none;
            box-shadow: 
                0 10px 30px rgba(0, 0, 0, 0.2),
                inset 0 1px 0 rgba(255, 255, 255, 0.3);
            position: relative;
            overflow: hidden;
        }

        @keyframes cardGradient {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .feature-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
            transition: left 0.5s;
        }

        .feature-card:hover::before {
            left: 100%;
        }

        .feature-card:hover {
            transform: translateY(-8px) scale(1.05);
            box-shadow: 
                0 20px 50px rgba(0, 0, 0, 0.3),
                0 0 30px rgba(255, 255, 255, 0.2);
        }

        .feature-card:active {
            transform: translateY(-5px) scale(1.02);
        }

        .feature-card .icon {
            font-size: 3em;
            margin-bottom: 15px;
            display: block;
            filter: drop-shadow(2px 2px 4px rgba(0, 0, 0, 0.3));
            animation: iconFloat 3s ease-in-out infinite;
        }

        @keyframes iconFloat {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-5px) rotate(5deg); }
        }

        .feature-card .title {
            font-weight: bold;
            color: #fff;
            font-size: 1.2em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
        }

        .message-box {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0.1));
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 25px;
            margin: 30px 0;
            border: 1px solid rgba(255, 255, 255, 0.3);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
        }

        .message-input {
            width: 100%;
            padding: 20px;
            border: none;
            border-radius: 20px;
            font-size: 1.1em;
            resize: none;
            background: rgba(255, 255, 255, 0.9);
            box-shadow: inset 0 2px 10px rgba(0, 0, 0, 0.1);
            outline: none;
            transition: all 0.3s ease;
        }

        .message-input:focus {
            background: rgba(255, 255, 255, 1);
            box-shadow: 
                inset 0 2px 10px rgba(0, 0, 0, 0.15),
                0 0 0 3px rgba(255, 107, 107, 0.3);
            transform: scale(1.02);
        }

        .send-button {
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1);
            background-size: 200% 200%;
            animation: buttonGradient 3s ease infinite;
            color: white;
            border: none;
            padding: 18px 35px;
            border-radius: 30px;
            font-size: 1.2em;
            font-weight: bold;
            cursor: pointer;
            margin-top: 20px;
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
        }

        @keyframes buttonGradient {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .send-button:hover {
            transform: translateY(-3px) scale(1.05);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }

        .footer {
            margin-top: 30px;
            color: #888;
            font-size: 0.9em;
        }

        .hearts {
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        .sparkle {
            display: inline-block;
            animation: sparkle 2s linear infinite;
        }

        @keyframes sparkle {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.7; transform: scale(1.2); }
        }

        .modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 1000;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .modal-content {
            background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
            padding: 30px;
            border-radius: 20px;
            max-width: 500px;
            width: 90%;
            max-height: 80vh;
            overflow-y: auto;
            position: relative;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        .close {
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 30px;
            cursor: pointer;
            color: #ff6b6b;
            font-weight: bold;
        }

        .close:hover {
            color: #ff4757;
            transform: scale(1.1);
        }

        .modal h2 {
            color: #ff6b6b;
            text-align: center;
            margin-bottom: 20px;
            font-size: 1.8em;
        }

        .modal-body {
            color: #333;
            line-height: 1.6;
            font-size: 1.1em;
            text-align: center;
            white-space: pre-line;
        }

        .music-btn, .game-btn, .refresh-btn {
            display: block;
            width: 100%;
            margin: 10px 0;
            padding: 12px;
            background: linear-gradient(45deg, #ff6b6b, #feca57);
            color: white;
            border: none;
            border-radius: 15px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .music-btn:hover, .game-btn:hover, .refresh-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }

        .refresh-btn {
            background: linear-gradient(45deg, #a8edea, #fed6e3);
            color: #333;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 class="hearts">Hey Bestie! 💕</h1>
            <p>Your personal cute space <span class="sparkle">✨</span></p>
        </div>

        <div class="feature-grid">
            <button class="feature-card" onclick="showPoetry()">
                <span class="icon">🌹</span>
                <span class="title">Sweet Poetry</span>
            </button>
            
            <button class="feature-card" onclick="showPhotos()">
                <span class="icon">📸</span>
                <span class="title">Beautiful Photos</span>
            </button>
        </div>

        <div class="extended-grid">
            <button class="feature-card" onclick="showMusic()">
                <span class="icon">🎵</span>
                <span class="title">Love Songs</span>
            </button>
            
            <button class="feature-card" onclick="showGames()">
                <span class="icon">🎮</span>
                <span class="title">Fun Games</span>
            </button>

            <button class="feature-card" onclick="showSurprise()">
                <span class="icon">🎁</span>
                <span class="title">Surprise Box</span>
            </button>
        </div>

        <div class="message-box">
            <textarea class="message-input" placeholder="Share your thoughts, dreams, or just say hi! 💭" rows="3" id="messageInput"></textarea>
            <button class="send-button" onclick="sendMessage()">Send Love 💕</button>
        </div>

        <div class="footer">
            <p>Made with <span class="hearts">💖</span> for the best friend ever!</p>
        </div>
    </div>

    <script>
        const surpriseCollection = [
            {
                type: "quote",
                content: "A friend like you is a treasure beyond measure 💎",
                title: "Daily Inspiration"
            },
            {
                type: "memory",
                content: "Remember that time we laughed until our stomachs hurt? 😂 Those are the moments that make life beautiful!",
                title: "Sweet Memory"
            },
            {
                type: "compliment",
                content: "Your smile can light up the darkest day ✨ You're absolutely amazing!",
                title: "Just Because"
            },
            {
                type: "future",
                content: "I can't wait for all the adventures we haven't had yet! 🌟",
                title: "Dreams Ahead"
            }
        ];

        function showSurprise() {
            const surprise = surpriseCollection[Math.floor(Math.random() * surpriseCollection.length)];
            const surpriseHTML = `
                <div style="text-align: center; padding: 20px;">
                    <div style="font-size: 4em; margin: 20px 0;">🎁</div>
                    <h3 style="color: #ff6b6b; margin: 15px 0; font-size: 1.5em;">${surprise.title}</h3>
                    <p style="font-size: 1.2em; color: #333; line-height: 1.6; margin: 20px 0;">${surprise.content}</p>
                    <button class="refresh-btn" onclick="showSurprise()" style="margin-top: 20px;">Another Surprise! 🎉</button>
                </div>
            `;
            showModal("✨ Special Surprise", surpriseHTML, 'surprise');
        }

        function showShayari() {
            const randomShayari = shayariCollection[Math.floor(Math.random() * shayariCollection.length)];
            showModal("💝 Beautiful Shayari", randomShayari, 'shayari');
        }

        const onlineGames = [
            { name: "20 Questions", desc: "I think of something, you guess what it is!" },
            { name: "Word Association", desc: "Say the first word that comes to mind!" },
            { name: "Story Building", desc: "We create a story together, one sentence at a time!" },
            { name: "Would You Rather", desc: "Fun choices that reveal interesting things!" },
            { name: "Emoji Guessing", desc: "Guess the movie/song from emojis!" },
            { name: "Virtual Truth or Dare", desc: "Safe and fun questions & challenges!" }
        ];

        const poetryCollection = [
            "In friendship's garden, we bloom together,\nThrough every storm and sunny weather.\nYour laughter is my favorite song,\nWith you, dear friend, I belong. 🌸",
            "Miles may separate, time may pass,\nBut true friendship will always last.\nIn every memory, you shine bright,\nMy dearest friend, my guiding light. ⭐",
            "Like flowers in spring, like stars at night,\nOur friendship makes everything right.\nThrough thick and thin, we'll always be,\nBest friends for all eternity. 💫"
        ];

        const loveSongs = [
            { title: "Perfect - Ed Sheeran", url: "https://www.youtube.com/watch?v=2Vv-BfVoq4g" },
            { title: "All of Me - John Legend", url: "https://www.youtube.com/watch?v=450p7goxZqg" },
            { title: "Counting Stars - OneRepublic", url: "https://www.youtube.com/watch?v=hT_nvWreIhg" },
            { title: "A Thousand Years - Christina Perri", url: "https://www.youtube.com/watch?v=rtOvBOTyX00" },
            { title: "Tum Hi Ho - Arijit Singh", url: "https://www.youtube.com/watch?v=IJq0yyWug1k" },
            { title: "Raabta - Arijit Singh", url: "https://www.youtube.com/watch?v=Oy8gHi3aLl4" }
        ];

        const photoCollection = [
            {
                emoji: "🌸",
                caption: "Beautiful Memories",
                description: "Cherry blossoms remind me of our friendship - beautiful and timeless"
            },
            {
                emoji: "🌅",
                caption: "Sunrise Together",
                description: "Every new day is better with a friend like you"
            },
            {
                emoji: "🦋",
                caption: "Free Spirits",
                description: "Like butterflies, we bring color to each other's world"
            },
            {
                emoji: "🌙",
                caption: "Dreamy Nights",
                description: "Late night talks under the stars"
            },
            {
                emoji: "🌈",
                caption: "After Every Storm",
                description: "You're the rainbow after my rain"
            },
            {
                emoji: "🏔️",
                caption: "Adventures Await",
                description: "Ready to climb mountains together"
            },
            {
                emoji: "🌊",
                caption: "Ocean of Love",
                description: "Our friendship runs as deep as the ocean"
            },
            {
                emoji: "🌺",
                caption: "Blooming Bond",
                description: "Like flowers in spring, our friendship grows"
            },
            {
                emoji: "✨",
                caption: "Magical Moments",
                description: "Every moment with you sparkles"
            }
        ];

        function showPhotos() {
            let photosHTML = `
                <div class="photo-gallery">
            `;
            
            photoCollection.forEach((photo, index) => {
                photosHTML += `
                    <div class="photo-item" onclick="showPhotoDetail(${index})">
                        <div class="photo-placeholder">${photo.emoji}</div>
                        <div class="photo-caption">${photo.caption}</div>
                    </div>
                `;
            });
            
            photosHTML += '</div>';
            
            showModal("📸 Beautiful Moments", photosHTML, 'photos');
        }

        function showPhotoDetail(index) {
            const photo = photoCollection[index];
            const detailHTML = `
                <div style="text-align: center; padding: 20px;">
                    <div style="font-size: 5em; margin: 20px 0;">${photo.emoji}</div>
                    <h3 style="color: #ff6b6b; margin: 15px 0;">${photo.caption}</h3>
                    <p style="font-style: italic; color: #666; font-size: 1.1em;">${photo.description}</p>
                    <button class="refresh-btn" onclick="showPhotos()" style="margin-top: 20px;">← Back to Gallery</button>
                </div>
            `;
            showModal("📷 Photo Details", detailHTML, 'photo-detail');
        }

        function showShayari() {
            const randomShayari = shayariCollection[Math.floor(Math.random() * shayariCollection.length)];
            showModal("💝 Beautiful Shayari", randomShayari, 'shayari');
        }

        function showPoetry() {
            const randomPoetry = poetryCollection[Math.floor(Math.random() * poetryCollection.length)];
            showModal("🌹 Sweet Poetry", randomPoetry, 'poetry');
        }

        function showMusic() {
            let musicList = "🎵 Love Songs Collection:\n\n";
            loveSongs.forEach((song, index) => {
                musicList += `${index + 1}. ${song.title}\n`;
            });
            musicList += "\nClick on any song name to listen! 💕";
            showModal("🎶 Love Music", musicList, 'music');
        }

        function showGames() {
            let gamesList = "🎮 Fun Games to Play:\n\n";
            onlineGames.forEach((game, index) => {
                gamesList += `${index + 1}. ${game.name}\n   ${game.desc}\n\n`;
            });
            gamesList += "Choose a number to start playing! ✨";
            showModal("🎯 Fun Zone", gamesList, 'games');
        }

        function showModal(title, content, type) {
            const modal = document.createElement('div');
            modal.className = 'modal';
            modal.innerHTML = `
                <div class="modal-content">
                    <span class="close" onclick="closeModal()">&times;</span>
                    <h2>${title}</h2>
                    <div class="modal-body" id="modalBody">${content}</div>
                    ${type === 'music' ? '<div id="musicButtons"></div>' : ''}
                    ${type === 'games' ? '<div id="gameButtons"></div>' : ''}
                    ${type === 'shayari' || type === 'poetry' ? '<button class="refresh-btn" onclick="' + (type === 'shayari' ? 'showShayari()' : 'showPoetry()') + '">Show Another 🔄</button>' : ''}
                </div>
            `;
            document.body.appendChild(modal);

            if (type === 'music') {
                const musicButtons = document.getElementById('musicButtons');
                loveSongs.forEach(song => {
                    const btn = document.createElement('button');
                    btn.className = 'music-btn';
                    btn.textContent = song.title;
                    btn.onclick = () => window.open(song.url, '_blank');
                    musicButtons.appendChild(btn);
                });
            }

            if (type === 'games') {
                const gameButtons = document.getElementById('gameButtons');
                onlineGames.forEach((game, index) => {
                    const btn = document.createElement('button');
                    btn.className = 'game-btn';
                    btn.textContent = `${index + 1}. ${game.name}`;
                    btn.onclick = () => startGame(game);
                    gameButtons.appendChild(btn);
                });
            }

            setTimeout(() => modal.style.opacity = '1', 10);
        }

        function closeModal() {
            const modal = document.querySelector('.modal');
            if (modal) {
                modal.style.opacity = '0';
                setTimeout(() => modal.remove(), 300);
            }
        }

        function startGame(game) {
            closeModal();
            alert(`🎮 Starting ${game.name}!\n\n${game.desc}\n\n✨ Let's have fun together! This would connect you both in a real game! ✨`);
        }

        function sendMessage() {
            const message = document.getElementById('messageInput').value;
            if (message.trim()) {
                alert('Message sent! 💕\n\n"' + message + '"\n\nYour bestie will love hearing from you! ✨');
                document.getElementById('messageInput').value = '';
            } else {
                alert('Don\'t forget to write something sweet! 💭✨');
            }
        }

        // Add some interactive sparkles
        document.addEventListener('mousemove', function(e) {
            if (Math.random() > 0.98) {
                createSparkle(e.clientX, e.clientY);
            }
        });

        function createSparkle(x, y) {
            const sparkle = document.createElement('div');
            sparkle.innerHTML = '✨';
            sparkle.style.position = 'fixed';
            sparkle.style.left = x + 'px';
            sparkle.style.top = y + 'px';
            sparkle.style.pointerEvents = 'none';
            sparkle.style.fontSize = '20px';
            sparkle.style.zIndex = '1000';
            sparkle.style.animation = 'sparkle 1s ease-out forwards';
            document.body.appendChild(sparkle);
            
            setTimeout(() => {
                sparkle.remove();
            }, 1000);
        }
    </script>
</body>
</html>
