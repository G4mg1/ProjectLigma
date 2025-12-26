<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Project Ligma | Premium Roblox Experience</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root {
  --blue: #2563eb;
  --blue-hover: #1d4ed8;
  --text: #0f172a;
  --muted: #64748b;
  --border: rgba(229, 231, 235, 0.8);
  --bg: #ffffff;
  --card-bg: rgba(255, 255, 255, 0.7);
  --shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.05);
}

* { box-sizing: border-box; font-family: 'Inter', sans-serif; scroll-behavior: smooth; }

body { 
  margin: 0; 
  background-color: var(--bg);
  background-image: 
    radial-gradient(at 0% 0%, rgba(37, 99, 235, 0.05) 0px, transparent 50%),
    radial-gradient(at 100% 100%, rgba(59, 130, 246, 0.05) 0px, transparent 50%);
  color: var(--text); 
  line-height: 1.6;
}


nav {
  padding: 16px 5%;
  display: flex; justify-content: space-between; align-items: center;
  position: sticky; top: 0; 
  background: rgba(255, 255, 255, 0.8);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  z-index: 100; 
  border-bottom: 1px solid var(--border);
}

nav .logo { font-weight: 700; font-size: 1.4rem; color: var(--blue); letter-spacing: -0.5px; }
nav .menu { font-size: 1.2rem; cursor: pointer; color: var(--text); opacity: 0.7; }

/* HERO */
header {
  padding: 140px 24px 100px; text-align: center;
}

.fade { opacity: 0; transform: translateY(20px); animation: fadeIn 0.8s cubic-bezier(0.2, 0.8, 0.2, 1) forwards; }

header h1 {
  font-size: clamp(2.5rem, 6vw, 4rem); 
  max-width: 900px; margin: auto; 
  line-height: 1.1; font-weight: 800; 
  letter-spacing: -0.02em;
}

.highlight-container {
  display: inline-block;
  position: relative;
}

.highlight {
  color: var(--blue);
}


.curve-under {
  position: absolute;
  left: 0;
  bottom: -15px; /* Adjust to move line up/down */
  width: 100%;
  height: 20px;
}

header p {
  color: var(--muted); max-width: 600px; margin: 24px auto 0; font-size: 1.15rem; font-weight: 400;
}

/* BUTTONS */
.cta { margin-top: 48px; display: flex; gap: 12px; justify-content: center; }

.btn {
  padding: 14px 32px; border-radius: 12px; font-weight: 600; font-size: 0.95rem;
  border: none; cursor: pointer; transition: all 0.2s ease;
  text-decoration: none; display: inline-block;
}

.btn.primary { background: var(--blue); color: #fff; }
.btn.primary:hover { background: var(--blue-hover); transform: translateY(-1px); box-shadow: 0 10px 20px rgba(37, 99, 235, 0.2); }

.btn.secondary { background: transparent; color: var(--text); border: 1px solid var(--border); }
.btn.secondary:hover { background: #f8fafc; border-color: #cbd5e1; }

/* SECTIONS */
section { padding: 100px 5%; max-width: 1200px; margin: auto; }
section h2 { text-align: center; font-size: 2rem; margin-bottom: 48px; letter-spacing: -0.01em; }

.grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 32px; }

.card {
  background: var(--card-bg); 
  border-radius: 24px; 
  padding: 32px;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
  transition: all 0.3s ease;
}
.card:hover { transform: translateY(-6px); border-color: var(--blue); }
.card h3 { margin-top: 0; font-size: 1.25rem; }
.card p { color: var(--muted); font-size: 1rem; margin-bottom: 0; }

/* PRICING SPECIFIC */
.card.pricing {
  text-align: center;
  max-width: 400px;
  margin: auto;
  background: #fff;
}
.price-tag { font-size: 3rem; font-weight: 800; margin: 16px 0; }
.price-tag span { font-size: 1rem; color: var(--muted); font-weight: 400; }

/* REVIEWS */
.comment { 
  background: var(--card-bg); 
  border-radius: 16px; 
  padding: 24px; 
  border: 1px solid var(--border);
  font-style: italic;
}
.comment strong { color: var(--text); font-style: normal; display: block; margin-bottom: 4px; font-size: 0.9rem; }


footer { padding: 60px 24px; text-align: center; color: var(--muted); border-top: 1px solid var(--border); font-size: 0.9rem; }
footer a { color: var(--blue); text-decoration: none; font-weight: 600; margin-left: 10px;}

/* ANIMATION */
@keyframes fadeIn { to { opacity: 1; transform: translateY(0); } }

@media (max-width: 640px) {
  header { padding-top: 80px; }
  .cta { flex-direction: column; }
}
</style>
</head>

<body>

<nav>
  <div class="logo">Ligma</div>
  <div> Best SS ever bro</div>
</nav>

<header class="fade">
  <span class="btn secondary" style="padding: 6px 16px; font-size: 0.8rem; margin-bottom: 20px; pointer-events: none;">Made By Ligma Devs</span>
  <h1>
    The most powerful <br>
    <span class="highlight-container">
      <span class="highlight">Serverside</span>
      <svg class="curve-under" viewBox="0 0 100 20" preserveAspectRatio="none">
        <path d="M 0,5 Q 50,20 100,5" stroke="#2563eb" stroke-width="4" fill="transparent" stroke-linecap="round" />
      </svg>
    </span>
     for Roblox
  </h1>
  <p>
    Experience high-performance Level Execution and Utlimate Trolls with No Rules .
  </p>
  <div class="cta">
    <a href="#pricing" class="btn primary">Start for Free</a>
    </div>
</header>

<section id="features" class="fade" style="animation-delay:.1s">
  <h2>Project Ligma</h2>
  <div class="grid">
    <div class="card">
      <h3>High-Performance</h3>
      <p>Our server-side backend is optimized and instant script execution across supported games.</p>
    </div>
    <div class="card">
      <h3>is this SS tuff?</h3>
      <p>BludClat yes this ss very tuff 67 omg ohhh.</p>
    </div>
    <div class="card">
      <h3>Realesed</h3>
      <p>Project Ligma was actually made on 2017 as a byfron bypass executor later got discontinued on 2022 and now had a revival on 2025!.</p>
    </div>
  </div>
</section>

<section id="pricing" class="fade" style="animation-delay:.2s">
  <h2>Simple Pricing</h2>
  <div class="card pricing">
    <span class="btn" style="background: rgba(37,99,235,0.1); color: var(--blue); font-size: 0.75rem; padding: 4px 12px; margin-bottom: 10px;">POPULAR</span>
    <h3>Starter Tier</h3>
    <div class="price-tag">$0<span>/forever</span></div>
    <ul style="list-style: none; padding: 0; margin: 24px 0; text-align: left; color: var(--muted);">
      <li style="margin-bottom: 12px;">✓ Basic server-side ads</li>
      <li style="margin-bottom: 12px;">✓ Community support access</li>
      <li style="margin-bottom: 12px;">✓ Standard execution priority</li>
    </ul>
    <a href="https://discord.gg/SJYQHbP7hq" target="_blank" class="btn primary" style="width: 100%;">Join the Discord</a>
  </div>
</section>

<section class="fade" style="animation-delay:.3s">
  <h2>Trusted by Creators</h2>
  <div class="grid">
    <div class="comment">
      <strong>@Stummy <(Tubers93 team)> </strong>
      "Man i love this server side executor !."
    </div>
    <div class="comment">
      <strong>@2ic <(Project Ligma Dev)> </strong>
      "Man Thanks to DreamyDolan2 We have made the Tuffest SS ever !."
    </div>
    <div class="comment">
      <strong>@SonicElijahMenia <(CONTENT Creator)> </strong>
      "Fire Bro keep it up!."
    </div>
    <div class="comment">
      <strong>@Erased_Citizen <(CONTENT Creator)> </strong>
      "Its been a year since i didnt used Project Ligma thanks for the comebacks!."
    </div>
    <div class="comment">
      <strong>@DreamyDolan2 <(Project Ligma Ceo)> </strong>
      "tuff bro !!!!!."
    </div>
  </div>
</section>

<footer>  
  © 2025 Project Ligma · 
  <a href="https://discord.gg/SJYQHbP7hq">Discord</a> · 
  <a href="#">Terms of Service</a>
</footer>

</body>
</html>
