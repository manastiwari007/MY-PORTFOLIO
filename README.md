# MY PORTFOLIO
PORTFOLIO
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Manas Tiwari | AI/ML Engineer in the making</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,600;9..144,800&family=Figtree:wght@400;500;600&display=swap">
<style>
:root{--bg:#060a16;--surface:rgba(255,255,255,.05);--ink:#eef3ff;--muted:#9fb0d4;--line:rgba(140,170,255,.18);--accent:#5b9bff;--accent2:#7fe3ff;--glow:rgba(91,155,255,.35);--btn-ink:#04101f;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:light){:root:not([data-theme="dark"]){--bg:#f4f7ff;--surface:#fff;--ink:#0b1f4d;--muted:#4a5a7d;--line:#cfe0fb;--accent:#1f5fe0;--accent2:#0a8fb8;--glow:rgba(31,95,224,.18);--btn-ink:#fff}}
:root[data-theme="light"]{--bg:#f4f7ff;--surface:#fff;--ink:#0b1f4d;--muted:#4a5a7d;--line:#cfe0fb;--accent:#1f5fe0;--accent2:#0a8fb8;--glow:rgba(31,95,224,.18);--btn-ink:#fff}
html{scroll-padding-top:80px;scroll-behavior:smooth}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}*{animation:none!important;transition:none!important}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 17px/1.65 Figtree,system-ui,sans-serif;overflow-x:hidden}
a{color:var(--accent)}
:focus-visible{outline:3px solid var(--accent2);outline-offset:3px}
.wrap{max-width:1080px;margin:0 auto;padding:0 24px}
.bar{position:sticky;top:0;z-index:20;padding-top:env(safe-area-inset-top,0px);backdrop-filter:blur(14px);background:color-mix(in srgb,var(--bg) 70%,transparent);border-bottom:1px solid var(--line)}
.bar .wrap{display:flex;align-items:center;justify-content:space-between;gap:12px;height:64px}
.bar b{font:800 20px Fraunces,Georgia,serif}
nav{display:flex;align-items:center;gap:6px;flex-wrap:wrap}
nav a{padding:6px 12px;color:var(--ink);text-decoration:none;font-weight:500;border-radius:99px}
nav a:hover{background:var(--surface)}
.btn{display:inline-flex;align-items:center;gap:8px;padding:13px 26px;border-radius:99px;border:0;cursor:pointer;font:600 16px Figtree,sans-serif;text-decoration:none;color:var(--btn-ink);background:linear-gradient(135deg,var(--accent),var(--accent2));box-shadow:0 8px 30px var(--glow);transition:transform .2s,box-shadow .2s}
.btn:hover{transform:translateY(-3px);box-shadow:0 14px 40px var(--glow)}
.btn.ghost{background:transparent;color:var(--ink);border:1.5px solid var(--line);box-shadow:none}
.btn.ghost:hover{border-color:var(--accent)}
.btn.sm{padding:8px 16px;font-size:14px}
.icon{width:42px;height:42px;padding:0;justify-content:center}
.hero{position:relative;padding:90px 0 100px;overflow:hidden}
.hero::before{content:"";position:absolute;width:640px;height:640px;right:-160px;top:-120px;background:radial-gradient(circle,var(--glow),transparent 65%);pointer-events:none}
.hero .wrap{display:grid;grid-template-columns:1.2fr .8fr;gap:56px;align-items:center;position:relative}
.hero h1{font:800 clamp(52px,8.5vw,108px)/.95 Fraunces,Georgia,serif;margin:0 0 24px;letter-spacing:-.03em;animation:rise .9s both}
.role{font:600 20px Figtree,sans-serif;color:var(--accent2);margin:0 0 18px}
.hero p.lead{max-width:30em;font-size:19px;color:var(--muted);margin:0 0 32px}
.cta{display:flex;flex-wrap:wrap;gap:12px}
.photo{justify-self:center;position:relative;animation:rise 1.1s .2s both}
.photo img{width:min(340px,70vw);aspect-ratio:1;border-radius:50%;object-fit:cover;display:block;border:3px solid var(--accent);box-shadow:0 0 0 14px var(--surface),0 30px 80px var(--glow)}
@keyframes rise{from{opacity:0;transform:translateY(28px)}to{opacity:1;transform:none}}
section{padding:72px 0}
h2{font:800 clamp(32px,4.5vw,46px)/1.1 Fraunces,Georgia,serif;margin:0 0 32px;letter-spacing:-.02em}
.about{max-width:44em;color:var(--muted);font-size:19px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
.card{background:var(--surface);border:1px solid var(--line);border-radius:20px;padding:28px;backdrop-filter:blur(8px);transition:transform .25s,border-color .25s}
.card:hover{transform:translateY(-6px);border-color:var(--accent)}
.card h3{font:700 24px Fraunces,Georgia,serif;margin:0 0 10px}
.card p{margin:0 0 16px;color:var(--muted)}
.more{display:none;border-top:1px solid var(--line);padding-top:14px;margin-bottom:16px;color:var(--ink)}
.more.open{display:block}
.tag{display:inline-block;border:1px solid var(--line);padding:2px 12px;border-radius:99px;font-size:14px;margin:0 6px 14px 0;color:var(--accent2)}
.skills{display:flex;flex-wrap:wrap;gap:12px;padding:0;margin:0 0 16px;list-style:none}
.skills li{background:var(--surface);border:1px solid var(--line);padding:10px 20px;border-radius:99px;font-weight:600}
.skills.main li{background:linear-gradient(135deg,var(--accent),var(--accent2));color:var(--btn-ink);border:0}
.two{display:grid;grid-template-columns:1fr 1fr;gap:56px}
.timeline{border-left:2px solid var(--line);margin:0;padding:0 0 0 28px;list-style:none}
.timeline li{margin-bottom:30px;position:relative}
.timeline li::before{content:"";position:absolute;left:-37px;top:8px;width:16px;height:16px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 5px var(--glow)}
.timeline small{color:var(--accent2);font-weight:600}
.timeline h3{margin:2px 0;font-size:20px}
.timeline p{margin:0;color:var(--muted)}
.contact .card{text-align:center;padding:56px 24px;background:linear-gradient(135deg,var(--glow),var(--surface))}
.contact .cta{justify-content:center}
.contact p{color:var(--muted);margin:0 auto 28px;max-width:30em}
footer{text-align:center;padding:28px;color:var(--muted);font-size:14px}
#top{position:fixed;right:20px;bottom:calc(20px + env(safe-area-inset-bottom,0px));z-index:30;opacity:0;pointer-events:none;transition:opacity .25s}
#top.show{opacity:1;pointer-events:auto}
#toast{position:fixed;left:50%;bottom:calc(24px + env(safe-area-inset-bottom,0px));transform:translateX(-50%);background:var(--ink);color:var(--bg);padding:10px 20px;border-radius:99px;font-weight:600;opacity:0;pointer-events:none;transition:opacity .25s;z-index:40}
#toast.show{opacity:1}
@media(max-width:800px){.hero .wrap,.two{grid-template-columns:1fr}.photo{order:-1}nav a{display:none}.hero{padding-top:48px}}
</style>
</head>
<body>
<div class="bar"><div class="wrap">
<b>Manas Tiwari</b>
<nav><a href="#about">About</a><a href="#projects">Projects</a><a href="#skills">Skills</a><a href="#journey">Journey</a><a href="#contact">Contact</a>
<button class="btn ghost icon" id="theme" aria-label="Switch light or dark theme">◐</button></nav>
</div></div>

<header class="hero"><div class="wrap">
<div>
<p class="role">Aspiring Computer Science Engineer · AI &amp; Machine Learning</p>
<h1>Manas Tiwari</h1>
<p class="lead">I build useful apps in Python and Java, and I’m growing toward a career as a product manager.</p>
<div class="cta">
<a class="btn" href="#projects">View my projects</a>
<a class="btn ghost" href="mailto:Manastiwari007@icloud.com">Hire me</a>
<a class="btn ghost" href="https://linkedin.com/in/manastiwari007" rel="noopener">LinkedIn</a>
</div>
</div>
<div class="photo"><img src="photo.jpg" alt="Portrait of Manas Tiwari"></div>
</div></header>

<main class="wrap">
<section id="about">
<h2>About me</h2>
<p class="about">I’m a B.Tech CSE (AI/ML) student at Shri Ramswaroop Memorial University in Lucknow. I like turning ideas into working software, from fintech tools to weather and entertainment apps. With strong communication and people skills, I want to bring technical knowledge and a product mindset to a team where I can keep growing.</p>
</section>

<section id="projects">
<h2>Projects</h2>
<div class="grid">
<article class="card"><h3>CredMate</h3><p>A fintech project that helps people manage and understand their credit and money matters in one place.</p><div class="more">Built to make finance simple and clear for everyday users.</div><span class="tag">Fintech</span><span class="tag">Python</span><br><button class="btn sm toggle" aria-expanded="false">Details</button></article>
<article class="card"><h3>Weather GPT</h3><p>An AI-powered weather forecaster that explains the forecast in plain, conversational language.</p><div class="more">Ask about any city and get an easy-to-read forecast instead of raw numbers.</div><span class="tag">AI</span><span class="tag">Python</span><br><button class="btn sm toggle" aria-expanded="false">Details</button></article>
<article class="card"><h3>Web Series Suggester</h3><p>Recommends web series based on your tastes, so you spend less time scrolling and more time watching.</p><div class="more">Pick what you like and get a short list of shows worth starting next.</div><span class="tag">Recommender</span><span class="tag">Python</span><br><button class="btn sm toggle" aria-expanded="false">Details</button></article>
</div>
</section>

<section id="skills">
<h2>Skills</h2>
<ul class="skills main"><li>Python</li><li>Java</li><li>C++</li><li>HTML</li><li>CSS</li></ul>
<ul class="skills"><li>Artificial Intelligence</li><li>Graphic Design</li><li>Writing</li><li>Communication</li><li>Deep Thinking</li></ul>
<p style="color:var(--muted)">Languages: English, हिन्दी</p>
</section>

<section id="journey"><div class="two">
<div><h2>Education</h2>
<ul class="timeline">
<li><small>2025 – 2029 (present)</small><h3>B.Tech CSE with AI/ML</h3><p>Shri Ramswaroop Memorial University</p></li>
<li><small>2023 – 2025</small><h3>Vivekanand S.S.M Inter College</h3></li>
</ul></div>
<div><h2>Experience</h2>
<ul class="timeline">
<li><small>2024 – 2025</small><h3>Freelancer, Chandigarh University</h3><p>Worked on real-world artificial intelligence projects on the university campus in Unnao.</p></li>
<li><small>2023 – 2024</small><h3>Trends Management Program</h3><p>Built communication, management and interpersonal skills, with exposure to marketing and customer support.</p></li>
</ul></div>
</div></section>

<section id="contact" class="contact">
<div class="card">
<h2>Let’s work together</h2>
<p>Have an opportunity, a project or a question? Reach out in whichever way suits you.</p>
<div class="cta">
<a class="btn" href="mailto:Manastiwari007@icloud.com">Email me</a>
<button class="btn ghost" id="copy">Copy email</button>
<a class="btn ghost" href="https://linkedin.com/in/manastiwari007" rel="noopener">LinkedIn</a>
<a class="btn ghost" href="tel:+919081497814">Call me</a>
</div>
<p style="margin-top:24px;margin-bottom:0">Lucknow, Uttar Pradesh, India</p>
</div>
</section>
</main>
<footer>© 2026 Manas Tiwari</footer>
<button class="btn icon" id="top" aria-label="Back to top">↑</button>
<div id="toast" role="status">Email copied</div>

<script>
document.querySelectorAll('.toggle').forEach(function(b){b.addEventListener('click',function(){
var m=b.parentNode.querySelector('.more'),o=m.classList.toggle('open');
b.textContent=o?'Hide details':'Details';b.setAttribute('aria-expanded',o)})});
var root=document.documentElement;
document.getElementById('theme').addEventListener('click',function(){
var dark=getComputedStyle(root).getPropertyValue('--bg').trim()==='#060a16';
root.setAttribute('data-theme',dark?'light':'dark')});
document.getElementById('copy').addEventListener('click',function(){
var t=document.getElementById('toast');
function ok(){t.classList.add('show');setTimeout(function(){t.classList.remove('show')},1800)}
try{navigator.clipboard.writeText('Manastiwari007@icloud.com').then(ok,function(){})}catch(e){}});
var up=document.getElementById('top');
up.addEventListener('click',function(){window.scrollTo({top:0})});
window.addEventListener('scroll',function(){up.classList.toggle('show',window.scrollY>500)});
</script>
</body>
</html>
