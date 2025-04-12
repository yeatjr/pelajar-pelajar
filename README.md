# pelajar-pelajar

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pixel Quest | Retro Gaming</title>
    <style>
        /* Pixel Art Styling */
        body {
            background-color: #1a1a2e;
            color: #e6e6e6;
            font-family: 'Press Start 2P', cursive;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            image-rendering: pixelated;
        }

        @font-face {
            font-family: 'Press Start 2P';
            src: url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
        }

        /* Pixel Border */
        .pixel-border {
            border-style: solid;
            border-width: 4px;
            border-color: #4a4a4a #e6e6e6 #e6e6e6 #4a4a4a;
            box-shadow: 4px 4px 0px #000000;
        }

        /* Header */
        header {
            background-color: #2d2d44;
            padding: 20px;
            text-align: center;
            border-bottom: 8px dotted #4a4a4a;
        }

        h1 {
            color: #ff5555;
            text-shadow: 4px 4px 0px #000000;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        /* Navigation */
        nav {
            background-color: #33334d;
            padding: 10px 0;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav li {
            margin: 0 15px;
        }

        nav a {
            color: #55ff55;
            text-decoration: none;
            padding: 5px 10px;
            transition: all 0.3s;
        }

        nav a:hover {
            background-color: #ff5555;
            color: #000000;
        }

        /* Main Content */
        main {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Game Cards */
        .game-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .game-card {
            background-color: #2d2d44;
            padding: 15px;
            transition: transform 0.3s;
        }

        .game-card:hover {
            transform: scale(1.05);
        }

        .game-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border: 4px solid #4a4a4a;
        }

        .game-card h3 {
            color: #55ffff;
            margin: 10px 0;
        }

        .game-card p {
            font-size: 0.8rem;
            color: #aaaaaa;
        }

        .play-btn {
            display: inline-block;
            background-color: #55ff55;
            color: #000000;
            padding: 8px 15px;
            margin-top: 10px;
            text-decoration: none;
            font-size: 0.8rem;
        }

        /* Featured Game */
        .featured-game {
            background-color: #33334d;
            padding: 20px;
            margin-bottom: 30px;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
        }

        .featured-game img {
            width: 300px;
            height: 200px;
            margin-right: 20px;
            border: 8px solid #4a4a4a;
        }

        .featured-content {
            flex: 1;
            min-width: 250px;
        }

        /* Footer */
        footer {
            background-color: #1a1a2e;
            text-align: center;
            padding: 20px;
            border-top: 8px dotted #4a4a4a;
            font-size: 0.7rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 5px 0;
            }
            
            .featured-game {
                flex-direction: column;
            }
            
            .featured-game img {
                margin-right: 0;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>
    <header class="pixel-border">
        <h1>PIXEL QUEST</h1>
        <p>RETRO GAMING EXPERIENCE</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">HOME</a></li>
            <li><a href="#games">GAMES</a></li>
            <li><a href="#about">ABOUT</a></li>
            <li><a href="#community">COMMUNITY</a></li>
            <li><a href="#contact">CONTACT</a></li>
        </ul>
    </nav>

    <main>
        <section id="featured" class="featured-game pixel-border">
            <img src="https://via.placeholder.com/300x200/33334d/55ff55?text=FEATURED+GAME" alt="Featured Game">
            <div class="featured-content">
                <h2>DRAGON'S LEGACY</h2>
                <p>Embark on an epic pixel adventure to save the kingdom from the ancient dragon's wrath. Collect power-ups, defeat enemies, and uncover hidden treasures!</p>
                <a href="#play" class="play-btn pixel-border">PLAY NOW</a>
            </div>
        </section>

        <section id="games">
            <h2>OUR GAME COLLECTION</h2>
            <div class="game-grid">
                <div class="game-card pixel-border">
                    <img src="https://via.placeholder.com/250x150/33334d/55ffff?text=SPACE+INVADERS" alt="Space Invaders">
                    <h3>SPACE INVADERS</h3>
                    <p>Defend Earth from alien invasion in this classic arcade shooter.</p>
                    <a href="#play" class="play-btn pixel-border">PLAY</a>
                </div>

                <div class="game-card pixel-border">
                    <img src="https://via.placeholder.com/250x150/33334d/ff55ff?text=PIXEL+JUMPER" alt="Pixel Jumper">
                    <h3>PIXEL JUMPER</h3>
                    <p>Jump through platforms and avoid obstacles in this challenging platformer.</p>
                    <a href="#play" class="play-btn pixel-border">PLAY</a>
                </div>

                <div class="game-card pixel-border">
                    <img src="https://via.placeholder.com/250x150/33334d/ffff55?text=ZOMBIE+APOCALYPSE" alt="Zombie Apocalypse">
                    <h3>ZOMBIE APOCALYPSE</h3>
                    <p>Survive the zombie horde in this action-packed survival game.</p>
                    <a href="#play" class="play-btn pixel-border">PLAY</a>
                </div>

                <div class="game-card pixel-border">
                    <img src="https://via.placeholder.com/250x150/33334d/55ff55?text=PIXEL+RACER" alt="Pixel Racer">
                    <h3>PIXEL RACER</h3>
                    <p>Race against time in this retro-style top-down racing game.</p>
                    <a href="#play" class="play-btn pixel-border">PLAY</a>
                </div>
            </div>
        </section>

        <section id="about" class="pixel-border" style="padding: 20px; margin-top: 30px;">
            <h2>ABOUT PIXEL QUEST</h2>
            <p>Pixel Quest is dedicated to bringing you the best retro pixel games. Our team of passionate developers creates unique gaming experiences that capture the nostalgia of classic 8-bit and 16-bit eras while incorporating modern gameplay elements.</p>
            <p>All our games are browser-based and completely free to play. No downloads required!</p>
        </section>
    </main>

    <footer>
        <p>© 2023 PIXEL QUEST | RETRO GAMING PORTAL</p>
        <p>CREATED WITH ♥ BY PIXEL WIZARDS</p>
        <p style="font-size: 0.6rem; margin-top: 10px;">PRESS START TO CONTINUE</p>
    </footer>
</body>
</html>
