<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mason Fantasy Hockey</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Inter,Arial,sans-serif;
}

body{
    background:#0d1117;
    color:white;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:25px 8%;
    position:sticky;
    top:0;
    backdrop-filter:blur(12px);
    background:rgba(13,17,23,.8);
}

.logo{
    font-size:1.5rem;
    font-weight:800;
}

nav ul{
    display:flex;
    gap:30px;
    list-style:none;
}

nav a{
    color:#c9d1d9;
    text-decoration:none;
    transition:.3s;
}

nav a:hover{
    color:#58a6ff;
}

.hero{
    min-height:85vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:40px;
    background:
    linear-gradient(rgba(13,17,23,.8),
    rgba(13,17,23,.9)),
    url("https://images.unsplash.com/photo-1515703407324-5f753afd8be8?auto=format&fit=crop&w=2000&q=80");
    background-size:cover;
    background-position:center;
}

.hero h1{
    font-size:4rem;
    font-weight:900;
    margin-bottom:20px;
}

.hero p{
    max-width:700px;
    color:#c9d1d9;
    font-size:1.2rem;
    margin-bottom:35px;
}

.hero button{
    background:#58a6ff;
    border:none;
    padding:15px 30px;
    border-radius:12px;
    color:white;
    font-size:1rem;
    font-weight:700;
    cursor:pointer;
    transition:.3s;
}

.hero button:hover{
    transform:translateY(-3px);
}

.section{
    padding:80px 8%;
}

.section-title{
    text-align:center;
    font-size:2.5rem;
    margin-bottom:50px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:#161b22;
    border:1px solid #30363d;
    border-radius:20px;
    padding:30px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
    border-color:#58a6ff;
}

.card h3{
    margin-bottom:10px;
}

.card p{
    color:#8b949e;
}

.footer{
    text-align:center;
    padding:40px;
    border-top:1px solid #30363d;
    color:#8b949e;
}
</style>
</head>

<body>

<nav>
    <div class="logo">🏒 Mason Fantasy Hockey</div>

    <ul>
        <li>#Home</a></li>
        <li>#Standings</a></li>
        <li>#Draft Board</a></li>
        <li>#Records</a></li>
        <li>#Champions</a></li>
    </ul>
</nav>

<section class="hero">
    <h1>Fantasy Hockey Central</h1>

    <p>
        Draft boards, standings, power rankings, league history,
        records, and everything your league needs in one place.
    </p>

    <button>View League</button>
</section>

<section class="section">
    <h2 class="section-title">League Hub</h2>

    <div class="cards">

        <div class="card">
            <h3>📊 Standings</h3>
            <p>
                Follow the latest rankings and team records throughout the season.
            </p>
        </div>

        <div class="card">
            <h3>🔥 Power Rankings</h3>
            <p>
                Weekly rankings featuring trends, hot streaks, and analysis.
            </p>
        </div>

        <div class="card">
            <h3>🎯 Draft Board</h3>
            <p>
                Review current and historical drafts with full pick details.
            </p>
        </div>

        <div class="card">
            <h3>🏆 Hall of Champions</h3>
            <p>
                Celebrate league winners and championship history.
            </p>
        </div>

    </div>
</section>

<div class="footer">
    Mason Fantasy Hockey • Built with GitHub Pages
</div>

</body>
</html>
