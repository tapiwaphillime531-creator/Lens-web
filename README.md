`<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A CORPORATE BADDIE'S CONFESSION🙈❤️</title>
<style>
/* GENERAL */
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  color: white;
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9)),
              url('https://images.unsplash.com/photo-1517649763962-0c623066013b');
  background-size: cover;
  background-position: center;
  overflow-x: hidden;
}
header {
  background: rgba(0,0,0,0.6);
  padding: 15px;
  backdrop-filter: blur(5px);
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 10;
}
header h1 { margin:0; color:#00ff88; }
nav a { color:white; margin:0 15px; text-decoration:none; font-weight:bold; cursor:pointer; }
nav a:hover { color:#00ff88; }

/* SECTIONS */
section {
  padding: 120px 20px 80px 20px;
  min-height: 100vh;
  display: none;
}
section.active { display: block; }

.hero h2 { font-size:42px; color:#00ff88; }

/* BUTTONS */
.btn {
  background:#00ff88; color:black; border:none; padding:12px 25px; font-size:16px;
  cursor:pointer; margin-top:20px; border-radius:25px; font-weight:bold; transition:0.3s;
}
.btn:hover { background:#00cc6a; transform:scale(1.05); }

/* CARDS */
.reasons { display:flex; flex-wrap:wrap; justify-content:center; }
.card { background: rgba(0,0,0,0.6); margin:15px; padding:20px; width:250px;
  border-radius:15px; border:1px solid #00ff88; backdrop-filter:blur(5px); transition:0.3s; }
.card:hover { transform:translateY(-10px); }

/* CONFESSION & PROPOSAL */
#proposal { display:none; }
.question { font-size:28px; margin-bottom:40px; color:#00ff88; animation:fadeIn 2s ease-in-out; }
@keyframes fadeIn { from{opacity:0; transform:translateY(30px);} to{opacity:1; transform:translateY(0);} }
.buttons { position:relative; height:200px; }
.yes-btn { background:#00ff88; color:black; }
.no-btn { background:red; color:white; position:absolute; left:60%; top:50%; transition:0.2s; }

/* PROGRESS BARS */
.bar { margin:20px auto; width:80%; max-width:400px; }
.progress { background:#222; border-radius:20px; overflow:hidden; }
.progress span { display:block; height:20px; background:#00ff88; animation:load 2s ease-in-out; }
@keyframes load { from{width:0;} to{width:100%;} }

/* FOOTBALL ANIMATION */
.football {
  width:60px; height:60px;
  background:url('https://upload.wikimedia.org/wikipedia/commons/d/d3/Soccerball.svg') no-repeat center/cover;
  position:fixed; bottom:20px; left:-80px; animation:moveBall 8s linear infinite; z-index:5;
}
@keyframes moveBall { 0%{left:-80px; transform:rotate(0deg);} 100%{left:110%; transform:rotate(720deg);} }

body { padding-top:70px; }
</style>
</head>
<body>

<header>
  <h1>A CORPORATE BADDIE'S CONFESSION🙈❤️</h1>
  <nav>
    <a onclick="showSection('home')">Home</a>
    <a onclick="showSection('about')">About</a>
    <a onclick="showSection('reasons')">Why I Love You</a>
    <a onclick="showSection('confession')">Confession</a>
  </nav>
</header>

<section id="home" class="active">
  <h2>Hey LENS🥹💖</h2>
  <p>I made something special just for you…I hope you like it😭😭😭😭😭😭😭❤️❤️</p>
</section>

<section id="about">
  <h2>About Us 💑</h2>
  <p>From the moment we met, everything felt different. You make my world brighter.You are my
    motivation aswell.🥹❤️I love how you always encourage me to do stuff like going to the gym etc.
    🥹❤️I made the theme of this website to be all about fitness to show you how far am willing to 
    go for you🥹❤️i want you to feel loved and appreciated because you are absolutely the best.
  </p>
</section>

<section id="reasons">
  <h2>Why I Love You 💕</h2>
  <div class="reasons">
    <div class="card"><h3>Your Smile 😊</h3><p>Makes everything better not forgetting to mention 
    your wonderful voice and amusing laugh🥹❤️.
    </p></div>
    <div class="card"><h3>Your Energy ⚡</h3><p>Lights up every room.I really like the fact that 
      i can be my full self around you.🥹❤️❤️!
    </i></p></div>
    <div class="card"><h3>You 💖</h3><p>I love everything about you. Please dont change pookie🥹❤️
      am always here for you aswell.🙈❤️
    </p></div>
  </div>

  <h2>How Much I Like You 😏</h2>
  <div class="bar"><p>Thinking about you 💭</p><div class="progress"><span style="width:80%"></span></div></div>
  <div class="bar"><p>Missing you 🥺</p><div class="progress"><span style="width:100%"></span></div></div>
  <div class="bar"><p>Liking you ❤️</p><div class="progress"><span style="width:100%"></span></div></div>
</section>

<section id="confession">
  <h2>My Confession 💌</h2>
  <p>From the moment we started talking you have made me feel special.We clicked immediately as
    if we have been talking for years🥹❤️Whenever i feel sad i know i can turn to you and you 
    would make me feel like a million bucks instantly🥹❤️You make me feel loved , seen and
    appreciated.You really are an answered preyer.Thank you for coming into my life Mr Raditlhong
    you are exactly what i needed.🥹😘" </iframe>❤️</p>
  <button class="btn" onclick="showProposal()">Click Me 😏</button>

  <div id="proposal">
    <h2 class="question">CAN YOU BE MY BOYFRIEND😭❤️ 
      SINCE YOU ARE TAKING A MILLION YEARS TO ASK ME😒❤️!</h2>
    <div class="buttons">
      <button class="btn yes-btn" onclick="sayYes()">YES 💖</button>
      <button class="btn no-btn" id="noBtn">NO 😒</button>
    </div>
  </div>
</section>

<footer>
  <p>Made with ❤️ just for you</p>
</footer>

<div class="football"></div>

<section id="music">
  <h2>Background Music 🎶</h2>

  <iframe width="0" height="0"
    src="https://www.youtube.com/embed/PWf8jHWrK5k?autoplay=1&loop=1&playlist=PWf8jHWrK5k"
    title="Is It a Crime by Mariah the Scientist & Kali Uchis"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen>
  </iframe>
</section>

<script>
// SINGLE PAGE NAVIGATION
function showSection(id) {
  document.querySelectorAll('section').forEach(sec => sec.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}

// PROPOSAL BUTTON
function showProposal() {
  document.getElementById('proposal').style.display = 'block';
  window.scrollTo({ top: document.getElementById('proposal').offsetTop, behavior:'smooth' });
}

function sayYes() {
  alert('YAYYY!! 😍❤️');
}

// NO BUTTON RUNAWAY
const noBtn = document.getElementById('noBtn');
noBtn.addEventListener('mouseover', moveButton);
noBtn.addEventListener('click', moveButton);

function moveButton() {
  const x = Math.random() * window.innerWidth * 0.7;
  const y = Math.random() * window.innerHeight * 0.6;
  noBtn.style.position='absolute';
  noBtn.style.left = x + 'px';
  noBtn.style.top = y + 'px';
}
</script>


</body>
</html>
