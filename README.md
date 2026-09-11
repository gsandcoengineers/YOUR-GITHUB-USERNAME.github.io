<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GS & CO Engineers Builders — Independent House Construction, Coimbatore</title>
<meta name="description" content="GS & CO Engineers Builders — engineer-led independent house construction in Keeranatham, Coimbatore. Premium quality, honest pricing.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Zilla+Slab:ital,wght@0,400;0,500;0,600;0,700;1,500&family=IBM+Plex+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
<link rel="icon" href="data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%20120%20120%22%3E%20%3Crect%20width=%22120%22%20height=%22120%22%20fill=%22none%22/%3E%20%3Cpolygon%20points=%2260,8%20106,34%20106,86%2060,112%2014,86%2014,34%22%20fill=%22none%22%20stroke=%22%23A9472B%22%20stroke-width=%225%22/%3E%20%3Cpath%20d=%22M36%2070V50l24-20%2024%2020v20M48%2070V53h24v17%22%20fill=%22none%22%20stroke=%22%2320242A%22%20stroke-width=%225%22%20stroke-linejoin=%22round%22/%3E%20%3C/svg%3E">
<style>
  :root{
    --stone:#EFEAE1;
    --paper:#FAF7F2;
    --ink:#20242A;
    --slate:#4B5563;
    --slate-soft:#6B7686;
    --brick:#A9472B;
    --brick-dark:#8A3820;
    --brick-light:#C97552;
    --line: rgba(32,36,42,0.16);
    --line-soft: rgba(32,36,42,0.09);
    --ochre:#B9852E;
  }
  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    margin:0;
    background:var(--stone);
    color:var(--ink);
    font-family:'IBM Plex Sans', sans-serif;
    font-size:16px;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
  }
  h1,h2,h3,h4{
    font-family:'Zilla Slab', serif;
    color:var(--ink);
    margin:0;
    line-height:1.12;
    font-weight:600;
  }
  p{margin:0;}
  a{color:inherit;text-decoration:none;}
  img{max-width:100%;display:block;}
  .wrap{max-width:1180px;margin:0 auto;padding:0 32px;}
  section{position:relative;}

  /* subtle blueprint grid backdrop */
  .grid-bg{
    position:absolute; inset:0;
    background-image:
      linear-gradient(var(--line-soft) 1px, transparent 1px),
      linear-gradient(90deg, var(--line-soft) 1px, transparent 1px);
    background-size: 44px 44px;
    -webkit-mask-image: linear-gradient(to bottom, rgba(0,0,0,0.9), rgba(0,0,0,0));
    mask-image: linear-gradient(to bottom, rgba(0,0,0,0.9), rgba(0,0,0,0));
    pointer-events:none;
  }

  /* ---------- HEADER ---------- */
  header{
    position:sticky; top:0; z-index:50;
    background:rgba(239,234,225,0.92);
    backdrop-filter:blur(8px);
    border-bottom:1px solid var(--line);
  }
  .header-inner{
    display:flex; align-items:center; justify-content:space-between;
    padding:12px 32px;
    max-width:1180px; margin:0 auto;
  }
  .brand{display:flex; align-items:center; gap:12px;}
  .brand img{height:52px; width:auto;}
  nav.mainnav{display:flex; align-items:center; gap:30px;}
  nav.mainnav a{
    font-size:14.5px; color:var(--slate); font-weight:500;
    padding:6px 0; border-bottom:1px solid transparent;
    transition:color .15s, border-color .15s;
  }
  nav.mainnav a:hover{color:var(--brick); border-color:var(--brick);}
  .header-actions{display:flex; align-items:center; gap:14px;}
  .btn{
    display:inline-flex; align-items:center; gap:8px;
    padding:11px 22px; font-size:14.5px; font-weight:600;
    border-radius:3px; border:1px solid transparent; cursor:pointer;
    font-family:'IBM Plex Sans', sans-serif;
    transition: transform .15s ease, background .15s ease, border-color .15s ease;
  }
  .btn:active{transform:translateY(1px);}
  .btn-primary{background:var(--brick); color:#fff;}
  .btn-primary:hover{background:var(--brick-dark);}
  .btn-outline{background:transparent; color:var(--ink); border-color:var(--ink);}
  .btn-outline:hover{border-color:var(--brick); color:var(--brick);}
  .btn-call{background:var(--ink); color:var(--paper);}
  .btn-call:hover{background:#000;}
  .btn-sm{padding:9px 16px; font-size:13.5px;}
  .icon{width:16px; height:16px; flex-shrink:0;}

  .menu-toggle{display:none; background:none; border:none; cursor:pointer; padding:6px;}
  .menu-toggle svg{width:26px; height:26px;}

  /* ---------- HERO ---------- */
  .hero{padding:86px 0 76px; overflow:hidden;}
  .hero-inner{
    display:grid; grid-template-columns:1.05fr 0.85fr; gap:56px; align-items:center;
  }
  .eyebrow-line{
    display:flex; align-items:center; gap:10px; margin-bottom:22px;
  }
  .eyebrow-line .tick{width:26px; height:1px; background:var(--brick);}
  .eyebrow-line span{font-size:13.5px; color:var(--brick); font-weight:600; letter-spacing:.2px;}
  .hero h1{
    font-size:47px; font-weight:600; letter-spacing:-0.3px; max-width:600px;
  }
  .hero h1 em{font-style:italic; font-weight:500; color:var(--brick);}
  .hero-sub{
    margin-top:22px; font-size:17.5px; color:var(--slate); max-width:520px; line-height:1.65;
  }
  .hero-cta{display:flex; gap:14px; margin-top:34px; flex-wrap:wrap;}
  .stat-strip{
    display:flex; gap:0; margin-top:52px; border-top:1px solid var(--line); padding-top:26px;
    max-width:560px;
  }
  .stat{padding-right:32px; margin-right:32px; border-right:1px solid var(--line);}
  .stat:last-child{border-right:none; margin-right:0; padding-right:0;}
  .stat .num{font-family:'Zilla Slab',serif; font-size:26px; font-weight:600; color:var(--ink);}
  .stat .label{font-size:12.5px; color:var(--slate-soft); margin-top:3px; max-width:120px;}

  .hero-visual{position:relative;}
  .hero-visual .hexwrap{
    position:relative; background:var(--paper); border:1px solid var(--line);
    padding:38px; border-radius:4px;
  }
  .hero-visual img.mark{width:150px; margin:0 auto 22px; display:block;}
  .spec-list{border-top:1px dashed var(--line); padding-top:18px;}
  .spec-row{display:flex; justify-content:space-between; padding:9px 0; font-size:14px; border-bottom:1px dashed var(--line);}
  .spec-row:last-child{border-bottom:none;}
  .spec-row .k{color:var(--slate-soft);}
  .spec-row .v{color:var(--ink); font-weight:600; text-align:right;}
  .corner-tag{
    position:absolute; top:-14px; right:20px; background:var(--brick); color:#fff;
    font-size:12px; font-weight:600; padding:7px 14px; border-radius:2px;
    box-shadow:0 4px 14px rgba(169,71,43,0.35);
  }

  /* ---------- SECTION HEADINGS ---------- */
  .section-head{max-width:620px; margin-bottom:52px;}
  .section-head .eyebrow-line span{color:var(--brick);}
  .section-head h2{font-size:34px; font-weight:600;}
  .section-head p{margin-top:14px; font-size:16px; color:var(--slate);}
  section.alt{background:var(--paper); border-top:1px solid var(--line); border-bottom:1px solid var(--line);}
  .pad{padding:92px 0;}

  /* ---------- ABOUT ---------- */
  .about-grid{display:grid; grid-template-columns:0.95fr 1.05fr; gap:64px; align-items:center;}
  .about-copy p{color:var(--slate); font-size:16px; margin-bottom:18px;}
  .about-copy p:last-child{margin-bottom:0;}
  .founder-line{
    margin-top:28px; padding-top:24px; border-top:1px solid var(--line);
    display:flex; gap:20px; align-items:flex-start;
  }
  .founder-line .qmark{font-family:'Zilla Slab',serif; font-size:40px; color:var(--brick); line-height:1;}
  .founder-line p{font-family:'Zilla Slab',serif; font-style:italic; font-size:18px; color:var(--ink); line-height:1.5;}

  /* ---------- WHY PREMIUM ---------- */
  .why-grid{display:grid; grid-template-columns:repeat(3,1fr); gap:0; border-top:1px solid var(--line);}
  .why-item{padding:34px 30px; border-right:1px solid var(--line); border-bottom:1px solid var(--line);}
  .why-item:last-child{border-right:none;}
  .why-item .wn{font-family:'Zilla Slab',serif; font-size:14px; color:var(--brick); font-weight:600; margin-bottom:14px; display:block;}
  .why-item h3{font-size:20px; margin-bottom:10px;}
  .why-item p{color:var(--slate); font-size:15px;}

  /* ---------- SERVICES ---------- */
  .services-grid{display:grid; grid-template-columns:repeat(3,1fr); gap:1px; background:var(--line);}
  .svc-card{background:var(--stone); padding:32px 28px;}
  .svc-card .icon-box{
    width:46px; height:46px; border:1px solid var(--ink); border-radius:50%;
    display:flex; align-items:center; justify-content:center; margin-bottom:20px;
  }
  .svc-card .icon-box svg{width:22px; height:22px; stroke:var(--ink); fill:none;}
  .svc-card h3{font-size:18.5px; margin-bottom:8px;}
  .svc-card p{color:var(--slate); font-size:14.5px;}

  /* ---------- PROJECTS ---------- */
  .proj-grid{display:grid; grid-template-columns:repeat(2,1fr); gap:26px;}
  .proj-card{background:var(--paper); border:1px solid var(--line); overflow:hidden; border-radius:4px;}
  .proj-illustration{
    aspect-ratio:16/10; background:
      linear-gradient(var(--line-soft) 1px, transparent 1px),
      linear-gradient(90deg, var(--line-soft) 1px, transparent 1px), #F1ECE3;
    background-size:20px 20px;
    display:flex; align-items:center; justify-content:center;
    border-bottom:1px solid var(--line);
  }
  .proj-illustration svg{width:62%; stroke:var(--slate); fill:none;}
  .proj-body{padding:22px 24px;}
  .proj-body .tag{font-size:12px; color:var(--brick); font-weight:600; letter-spacing:.2px;}
  .proj-body h3{font-size:19px; margin-top:8px;}
  .proj-body p{color:var(--slate); font-size:14.5px; margin-top:8px;}
  .proj-note{
    grid-column:1/-1; font-size:13.5px; color:var(--slate-soft); border-top:1px dashed var(--line);
    padding-top:18px; margin-top:4px; font-style:italic;
  }

  /* ---------- PROCESS ---------- */
  .process-row{display:flex; border-top:1px solid var(--line);}
  .process-step{flex:1; padding:30px 22px 0; position:relative;}
  .process-step:not(:last-child){border-right:1px solid var(--line);}
  .process-step .marker{
    width:34px; height:34px; border:1px solid var(--ink); border-radius:50%;
    display:flex; align-items:center; justify-content:center; font-family:'Zilla Slab',serif;
    font-size:14px; font-weight:600; background:var(--stone); margin-top:-18px; margin-bottom:18px;
  }
  section.alt .process-step .marker{background:var(--paper);}
  .process-step h4{font-size:16.5px; margin-bottom:8px;}
  .process-step p{font-size:13.5px; color:var(--slate); padding-bottom:28px;}

  /* ---------- TESTIMONIALS ---------- */
  .testi-grid{display:grid; grid-template-columns:1fr 1fr; gap:26px;}
  .testi-card{
    border:1px dashed var(--line); border-radius:4px; padding:30px 28px; background:var(--stone);
  }
  section.alt .testi-card{background:var(--paper);}
  .testi-card .qmark{font-family:'Zilla Slab',serif; font-size:32px; color:var(--brick); display:block; margin-bottom:6px;}
  .testi-card p.txt{font-size:15px; color:var(--slate); font-style:italic; line-height:1.6;}
  .testi-card .who{margin-top:16px; font-size:13.5px; color:var(--slate-soft); font-weight:600; font-style:normal;}

  /* ---------- CONTACT ---------- */
  .contact-grid{display:grid; grid-template-columns:0.9fr 1.1fr; gap:56px;}
  .contact-info .row{display:flex; gap:16px; padding:18px 0; border-bottom:1px solid var(--line);}
  .contact-info .row:first-child{padding-top:0;}
  .contact-info .row .icon-box{
    width:38px; height:38px; border:1px solid var(--ink); border-radius:50%; flex-shrink:0;
    display:flex; align-items:center; justify-content:center;
  }
  .contact-info .row .icon-box svg{width:18px; height:18px; stroke:var(--ink); fill:none;}
  .contact-info .row .label{font-size:12.5px; color:var(--slate-soft); text-transform:none; margin-bottom:4px;}
  .contact-info .row .val{font-size:15.5px; color:var(--ink); font-weight:500;}
  .contact-info .row .val a{border-bottom:1px solid var(--line);}
  .contact-info .row .val a:hover{color:var(--brick); border-color:var(--brick);}
  .map-embed{margin-top:26px; border:1px solid var(--line); border-radius:4px; overflow:hidden; height:220px;}
  .map-embed iframe{width:100%; height:100%; border:0;}

  form.inquiry{background:var(--paper); border:1px solid var(--line); padding:34px; border-radius:4px;}
  .form-row{display:grid; grid-template-columns:1fr 1fr; gap:16px; margin-bottom:16px;}
  .form-field{margin-bottom:16px;}
  .form-field label{display:block; font-size:12.5px; color:var(--slate-soft); margin-bottom:6px;}
  .form-field input, .form-field select, .form-field textarea{
    width:100%; border:1px solid var(--line); background:var(--stone); border-radius:3px;
    padding:11px 13px; font-family:'IBM Plex Sans',sans-serif; font-size:14.5px; color:var(--ink);
  }
  .form-field input:focus, .form-field select:focus, .form-field textarea:focus{
    outline:2px solid var(--brick); outline-offset:1px; border-color:var(--brick);
  }
  .form-field textarea{resize:vertical; min-height:90px;}
  .form-note{font-size:12.5px; color:var(--slate-soft); margin-top:14px;}

  /* ---------- FOOTER ---------- */
  footer{background:var(--ink); color:#D7D9DC; padding:56px 0 26px;}
  .footer-grid{display:grid; grid-template-columns:1.3fr 1fr 1fr 1fr; gap:40px; padding-bottom:36px; border-bottom:1px solid rgba(255,255,255,0.12);}
  .footer-brand img{height:46px; margin-bottom:14px;}
  .footer-brand p{font-size:14px; color:#9AA0A8; max-width:260px;}
  footer h5{font-family:'Zilla Slab',serif; color:#fff; font-size:15px; margin-bottom:16px; font-weight:600;}
  footer ul{list-style:none; margin:0; padding:0;}
  footer li{margin-bottom:10px;}
  footer a{font-size:14px; color:#9AA0A8;}
  footer a:hover{color:#fff;}
  .footer-bottom{display:flex; justify-content:space-between; align-items:center; padding-top:22px; font-size:13px; color:#7A8089; flex-wrap:wrap; gap:10px;}

  .whatsapp-float{
    position:fixed; bottom:24px; right:24px; z-index:60;
    width:56px; height:56px; border-radius:50%; background:#25D366;
    display:flex; align-items:center; justify-content:center;
    box-shadow:0 6px 18px rgba(0,0,0,0.25);
  }
  .whatsapp-float svg{width:28px; height:28px; fill:#fff;}

  /* ---------- RESPONSIVE ---------- */
  @media (max-width: 900px){
    nav.mainnav, .header-actions .btn-outline{display:none;}
    .menu-toggle{display:block;}
    .hero-inner{grid-template-columns:1fr; gap:44px;}
    .hero h1{font-size:36px;}
    .about-grid{grid-template-columns:1fr;}
    .why-grid{grid-template-columns:1fr;}
    .why-item{border-right:none;}
    .services-grid{grid-template-columns:1fr 1fr;}
    .proj-grid{grid-template-columns:1fr;}
    .process-row{flex-wrap:wrap;}
    .process-step{flex:1 1 50%; border-right:none !important; margin-bottom:20px;}
    .testi-grid{grid-template-columns:1fr;}
    .contact-grid{grid-template-columns:1fr;}
    .form-row{grid-template-columns:1fr;}
    .footer-grid{grid-template-columns:1fr 1fr;}
    .stat-strip{flex-wrap:wrap; gap:20px;}
    .stat{border-right:none; margin-right:0; padding-right:0;}
  }
  @media (max-width: 560px){
    .wrap{padding:0 20px;}
    .header-inner{padding:10px 20px;}
    .hero{padding:56px 0 50px;}
    .hero h1{font-size:29px;}
    .section-head h2{font-size:26px;}
    .services-grid{grid-template-columns:1fr;}
    .pad{padding:64px 0;}
    .footer-grid{grid-template-columns:1fr;}
    .brand img{height:42px;}
  }

  @media (prefers-reduced-motion: reduce){
    html{scroll-behavior:auto;}
    *{transition:none !important;}
  }
</style>
</head>
<body>

<!-- ============ HEADER ============ -->
<header>
  <div class="header-inner">
    <a href="#home" class="brand">
      <img src="data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%20320%2080%22%3E%20%3Crect%20width=%22320%22%20height=%2280%22%20fill=%22none%22/%3E%20%3Cg%20fill=%22none%22%20stroke=%22%23A9472B%22%20stroke-width=%223%22%3E%20%3Cpath%20d=%22M28%2040%2052%2018l24%2022-24%2022z%22/%3E%3Cpath%20d=%22M40%2040h24%22/%3E%3Cpath%20d=%22M52%2028v24%22/%3E%20%3C/g%3E%20%3Ctext%20x=%2292%22%20y=%2236%22%20font-family=%22Arial,sans-serif%22%20font-size=%2225%22%20font-weight=%22700%22%20fill=%22%2320242A%22%3EGS%20&amp;%20CO%3C/text%3E%20%3Ctext%20x=%2292%22%20y=%2257%22%20font-family=%22Arial,sans-serif%22%20font-size=%2211%22%20letter-spacing=%221.5%22%20fill=%22%234B5563%22%3EENGINEERS%20•%20BUILDERS%3C/text%3E%20%3C/svg%3E" alt="GS & CO Engineers Builders logo">
    </a>
    <nav class="mainnav">
      <a href="#about">About</a>
      <a href="#why">Why Us</a>
      <a href="#services">Services</a>
      <a href="#projects">Projects</a>
      <a href="#process">Process</a>
      <a href="#contact">Contact</a>
    </nav>
    <div class="header-actions">
      <a class="btn btn-outline btn-sm" href="tel:+919790028004">
        <svg class="icon" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.8" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.362 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.338 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
        97900 28004
      </a>
      <a class="btn btn-primary btn-sm" href="#contact">Get Free Consultation</a>
    </div>
    <button class="menu-toggle" id="menuToggle" aria-label="Open menu" aria-expanded="false" aria-controls="mnav">
      <svg viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.8" fill="none" stroke-linecap="round"><path d="M3 6h18M3 12h18M3 18h18"/></svg>
    </button>
  </div>
  <nav id="mnav" aria-label="Mobile navigation">
    <a href="#about" style="padding:10px 0;">About</a>
    <a href="#why" style="padding:10px 0;">Why Us</a>
    <a href="#services" style="padding:10px 0;">Services</a>
    <a href="#projects" style="padding:10px 0;">Projects</a>
    <a href="#process" style="padding:10px 0;">Process</a>
    <a href="#contact" style="padding:10px 0;">Contact</a>
    <a href="tel:+919790028004" style="padding:10px 0; font-weight:600; color:var(--brick);">Call 97900 28004</a>
  </nav>
</header>

<style>
#mnav{display:none; flex-direction:column; padding:10px 20px 18px; gap:2px; border-top:1px solid var(--line);}
#mnav.open{display:flex !important;}
@media (min-width:901px){#mnav{display:none !important;}}
</style>


<!-- ============ HERO ============ -->
<section class="hero" id="home">
  <div class="grid-bg"></div>
  <div class="wrap hero-inner">
    <div>
      <div class="eyebrow-line"><span class="tick"></span><span>Engineers &amp; Builders · Keeranatham, Coimbatore</span></div>
      <h1>Your home deserves an <em>engineer's eye</em>, not just a contractor's guess.</h1>
      <p class="hero-sub">GS &amp; CO plans and builds independent houses with the same structural discipline used on large institutional projects — so you get a home that's engineered to last, priced for a real family budget.</p>
      <div class="hero-cta">
        <a href="#contact" class="btn btn-primary">Get a Free Consultation</a>
        <a href="tel:+919790028004" class="btn btn-outline">Call 97900 28004</a>
      </div>
      <div class="stat-strip">
        <div class="stat"><div class="num">₹1 Cr+</div><div class="label">Annual construction turnover</div></div>
        <div class="stat"><div class="num">Engineer</div><div class="label">Led design &amp; site supervision</div></div>
        <div class="stat"><div class="num">Coimbatore</div><div class="label">Based &amp; building locally</div></div>
      </div>
    </div>
    <div class="hero-visual">
      <div class="corner-tag">Premium quality, honest pricing</div>
      <div class="hexwrap">
        <img class="mark" src="data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%20120%20120%22%3E%20%3Crect%20width=%22120%22%20height=%22120%22%20fill=%22none%22/%3E%20%3Cpolygon%20points=%2260,8%20106,34%20106,86%2060,112%2014,86%2014,34%22%20fill=%22none%22%20stroke=%22%23A9472B%22%20stroke-width=%225%22/%3E%20%3Cpath%20d=%22M36%2070V50l24-20%2024%2020v20M48%2070V53h24v17%22%20fill=%22none%22%20stroke=%22%2320242A%22%20stroke-width=%225%22%20stroke-linejoin=%22round%22/%3E%20%3C/svg%3E" alt="GS & CO hexagon mark">
        <div class="spec-list">
          <div class="spec-row"><span class="k">Founded on</span><span class="v">Institutional-scale engineering</span></div>
          <div class="spec-row"><span class="k">Specialism</span><span class="v">Independent houses</span></div>
          <div class="spec-row"><span class="k">Model</span><span class="v">Build-to-sell &amp; client-commissioned</span></div>
          <div class="spec-row"><span class="k">Service area</span><span class="v">Coimbatore &amp; surrounds</span></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ ABOUT ============ -->
<section class="alt" id="about">
  <div class="wrap pad">
    <div class="about-grid">
      <div>
        <svg viewBox="0 0 400 340" style="width:100%; stroke:var(--slate); fill:none; stroke-width:1.4;">
          <rect x="20" y="20" width="360" height="300" fill="none" stroke="var(--line)" stroke-dasharray="4 4"/>
          <polygon points="60,220 60,140 200,60 340,140 340,220" />
          <line x1="60" y1="220" x2="340" y2="220" stroke-width="2"/>
          <rect x="110" y="150" width="60" height="70"/>
          <rect x="230" y="150" width="60" height="70"/>
          <line x1="200" y1="60" x2="200" y2="100" stroke-dasharray="3 3"/>
          <polygon points="150,220 150,160 200,130 250,160 250,220" fill="var(--paper)" stroke="var(--ink)" stroke-width="1.6"/>
          <line x1="200" y1="130" x2="200" y2="220" stroke-dasharray="2 3"/>
          <text x="200" y="300" text-anchor="middle" font-family="IBM Plex Sans" font-size="11" fill="var(--slate-soft)" stroke="none">FOUNDATION TO FINISH — ENGINEERED, NOT ESTIMATED</text>
        </svg>
      </div>
      <div class="about-copy">
        <div class="eyebrow-line"><span class="tick"></span><span>About GS &amp; CO</span></div>
        <h2 style="font-size:32px; margin-bottom:20px;">Built by an engineer who learned on institutions, before building homes.</h2>
        <p>Before GS &amp; CO turned its focus to independent houses, its founder spent years on large-scale institutional construction — including work on an NIT college campus — where structural tolerances are inspected, not guessed, and there's no room for shortcuts.</p>
        <p>That discipline is what now goes into every house GS &amp; CO builds or sells, whether it's a home constructed for a client from the ground up, or a ready-built independent house sold directly. The business has grown to an annual construction turnover of ₹1 crore, built entirely on word of mouth and repeat trust in Keeranatham and across Coimbatore.</p>
        <div class="founder-line">
          <span class="qmark">"</span>
          <p>A house isn't just walls and a roof — it's a structure someone's family will live inside for decades. We build it the way we were trained to: like it has to hold.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ WHY PREMIUM YET AFFORDABLE ============ -->
<section id="why">
  <div class="grid-bg"></div>
  <div class="wrap pad">
    <div class="section-head">
      <div class="eyebrow-line"><span class="tick"></span><span>The GS &amp; CO Difference</span></div>
      <h2>Premium quality, without the premium price tag</h2>
      <p>Most families have to choose between a home that's well-engineered and a home they can actually afford. GS &amp; CO exists to close that gap.</p>
    </div>
    <div class="why-grid">
      <div class="why-item">
        <span class="wn">Engineering-first</span>
        <h3>Decided by an engineer, not eyeballed by a mason</h3>
        <p>Structural drawings, load calculations and material specs are worked out properly before construction starts — so nothing gets fixed after the fact, at your cost.</p>
      </div>
      <div class="why-item">
        <span class="wn">Institutional discipline</span>
        <h3>The same rigor as a campus project, on your site</h3>
        <p>The inspection and quality standards used on large institutional builds are applied to a single independent house, at the same level of care.</p>
      </div>
      <div class="why-item">
        <span class="wn">Direct from the builder</span>
        <h3>Honest margins, because there's no middleman stack</h3>
        <p>GS &amp; CO designs and builds under one roof. Without layers of contractors each adding their own markup, the savings are passed straight to you.</p>
      </div>
    </div>
  </div>
</section>

<!-- ============ SERVICES ============ -->
<section class="alt" id="services">
  <div class="wrap pad">
    <div class="section-head">
      <div class="eyebrow-line"><span class="tick"></span><span>What We Do</span></div>
      <h2>Services</h2>
      <p>From a blank plot to a finished, move-in-ready home — and everything an independent house needs along the way.</p>
    </div>
    <div class="services-grid">
      <div class="svc-card">
        <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M3 11.5 12 4l9 7.5"/><path d="M5 10v10h14V10"/><path d="M10 20v-6h4v6"/></svg></div>
        <h3>Custom Home Construction</h3>
        <p>End-to-end construction of your house from foundation to handover, designed around how your family actually lives.</p>
      </div>
      <div class="svc-card">
        <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M4 21V9l8-6 8 6v12"/><path d="M9 21v-7h6v7"/><path d="M4 21h16"/></svg></div>
        <h3>Ready-to-Move Independent Houses</h3>
        <p>Houses built and finished by GS &amp; CO, ready for a family to walk in and live — no waiting through a construction cycle.</p>
      </div>
      <div class="svc-card">
        <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6"/><path d="M9 15h6M9 11h3"/></svg></div>
        <h3>Renovation &amp; Interior Fit-Out</h3>
        <p>Structural additions, upgrades and interior finishing for homes that need to grow with your family or simply feel new again.</p>
      </div>
      <div class="svc-card">
        <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M9 3H4v18h5M15 3h5v18h-5M9 3v18M15 3v18"/></svg></div>
        <h3>Structural Consulting</h3>
        <p>Engineering review of your plans, site or existing structure — for peace of mind before you commit to building.</p>
      </div>
      <div class="svc-card">
        <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="m9 11 3 3L22 4"/><path d="M21 12v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11"/></svg></div>
        <h3>Plan &amp; Approval Assistance</h3>
        <p>Help navigating building plan sanctions and approvals, so paperwork doesn't hold up your construction timeline.</p>
      </div>
      <div class="svc-card" style="background:var(--brick); color:#fff;">
        <div class="icon-box" style="border-color:#fff;"><svg viewBox="0 0 24 24" stroke="#fff" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.362 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.338 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg></div>
        <h3 style="color:#fff;">Not sure what you need?</h3>
        <p style="color:rgba(255,255,255,0.85);">Call 97900 28004 or 90800 26961 — we'll talk through your plot and budget first, no obligation.</p>
      </div>
    </div>
  </div>
</section>

<!-- ============ PROJECTS ============ -->
<section id="projects">
  <div class="wrap pad">
    <div class="section-head">
      <div class="eyebrow-line"><span class="tick"></span><span>What We Build</span></div>
      <h2>House types we specialise in</h2>
      <p>Every plot and every family is different, so every house is planned from scratch. Here's the range GS &amp; CO typically builds.</p>
    </div>
    <div class="proj-grid">
      <div class="proj-card">
        <div class="proj-illustration">
          <svg viewBox="0 0 200 130"><polygon points="30,90 30,50 100,15 170,50 170,90"/><line x1="30" y1="90" x2="170" y2="90"/><rect x="55" y="60" width="25" height="30"/><rect x="120" y="60" width="25" height="30"/><line x1="100" y1="15" x2="100" y2="40" stroke-dasharray="3 3"/></svg>
        </div>
        <div class="proj-body">
          <span class="tag">Compact &amp; Efficient</span>
          <h3>Compact Independent Homes</h3>
          <p>Space-efficient 2–3 bedroom houses for smaller plots, built without compromising on structural quality.</p>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-illustration">
          <svg viewBox="0 0 200 130"><polygon points="20,95 20,55 60,30 140,30 180,55 180,95"/><line x1="20" y1="95" x2="180" y2="95"/><line x1="100" y1="30" x2="100" y2="95"/><rect x="35" y="65" width="22" height="30"/><rect x="145" y="65" width="22" height="30"/></svg>
        </div>
        <div class="proj-body">
          <span class="tag">Growing Families</span>
          <h3>Duplex Family Homes</h3>
          <p>Two-floor independent houses planned for growing families, with room to add on later without re-engineering the structure.</p>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-illustration">
          <svg viewBox="0 0 200 130"><polygon points="15,100 15,55 100,15 185,55 185,100"/><rect x="15" y="100" width="170" height="15"/><rect x="40" y="65" width="30" height="35"/><rect x="130" y="65" width="30" height="35"/><line x1="100" y1="15" x2="100" y2="100" stroke-dasharray="3 3"/></svg>
        </div>
        <div class="proj-body">
          <span class="tag">Within Budget</span>
          <h3>Premium Villas, Real Budgets</h3>
          <p>A villa-level finish and layout, planned around an honest, transparent budget from day one — not a number that grows mid-build.</p>
        </div>
      </div>
      <div class="proj-card">
        <div class="proj-illustration">
          <svg viewBox="0 0 200 130"><rect x="30" y="30" width="140" height="70"/><line x1="30" y1="55" x2="170" y2="55" stroke-dasharray="3 3"/><line x1="70" y1="30" x2="70" y2="100"/><line x1="130" y1="30" x2="130" y2="100"/><path d="M20 30h160" stroke-dasharray="2 4"/></svg>
        </div>
        <div class="proj-body">
          <span class="tag">Upgrade, Not Rebuild</span>
          <h3>Renovations &amp; Extensions</h3>
          <p>Structural additions and full interior overhauls for existing homes that need more space or a proper reinforcement check.</p>
        </div>
      </div>
      <div class="proj-note">Completed-project photos are added here as each site is finished — ask us for the current portfolio and site visits when you call.</div>
    </div>
  </div>
</section>

<!-- ============ PROCESS ============ -->
<section class="alt" id="process">
  <div class="wrap pad">
    <div class="section-head">
      <div class="eyebrow-line"><span class="tick"></span><span>How It Works</span></div>
      <h2>From first call to handover</h2>
    </div>
    <div class="process-row">
      <div class="process-step">
        <div class="marker">1</div>
        <h4>Consultation</h4>
        <p>We visit your plot, understand your family's needs and your budget honestly, upfront.</p>
      </div>
      <div class="process-step">
        <div class="marker">2</div>
        <h4>Design &amp; Engineering</h4>
        <p>Structural drawings, layout and material specs are worked out by the engineer, not estimated on site.</p>
      </div>
      <div class="process-step">
        <div class="marker">3</div>
        <h4>Approvals</h4>
        <p>We help get your building plan sanctioned so there's no delay once construction is ready to start.</p>
      </div>
      <div class="process-step">
        <div class="marker">4</div>
        <h4>Construction</h4>
        <p>Built to the drawings, inspected at every stage, with regular updates so you always know where things stand.</p>
      </div>
      <div class="process-step">
        <div class="marker">5</div>
        <h4>Handover</h4>
        <p>A final walkthrough, documentation handed over, and a house that's ready to move into.</p>
      </div>
    </div>
  </div>
</section>

<!-- ============ TESTIMONIALS ============ -->
<section id="testimonials">
  <div class="wrap pad">
    <div class="section-head">
      <div class="eyebrow-line"><span class="tick"></span><span>Client Trust</span></div>
      <h2>What clients say</h2>
    </div>
    <div class="testi-grid">
      <div class="testi-card">
        <span class="qmark">"</span>
        <p class="txt">Add a testimonial from a homeowner here — a short line on how the process felt and how the finished house turned out works best.</p>
        <div class="who">— Client name, area, Coimbatore</div>
      </div>
      <div class="testi-card">
        <span class="qmark">"</span>
        <p class="txt">Add a second testimonial here — quotes about honest pricing, communication during construction, or build quality carry the most weight.</p>
        <div class="who">— Client name, area, Coimbatore</div>
      </div>
    </div>
  </div>
</section>

<!-- ============ CONTACT ============ -->
<section class="alt" id="contact">
  <div class="grid-bg"></div>
  <div class="wrap pad">
    <div class="section-head">
      <div class="eyebrow-line"><span class="tick"></span><span>Get In Touch</span></div>
      <h2>Let's talk about your plot</h2>
      <p>Call, WhatsApp, or send your details below — we'll get back to you to arrange a site visit.</p>
    </div>
    <div class="contact-grid">
      <div class="contact-info">
        <div class="row">
          <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M21 10c0 7-9 12-9 12s-9-5-9-12a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg></div>
          <div>
            <div class="label">Site Address</div>
            <div class="val">4X8J+223, Pudupalayam Main, Keeranatham, Tamil Nadu 641035</div>
          </div>
        </div>
        <div class="row">
          <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.362 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.338 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg></div>
          <div>
            <div class="label">Phone</div>
            <div class="val"><a href="tel:+919790028004">97900 28004</a> &nbsp;·&nbsp; <a href="tel:+919080026961">90800 26961</a></div>
          </div>
        </div>
        <div class="row">
          <div class="icon-box"><svg viewBox="0 0 24 24" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16v16H4z" stroke="none"/><path d="M4 4h16v16H4V4z"/><path d="m4 4 8 9 8-9"/></svg></div>
          <div>
            <div class="label">Email</div>
            <div class="val"><a href="mailto:gunasekaranandco22@gmail.com">gunasekaranandco22@gmail.com</a></div>
          </div>
        </div>
        <div class="row" style="border-bottom:none;">
          <div class="icon-box" style="border-color:#25D366;"><svg viewBox="0 0 24 24" fill="#25D366" stroke="none"><path d="M17.6 6.32A7.85 7.85 0 0 0 12.02 4a7.94 7.94 0 0 0-6.87 11.9L4 20l4.2-1.1a7.9 7.9 0 0 0 3.8 1h.02A7.94 7.94 0 0 0 20 12.05a7.9 7.9 0 0 0-2.4-5.73zM12.02 18.4a6.5 6.5 0 0 1-3.34-.92l-.24-.14-2.5.65.67-2.44-.16-.25a6.55 6.55 0 1 1 5.57 3.1zm3.6-4.9c-.2-.1-1.17-.58-1.35-.64s-.32-.1-.45.1-.5.63-.62.77-.23.15-.43.05a5.4 5.4 0 0 1-2.7-2.36c-.2-.35.2-.32.58-1.08.06-.13.03-.24-.02-.34s-.45-1.08-.61-1.48c-.16-.38-.33-.33-.45-.34h-.39a.75.75 0 0 0-.54.25 2.28 2.28 0 0 0-.71 1.7 3.96 3.96 0 0 0 .83 2.1 9.05 9.05 0 0 0 3.46 3.06c.48.21.86.33 1.15.42.48.15.92.13 1.27.08.39-.06 1.17-.48 1.34-.94s.17-.86.12-.94-.18-.13-.38-.23z"/></svg></div>
          <div>
            <div class="label">WhatsApp</div>
            <div class="val"><a href="https://wa.me/919790028004" target="_blank" rel="noopener">97900 28004</a> &nbsp;·&nbsp; <a href="https://wa.me/919080026961" target="_blank" rel="noopener">90800 26961</a></div>
          </div>
        </div>
        <div class="map-embed">
          <iframe src="https://www.google.com/maps?q=4X8J%2B223+Pudupalayam+Main+Keeranatham+Tamil+Nadu+641035&output=embed" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="GS & CO location map"></iframe>
        </div>
      </div>

      <form class="inquiry" id="inquiryForm">
        <div class="form-row">
          <div class="form-field">
            <label for="fname">Full name</label>
            <input type="text" id="fname" name="fname" required placeholder="Your name">
          </div>
          <div class="form-field">
            <label for="fphone">Phone number</label>
            <input type="tel" id="fphone" name="fphone" required placeholder="Your phone number">
          </div>
        </div>
        <div class="form-field">
          <label for="fneed">What are you looking for?</label>
          <select id="fneed" name="fneed">
            <option>Build a custom house</option>
            <option>Buy a ready-built house</option>
            <option>Renovation / extension</option>
            <option>Structural consulting</option>
            <option>Not sure — just enquiring</option>
          </select>
        </div>
        <div class="form-field">
          <label for="fmsg">Tell us about your plot / requirement</label>
          <textarea id="fmsg" name="fmsg" placeholder="Plot size, location, rough budget, timeline..."></textarea>
        </div>
        <button type="submit" class="btn btn-primary" style="width:100%; justify-content:center;">Send via WhatsApp</button>
        <p class="form-note">Submitting opens WhatsApp with your details pre-filled to GS &amp; CO — nothing is stored on this site.</p>
      </form>
    </div>
  </div>
</section>

<!-- ============ FOOTER ============ -->
<footer>
  <div class="wrap">
    <div class="footer-grid">
      <div class="footer-brand">
        <img src="data:image/svg+xml;charset=UTF-8,%3Csvg%20xmlns=%22http://www.w3.org/2000/svg%22%20viewBox=%220%200%20120%20120%22%3E%20%3Crect%20width=%22120%22%20height=%22120%22%20fill=%22none%22/%3E%20%3Cpolygon%20points=%2260,8%20106,34%20106,86%2060,112%2014,86%2014,34%22%20fill=%22none%22%20stroke=%22%23A9472B%22%20stroke-width=%225%22/%3E%20%3Cpath%20d=%22M36%2070V50l24-20%2024%2020v20M48%2070V53h24v17%22%20fill=%22none%22%20stroke=%22%2320242A%22%20stroke-width=%225%22%20stroke-linejoin=%22round%22/%3E%20%3C/svg%3E" alt="GS & CO">
        <p>Engineer-led construction of independent houses in Keeranatham and across Coimbatore. Premium quality, honest pricing.</p>
      </div>
      <div>
        <h5>Explore</h5>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#why">Why Us</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#projects">Projects</a></li>
        </ul>
      </div>
      <div>
        <h5>Get In Touch</h5>
        <ul>
          <li><a href="tel:+919790028004">97900 28004</a></li>
          <li><a href="tel:+919080026961">90800 26961</a></li>
          <li><a href="mailto:gunasekaranandco22@gmail.com">gunasekaranandco22@gmail.com</a></li>
        </ul>
      </div>
      <div>
        <h5>Address</h5>
        <ul>
          <li style="color:#9AA0A8;">4X8J+223, Pudupalayam Main,<br>Keeranatham, Tamil Nadu 641035</li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 2026 GS &amp; CO Engineers Builders. All rights reserved.</span>
      <span>Built with precision, priced with honesty.</span>
    </div>
  </div>
</footer>

<a class="whatsapp-float" href="https://wa.me/919790028004" target="_blank" rel="noopener" aria-label="Chat on WhatsApp">
  <svg viewBox="0 0 24 24"><path d="M17.6 6.32A7.85 7.85 0 0 0 12.02 4a7.94 7.94 0 0 0-6.87 11.9L4 20l4.2-1.1a7.9 7.9 0 0 0 3.8 1h.02A7.94 7.94 0 0 0 20 12.05a7.9 7.9 0 0 0-2.4-5.73zM12.02 18.4a6.5 6.5 0 0 1-3.34-.92l-.24-.14-2.5.65.67-2.44-.16-.25a6.55 6.55 0 1 1 5.57 3.1zm3.6-4.9c-.2-.1-1.17-.58-1.35-.64s-.32-.1-.45.1-.5.63-.62.77-.23.15-.43.05a5.4 5.4 0 0 1-2.7-2.36c-.2-.35.2-.32.58-1.08.06-.13.03-.24-.02-.34s-.45-1.08-.61-1.48c-.16-.38-.33-.33-.45-.34h-.39a.75.75 0 0 0-.54.25 2.28 2.28 0 0 0-.71 1.7 3.96 3.96 0 0 0 .83 2.1 9.05 9.05 0 0 0 3.46 3.06c.48.21.86.33 1.15.42.48.15.92.13 1.27.08.39-.06 1.17-.48 1.34-.94s.17-.86.12-.94-.18-.13-.38-.23z"/></svg>
</a>

<script>
  const menuToggle = document.getElementById('menuToggle');
  const mobileNav = document.getElementById('mnav');

  menuToggle.addEventListener('click', () => {
    const isOpen = mobileNav.classList.toggle('open');
    menuToggle.setAttribute('aria-expanded', String(isOpen));
    menuToggle.setAttribute('aria-label', isOpen ? 'Close menu' : 'Open menu');
  });

  mobileNav.querySelectorAll('a').forEach(link => {
    link.addEventListener('click', () => {
      mobileNav.classList.remove('open');
      menuToggle.setAttribute('aria-expanded', 'false');
      menuToggle.setAttribute('aria-label', 'Open menu');
    });
  });

  document.getElementById('inquiryForm').addEventListener('submit', function(e){
    e.preventDefault();

    const name = document.getElementById('fname').value.trim();
    const phone = document.getElementById('fphone').value.trim();
    const need = document.getElementById('fneed').value;
    const msg = document.getElementById('fmsg').value.trim();

    if (!name || !phone) {
      alert('Please enter your name and phone number.');
      return;
    }

    const text =
      `Hi GS & CO, I'm ${name} (${phone}).\n` +
      `I'm interested in: ${need}.` +
      (msg ? `\nDetails: ${msg}` : '');

    const whatsappUrl = 'https://wa.me/919790028004?text=' + encodeURIComponent(text);
    window.open(whatsappUrl, '_blank', 'noopener,noreferrer');
  });
</script>

</body>
</html>
