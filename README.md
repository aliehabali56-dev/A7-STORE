# A7-STORE
Trusted Recharging Online Games
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A7 STORE – Game Top-Ups</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

    <style>
        * {margin:0; padding:0; box-sizing:border-box;}
        body {font-family:'Poppins', sans-serif; background:#0d0f12; color:#fff; overflow-x:hidden;}

        header {
            display:flex; justify-content:space-between; align-items:center;
            padding:20px 5%; background:rgba(255,255,255,0.03); backdrop-filter:blur(10px);
        }
        header h1 {color:#4da6ff; font-size:26px;}
        nav a {margin-left:20px; text-decoration:none; color:#fff; font-weight:500; transition:0.3s;}
        nav a:hover {color:#4da6ff;}

        .hero {
            height:400px; display:flex; align-items:center; justify-content:flex-start;
            padding-left:5%; background:url('https://i.imgur.com/2DpQk5W.jpeg') center/cover no-repeat;
            position:relative;
        }
        .hero::after {
            content:""; position:absolute; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.5);
        }
        .hero-content {position:relative; color:#fff; max-width:500px;}
        .hero-content h2 {font-size:42px; margin-bottom:20px;}
        .hero-content button {
            padding:14px 28px; background:#4da6ff; border:none; border-radius:10px;
            font-weight:600; cursor:pointer; color:#000; transition:0.3s;
        }
        .hero-content button:hover {background:#77c0ff;}

        .section-title {
            text-align:center; font-size:28px; margin:40px 0 20px; color:#4da6ff;
        }

        .games-grid {
            display:grid; grid-template-columns:repeat(auto-fit, minmax(180px,1fr)); gap:20px;
            padding:0 5% 50px;
        }
        .game-card {
            background:#111418; border-radius:14px; overflow:hidden; border:1px solid rgba(255,255,255,0.08);
            transition:0.3s; cursor:pointer;
        }
        .game-card:hover {transform:translateY(-6px); border-color:#4da6ff;}
        .game-card img {width:100%; height:140px; object-fit:cover;}
        .game-card p {padding:12px; text-align:center; font-size:16px; font-weight:500;}

        .payments {text-align:center; padding-bottom:50px;}
        .payments img {width:130px; margin:10px;}

        footer {background:#0b0c0f; text-align:center; padding:20px; color:#777;}
    </style>
</head>

<body>
<header>
    <h1>A7 STORE</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Games</a>
        <a href="#">Support</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h2>Fast & Trusted Game Top-Ups • PUBG • Free Fire • FIFA • eFootball</h2>
        <button>Start Recharge</button>
    </div>
</section>

<h3 class="section-title">Popular Games</h3>
<section class="games-grid">
    <div class="game-card"><img src="https://i.imgur.com/aRlvpyB.jpeg"><p>PUBG Mobile</p></div>
    <div class="game-card"><img src="https://i.imgur.com/8FPjQn3.jpeg"><p>Free Fire</p></div>
    <div class="game-card"><img src="https://i.imgur.com/g0w7p47.jpeg"><p>FC Mobile</p></div>
    <div class="game-card"><img src="https://i.imgur.com/dk76foe.jpeg"><p>eFootball / PES</p></div>
    <div class="game-card"><img src="https://i.imgur.com/i9Yx86F.jpeg"><p>Clash of Clans</p></div>
    <div class="game-card"><img src="https://i.imgur.com/LnhkTzN.jpeg"><p>Clash Royale</p></div>
</section>

<h3 class="section-title">Payment Methods</h3>
<section class="payments">
    <img src="https://i.imgur.com/8nY8JQs.png" alt="Vodafone Cash">
    <img src="https://i.imgur.com/q3xY8Fm.png" alt="Orange Cash">
    <img src="https://i.imgur.com/d4nVxcC.png" alt="Etisalat Cash">
    <img src="https://i.imgur.com/Q7vCRyZ.png" alt="WE Pay">
</section>

<footer>© 2025 A7 STORE — All Rights Reserved.</footer>

</body>
</html>
