<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Borhan Kabir — @bk4ivv | Entrepreneur · Founder of IBEDGE</title>
<meta name="description" content="Portfolio of Khandaker Md Borhan Kabir (@bk4ivv) — Entrepreneur, Founder of IBEDGE, Social Media Growth & Digital Advertising Specialist based in Kuala Lumpur.">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/space-grotesk@5/400.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/space-grotesk@5/500.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/space-grotesk@5/700.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/inter@5/400.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/inter@5/500.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/inter@5/600.css">
<style>
:root{
  --bg:#070711;
  --bg2:#0c0c1d;
  --card:rgba(255,255,255,.04);
  --border:rgba(255,255,255,.09);
  --txt:#eef0ff;
  --muted:#9aa0c3;
  --acc:#8b5cf6;
  --acc2:#22d3ee;
  --acc3:#f472b6;
  --grad:linear-gradient(120deg,#8b5cf6,#22d3ee);
  --grad2:linear-gradient(120deg,#f472b6,#8b5cf6);
  --radius:20px;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  background:var(--bg);
  color:var(--txt);
  font-family:'Inter',sans-serif;
  overflow-x:hidden;
  line-height:1.6;
}
h1,h2,h3,h4{font-family:'Space Grotesk',sans-serif;line-height:1.15}
::selection{background:var(--acc);color:#fff}
::-webkit-scrollbar{width:10px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:linear-gradient(var(--acc),var(--acc2));border-radius:10px}

/* ---------- ambient background ---------- */
.bg-orbs{position:fixed;inset:0;z-index:-2;pointer-events:none}
.orb{position:absolute;border-radius:50%;filter:blur(110px);opacity:.28}
.orb1{width:520px;height:520px;background:#6d28d9;top:-140px;left:-120px;animation:drift1 22s ease-in-out infinite alternate}
.orb2{width:440px;height:440px;background:#0e7490;bottom:-120px;right:-100px;animation:drift2 26s ease-in-out infinite alternate}
.orb3{width:360px;height:360px;background:#9d174d;top:45%;left:55%;opacity:.16;animation:drift1 30s ease-in-out infinite alternate-reverse}
@keyframes drift1{to{transform:translate(90px,70px) scale(1.15)}}
@keyframes drift2{to{transform:translate(-80px,-60px) scale(1.1)}}
#particles{position:fixed;inset:0;z-index:-1;pointer-events:none}
.grid-overlay{position:fixed;inset:0;z-index:-1;pointer-events:none;
  background-image:linear-gradient(rgba(139,92,246,.05) 1px,transparent 1px),linear-gradient(90deg,rgba(139,92,246,.05) 1px,transparent 1px);
  background-size:56px 56px;
  mask-image:radial-gradient(ellipse at 50% 0%,#000 30%,transparent 75%);
}

/* ---------- nav ---------- */
nav{position:fixed;top:0;left:0;right:0;z-index:100;transition:.35s;padding:18px 0}
nav.scrolled{background:rgba(7,7,17,.78);backdrop-filter:blur(18px);border-bottom:1px solid var(--border);padding:10px 0}
.nav-in{max-width:1180px;margin:auto;padding:0 24px;display:flex;align-items:center;justify-content:space-between}
.logo{display:flex;align-items:center;gap:11px;text-decoration:none;color:var(--txt);font-weight:700;font-family:'Space Grotesk',sans-serif}
.logo-mark{width:38px;height:38px;border-radius:12px;background:var(--grad);display:grid;place-items:center;font-size:15px;color:#fff;box-shadow:0 0 22px rgba(139,92,246,.5)}
.logo span small{display:block;font-size:10.5px;font-weight:500;color:var(--muted);letter-spacing:1.4px;font-family:'Inter',sans-serif}
.nav-links{display:flex;gap:6px;align-items:center;list-style:none}
.nav-links a{color:var(--muted);text-decoration:none;font-size:14.5px;font-weight:500;padding:8px 15px;border-radius:10px;transition:.25s}
.nav-links a:hover,.nav-links a.active{color:#fff;background:rgba(139,92,246,.14)}
.nav-cta{background:var(--grad)!important;color:#fff!important;box-shadow:0 4px 18px rgba(139,92,246,.4)}
.burger{display:none;background:none;border:1px solid var(--border);border-radius:10px;padding:8px 11px;color:var(--txt);cursor:pointer;font-size:18px}

/* ---------- hero ---------- */
.hero{min-height:100vh;display:flex;align-items:center;position:relative;padding:130px 24px 70px}
.hero-in{max-width:1180px;margin:auto;display:grid;grid-template-columns:1.25fr .75fr;gap:60px;align-items:center;width:100%}
.badge{display:inline-flex;align-items:center;gap:9px;background:rgba(34,211,238,.09);border:1px solid rgba(34,211,238,.3);color:var(--acc2);padding:7px 16px;border-radius:100px;font-size:13px;font-weight:600;margin-bottom:26px}
.dot{width:8px;height:8px;border-radius:50%;background:#34d399;box-shadow:0 0 0 0 rgba(52,211,153,.6);animation:pulse 2s infinite}
@keyframes pulse{70%{box-shadow:0 0 0 9px rgba(52,211,153,0)}100%{box-shadow:0 0 0 0 rgba(52,211,153,0)}}
.hero h1{font-size:clamp(38px,5.6vw,66px);font-weight:700;letter-spacing:-1.5px}
.hero h1 .grad{background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero .handle{font-size:clamp(16px,2vw,19px);color:var(--acc2);font-weight:600;margin:12px 0 6px;font-family:'Space Grotesk',sans-serif}
.hero .tagline{font-size:clamp(15px,1.7vw,17.5px);color:var(--muted);max-width:540px;margin:14px 0 8px}
.hero .tagline em{color:var(--txt);font-style:italic}
.hero .loc{display:flex;align-items:center;gap:7px;color:var(--muted);font-size:14px;margin:16px 0 30px}
.hero-btns{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:38px}
.btn{display:inline-flex;align-items:center;gap:9px;padding:14px 28px;border-radius:14px;font-weight:600;font-size:15px;text-decoration:none;transition:.3s;border:none;cursor:pointer;font-family:'Inter',sans-serif}
.btn-p{background:var(--grad);color:#fff;box-shadow:0 8px 28px rgba(139,92,246,.42)}
.btn-p:hover{transform:translateY(-3px);box-shadow:0 14px 36px rgba(139,92,246,.55)}
.btn-g{background:transparent;color:var(--txt);border:1px solid var(--border)}
.btn-g:hover{border-color:var(--acc);background:rgba(139,92,246,.09);transform:translateY(-3px)}
.socials{display:flex;gap:12px}
.soc{width:44px;height:44px;border-radius:13px;border:1px solid var(--border);background:var(--card);display:grid;place-items:center;color:var(--muted);text-decoration:none;transition:.3s}
.soc:hover{color:#fff;border-color:var(--acc);transform:translateY(-4px);box-shadow:0 8px 22px rgba(139,92,246,.35);background:rgba(139,92,246,.12)}
.soc svg{width:19px;height:19px;fill:currentColor}

/* avatar card */
.avatar-wrap{display:flex;justify-content:center;position:relative}
.avatar-card{position:relative;width:min(330px,80vw);aspect-ratio:1/1.12;border-radius:32px;background:linear-gradient(160deg,rgba(139,92,246,.16),rgba(34,211,238,.07) 60%,rgba(244,114,182,.1));border:1px solid var(--border);backdrop-filter:blur(8px);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:20px;overflow:hidden;animation:floaty 6s ease-in-out infinite}
@keyframes floaty{50%{transform:translateY(-14px)}}
.avatar-card::before{content:"";position:absolute;inset:-2px;border-radius:34px;padding:2px;background:linear-gradient(140deg,rgba(139,92,246,.7),transparent 40%,transparent 60%,rgba(34,211,238,.6));-webkit-mask:linear-gradient(#fff 0 0) content-box,linear-gradient(#fff 0 0);-webkit-mask-composite:xor;mask-composite:exclude;pointer-events:none}
.mono-ring{width:170px;height:170px;border-radius:50%;background:var(--grad);display:grid;place-items:center;box-shadow:0 0 60px rgba(139,92,246,.55);position:relative}
.mono-ring::after{content:"";position:absolute;inset:-14px;border-radius:50%;border:1.5px dashed rgba(139,92,246,.55);animation:spin 26s linear infinite}
@keyframes spin{to{transform:rotate(360deg)}}
.mono-ring span{font-family:'Space Grotesk',sans-serif;font-size:56px;font-weight:700;color:#fff;letter-spacing:-2px}
.avatar-card h3{font-size:20px}
.avatar-card p{color:var(--muted);font-size:13.5px;padding:0 26px;text-align:center}
.chip-row{display:flex;gap:8px;flex-wrap:wrap;justify-content:center;padding:0 20px}
.chip{font-size:11.5px;font-weight:600;padding:5px 13px;border-radius:100px;border:1px solid var(--border);background:rgba(255,255,255,.04);color:var(--acc2)}
.chip.b{color:var(--acc3)}
.chip.c{color:var(--acc)}

/* ---------- sections ---------- */
section{padding:100px 24px;position:relative}
.sec-in{max-width:1180px;margin:auto}
.sec-label{display:inline-block;font-size:12.5px;font-weight:700;letter-spacing:3px;text-transform:uppercase;color:var(--acc2);margin-bottom:14px}
.sec-title{font-size:clamp(28px,3.6vw,42px);font-weight:700;letter-spacing:-.8px;margin-bottom:16px}
.sec-title .grad{background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.sec-sub{color:var(--muted);max-width:640px;font-size:16px}

/* reveal */
.rv{opacity:0;transform:translateY(38px);transition:opacity .75s ease,transform .75s ease}
.rv.on{opacity:1;transform:none}
.rv.d1{transition-delay:.1s}.rv.d2{transition-delay:.2s}.rv.d3{transition-delay:.3s}.rv.d4{transition-delay:.4s}

/* about */
.about-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:56px;margin-top:46px;align-items:start}
.about-p{color:var(--muted);font-size:16px;margin-bottom:18px}
.about-p strong{color:var(--txt);font-weight:600}
.quote-box{margin-top:26px;padding:24px 26px;border-left:3px solid var(--acc);background:var(--card);border-radius:0 16px 16px 0}
.quote-box p{font-family:'Space Grotesk',sans-serif;font-size:19px;font-style:italic;color:var(--txt)}
.quote-box cite{display:block;margin-top:10px;font-size:13px;color:var(--muted);font-style:normal}
.info-cards{display:grid;gap:16px}
.info-card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:22px 24px;display:flex;gap:16px;align-items:center;transition:.3s}
.info-card:hover{border-color:rgba(139,92,246,.55);transform:translateX(6px);background:rgba(139,92,246,.07)}
.info-ic{width:48px;height:48px;border-radius:14px;background:var(--grad);display:grid;place-items:center;flex-shrink:0}
.info-ic svg{width:22px;height:22px;fill:#fff}
.info-card h4{font-size:15.5px;margin-bottom:3px}
.info-card p{font-size:13.5px;color:var(--muted)}

/* ventures */
.ventures-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:26px;margin-top:52px}
.v-card{background:var(--card);border:1px solid var(--border);border-radius:24px;overflow:hidden;transition:.4s;position:relative;display:flex;flex-direction:column}
.v-card:hover{transform:translateY(-9px);border-color:rgba(139,92,246,.6);box-shadow:0 24px 55px rgba(0,0,0,.55)}
.v-art{height:180px;position:relative;overflow:hidden;display:grid;place-items:center}
.v-art svg{width:100%;height:100%;transition:.5s}
.v-card:hover .v-art svg{transform:scale(1.07)}
.v-tag{position:absolute;top:14px;left:14px;font-size:11px;font-weight:700;letter-spacing:1.2px;text-transform:uppercase;padding:5px 12px;border-radius:100px;background:rgba(7,7,17,.6);backdrop-filter:blur(6px);border:1px solid rgba(255,255,255,.18);color:#fff;z-index:2}
.v-body{padding:26px 26px 28px;flex:1;display:flex;flex-direction:column}
.v-body h3{font-size:21px;margin-bottom:4px}
.v-handle{font-size:13px;color:var(--acc2);font-weight:600;margin-bottom:12px}
.v-body p{color:var(--muted);font-size:14.5px;flex:1}
.v-feats{display:flex;gap:8px;flex-wrap:wrap;margin-top:18px}
.v-feats span{font-size:11.5px;font-weight:600;padding:5px 12px;border-radius:100px;background:rgba(139,92,246,.12);border:1px solid rgba(139,92,246,.3);color:#c4b5fd}
.v-link{margin-top:20px;display:inline-flex;align-items:center;gap:8px;color:var(--txt);text-decoration:none;font-weight:600;font-size:14px;width:fit-content;border-bottom:1.5px solid transparent;transition:.3s}
.v-link:hover{color:var(--acc2);border-color:var(--acc2);gap:12px}

/* skills */
.skills-wrap{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:52px}
.skill{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:28px 24px;transition:.35s;position:relative;overflow:hidden}
.skill::before{content:"";position:absolute;top:0;left:0;right:0;height:3px;background:var(--grad);transform:scaleX(0);transform-origin:left;transition:.4s}
.skill:hover::before{transform:scaleX(1)}
.skill:hover{transform:translateY(-6px);border-color:rgba(34,211,238,.45);background:rgba(34,211,238,.05)}
.skill-ic{width:52px;height:52px;border-radius:15px;background:rgba(139,92,246,.15);display:grid;place-items:center;margin-bottom:18px}
.skill-ic svg{width:25px;height:25px;stroke:var(--acc2);fill:none;stroke-width:1.8}
.skill h3{font-size:17px;margin-bottom:8px}
.skill p{font-size:13.8px;color:var(--muted)}
.skill .bar{height:5px;border-radius:5px;background:rgba(255,255,255,.08);margin-top:18px;overflow:hidden}
.skill .bar i{display:block;height:100%;border-radius:5px;background:var(--grad);width:0;transition:width 1.4s cubic-bezier(.2,.7,.3,1)}

/* stats */
.stats{background:linear-gradient(135deg,rgba(139,92,246,.14),rgba(34,211,238,.08));border:1px solid var(--border);border-radius:28px;padding:56px 30px;margin-top:8px;display:grid;grid-template-columns:repeat(4,1fr);gap:24px;text-align:center;position:relative;overflow:hidden}
.stats::after{content:"";position:absolute;width:340px;height:340px;border-radius:50%;background:rgba(139,92,246,.22);filter:blur(90px);top:-140px;right:-90px;pointer-events:none}
.stat h3{font-size:clamp(30px,3.8vw,46px);font-weight:700;background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.stat p{color:var(--muted);font-size:13.5px;font-weight:500;margin-top:6px}

/* timeline */
.tl{margin-top:56px;position:relative;padding-left:34px}
.tl::before{content:"";position:absolute;left:9px;top:6px;bottom:6px;width:2px;background:linear-gradient(var(--acc),var(--acc2),transparent)}
.tl-item{position:relative;padding:0 0 44px 24px}
.tl-item:last-child{padding-bottom:0}
.tl-item::before{content:"";position:absolute;left:-31px;top:5px;width:16px;height:16px;border-radius:50%;background:var(--bg);border:3px solid var(--acc);box-shadow:0 0 16px rgba(139,92,246,.7)}
.tl-item .yr{font-size:12.5px;font-weight:700;letter-spacing:1.6px;color:var(--acc2);text-transform:uppercase}
.tl-item h3{font-size:19px;margin:6px 0 8px}
.tl-item p{color:var(--muted);font-size:14.5px;max-width:620px}

/* contact */
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:44px;margin-top:50px;align-items:start}
.c-links{display:grid;gap:14px}
.c-link{display:flex;align-items:center;gap:16px;padding:18px 22px;background:var(--card);border:1px solid var(--border);border-radius:16px;text-decoration:none;color:var(--txt);transition:.3s}
.c-link:hover{border-color:var(--acc);background:rgba(139,92,246,.08);transform:translateX(7px)}
.c-link .ic{width:44px;height:44px;border-radius:12px;display:grid;place-items:center;flex-shrink:0}
.c-link .ic svg{width:20px;height:20px;fill:#fff}
.c-link b{font-size:15px;display:block}
.c-link small{color:var(--muted);font-size:12.8px}
.c-link .arw{margin-left:auto;color:var(--muted);transition:.3s;font-size:18px}
.c-link:hover .arw{color:var(--acc2);transform:translateX(4px)}
form{background:var(--card);border:1px solid var(--border);border-radius:24px;padding:34px}
form h3{font-size:20px;margin-bottom:22px}
.f-row{margin-bottom:16px}
.f-row label{display:block;font-size:13px;font-weight:600;color:var(--muted);margin-bottom:7px}
.f-row input,.f-row textarea{width:100%;background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:12px;padding:13px 16px;color:var(--txt);font-family:'Inter',sans-serif;font-size:14.5px;transition:.25s;resize:vertical}
.f-row input:focus,.f-row textarea:focus{outline:none;border-color:var(--acc);box-shadow:0 0 0 3px rgba(139,92,246,.18)}
.form-msg{display:none;margin-top:14px;padding:13px 16px;border-radius:12px;background:rgba(52,211,153,.12);border:1px solid rgba(52,211,153,.4);color:#6ee7b7;font-size:14px}

footer{border-top:1px solid var(--border);padding:38px 24px;text-align:center;color:var(--muted);font-size:13.5px}
footer .grad{background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent;font-weight:700}

@media(max-width:960px){
  .hero-in{grid-template-columns:1fr;text-align:center;gap:48px}
  .hero .badge,.hero .loc{margin-left:auto;margin-right:auto}
  .hero .loc{justify-content:center}
  .hero-btns,.socials{justify-content:center}
  .hero .tagline{margin-left:auto;margin-right:auto}
  .avatar-wrap{order:-1}
  .about-grid,.contact-grid{grid-template-columns:1fr}
  .ventures-grid{grid-template-columns:1fr}
  .skills-wrap{grid-template-columns:repeat(2,1fr)}
  .stats{grid-template-columns:repeat(2,1fr)}
}
@media(max-width:640px){
  .nav-links{position:fixed;inset:0 0 auto;top:0;flex-direction:column;background:rgba(7,7,17,.97);backdrop-filter:blur(20px);padding:92px 28px 34px;gap:8px;transform:translateY(-110%);transition:.4s;border-bottom:1px solid var(--border);align-items:stretch}
  .nav-links.open{transform:none}
  .nav-links a{padding:14px 18px;font-size:16px}
  .burger{display:block;z-index:110}
  .skills-wrap{grid-template-columns:1fr}
  section{padding:74px 20px}
}
</style>
</head>
<body>

<div class="bg-orbs"><div class="orb orb1"></div><div class="orb orb2"></div><div class="orb orb3"></div></div>
<div class="grid-overlay"></div>
<canvas id="particles"></canvas>

<!-- NAV -->
<nav id="nav">
  <div class="nav-in">
    <a class="logo" href="#home">
      <div class="logo-mark">BK</div>
      <span>Borhan Kabir<small>@BK4IVV</small></span>
    </a>
    <button class="burger" id="burger" aria-label="Menu">☰</button>
    <ul class="nav-links" id="navLinks">
      <li><a href="#home" class="active">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#ventures">Ventures</a></li>
      <li><a href="#skills">Expertise</a></li>
      <li><a href="#journey">Journey</a></li>
      <li><a href="#contact" class="nav-cta">Let's Talk</a></li>
    </ul>
  </div>
</nav>

<!-- HERO -->
<header class="hero" id="home">
  <div class="hero-in">
    <div>
      <div class="badge rv"><span class="dot"></span> Available for collaborations &amp; brand growth projects</div>
      <h1 class="rv d1">Khandaker Md<br><span class="grad">Borhan Kabir</span></h1>
      <div class="handle rv d2">@bk4ivv — IIIIVV</div>
      <p class="tagline rv d2"><em>"Lost in books. Found in ambition. Bound for more."</em><br>Entrepreneur · Founder of IBEDGE · Social Media Growth &amp; Digital Advertising Specialist with a focus on international marketing.</p>
      <div class="loc rv d3">
        <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="#9aa0c3" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
        Kuala Lumpur, Malaysia · Originally from Naogaon, Bangladesh
      </div>
      <div class="hero-btns rv d3">
        <a href="#ventures" class="btn btn-p">Explore My Ventures
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
        </a>
        <a href="#contact" class="btn btn-g">Get In Touch</a>
      </div>
      <div class="socials rv d4">
        <a class="soc" href="https://www.instagram.com/bk4ivv/" target="_blank" rel="noopener" aria-label="Instagram">
          <svg viewBox="0 0 24 24"><path d="M12 2.2c3.2 0 3.6 0 4.9.07 3.25.15 4.77 1.69 4.92 4.92.06 1.27.07 1.65.07 4.86s-.01 3.58-.07 4.85c-.15 3.23-1.66 4.77-4.92 4.92-1.27.06-1.64.07-4.89.07-3.2 0-3.58-.01-4.85-.07-3.26-.15-4.77-1.7-4.92-4.92C2.17 15.62 2.16 15.24 2.16 12s.01-3.58.07-4.85C2.38 3.92 3.89 2.38 7.15 2.23 8.42 2.18 8.8 2.17 12 2.17zm0 3.68a6.15 6.15 0 1 0 0 12.3 6.15 6.15 0 0 0 0-12.3zM12 16a4 4 0 1 1 0-8 4 4 0 0 1 0 8zm6.4-11.85a1.44 1.44 0 1 0 0 2.88 1.44 1.44 0 0 0 0-2.88z"/></svg>
        </a