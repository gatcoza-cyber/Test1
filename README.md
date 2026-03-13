<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium Network Links</title>
    <style>
        :root {
            --bg-color: #0f0f0f;
            --card-bg: #1a1a1a;
            --accent-color: #ff00ff; /* Brand Pink/Purple */
            --text-color: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
            margin: 0;
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .link-container {
            width: 100%;
            max-width: 400px;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        /* The Link Card */
        .link-card {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            text-decoration: none;
            color: white;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid #333;
            position: relative;
        }

        /* Hover Effects */
        .link-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(255, 0, 255, 0.2);
            border-color: var(--accent-color);
        }

        .link-card img {
            width: 100%;
            display: block;
            transition: filter 0.3s ease;
        }

        .link-card:hover img {
            filter: brightness(1.1);
        }

        .link-info {
            padding: 15px;
            text-align: center;
            background: linear-gradient(transparent, rgba(0,0,0,0.8));
        }

        .link-title {
            font-weight: bold;
            font-size: 1.2rem;
            display: block;
        }

        .link-sub {
            font-size: 0.9rem;
            color: #aaa;
        }

        /* Play Button Overlay */
        .play-overlay {
            position: absolute;
            top: 40%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 40px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .link-card:hover .play-overlay {
            opacity: 1;
        }

    </style>
</head>
<body>

    <div class="header">
        <h1>Exclusive Access</h1>
        <p>Premium Content Networks</p>
    </div>

    <div class="link-container">

        <a href="https://(https://sl1nk.com/HZxvl)/hentai" class="link-card">
            <img src="https://path-to-your-image.png" alt="Hentai Pros">
            <div class="play-overlay">▶</div>
            <div class="link-info">
                <span class="link-title">Hentai Pros</span>
                <span class="link-sub">Uncensored 4K Animation</span>
            </div>
        </a>

        <a href="https://YOUR-AFFILIATE-URL.com/brazzers" class="link-card">
            <img src="https://path-to-brazzers-image.jpg" alt="Brazzers">
            <div class="play-overlay">▶</div>
            <div class="link-info">
                <span class="link-title">Brazzers Network</span>
                <span class="link-sub">The Industry Gold Standard</span>
            </div>
        </a>

        <a href="https://YOUR-AFFILIATE-URL.com/familysinners" class="link-card">
            <img src="https://path-to-family-image.jpg" alt="Family Sinners">
            <div class="play-overlay">▶</div>
            <div class="link-info">
                <span class="link-title">Family Sinners</span>
                <span class="link-sub">Exclusive Taboo Stories</span>
            </div>
        </a>

    </div>

</body>
</html>
