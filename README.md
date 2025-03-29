# loops-weeb
for malayali gaimers
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime World</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Anime World</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#anime-list">Anime List</a></li>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="anime-list">
        <h2>Popular Anime</h2>
        <div class="anime-container">
            <div class="anime-card" onclick="showMessage('Attack on Titan')">
                <img src="aot.jpg" alt="Attack on Titan">
                <h3>Attack on Titan</h3>
            </div>
            <div class="anime-card" onclick="showMessage('One Piece')">
                <img src="onepiece.jpg" alt="One Piece">
                <h3>One Piece</h3>
            </div>
            <div class="anime-card" onclick="showMessage('Jujutsu Kaisen')">
                <img src="jjk.jpg" alt="Jujutsu Kaisen">
                <h3>Jujutsu Kaisen</h3>
            </div>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 Anime World. All rights reserved.</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>
