<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About — The African Pantry Mahjong</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a3a, #0d1b2a);
            color: #e0e0e0;
            font-family: 'Segoe UI', 'Roboto', system-ui, sans-serif;
            line-height: 1.7;
            padding: 60px 20px;
            font-weight: 300;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(13, 27, 42, 0.9);
            border-radius: 8px;
            padding: 50px;
            box-shadow: 0 12px 40px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(200, 170, 120, 0.15);
        }
        
        h1 {
            color: #f9a826;
            font-weight: 400;
            font-size: 2.2rem;
            letter-spacing: 1px;
            margin-bottom: 20px;
            border-bottom: 1px solid rgba(249, 168, 38, 0.3);
            padding-bottom: 15px;
        }
        
        h2 {
            color: #f9a826;
            font-weight: 400;
            font-size: 1.6rem;
            margin: 50px 0 20px;
            letter-spacing: 0.5px;
        }
        
        h3 {
            color: #d4af7a;
            font-weight: 400;
            font-size: 1.2rem;
            margin: 30px 0 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        p {
            margin-bottom: 25px;
            color: #cbd5e0;
            font-size: 1rem;
        }
        
        .play-button {
            display: inline-block;
            background: transparent;
            color: #f9a826;
            text-decoration: none;
            padding: 12px 32px;
            border-radius: 0;
            font-weight: 400;
            font-size: 1.1rem;
            margin: 10px 0 30px;
            transition: all 0.2s ease;
            border: 1px solid #f9a826;
            letter-spacing: 1px;
        }
        
        .play-button:hover {
            background: #f9a826;
            color: #0d1b2a;
        }
        
        .ingredients-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
            gap: 12px 25px;
            margin: 30px 0 20px;
        }
        
        .ingredient-item {
            color: #cbd5e0;
            font-size: 0.95rem;
            padding: 6px 0;
            border-bottom: 1px dotted rgba(200, 170, 120, 0.2);
            display: flex;
            justify-content: space-between;
            align-items: baseline;
        }
        
        .ingredient-name {
            color: #d4af7a;
            font-weight: 400;
        }
        
        .ingredient-note {
            color: #8f9eb0;
            font-size: 0.85rem;
            font-style: italic;
        }
        
        .proverb {
            font-style: italic;
            color: #b8c7d6;
            font-size: 1.1rem;
            text-align: center;
            margin: 50px 0;
            padding: 25px 40px;
            border-top: 1px solid rgba(249, 168, 38, 0.2);
            border-bottom: 1px solid rgba(249, 168, 38, 0.2);
            background: rgba(10, 20, 30, 0.4);
            letter-spacing: 0.3px;
        }
        
        .how-to-play {
            background: rgba(20, 35, 50, 0.6);
            border-radius: 4px;
            padding: 35px;
            margin: 40px 0;
            border-left: 3px solid #f9a826;
        }
        
        .how-to-play ol {
            margin-left: 20px;
            color: #cbd5e0;
        }
        
        .how-to-play li {
            margin-bottom: 15px;
            padding-left: 10px;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 25px;
            margin: 35px 0;
        }
        
        .feature-item {
            background: rgba(20, 35, 50, 0.4);
            padding: 20px 25px;
            border-radius: 4px;
            border-left: 2px solid #8f9eb0;
            color: #cbd5e0;
            font-size: 0.95rem;
        }
        
        .footer {
            margin-top: 70px;
            padding-top: 30px;
            border-top: 1px solid rgba(200, 170, 120, 0.2);
            text-align: center;
            color: #7f8fa0;
            font-size: 0.9rem;
            letter-spacing: 0.3px;
        }
        
        .footer a {
            color: #cbd5e0;
            text-decoration: none;
            border-bottom: 1px dotted #7f8fa0;
        }
        
        .footer a:hover {
            color: #f9a826;
            border-bottom-color: #f9a826;
        }
        
        .tagline {
            font-size: 1.3rem;
            color: #d4af7a;
            text-align: center;
            margin: 50px 0 20px;
            font-weight: 300;
            letter-spacing: 2px;
        }
        
        .sub-tagline {
            text-align: center;
            color: #7f8fa0;
            font-size: 0.9rem;
            letter-spacing: 1px;
            text-transform: uppercase;
        }
        
        .section-intro {
            color: #b8c7d6;
            font-size: 1rem;
            margin-bottom: 25px;
            border-left: 2px solid #f9a826;
            padding-left: 20px;
        }
        
        hr {
            border: none;
            height: 1px;
            background: linear-gradient(90deg, transparent, rgba(249, 168, 38, 0.3), transparent);
            margin: 40px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>The African Pantry Mahjong</h1>
        <p style="font-size: 1.1rem; color: #b8c7d6;">A cultural matching game exploring the ingredients and foodways of Africa through play.</p>
        
        <a href="https://chicafricanculture.github.io/african-foodways-data/" class="play-button">PLAY THE GAME</a>
        
        <hr>
        
        <h2>About</h2>
        <p>The African Pantry Mahjong transforms the classic tile-matching game into a quiet journey through African cuisine. Each tile features a black-and-white icon of a real ingredient—clean, simple, and instantly recognizable. Every matched pair reveals a traditional recipe, a cultural fact, or cooking wisdom passed down through generations.</p>
        
        <div class="proverb">
            "The one who eats alone cannot discuss the taste of the food with others."
        </div>
        
        <h2>Ingredients</h2>
        <p class="section-intro">Twenty-two ingredients from across the continent's culinary traditions.</p>
        
        <div class="ingredients-list">
            <div class="ingredient-item"><span class="ingredient-name">Goat</span> <span class="ingredient-note">pepper soup, ceremonial dishes</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Cow</span> <span class="ingredient-note">suya, rich stews</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Crab</span> <span class="ingredient-note">coastal soups, crab pepper soup</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Egg</span> <span class="ingredient-note">Ghanaian egg stew, puff-puff</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Fire</span> <span class="ingredient-note">traditional cooking methods</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Fish</span> <span class="ingredient-note">grilled tilapia, fish pepper soups</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Fishing</span> <span class="ingredient-note">river and coastal communities</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Maggi</span> <span class="ingredient-note">essential seasoning</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Mortar</span> <span class="ingredient-note">pounding fufu, grinding spices</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Palm Oil</span> <span class="ingredient-note">banga soup, essential for stews</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Pepper</span> <span class="ingredient-note">Scotch bonnet, spice blends</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Pot</span> <span class="ingredient-note">one-pot cooking, communal meals</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Rice</span> <span class="ingredient-note">jollof, coconut rice</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Salt</span> <span class="ingredient-note">preservation and flavor</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Vegetables</span> <span class="ingredient-note">cassava leaves, bitterleaf</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Water</span> <span class="ingredient-note">foundation of all cooking</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Wood</span> <span class="ingredient-note">fuel for traditional fires</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Yam</span> <span class="ingredient-note">asaro, boiled yam with sauces</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Plantain</span> <span class="ingredient-note">kelewele, dodo</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Peanuts</span> <span class="ingredient-note">groundnut stew, mafé</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Beans</span> <span class="ingredient-note">gbegiri, ewa aganyin</span></div>
            <div class="ingredient-item"><span class="ingredient-name">Okra</span> <span class="ingredient-note">okra soup, draw soup</span></div>
        </div>
        
        <h2>Play</h2>
        <div class="how-to-play">
            <ol>
                <li><strong>Match identical ingredients</strong> by selecting two free tiles.</li>
                <li><strong>Only top tiles</strong> on stacks can be selected — as in classic mahjong.</li>
                <li><strong>Clear the board</strong> to advance. Each level adds more stacked tiles.</li>
                <li><strong>Learn as you play</strong> — each match reveals a recipe or food fact.</li>
                <li><strong>Use hints or shuffle</strong> when stuck. The game adapts.</li>
            </ol>
        </div>
        
        <h2>Learning Through Play</h2>
        <p>The game is designed for knowledge to emerge naturally through play, not instruction. By clearing the board, players encounter:</p>
        
        <div class="feature-grid">
            <div class="feature-item">Regional dishes from across Africa</div>
            <div class="feature-item">Cooking techniques and traditions</div>
            <div class="feature-item">Cultural significance of ingredients</div>
            <div class="feature-item">How food connects communities</div>
        </div>
        
        <div class="proverb">
            "The firewood that cooks the food is the same one that burns the cook."
        </div>
        
        <h2>Project</h2>
        <p>Built with HTML5, CSS3, and JavaScript. Custom black-and-white icons. Responsive design for desktop and mobile.</p>
        
        <p>Part of the <strong>African Foodways Project</strong> — an initiative to document, celebrate, and share the diverse food traditions of Africa. <a href="https://chicafricanculture.github.io/african-foodways-data/" style="color: #f9a826; text-decoration: none; border-bottom: 1px dotted;">Visit the main archive →</a></p>
        
        <p style="margin-top: 30px;">Contributions welcome. The African pantry is vast. <a href="#" style="color: #f9a826; text-decoration: none; border-bottom: 1px dotted;">GitHub</a></p>
        
        <hr>
        
        <div class="tagline">
            Match tiles. Discover tastes. Explore the pantry.
        </div>
        <div class="sub-tagline">
            The African Pantry Mahjong — where every match tells a story.
        </div>
        
        <div class="footer">
            <p>© 2024 The African Foodways Project · <a href="#">MIT License</a></p>
            <p style="margin-top: 15px; font-size: 0.85rem;">Inspired by traditional African cooking and the wisdom of grandmothers everywhere.</p>
        </div>
    </div>
</body>
</html>
