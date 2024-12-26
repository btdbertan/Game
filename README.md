# Game <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sesli Komut Oyunu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="game-container">
        <h1>Sesli Komutlarla Oyun</h1>
        <button id="start-btn">Oyunu Başlat</button>
        <div id="objects-container">
            <div id="tree" class="game-object">Ağaç</div>
            <div id="car" class="game-object">Araba</div>
            <div id="house" class="game-object">Ev</div>
        </div>
        <p id="status">Komut vermek için "create tree", "create car" veya "spawn house" diyebilirsiniz.</p>
    </div>
    
    <script src="app.js"></script>
</body>
</html>
