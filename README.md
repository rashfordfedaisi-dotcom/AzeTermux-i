<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AzeTermux</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#080c10;
    color:white;
}

header{
    padding:20px;
    text-align:center;
    background:#111820;
    border-bottom:1px solid #26313d;
}

.logo{
    font-size:30px;
    font-weight:bold;
}

.logo span{
    color:#00ff88;
}

main{
    max-width:850px;
    margin:auto;
    padding:30px 20px;
}

.hero{
    text-align:center;
    padding:50px 10px;
}

.hero h1{
    font-size:45px;
}

.hero p{
    color:#aaa;
    font-size:18px;
}

.card{
    background:#111820;
    border:1px solid #26313d;
    border-radius:15px;
    padding:25px;
    margin:20px 0;
}

button{
    background:#00ff88;
    border:0;
    border-radius:10px;
    padding:13px 22px;
    font-weight:bold;
    font-size:16px;
}

footer{
    text-align:center;
    padding:30px;
    color:#777;
}
</style>
</head>

<body>

<header>
    <div class="logo">Aze<span>Termux</span></div>
</header>

<main>

<section class="hero">
    <h1>🚀 AzeTermux</h1>
    <p>Termux, Linux, Python və proqramlaşdırma dünyası.</p>
</section>

<div class="card">
    <h2>💻 Termux</h2>
    <p>Mobil cihazda Linux və proqramlaşdırmanı öyrən.</p>
    <button onclick="basla()">Başla</button>
    <p id="mesaj"></p>
</div>

<div class="card">
    <h2>🐍 Python</h2>
    <p>Python layihələri və faydalı kodlar.</p>
</div>

<div class="card">
    <h2>🛠️ Layihələr</h2>
    <p>AzeTermux layihələri burada paylaşılacaq.</p>
</div>

</main>

<footer>
    © 2026 AzeTermux
</footer>

<script>
function basla(){
    document.getElementById("mesaj").textContent =
    "AzeTermux-a xoş gəlmisən! 🔥";
}
</script>

</body>
</html>
