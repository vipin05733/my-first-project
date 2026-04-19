# my-first-project
I went to the AI Impact Summit 2026 in New Delhi on behalf of my college. I really enjoyed it because it was the first time I had attended an event on behalf of my college. I'm very happy to say this. I made a code and posted it below after returning from there.

<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AI Impact Summit | Vipin</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

<style>
:root{
    --bg:#020617;
    --accent:#38bdf8;
    --glass:rgba(255,255,255,0.08);
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
    scroll-behavior:smooth;
}

body{
    background:var(--bg);
    color:white;
    overflow-x:hidden;
}

/* Particles Background */
#particles-js{
    position:fixed;
    width:100%;
    height:100%;
    z-index:-1;
}

/* Navbar */
nav{
    display:flex;
    justify-content:space-between;
    padding:20px 8%;
    position:sticky;
    top:0;
    backdrop-filter:blur(10px);
    background:rgba(2,6,23,0.7);
}

.logo{
    font-weight:700;
    color:var(--accent);
}

/* Hero */
.hero{
    text-align:center;
    padding:100px 20px 60px;
}

.profile-img{
    width:170px;
    height:170px;
    border-radius:50%;
    object-fit:cover;
    border:4px solid var(--accent);
    box-shadow:0 0 40px rgba(56,189,248,0.6);
    animation:float 4s ease-in-out infinite;
}

@keyframes float{
    0%{transform:translateY(0);}
    50%{transform:translateY(-12px);}
    100%{transform:translateY(0);}
}

.hero h1{
    margin-top:25px;
    font-size:2.3rem;
    background:linear-gradient(90deg,#38bdf8,#0ea5e9);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

/* Glass Card */
.section{
    max-width:1000px;
    margin:60px auto;
    padding:40px;
    background:var(--glass);
    border-radius:20px;
    backdrop-filter:blur(15px);
    border:1px solid rgba(255,255,255,0.1);
}

/* Slider */
.slider{
    position:relative;
    max-width:900px;
    margin:auto;
    overflow:hidden;
    border-radius:20px;
}

.slides{
    display:flex;
    width:600%;
    animation:slide 24s infinite;
}

.slides img{
    width:100%;
    height:450px;
    object-fit:cover;
}

@keyframes slide{
    0%{margin-left:0;}
    15%{margin-left:0;}
    20%{margin-left:-100%;}
    35%{margin-left:-100%;}
    40%{margin-left:-200%;}
    55%{margin-left:-200%;}
    60%{margin-left:-300%;}
    75%{margin-left:-300%;}
    80%{margin-left:-400%;}
    95%{margin-left:-400%;}
    100%{margin-left:-500%;}
}

footer{
    text-align:center;
    padding:30px;
    color:#94a3b8;
}
</style>
</head>

<body>

<div id="particles-js"></div>

<nav>
<div class="logo">AI Summit 2024</div>
</nav>

<section class="hero">
<img src="IMG-20260216-WA0202.jpg" class="profile-img">
<h1>AI Impact Summit - Delhi</h1>
<p style="margin-top:20px;color:#cbd5e1;max-width:700px;margin-left:auto;margin-right:auto;">
Yeh summit mere liye ek life-changing experience raha jahan maine AI innovation,
future technology aur industry leaders se real-world insights seekhe.
</p>
</section>

<section class="section">
<h2 style="color:var(--accent);margin-bottom:30px;text-align:center;">Event Gallery</h2>

<div class="slider">
<div class="slides">
<img src="IMG-20260216-WA0202.jpg">
<img src="1771489075102.jpg">
<img src="IMG_20260220_103448_5.jpg">
<img src="IMG_20260217_183756_852.jpg">
<img src="IMG-20260217-WA0093.jpg">
<img src="IMG-20260216-WA0215.jpg">
</div>
</div>
</section>

<footer>
© 2024 Vipin | AI Impact Summit Experience
</footer>

<!-- Particles JS -->
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>

<script>
particlesJS("particles-js",{
  particles:{
    number:{value:60},
    size:{value:3},
    color:{value:"#38bdf8"},
    line_linked:{enable:true,color:"#38bdf8"},
    move:{speed:2}
  }
});
</script>

</body>
</html>
