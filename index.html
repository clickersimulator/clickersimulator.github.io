<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pet Catalog Index</title>
    <style>
        :root {
            --bg-color: #0c0d10;
            --card-bg: #14161b;
            --border-color: #1f232b;
            --accent-color: #3b82f6;
            --text-main: #f3f4f6;
            --text-muted: #9ca3af;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            padding: 50px 20px;
            overflow-x: hidden;
        }

        header {
            text-align: center;
            margin-bottom: 50px;
            opacity: 0;
            transform: translateY(-20px);
            animation: fadeInDown 0.8s cubic-bezier(0.16, 1, 0.3, 1) forwards;
        }

        h1 {
            font-size: 2.8rem;
            font-weight: 800;
            letter-spacing: -1.5px;
            color: #ffffff;
            margin-bottom: 12px;
        }

        .counter-badge {
            display: inline-block;
            background: rgba(59, 130, 246, 0.1);
            color: var(--accent-color);
            border: 1px solid rgba(59, 130, 246, 0.2);
            padding: 6px 16px;
            border-radius: 50px;
            font-size: 0.95rem;
            font-weight: 600;
            letter-spacing: -0.2px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(210px, 1fr));
            gap: 24px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 14px;
            padding: 24px 16px;
            text-align: center;
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUp 0.6s cubic-bezier(0.16, 1, 0.3, 1) forwards;
            transition: transform 0.3s cubic-bezier(0.16, 1, 0.3, 1), border-color 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-6px) scale(1.02);
            border-color: rgba(59, 130, 246, 0.5);
            box-shadow: 0 12px 30px -10px rgba(59, 130, 246, 0.2);
        }

        .icon-container {
            width: 100px;
            height: 100px;
            margin: 0 auto 18px auto;
            background: #1a1d24;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 12px;
            transition: transform 0.3s ease;
        }

        .card:hover .icon-container {
            transform: scale(1.08);
        }

        .icon-container img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
            filter: drop-shadow(0 4px 8px rgba(0,0,0,0.3));
        }

        .pet-name {
            font-size: 1.05rem;
            font-weight: 600;
            color: var(--text-main);
            margin-bottom: 6px;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        .pet-id {
            font-size: 0.75rem;
            color: var(--text-muted);
            font-family: monospace;
        }

        footer {
            text-align: center;
            margin-top: 60px;
            color: var(--text-muted);
            font-size: 0.9rem;
            opacity: 0;
            animation: fadeInDown 0.8s cubic-bezier(0.16, 1, 0.3, 1) 0.5s forwards;
        }

        @keyframes fadeInDown {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Pet Collection Index</h1>
        <div class="counter-badge" id="counterBadge">Loading pets...</div>
    </header>

    <div class="grid" id="petGrid"></div>

    <footer>
        site made by parkerdv
    </footer>

    <script>
        const petsData = [
            { id: "Chocolate", name: "Chocolate", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=88579842245566&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "MoltenSlime", name: "Molten Slime", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=101193237026541&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Tiger", name: "Tiger", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=95596298936664&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "CherubisBloom", name: "Cherubis Bloom", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=124617723377564&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "TheOverlord", name: "The Overlord", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=97919633977640&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "ReversedDog", name: "Reversed Dog", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=117279998342366&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "RedSeahorse", name: "Red Seahorse", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=107005491414695&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "BlackBear", name: "Black Bear", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=100849484124283&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "DiscoBall", name: "Disco Ball", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=126155707363304&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Kitsune", name: "Kitsune", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=130514860854088&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Zebra", name: "Zebra", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=110421432076873&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "PurpleJellyfish", name: "Purple Jellyfish", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=106815127190613&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "ChestMimicInABucket", name: "Chest Mimic In A Bucket", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=122308136266050&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Crab", name: "Crab", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=106101390579826&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "ChocolateIceCream", name: "Chocolate Ice Cream", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=103695890628134&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "CatInABucket", name: "Cat In A Bucket", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=110017610202834&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Deer", name: "Deer", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=102567070166623&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "IceCream", name: "Ice Cream", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=123120221719628&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "ReversedCat", name: "Reversed Cat", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=73922675494304&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Unicorn", name: "Unicorn", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=94950279525592&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Monkey", name: "Monkey", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=76566737639052&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "PartyCogmower", name: "Party Cogmower", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=111691424014620&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Squirrel", name: "Squirrel", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=75141867203901&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "MagmaCube", name: "Magma Cube", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=72364434873752&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Hellwing", name: "Hellwing", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=137075188552606&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Wolf", name: "Wolf", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=138215752939932&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "BlueJellyfish", name: "Blue Jellyfish", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=88318732629648&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Acorn", name: "Acorn", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=121864183808487&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Cupcake", name: "Cupcake", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=128905816444157&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Goat", name: "Goat", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=100840643293388&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Bee", name: "Bee", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=75437677377369&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Raccoon", name: "Raccoon", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=133670805606540&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "YellowSeahorse", name: "Yellow Seahorse", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=107722451853461&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Pufferfish", name: "Pufferfish", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=102535973943066&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "BubbleGum", name: "Bubble Gum", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=84348209283744&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Cookieman", name: "Cookieman", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=113484920991712&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Equalizer", name: "Equalizer", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=101667041174340&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Snake", name: "Snake", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=123785830108382&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "ChestMimic", name: "Chest Mimic", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=92749426462005&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Elephant", name: "Elephant", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=127429039913734&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Skier", name: "Skier", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=133308426943862&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Giraffe", name: "Giraffe", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=124786611820303&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Owl", name: "Owl", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=107483178343791&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Ktulhu", name: "Ktulhu", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=111184864451932&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Cactus", name: "Cactus", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=127314117919964&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Cheetah", name: "Cheetah", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=72914760626794&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Penguin", name: "Penguin", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=107610673949818&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Bull", name: "Bull", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=105852961774706&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Yeti", name: "Yeti", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=95091967341491&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "AureliteHalo", name: "Aurelite Halo", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=70982658481418&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Starforge", name: "Starforge", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=76782769566021&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Slime", name: "Slime", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=89345627737735&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Lion", name: "Lion", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=126606000761880&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Mouse", name: "Mouse", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=72274074632743&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Snowman", name: "Snowman", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=93654987601779&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Candy", name: "Candy", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=95584489425177&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "CandyDominus", name: "Candy Dominus", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=82795329520323&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "HellfireBat", name: "Hellfire Bat", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=102029048545841&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "SummerDog", name: "Summer Dog", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=139895329802162&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Fox", name: "Fox", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=88839098262704&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "SakuraTurtle", name: "Sakura Turtle", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=115616671857870&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Turtle", name: "Turtle", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=125290338866815&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Poseidon", name: "Poseidon", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=98743994253100&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Tanuki", name: "Tanuki", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=124299252102658&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Strawberry", name: "Strawberry", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=124916911644687&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "GodlyGem", name: "Godly Gem", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=114654108504631&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Pig", name: "Pig", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=77488028236584&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Shark", name: "Shark", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=86472498546769&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Shell", name: "Shell", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=124964487894708&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Calf", name: "Calf", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=97812410796433&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "SummerCat", name: "Summer Cat", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=128065489833609&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Duck", name: "Duck", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=74730912211465&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "CoreGuardian", name: "Core Guardian", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=98064774940672&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Cow", name: "Cow", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=116193935880630&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "GoldFish", name: "Gold Fish", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=86590960041962&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Ophanim", name: "Ophanim", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=99580393209518&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "DogInABucket", name: "Dog In A Bucket", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=96478946438068&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Fish", name: "Fish", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=105943860706214&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Kraken", name: "Kraken", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=87878967180615&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Cat", name: "Cat", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=90402349428850&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "StarFish", name: "Star Fish", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=80877936356719&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Swimmer", name: "Swimmer", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=121290263315258&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Frog", name: "Frog", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=84586002155513&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Dog", name: "Dog", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=84816537610420&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Bunny", name: "Bunny", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=104763135259770&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "PetalMoth", name: "Petal Moth", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=129488213450565&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "TurtleInABucket", name: "Turtle In A Bucket", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=126004551645658&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Spider", name: "Spider", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=79349989622603&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Cowboy", name: "Cowboy", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=103727699693840&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Bear", name: "Bear", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=130466798991896&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "BlackCat", name: "Black Cat", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=81156479883478&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Seal", name: "Seal", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=112684814892826&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Boombox", name: "Boombox", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=86349572042892&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Camel", name: "Camel", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=104897716469948&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Poly", name: "Poly", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=72700884296344&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "CandyGun", name: "Candy Gun", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=77766252091625&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "LotusSerpent", name: "Lotus Serpent", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=132051694605745&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Gorilla", name: "Gorilla", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=111732465618458&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "Phoenix", name: "Phoenix", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=124071335203484&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "HolyEgg", name: "Holy Egg", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=93430094725986&returnPolicy=2&size=150x150&format=Png&isCircular=false" },
            { id: "PolarBear", name: "Polar Bear", icon: "https://thumbnails.roblox.com/v1/assets?assetIds=92922411418772&returnPolicy=2&size=150x150&format=Png&isCircular=false" }
        ];

        document.getElementById('counterBadge').textContent = `Total Pets: ${petsData.length}`;

        const grid = document.getElementById('petGrid');

        petsData.forEach((pet, index) => {
            const card = document.createElement('div');
            card.className = 'card';
            card.style.animationDelay = `${Math.min(index * 0.03, 1.2)}s`;
            
            card.innerHTML = `
                <div class="icon-container">
                    <img src="${pet.icon}" alt="${pet.name}" loading="lazy">
                </div>
                <div class="pet-name">${pet.name}</div>
                <div class="pet-id">${pet.id}</div>
            `;
            
            grid.appendChild(card);
        });
    </script>
</body>
</html>
