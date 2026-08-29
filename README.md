
<!doctype html><html lang="en"><head><meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1"><!-- Road to NEC 2026 v6.3 Gemini + Teacher Review Fix -->
<!-- Road to NEC 2026 v6.4 Feedback Code -->
<title>Road to NEC 2026 · English Excellence Portal</title><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Poppins:wght@600;700;800&display=swap" rel="stylesheet">
<style>

:root{
  --navy:#08245c;--navy2:#0d357f;--blue:#1677ff;--blue2:#4ca8ff;
  --red:#e63946;--red2:#ff5c68;--gold:#ffbf2f;--gold2:#ffe08a;
  --sky:#eaf6ff;--cream:#fffaf0;--mint:#e8fbf5;--green:#138a61;
  --ink:#12213f;--slate:#60708d;--line:#dfe7f3;--white:#fff;
  --bg:#f6f9ff;--soft:#eef4ff;--bad:#cf2e3d;
  --shadow:0 16px 42px rgba(8,36,92,.10);--shadow2:0 7px 20px rgba(8,36,92,.08);
  --r:20px;--r2:14px;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;color:var(--ink);background:
  radial-gradient(circle at 4% 2%,rgba(76,168,255,.10),transparent 24rem),
  radial-gradient(circle at 96% 18%,rgba(230,57,70,.07),transparent 22rem),
  var(--bg);
  font-family:'Inter','Segoe UI',Arial,sans-serif;line-height:1.58;
}
h1,h2,h3,.brand,.btn,.topnav button{font-family:'Poppins','Segoe UI',Arial,sans-serif}
button,input,select{font:inherit}
a{color:var(--blue)}
.wrap{max-width:1180px;margin:auto}
.hidden{display:none!important}
.muted{color:var(--slate)}
code{background:#edf3fc;padding:2px 6px;border-radius:6px;color:#29466f}
.tablewrap{overflow:auto;border:1px solid var(--line);border-radius:14px;background:#fff}

/* NAV */
.site-nav{
  position:sticky;top:0;z-index:80;background:rgba(255,255,255,.93);
  backdrop-filter:blur(12px);border-bottom:1px solid rgba(223,231,243,.9);
}
.site-nav .wrap{height:70px;display:flex;align-items:center;gap:18px;padding:0 20px}
.brand{display:flex;align-items:center;gap:11px;color:var(--navy);font-weight:800;text-decoration:none}
.logo{
  width:42px;height:42px;border-radius:13px;display:grid;place-items:center;color:#fff;font-size:.84rem;
  background:linear-gradient(135deg,var(--navy),var(--blue) 62%,#68d3ff);
  box-shadow:0 8px 18px rgba(22,119,255,.25);letter-spacing:.04em
}
.brand small{display:block;color:var(--red);font:700 .63rem 'Inter';letter-spacing:.14em;text-transform:uppercase;margin-top:-2px}
.navlinks{margin-left:auto;display:flex;gap:3px;align-items:center}
.navlinks button{
  border:0;background:transparent;color:#526583;padding:9px 12px;border-radius:10px;font-weight:700;cursor:pointer
}
.navlinks button:hover{background:var(--soft);color:var(--navy)}
.navlinks .nav-teacher{background:var(--navy);color:#fff}
.navlinks .nav-cloud{color:var(--red);background:#fff1f2}
.nav-flag{height:5px;display:grid;grid-template-columns:2fr 1fr 2fr 1fr 2fr}
.nav-flag i:nth-child(1),.nav-flag i:nth-child(5){background:var(--navy)}
.nav-flag i:nth-child(2),.nav-flag i:nth-child(4){background:#fff}
.nav-flag i:nth-child(3){background:var(--red)}

/* HERO */
.hero{
  position:relative;overflow:hidden;color:#fff;padding:0;
  background:
  radial-gradient(850px 420px at 84% 8%,rgba(91,209,255,.50),transparent 60%),
  radial-gradient(700px 380px at 5% 102%,rgba(230,57,70,.42),transparent 62%),
  linear-gradient(128deg,#071c4d 0%,#0b2f78 48%,#164fa5 100%);
}
.hero:before{
  content:"";position:absolute;inset:0;opacity:.16;pointer-events:none;
  background-image:radial-gradient(circle at 20% 30%,#fff 0 1px,transparent 1.4px),
  radial-gradient(circle at 70% 20%,#fff 0 1px,transparent 1.4px),
  radial-gradient(circle at 87% 65%,#fff 0 1px,transparent 1.4px);
  background-size:88px 88px,120px 120px,155px 155px;
}
.hero .wrap{position:relative;z-index:2;padding:70px 20px 74px;display:grid;grid-template-columns:1.35fr .75fr;gap:42px;align-items:center}
.hero-kicker{display:inline-flex;align-items:center;gap:9px;padding:7px 14px;border-radius:999px;background:rgba(255,255,255,.13);border:1px solid rgba(255,255,255,.24);font-size:.79rem;font-weight:800;letter-spacing:.08em;text-transform:uppercase}
.hero h1{font-size:clamp(2.65rem,6vw,4.7rem);line-height:1.02;margin:17px 0 14px;letter-spacing:-.045em}
.hero h1 .gold{color:var(--gold)}
.hero p{max-width:720px;color:#dbe8ff;font-size:1.08rem;margin:0}
.hero-cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:25px}
.btn,.topnav button{
  border:0;border-radius:12px;padding:11px 16px;font-weight:800;cursor:pointer;transition:.15s ease;
}
.btn:hover,.topnav button:hover{transform:translateY(-2px)}
.btn.primary{background:linear-gradient(135deg,var(--blue),var(--blue2));color:#fff;box-shadow:0 8px 20px rgba(22,119,255,.25)}
.btn.secondary{background:#edf3fc;color:var(--navy)}
.btn.red{background:linear-gradient(135deg,var(--red),var(--red2));color:#fff;box-shadow:0 8px 20px rgba(230,57,70,.23)}
.btn.gold{background:linear-gradient(135deg,var(--gold),#ffd970);color:#422d00;box-shadow:0 8px 20px rgba(255,191,47,.28)}
.btn.ghost{background:rgba(255,255,255,.10);border:1px solid rgba(255,255,255,.28);color:#fff}
.hero-card{
  background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.24);border-radius:24px;padding:22px;
  backdrop-filter:blur(12px);box-shadow:0 24px 55px rgba(0,0,0,.20)
}
.hero-card .mini-title{font-weight:800;letter-spacing:.08em;text-transform:uppercase;font-size:.72rem;color:#cfe1ff}
.mission{display:grid;gap:10px;margin-top:14px}
.mission-row{display:flex;align-items:center;gap:11px;padding:12px;border-radius:14px;background:rgba(255,255,255,.09)}
.mission-row .ic{width:38px;height:38px;border-radius:11px;background:rgba(255,255,255,.15);display:grid;place-items:center;font-size:1.1rem}
.mission-row b{display:block;font-size:.93rem}.mission-row span{color:#dce8ff;font-size:.79rem}
.hero-quote{margin-top:18px;border-top:1px solid rgba(255,255,255,.18);padding-top:16px;color:#f3f7ff;font-style:italic}
.hero-quote b{display:block;color:var(--gold2);font-style:normal;font-size:.80rem;margin-top:5px}

/* SECTION */
.section{padding:58px 20px}
.section.alt{background:linear-gradient(180deg,rgba(255,255,255,.75),rgba(235,244,255,.70))}
.section-head{display:flex;justify-content:space-between;gap:24px;align-items:flex-end;margin-bottom:24px}
.eyebrow{color:var(--red);font-weight:800;text-transform:uppercase;letter-spacing:.14em;font-size:.72rem}
.section h2{font-size:clamp(1.7rem,3.5vw,2.45rem);margin:6px 0;color:var(--navy);letter-spacing:-.03em}
.lead{color:var(--slate);max-width:760px;margin:0}

/* CARDS */
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px}
.testcard,.resource,.panel,.skill{
  background:#fff;border:1px solid var(--line);border-radius:var(--r);box-shadow:var(--shadow2);
}
.testcard{padding:20px;position:relative;overflow:hidden;transition:.17s ease}
.testcard:before{content:"";position:absolute;left:0;top:0;right:0;height:5px;background:linear-gradient(90deg,var(--blue),#52c7ff)}
.testcard:nth-child(3n+2):before{background:linear-gradient(90deg,var(--red),#ff8a8f)}
.testcard:nth-child(3n):before{background:linear-gradient(90deg,var(--gold),#ffd97c)}
.testcard:hover,.resource:hover,.skill:hover{transform:translateY(-4px);box-shadow:var(--shadow)}
.testcard h3{margin:11px 0 7px;color:var(--navy);font-size:1.12rem}
.badge{display:inline-flex;align-items:center;gap:6px;font-size:.68rem;font-weight:900;padding:5px 9px;border-radius:999px;background:#e6f8f0;color:var(--green);text-transform:uppercase;letter-spacing:.06em}
.badge:before{content:"●";font-size:.55rem}
.badge.soon{background:#eff3f8;color:#7b8ba4}.badge.soon:before{content:"○"}
.actions{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:16px}
.actions button{padding:10px;border:1px solid #d7e2f0;border-radius:10px;background:#f4f8ff;color:var(--navy);font-weight:800;cursor:pointer}
.actions button:first-child{background:linear-gradient(135deg,var(--navy),var(--blue));color:#fff;border-color:transparent}
.actions button:hover:not(:disabled){transform:translateY(-1px);border-color:#aac8f1}
.actions button:disabled{opacity:.43;cursor:not-allowed}

/* PRACTICE NOTICE */
.notice{padding:12px 14px;background:#fff8df;border:1px solid #f4df96;border-left:4px solid var(--gold);border-radius:11px;margin:12px 0;color:#53627c}
.oknotice{background:#e9fbf3;border-color:#bcebd8;border-left-color:var(--green)}
.badnotice{background:#fff0f2;border-color:#f5c4cb;border-left-color:var(--red);color:#7a3039}
.statusdot{display:inline-block;width:9px;height:9px;border-radius:50%;background:#9bacbf;margin-right:6px}
.online{background:#20a875;box-shadow:0 0 0 4px #20a87520}.offline{background:#df4653}

/* SKILLS */
.skills{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.skill{padding:22px;transition:.17s ease;position:relative;overflow:hidden}
.skill:after{content:"";position:absolute;width:110px;height:110px;border-radius:50%;right:-45px;top:-50px;background:rgba(22,119,255,.08)}
.skill:nth-child(2):after{background:rgba(230,57,70,.08)}
.skill:nth-child(3):after{background:rgba(255,191,47,.16)}
.skill .skill-icon{width:48px;height:48px;display:grid;place-items:center;border-radius:14px;background:var(--soft);font-size:1.35rem;margin-bottom:15px}
.skill b{color:var(--navy);font-size:1.13rem}.skill p{color:var(--slate);min-height:76px}

/* QUOTE BAND */
.quote-band{margin:4px 0 0;background:linear-gradient(125deg,var(--navy),#154b9d);color:#fff;border-radius:24px;padding:28px 30px;display:flex;gap:18px;align-items:center;box-shadow:var(--shadow)}
.quote-mark{font:700 3.4rem Georgia;color:var(--gold);line-height:.8}
.quote-band .q{font-size:1.18rem;font-weight:700;font-style:italic}.quote-band .a{color:#cfe0ff;font-size:.84rem;margin-top:5px}

/* RESOURCES */
.resource{padding:19px;transition:.17s ease}
.resource .meta{font-size:.68rem;font-weight:900;color:var(--blue);text-transform:uppercase;letter-spacing:.08em}
.resource h3{font-size:1.05rem!important}
.resource-actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:13px}
.resource-actions a,.resource-actions button,.resource>a{
  display:inline-flex;align-items:center;gap:6px;border:0;border-radius:10px;padding:9px 12px;font-weight:800;cursor:pointer;text-decoration:none
}
.resource-actions a{background:linear-gradient(135deg,var(--blue),var(--blue2));color:#fff!important}
.resource>a{margin-top:6px;background:#eef4ff;color:var(--navy)}
.resource b{color:var(--navy);font-size:1.04rem}
.resource p{color:var(--slate)}
.authentic-card b:before{margin-right:8px}

/* CLOUD SETUP */
.panel{padding:22px}
.setup-strip{background:linear-gradient(135deg,#fff,#f1f6ff);border:1px solid var(--line);border-radius:20px;padding:20px;display:flex;gap:16px;align-items:center;box-shadow:var(--shadow2)}
.setup-strip .setup-icon{width:52px;height:52px;border-radius:16px;background:linear-gradient(135deg,var(--navy),var(--blue));color:#fff;display:grid;place-items:center;font-size:1.4rem;flex:none}
.setup-strip .grow{flex:1}

/* TEACHER */
.teacher{
  background:
  radial-gradient(620px 240px at 90% 0,rgba(76,168,255,.18),transparent 60%),
  linear-gradient(145deg,#061943,#092760 65%,#0c377a);
  color:#fff;
}
.teacher h2,.teacher .eyebrow{color:#fff}.teacher .eyebrow{opacity:.72}
.teacher .panel{color:var(--ink);background:#fff}
.teacher-login{display:flex;gap:10px;align-items:center}
.teacher-login input{flex:1}
.kpis{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin:16px 0}
.kpi{background:linear-gradient(180deg,#fff,#f4f8ff);border:1px solid var(--line);border-radius:15px;padding:15px}
.kpi b{font-size:1.55rem;color:var(--navy)}
.configgrid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.setup-actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
table{width:100%;border-collapse:collapse;font-size:.84rem;min-width:760px}
th,td{text-align:left;padding:10px 11px;border-bottom:1px solid #e8eef6;white-space:nowrap}
th{background:#f1f6fd;color:var(--navy);font-weight:800;position:sticky;top:0}
tbody tr:hover{background:#fbfdff}

/* MODAL */
.setup-fab{position:fixed;right:18px;bottom:18px;z-index:90;background:linear-gradient(135deg,var(--red),var(--red2));color:#fff;border:0;border-radius:999px;padding:13px 18px;font-weight:900;box-shadow:0 10px 26px rgba(230,57,70,.32);cursor:pointer}
.modal-backdrop{position:fixed;inset:0;background:rgba(4,18,50,.72);z-index:100;display:flex;align-items:center;justify-content:center;padding:18px;backdrop-filter:blur(5px)}
.setup-modal{background:#fff;width:min(740px,100%);max-height:91vh;overflow:auto;border-radius:22px;padding:24px;box-shadow:0 26px 70px rgba(0,0,0,.32)}
.setup-modal h2{margin-top:0;color:var(--navy)}
.setup-close{float:right;border:0;background:#edf3fb;border-radius:10px;padding:8px 11px;font-weight:800;cursor:pointer}
.setup-help{background:#f4f8ff;border:1px solid var(--line);border-radius:13px;padding:13px;margin:12px 0}
.setup-help ol{margin:8px 0 0 20px;padding:0}.setup-help li{margin:6px 0}

/* FOOTER */
.footer{
  background:#061943;color:#cbd9f5;padding:34px 20px;text-align:left;margin-top:0
}
.footer .wrap{display:flex;gap:28px;justify-content:space-between;align-items:center}
.footer .foot-brand{color:#fff;font-weight:800}.footer .foot-quote{max-width:600px;font-style:italic;color:#e8efff}


/* WRITING STUDIO */
.writing-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;margin-top:18px}
.writing-card{background:#fff;border:1px solid var(--line);border-radius:20px;padding:20px;box-shadow:var(--shadow2);position:relative;overflow:hidden;transition:.16s transform,.16s box-shadow}
.writing-card:hover{transform:translateY(-4px);box-shadow:var(--shadow)}
.writing-card:before{content:"";position:absolute;left:0;top:0;bottom:0;width:6px;background:linear-gradient(180deg,var(--red),var(--gold),var(--blue))}
.writing-card .wtop{display:flex;justify-content:space-between;gap:10px;align-items:flex-start}.writing-card .wicon{width:48px;height:48px;border-radius:14px;display:grid;place-items:center;font-size:1.45rem;background:var(--soft)}
.writing-card .wmeta{font-size:.76rem;font-weight:800;color:var(--blue);text-transform:uppercase;letter-spacing:.06em}.writing-card h3{color:var(--navy);margin:10px 0 5px}.writing-card p{color:var(--slate);font-size:.92rem}.writing-card .wstats{display:flex;flex-wrap:wrap;gap:7px;margin:12px 0}.writing-card .wstats span{background:#f2f6fc;border:1px solid var(--line);padding:5px 9px;border-radius:999px;font-size:.75rem;font-weight:700;color:var(--slate)}
.writing-card.pending{border-style:dashed}.writing-card.pending:after{content:"TEACHER EDITABLE";position:absolute;right:-38px;top:18px;transform:rotate(35deg);background:var(--gold);color:#4b3500;font-size:.62rem;font-weight:900;padding:5px 42px;letter-spacing:.06em}
.writing-intro{display:grid;grid-template-columns:1.4fr .8fr;gap:18px;align-items:stretch}.ai-card{background:linear-gradient(145deg,#0b2f76,#174da9);color:#fff;border-radius:20px;padding:20px;box-shadow:var(--shadow)}.ai-card h3{margin:0 0 6px}.ai-card p{color:#dbe8ff;font-size:.9rem}.ai-card .btn{margin-top:8px}
.writing-modal{width:min(1120px,100%);max-height:94vh}.writing-layout{display:grid;grid-template-columns:.92fr 1.18fr;gap:18px}.writing-prompt{background:#f5f8ff;border:1px solid var(--line);border-radius:16px;padding:18px;position:sticky;top:0;align-self:start}.writing-prompt h3{color:var(--navy);margin-top:0}.prompt-text{white-space:pre-wrap;font-size:.96rem;line-height:1.65}.writing-workspace textarea{width:100%;resize:vertical;min-height:110px}.writing-workspace #writingResponse{min-height:390px;line-height:1.65;font-size:1rem}.editor-tools{display:flex;gap:8px;flex-wrap:wrap;align-items:center;margin:8px 0}.editor-stat{background:#eef4ff;border:1px solid var(--line);border-radius:10px;padding:7px 10px;font-weight:800;color:var(--navy);font-size:.82rem}.timer-chip{background:#fff0f1;color:#b61d32}.timer-chip.warn{background:#fff1d8;color:#9a5a00}.timer-chip.danger{background:#ffe1e4;color:#b0132a;animation:pulse 1s infinite}@keyframes pulse{50%{opacity:.6}}
.ai-panel{margin-top:18px;background:#f8fbff;border:1px solid #dce7f6;border-radius:16px;padding:16px}.ai-output{white-space:pre-wrap;background:#fff;border:1px solid var(--line);border-radius:12px;padding:15px;line-height:1.55;max-height:420px;overflow:auto}.ai-key-row{display:grid;grid-template-columns:1fr auto;gap:9px}.ai-disclaimer{font-size:.78rem;color:var(--slate);margin-top:7px}
.writing-admin{margin:22px 0;padding:18px;border:1px solid #d9e2ec;border-radius:17px;background:#fff}.writing-admin textarea{min-height:120px}
@media(max-width:850px){.writing-intro,.writing-layout{grid-template-columns:1fr}.writing-prompt{position:static}.writing-workspace #writingResponse{min-height:320px}}

/* RESPONSIVE */
@media(max-width:900px){
  .hero .wrap{grid-template-columns:1fr}.hero-card{max-width:620px}
  .studentbar{grid-template-columns:1fr 1fr}.studentbar .save-profile{grid-column:1/-1}
  .skills{grid-template-columns:1fr}.navlinks button:not(.nav-teacher):not(.nav-cloud){display:none}
}
@media(max-width:650px){
  .site-nav .wrap{padding:0 14px}.brand span{display:none}.navlinks{gap:6px}.navlinks button{padding:8px 9px;font-size:.8rem}
  .hero .wrap{padding:48px 18px 58px}.hero h1{font-size:2.65rem}.hero-card{padding:17px}
  .section{padding:42px 16px}.section-head{display:block}
  .studentbar,.configgrid,.kpis{grid-template-columns:1fr}.studentbar .save-profile{grid-column:auto}
  .actions{grid-template-columns:1fr}.teacher-login{display:block}.teacher-login .btn{margin-top:9px;width:100%}
  .quote-band{align-items:flex-start}.footer .wrap{display:block}.footer .foot-quote{margin-top:14px}
}

</style></head><body>

<div class="site-nav">
  <div class="wrap">
    <a class="brand" href="#" onclick="window.scrollTo({top:0,behavior:'smooth'});return false">
      <div class="logo">NEC</div>
      <span>Road to NEC 2026<small>English Excellence</small></span>
    </a>
    <div class="navlinks">
      <button onclick="go('tests')">Practice</button>
      <button onclick="go('skills')">Skills</button>
      <button onclick="go('writing')">✍️ Writing Studio</button>
      <button onclick="go('library')">Library</button>
      <button onclick="go('authentic')">Authentic English</button>
      <button class="nav-cloud" onclick="openCloudSetup()">⚙ Cloud</button>
      <button class="nav-teacher" onclick="go('teacher')">👩‍🏫 Teachers</button>
    </div>
  </div>
  <div class="nav-flag"><i></i><i></i><i></i><i></i><i></i></div>
</div>

<header class="hero">
  <div class="wrap">
    <div>
      <div class="hero-kicker">🇺🇸 🇬🇧 National English Competition · 2026</div>
      <h1>Train smart.<br><span class="gold">Think bigger.</span><br>Go further.</h1>
      <p>One focused hub for National Excellent Student English preparation — full mock tests, targeted skill practice, curated resources and a clear record of progress.</p>
      <div class="hero-cta">
        <button class="btn gold" onclick="go('tests')">🎯 Start practising</button>
        <button class="btn ghost" onclick="go('library')">📚 Explore the library</button>
      </div>
      <div class="hero-quote">“Success is the sum of small efforts, repeated day in and day out.”<b>— Robert Collier</b></div>
    </div>
    <aside class="hero-card">
      <div class="mini-title">Your NEC training map</div>
      <div class="mission">
        <div class="mission-row"><div class="ic">🎧</div><div><b>Listen actively</b><span>Track detail, stance, inference and paraphrase.</span></div></div>
        <div class="mission-row"><div class="ic">🔤</div><div><b>Master precision</b><span>Build C1–C2 lexico-grammar and collocation control.</span></div></div>
        <div class="mission-row"><div class="ic">📖</div><div><b>Read like a finalist</b><span>Notice structure, implication and writer purpose.</span></div></div>
      </div>
      <div class="hero-quote">Small gains compound. One serious session today is one less weakness tomorrow.</div>
    </aside>
  </div>
</header>

<section class="cloud-profile">
  <div class="wrap">
    <div class="profile-shell">
      <div id="cloudStatus" class="notice"><span class="statusdot"></span><b>Cloud:</b> checking configuration…</div>
      <div class="studentbar">
        <input id="studentName" placeholder="👤 Student full name">
        <input id="studentClass" placeholder="🏫 Class">
        <input id="joinCode" placeholder="🔑 Class code">
        <select id="practiceTimer" title="Optional practice timer">
          <option value="0">⏱ No timer</option><option value="30">30 minutes</option><option value="45">45 minutes</option>
          <option value="60">60 minutes</option><option value="90">90 minutes</option><option value="120">120 minutes</option>
          <option value="180">180 minutes</option><option value="custom">Custom time…</option>
        </select>
        <button class="btn red save-profile" onclick="saveStudent()">✓ Save profile</button>
      </div>
    </div>
  </div>
</section>

<section class="section" id="tests">
  <div class="wrap">
    <div class="section-head">
      <div><div class="eyebrow">Practice Zone</div><h2>Choose your next challenge</h2>
      <p class="lead">Take a complete paper under test conditions, or train one skill at a time. Every submitted attempt is stored separately, so improvement becomes visible.</p></div>
    </div>
    <div class="notice"><b>⏱ Practice timer:</b> Choose a time limit in your profile above. You may repeat any available test as many times as you need.</div>
    <div class="grid" id="testGrid"></div>
  </div>
</section>

<section class="section alt" id="skills">
  <div class="wrap">
    <div class="section-head"><div><div class="eyebrow">Skill Builder</div><h2>Turn weak points into strengths</h2>
    <p class="lead">Target one area when you want focused repetition rather than a full three-hour paper.</p></div></div>
    <div class="skills">
      <div class="skill"><div class="skill-icon">🎧</div><b>Listening</b><p>Train information tracking, inference, short answers and summary completion with authentic-speed audio.</p><button class="btn primary" onclick="skillMenu('Listening')">Choose a test →</button></div>
      <div class="skill"><div class="skill-icon">🧠</div><b>Language in Use</b><p>Sharpen advanced lexico-grammar, word formation, collocation and error correction.</p><button class="btn red" onclick="skillMenu('Language in Use')">Choose a test →</button></div>
      <div class="skill"><div class="skill-icon">📚</div><b>Reading</b><p>Practise open cloze, ordering, T/F/NG, matching, inference and high-level comprehension.</p><button class="btn gold" onclick="skillMenu('Reading')">Choose a test →</button></div>
    </div>
    <div class="quote-band" style="margin-top:28px"><div class="quote-mark">“</div><div><div class="q">The expert in anything was once a beginner.</div><div class="a">— Helen Hayes</div></div></div>
  </div>
</section>


<section class="section" id="writing">
  <div class="wrap">
    <div class="section-head"><div><div class="eyebrow">Writing Studio</div><h2>Plan. Draft. Review. Improve.</h2>
    <p class="lead">Build exam-ready writing through timed practice, autosaved drafts, multiple attempts and optional AI feedback. Your teacher can add new prompts without changing this webpage.</p></div></div>
    <div class="writing-intro">
      <div class="quote-band" style="margin:0;background:linear-gradient(125deg,#123a9c,#0a2472)"><div class="quote-mark">“</div><div><div class="q">Good writing is rewriting. Strong ideas become stronger through deliberate revision.</div><div class="a">— Writing Studio principle</div></div></div>
      <div class="ai-card"><h3>✨ AI Writing Coach</h3><p>After you submit, add your own Gemini API key to receive an indicative score, targeted feedback, corrected examples and a next-step practice plan.</p><button class="btn gold" onclick="openAIKeyHelp()">🔑 Set up Gemini API key</button></div>
    </div>
    <div id="writingStatus" class="notice" style="margin-top:18px"><b>✍️ Writing tasks:</b> loading…</div>
    <div class="writing-grid" id="writingGrid"></div>
    <div class="writing-admin" style="margin-top:22px;background:linear-gradient(145deg,#fff,#f5f8ff)">
      <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap">
        <div style="margin-right:auto"><div class="eyebrow">Teacher Feedback</div><h3 style="margin:2px 0;color:var(--navy)">📬 My Returned Writing</h3></div>
      </div>
      <p class="muted">Every submitted writing attempt receives a private <b>Feedback Code</b>. Keep the code. You can use it on any device to check whether your teacher has returned a score and comments.</p>
      <div class="configgrid" style="margin-top:12px">
        <div><label><b>Feedback Code</b></label><input id="studentFeedbackCode" placeholder="e.g. NEC-WR-7K4P9X2Q" autocomplete="off" style="text-transform:uppercase"></div>
        <div style="display:flex;align-items:end"><button class="btn secondary" style="width:100%" onclick="checkTeacherWritingFeedbackByCode()">🔎 Check feedback</button></div>
      </div>
      <div class="setup-actions"><button class="btn secondary" onclick="checkTeacherWritingFeedback()">Check feedback saved on this device</button></div>
      <div id="studentWritingFeedbackBox" class="notice">No returned feedback checked yet.</div>
    </div>
  </div>
</section>

<section class="section" id="library">
  <div class="wrap">
    <div class="section-head"><div><div class="eyebrow">Resource Library</div><h2>Build the knowledge behind the score</h2>
    <p class="lead">Teacher-curated materials for NEC preparation. Files uploaded to <code>resources/</code> and published through the Teacher Dashboard appear here automatically.</p></div></div>
    <div id="resourceStatus" class="notice"><b>📚 Resources:</b> loading published materials…</div>
    <div class="grid" id="resourceGrid"></div>
  </div>
</section>

<section class="section alt" id="authentic">
  <div class="wrap">
    <div class="section-head"><div><div class="eyebrow">English in the Wild</div><h2>Read authentic English every day</h2>
    <p class="lead">High-level exam performance grows from wide reading. Explore serious journalism, science, culture and ideas from trusted US & UK sources.</p></div></div>
    <div class="grid">
      <div class="resource authentic-card"><div class="meta">🇬🇧 UK · News</div><b>BBC</b><p>Current affairs, science, culture and international reporting.</p><a target="_blank" rel="noopener" href="https://www.bbc.com/news">Open BBC News ↗</a></div>
      <div class="resource authentic-card"><div class="meta">🇺🇸 USA · Audio + News</div><b>NPR</b><p>News, analysis, science, culture and transcript-rich audio journalism.</p><a target="_blank" rel="noopener" href="https://www.npr.org/">Open NPR ↗</a></div>
      <div class="resource authentic-card"><div class="meta">🇺🇸 USA · Journalism</div><b>The New York Times</b><p>Long-form reporting, opinion and international coverage. Some articles require a subscription.</p><a target="_blank" rel="noopener" href="https://www.nytimes.com/international/">Open NYT ↗</a></div>
      <div class="resource authentic-card"><div class="meta">🇺🇸 USA · Science + Culture</div><b>Smithsonian Magazine</b><p>High-level writing on science, history, culture and innovation.</p><a target="_blank" rel="noopener" href="https://www.smithsonianmag.com/">Open Smithsonian ↗</a></div>
      <div class="resource authentic-card"><div class="meta">🌍 Research · Analysis</div><b>The Conversation</b><p>Research-informed articles written with academic experts.</p><a target="_blank" rel="noopener" href="https://theconversation.com/global">Open The Conversation ↗</a></div>
      <div class="resource authentic-card"><div class="meta">🇬🇧 UK · Long-form Ideas</div><b>Aeon</b><p>Long-form essays in philosophy, science, psychology and culture.</p><a target="_blank" rel="noopener" href="https://aeon.co/">Open Aeon ↗</a></div>
    </div>
    <div class="quote-band" style="margin-top:28px;background:linear-gradient(125deg,#a51d2d,#e63946)"><div class="quote-mark">“</div><div><div class="q">The beautiful thing about learning is that no one can take it away from you.</div><div class="a">— B. B. King</div></div></div>
  </div>
</section>

<section class="section" id="setup">
  <div class="wrap">
    <div class="setup-strip">
      <div class="setup-icon">☁️</div>
      <div class="grow"><div class="eyebrow">Teacher Setup</div><h3 style="margin:3px 0;color:var(--navy)">Connect Road to NEC 2026 to the cloud</h3>
      <p class="muted" style="margin:0">Enter your Supabase Project URL, Publishable Key and Class Code once on this browser.</p></div>
      <button class="btn primary" onclick="openCloudSetup()">⚙ Open Cloud Setup</button>
      <span id="setupInlineStatus" class="muted"></span>
    </div>
  </div>
</section>

<section class="section teacher" id="teacher">
  <div class="wrap">
    <div class="section-head"><div><div class="eyebrow">For Teachers</div><h2>Teacher Dashboard</h2>
    <p class="lead" style="color:#d1e1ff">Track attempts, scores and progress; manage resources; and keep the portal secure.</p></div></div>
    <div class="panel">
      <div id="teacherLock">
        <div style="display:flex;gap:14px;align-items:flex-start"><div style="font-size:2rem">🔐</div><div style="flex:1"><h3 style="margin:0 0 5px;color:var(--navy)">Private teacher access</h3><p class="muted" style="margin-top:0">Enter your private teacher code. It is checked in the database and is not stored in the student link.</p>
        <div class="teacher-login"><input id="teacherCode" type="password" placeholder="Teacher code"><button class="btn primary" onclick="teacherLogin()">Open cloud dashboard</button></div></div></div>
      </div>
      <div id="teacherData" class="hidden">
        <div class="kpis">
          <div class="kpi"><span class="muted">Submissions</span><br><b id="kpiSub">0</b></div>
          <div class="kpi"><span class="muted">Students</span><br><b id="kpiStu">0</b></div>
          <div class="kpi"><span class="muted">Tests attempted</span><br><b id="kpiTests">0</b></div>
          <div class="kpi"><span class="muted">Average</span><br><b id="kpiAvg">—</b></div>
        </div>
        <div style="display:flex;gap:9px;flex-wrap:wrap;align-items:center;margin:12px 0 8px">
          <h3 style="margin-right:auto;color:var(--navy)">📊 Student activity</h3>
          <button class="btn secondary" onclick="refreshTeacher()">↻ Refresh</button>
          <button class="btn secondary" onclick="exportCSV()">⬇ Export CSV</button>
          <button class="btn secondary" onclick="toggleChangeTeacherCode()">🔑 Change teacher code</button>
          <button class="btn red" onclick="teacherLogout()">🔒 Lock dashboard</button>
        </div>

        <div id="changeTeacherCodeBox" class="hidden" style="margin:14px 0;padding:16px;border:1px solid #d9e2ec;border-radius:15px;background:#f7faff">
          <h3 style="margin-top:0;color:var(--navy)">Change teacher code</h3>
          <p class="muted">Choose a private code of at least 8 characters. The new code is hashed in Supabase and is never stored in this webpage.</p>
          <div class="configgrid"><div><label><b>New teacher code</b></label><input id="newTeacherCode" type="password" autocomplete="new-password" placeholder="New private code"></div><div><label><b>Confirm new code</b></label><input id="confirmTeacherCode" type="password" autocomplete="new-password" placeholder="Confirm new code"></div></div>
          <div class="setup-actions"><button class="btn primary" onclick="changeTeacherCode()">Save new teacher code</button><button class="btn secondary" onclick="toggleChangeTeacherCode(false)">Cancel</button></div>
          <div id="changeTeacherMessage" class="notice hidden" style="margin-top:12px"></div>
        </div>


        <div class="writing-admin" id="writingManager">
          <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap">
            <div style="margin-right:auto"><div class="eyebrow">Writing Manager</div><h3 style="margin:2px 0;color:var(--navy)">✍️ Manage Writing Tasks</h3></div>
            <button class="btn secondary" onclick="refreshTeacherWritingTasks()">↻ Refresh tasks</button>
            <button class="btn secondary" onclick="refreshWritingSubmissions()">📊 Writing attempts</button>
          </div>
          <p class="muted">Add or edit prompts here. New tasks are published to the Writing Studio immediately through Supabase.</p>
          <div class="configgrid">
            <div><label><b>Title</b></label><input id="wtTitle" placeholder="e.g. Data Description 01"></div>
            <div><label><b>Category</b></label><select id="wtCategory"><option>Data Description</option><option>Discursive Essay</option></select></div>
            <div><label><b>Time limit</b></label><input id="wtTime" type="number" min="5" max="180" value="20"></div>
            <div><label><b>Difficulty</b></label><input id="wtDifficulty" placeholder="e.g. C1–C2 / NEC"></div>
          </div>
          <div class="configgrid" style="margin-top:10px"><div><label><b>Optional task image path / URL</b></label><input id="wtImage" placeholder="resources/writing/chart01.png"></div><div><label><b>Word guidance</b></label><input id="wtWords" placeholder="e.g. 180–220 words"></div></div><div style="margin-top:10px"><label><b>Task prompt</b></label><textarea id="wtPrompt" placeholder="Paste the complete task prompt here. For a chart/table task, include the image URL or description if needed."></textarea></div>
          <div style="margin-top:10px"><label><b>Optional rubric / teacher notes</b></label><input id="wtRubric" placeholder="AI uses this rubric if provided"></div>
          <div class="setup-actions"><button class="btn primary" onclick="saveWritingTask()">Publish writing task</button><button class="btn secondary" onclick="clearWritingTaskForm()">Clear form</button></div>
          <div id="writingManagerMessage" class="notice hidden" style="margin-top:12px"></div>
          <div class="tablewrap" style="margin-top:14px"><table><thead><tr><th>Title</th><th>Category</th><th>Time</th><th>Difficulty</th><th>Status</th><th>Actions</th></tr></thead><tbody id="teacherWritingTasksBody"></tbody></table></div>
          <div id="writingAttemptsBox" class="hidden" style="margin-top:16px"><h3 style="color:var(--navy)">Writing attempts</h3><div class="tablewrap"><table><thead><tr><th>Student</th><th>Class</th><th>Task</th><th>Category</th><th>Feedback Code</th><th>Attempts</th><th>Words</th><th>Status</th><th>Score</th><th>Submitted</th><th>Action</th></tr></thead><tbody id="writingAttemptsBody"></tbody></table></div>
            <div id="writingReviewPanel" class="hidden" style="margin-top:16px;padding:18px;border:1px solid var(--line);border-radius:16px;background:#f8fbff">
              <div style="display:flex;align-items:center;gap:10px;flex-wrap:wrap"><div style="margin-right:auto"><div class="eyebrow">Teacher Review</div><h3 id="reviewStudentTitle" style="margin:2px 0;color:var(--navy)">Review submission</h3></div><button class="btn secondary" onclick="closeWritingReview()">Close review</button></div>
              <div class="configgrid" style="margin-top:12px"><div><b>Task</b><div id="reviewTaskTitle" class="muted"></div></div><div><b>Submitted</b><div id="reviewSubmittedAt" class="muted"></div></div></div>
              <label style="display:block;margin-top:12px"><b>Student response</b></label><div id="reviewResponseText" style="white-space:pre-wrap;max-height:360px;overflow:auto;background:#fff;border:1px solid var(--line);border-radius:12px;padding:14px;line-height:1.65"></div>
              <div id="reviewCriteriaBox" class="configgrid" style="margin-top:14px"></div>
              <div style="margin-top:12px"><label><b>Teacher feedback</b></label><textarea id="reviewTeacherFeedback" placeholder="Write clear, actionable feedback for the student…" style="min-height:150px"></textarea></div>
              <div class="setup-actions"><span class="editor-stat" id="reviewTotalScore">0.00 / 0.00</span><button class="btn primary" onclick="returnWritingReviewToStudent()">✅ Return score & feedback to student</button></div>
              <div id="reviewSaveMessage" class="notice hidden" style="margin-top:12px"></div>
            </div>
          </div>
        </div>

        <div id="resourceManager" style="margin:22px 0;padding:18px;border:1px solid #d9e2ec;border-radius:17px;background:#fff">
          <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap">
            <div style="margin-right:auto"><div class="eyebrow">Library Manager</div><h3 style="margin:2px 0;color:var(--navy)">📚 Manage Resources</h3></div>
            <button class="btn primary" onclick="scanGitHubResources()">🔎 Scan GitHub Resources</button>
            <button class="btn secondary" onclick="refreshTeacherResources()">↻ Refresh published resources</button>
          </div>
          <p class="muted">Upload files to GitHub <code>resources/</code>, then scan. Unpublished files can be added to the student Resource Library with one click.</p>
          <div id="githubScanBox" class="hidden" style="margin:14px 0;padding:14px;border:1px solid #d9e2ec;border-radius:12px;background:#f8fbff">
            <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap"><b>Files found on GitHub</b><span id="githubScanStatus" class="muted"></span></div>
            <div class="tablewrap" style="margin-top:10px"><table><thead><tr><th>File</th><th>Type</th><th>Status</th><th>Action</th></tr></thead><tbody id="githubScanBody"></tbody></table></div>
          </div>
          <div class="configgrid">
            <div><label><b>Resource title</b></label><input id="resTitle" placeholder="e.g. CPE Reading Practice"></div>
            <div><label><b>Category</b></label><input id="resCategory" placeholder="e.g. Practice Paper / Vocabulary"></div>
            <div><label><b>Level</b></label><input id="resLevel" placeholder="e.g. C1–C2 / C2+"></div>
            <div><label><b>File path or URL</b></label><input id="resUrl" placeholder="resources/filename.pdf"></div>
          </div>
          <div style="margin-top:10px"><label><b>Description</b></label><input id="resDescription" placeholder="Short description shown to students"></div>
          <div class="setup-actions"><button class="btn primary" onclick="publishResource()">Publish resource</button><button class="btn secondary" onclick="clearResourceForm()">Clear form</button></div>
          <div id="resourceManagerMessage" class="notice hidden" style="margin-top:12px"></div>
          <div class="tablewrap" style="margin-top:14px"><table><thead><tr><th>Title</th><th>Category</th><th>Level</th><th>Path</th><th>Status</th><th>Actions</th></tr></thead><tbody id="teacherResourcesBody"></tbody></table></div>
        </div>

        <div class="tablewrap"><table><thead><tr><th>Student</th><th>Class</th><th>Test</th><th>Mode</th><th>Attempts</th><th>Result</th><th>Listening</th><th>LIU</th><th>Reading</th><th>Submitted</th></tr></thead><tbody id="recordsBody"></tbody></table></div>
      </div>
    </div>
  </div>
</section>


<div id="writingModal" class="modal-backdrop hidden" role="dialog" aria-modal="true" aria-labelledby="writingModalTitle">
  <div class="setup-modal writing-modal">
    <button class="setup-close" onclick="closeWritingTask()">✕ Close</button>
    <h2 id="writingModalTitle">✍️ Writing Studio</h2>
    <div class="writing-layout">
      <aside class="writing-prompt">
        <div id="writingTaskMeta" class="eyebrow">Writing Task</div>
        <h3 id="writingTaskTitle">Task</h3>
        <div class="wstats" style="display:flex;gap:7px;flex-wrap:wrap;margin-bottom:12px"><span class="editor-stat" id="writingTaskTime">20 minutes</span><span class="editor-stat" id="writingTaskWords">Word guidance</span><span class="editor-stat" id="writingTaskDifficulty">NEC</span></div>
        <img id="writingTaskImage" class="hidden" alt="Writing task visual" style="width:100%;max-height:430px;object-fit:contain;background:#fff;border:1px solid var(--line);border-radius:12px;margin:0 0 14px"><div class="prompt-text" id="writingTaskPrompt"></div>
        <div class="notice" style="margin-top:14px"><b>Strategy:</b> spend a few minutes planning, write with purpose, then reserve time to review.</div>
      </aside>
      <div class="writing-workspace">
        <label><b>🧠 Planning notes</b> <span class="muted">(private draft notes)</span></label>
        <textarea id="writingPlan" placeholder="Thesis / overview / key features / main arguments / examples…" oninput="saveWritingDraft()"></textarea>
        <div class="editor-tools"><span class="editor-stat" id="writingWordCount">0 words</span><span class="editor-stat timer-chip" id="writingTimer">00:00</span><span class="editor-stat" id="writingSaveState">Draft ready</span></div>
        <label><b>📝 Final response</b></label>
        <textarea id="writingResponse" placeholder="Write your response here…" oninput="writingInputChanged()"></textarea>
        <div class="setup-actions"><button class="btn secondary" onclick="saveWritingDraft(true)">💾 Save draft</button><button class="btn secondary" onclick="newWritingAttempt()">↻ Start new attempt</button><button class="btn red" onclick="submitWritingAttempt()">Submit writing</button></div>
        <div id="writingSubmitMessage" class="notice hidden" style="margin-top:12px"></div>
        <div class="setup-actions"><button class="btn secondary" onclick="checkTeacherWritingFeedback()">📬 Check teacher feedback</button></div>
        <div class="ai-panel" id="writingAIBox">
          <h3 style="color:var(--navy);margin-top:0">✨ AI Writing Coach</h3>
          <p class="muted">AI feedback becomes available after you submit. The score is formative and advisory, not an official NEC grade.</p>
          <div class="ai-key-row"><input id="geminiKey" type="password" placeholder="Paste your Gemini API key"><button class="btn secondary" onclick="saveGeminiKey()">Save key</button></div>
          <div class="ai-disclaimer">Your API key is stored only in this browser and is sent directly to Google Gemini when you request feedback. It is not uploaded to Supabase.</div>
          <div class="setup-actions"><button class="btn gold" id="aiFeedbackBtn" onclick="requestAIFeedback()" disabled>✨ Get AI score & feedback</button><button class="btn secondary" onclick="openAIKeyHelp()">How to get a key</button></div>
          <div id="aiFeedbackStatus" class="notice hidden"></div><div id="aiFeedbackOutput" class="ai-output hidden"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="cloudSetupModal" class="modal-backdrop hidden" role="dialog" aria-modal="true" aria-labelledby="cloudSetupTitle">
  <div class="setup-modal">
    <button class="setup-close" onclick="closeCloudSetup()">✕ Close</button>
    <h2 id="cloudSetupTitle">☁️ Cloud Setup</h2>
    <p>Enter the public Supabase settings for <b>Road to NEC 2026</b>. These values are saved only in this browser.</p>
    <div class="setup-help"><b>Where to find these values</b><ol><li>Open your Supabase project.</li><li>Copy the <b>Project URL</b>.</li><li>Copy the <b>Publishable key</b> beginning with <code>sb_publishable_</code>.</li><li>Use the class code created by your SQL setup, for example <code>CVA-NEC-2026</code>.</li></ol></div>
    <div class="configgrid"><div><label><b>Supabase Project URL</b></label><input id="sbUrl" placeholder="https://YOUR-PROJECT.supabase.co"></div><div><label><b>Publishable Key</b></label><input id="sbKey" placeholder="sb_publishable_..."></div><div><label><b>Class Code</b></label><input id="setupJoin" placeholder="CVA-NEC-2026"></div></div>
    <div class="setup-actions"><button class="btn primary" onclick="saveCloudConfig()">Save & Test Connection</button><button class="btn secondary" onclick="copyStudentLink()">Copy Configured Student Link</button></div>
    <div id="setupMessage" class="notice" style="margin-top:14px">No connection test has been run yet.</div>
  </div>
</div>

<button class="setup-fab" onclick="openCloudSetup()">⚙ Cloud Setup</button>

<div class="footer"><div class="wrap"><div><div class="foot-brand">🇺🇸 🇬🇧 Road to NEC 2026 · English Excellence</div><div class="muted" style="color:#9fb4d8;margin-top:4px">Built for focused, ambitious learners.</div></div><div class="foot-quote">“Don’t watch the clock; do what it does. Keep going.” — Sam Levenson</div></div></div>

<script>
const TESTS=[{id:1,name:'Homework 6.8',file:'Test_01_Homework_6.8.html',status:'Available'},{id:2,name:'Homework 7.8',file:'Test_02_Homework_7.8.html',status:'Available'},{id:3,name:'Homework 13.8',file:'Test_03_Homework_13.8.html',status:'Available'},{id:4,name:'Homework 20.8',file:'Test_04_Homework_20.8.html',status:'Available'},{id:5,name:'Homework 24.8',file:'Test_05_Homework_24.8.html',status:'Available'},{id:6,name:'Homework 27.8',file:'Test_06_Homework_27.8.html',status:'Available'},...Array.from({length:14},(_,i)=>({id:i+7,name:'Practice Test '+(i+7),status:'Coming soon'}))];
let teacherRows=[], teacherTimer=null, activeTeacherCode='';
function go(id){document.getElementById(id).scrollIntoView({behavior:'smooth'})}
function openCloudSetup(){loadStudent();cloudSetupModal.classList.remove('hidden');setTimeout(()=>sbUrl.focus(),50)}
function closeCloudSetup(){cloudSetupModal.classList.add('hidden')}
cloudSetupModal?.addEventListener('click',e=>{if(e.target===cloudSetupModal)closeCloudSetup()});
document.addEventListener('keydown',e=>{if(e.key==='Escape'&&!cloudSetupModal.classList.contains('hidden'))closeCloudSetup()});
function esc(s){return String(s??'').replace(/[&<>"']/g,m=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[m]))}
function getCloud(){const p=new URLSearchParams(location.search), saved=JSON.parse(localStorage.getItem('NEC_CLOUD_CONFIG')||'{}');return {url:(p.get('sburl')||saved.url||'').replace(/\/$/,''),key:p.get('sbkey')||saved.key||'',join:p.get('join')||saved.join||''}}
function configured(){let c=getCloud();return /^https:\/\/.+\.supabase\.co$/.test(c.url)&&c.key.startsWith('sb_publishable_')&&!!c.join}
async function rpc(name,body){let c=getCloud();if(!c.url||!c.key)throw new Error('Supabase is not configured');let r=await fetch(c.url+'/rest/v1/rpc/'+name,{method:'POST',headers:{'Content-Type':'application/json','apikey':c.key},body:JSON.stringify(body)});let text=await r.text();if(!r.ok)throw new Error(text||('HTTP '+r.status));return text?JSON.parse(text):null}
function updateCloudStatus(msg,ok){let e=document.getElementById('cloudStatus'),c=getCloud();e.className='notice '+(ok?'oknotice':'badnotice');e.innerHTML='<span class="statusdot '+(ok?'online':'offline')+'"></span><b>Cloud:</b> '+esc(msg)+(c.join?' · class code <code>'+esc(c.join)+'</code>':'')}
async function checkCloud(){if(!configured()){updateCloudStatus('not configured yet. Use Cloud Setup below.',false);return}try{let c=getCloud(),d=await rpc('nec_class_info',{p_join_code:c.join});if(d&&d.length)updateCloudStatus('connected to '+d[0].class_name,true);else updateCloudStatus('connected, but the class code is invalid.',false)}catch(e){updateCloudStatus('connection failed: '+e.message,false)}}
function renderTests(){testGrid.innerHTML=TESTS.map(t=>{const live=!!t.file;const icon=t.id%3===1?'🎯':t.id%3===2?'🚀':'🏆';return `<div class="testcard"><div style="display:flex;justify-content:space-between;align-items:flex-start;gap:10px"><span class="badge ${t.status!=='Available'?'soon':''}">${t.status}</span><span style="font-size:1.35rem">${live?icon:'🔒'}</span></div><h3>Test ${String(t.id).padStart(2,'0')} · ${esc(t.name)}</h3><p class="muted" style="font-size:.9rem">🎧 Listening &nbsp;·&nbsp; 🔤 Language in Use &nbsp;·&nbsp; 📖 Reading</p><div class="actions"><button ${live?'':'disabled'} onclick="openTest(${t.id},'Full Test')">🎯 Full Test</button><button ${live?'':'disabled'} onclick="openTest(${t.id},'Listening')">🎧 Listening</button><button ${live?'':'disabled'} onclick="openTest(${t.id},'Language in Use')">🔤 Language in Use</button><button ${live?'':'disabled'} onclick="openTest(${t.id},'Reading')">📖 Reading</button></div></div>`}).join('')}
function saveStudent(){localStorage.setItem('NEC_STUDENT',JSON.stringify({name:studentName.value.trim(),className:studentClass.value.trim(),timer:practiceTimer.value}));let c=getCloud();if(joinCode.value.trim()){c.join=joinCode.value.trim();localStorage.setItem('NEC_CLOUD_CONFIG',JSON.stringify(c))}alert('Profile saved. You are ready to practise!')}
function loadStudent(){try{let s=JSON.parse(localStorage.getItem('NEC_STUDENT')||'{}');studentName.value=s.name||'';studentClass.value=s.className||'';if(document.getElementById('practiceTimer'))practiceTimer.value=s.timer||'0'}catch(e){}let c=getCloud();joinCode.value=c.join||'';sbUrl.value=c.url||'';sbKey.value=c.key||'';setupJoin.value=c.join||''}
function openTest(id,mode){
  let t=TESTS.find(x=>x.id===id);if(!t||!t.file)return;
  let name="Ẩn danh", cl="Không rõ", c=getCloud();
  let join="NO_JOIN";
  let mins=practiceTimer ? practiceTimer.value : 0;
  let q=new URLSearchParams({practice:mode,student:name,class:cl,join:join,timer:String(mins||0)});
  window.open(t.file+'?'+q.toString(),'_blank')
}
mins=practiceTimer.value;if(mins==='custom'){let v=prompt('Enter your practice time in minutes (1–300):','60');if(v===null)return;mins=Math.max(1,Math.min(300,parseInt(v,10)||60));}saveStudent();let q=new URLSearchParams({practice:mode,student:name,class:cl,join:join,timer:String(mins||0)});if(c.url)q.set('sburl',c.url);if(c.key)q.set('sbkey',c.key);window.open(t.file+'?'+q.toString(),'_blank')}
function skillMenu(skill){let avail=TESTS.filter(t=>t.file);let n=prompt('Enter the test number for '+skill+' practice ('+avail.map(x=>x.id).join(', ')+'):');let id=Number(n);if(avail.some(x=>x.id===id))openTest(id,skill);else if(n!==null)alert('That test is not available yet.')}
async function saveCloudConfig(){let c={url:sbUrl.value.trim().replace(/\/$/,''),key:sbKey.value.trim(),join:setupJoin.value.trim()};localStorage.setItem('NEC_CLOUD_CONFIG',JSON.stringify(c));joinCode.value=c.join;setupMessage.className='notice';setupMessage.textContent='Testing connection…';try{let d=await rpc('nec_class_info',{p_join_code:c.join});if(d&&d.length){setupMessage.className='notice oknotice';setupMessage.textContent='Connected successfully to '+d[0].class_name+'.';if(document.getElementById('setupInlineStatus'))setupInlineStatus.textContent='Cloud connected.';updateCloudStatus('connected to '+d[0].class_name,true)}else throw new Error('Class code not found')}catch(e){setupMessage.className='notice badnotice';setupMessage.textContent='Connection failed: '+e.message;if(document.getElementById('setupInlineStatus'))setupInlineStatus.textContent='Not connected.';updateCloudStatus('connection failed',false)}}
function configuredUrl(){let c=getCloud(),u=new URL(location.href);u.search='';u.hash='';u.searchParams.set('sburl',c.url);u.searchParams.set('sbkey',c.key);u.searchParams.set('join',c.join);return u.href}
async function copyStudentLink(){if(!configured()){alert('Save a valid Supabase URL, publishable key and class code first.');return}if(location.protocol==='file:'){alert('For use on multiple devices, upload these HTML files to a static host such as GitHub Pages first. Then use this button on the hosted page.');return}let u=configuredUrl();try{await navigator.clipboard.writeText(u);setupMessage.textContent='Configured student link copied.'}catch(e){prompt('Copy this student link:',u)}}
window.addEventListener('message',e=>{let d=e.data;if(!d||d.type!=='NEC_RESULT')return;let recs=JSON.parse(localStorage.getItem('NEC_LOCAL_RECORDS')||'[]');recs.push(d);localStorage.setItem('NEC_LOCAL_RECORDS',JSON.stringify(recs))});
async function teacherLogin(){let code=teacherCode.value.trim();if(!code){alert('Enter the teacher code.');return}if(!configured()){alert('Configure Supabase first in Cloud Setup.');go('setup');return}activeTeacherCode=code;try{await refreshTeacher();teacherLock.classList.add('hidden');teacherData.classList.remove('hidden');await refreshTeacherResources();teacherTimer=setInterval(()=>{refreshTeacher();refreshTeacherResources()},30000)}catch(e){activeTeacherCode='';alert('Dashboard access failed. Check the teacher code and Supabase setup.\n'+e.message)}}
async function refreshTeacher(){if(!activeTeacherCode)return;let d=await rpc('teacher_nec_dashboard',{p_teacher_code:activeTeacherCode,p_limit:2000});teacherRows=Array.isArray(d)?d:[];renderRecords()}
function toggleChangeTeacherCode(force){const box=document.getElementById('changeTeacherCodeBox');if(!box)return;const show=typeof force==='boolean'?force:box.classList.contains('hidden');box.classList.toggle('hidden',!show);if(show){document.getElementById('newTeacherCode').value='';document.getElementById('confirmTeacherCode').value='';document.getElementById('changeTeacherMessage').classList.add('hidden');document.getElementById('newTeacherCode').focus()}}
async function changeTeacherCode(){if(!activeTeacherCode){alert('Unlock the Teacher Dashboard first.');return}const n=document.getElementById('newTeacherCode').value.trim(),c=document.getElementById('confirmTeacherCode').value.trim(),msg=document.getElementById('changeTeacherMessage');msg.classList.remove('hidden','oknotice','badnotice');if(n.length<8){msg.classList.add('badnotice');msg.textContent='The new teacher code must contain at least 8 characters.';return}if(n!==c){msg.classList.add('badnotice');msg.textContent='The two new-code entries do not match.';return}if(n===activeTeacherCode){msg.classList.add('badnotice');msg.textContent='Choose a new code different from the current one.';return}try{await rpc('change_nec_teacher_code',{p_current_code:activeTeacherCode,p_new_code:n});activeTeacherCode=n;teacherCode.value=n;msg.classList.add('oknotice');msg.textContent='Teacher code changed successfully. Use the new code from now on.';document.getElementById('newTeacherCode').value='';document.getElementById('confirmTeacherCode').value=''}catch(e){msg.classList.add('badnotice');msg.textContent='Could not change the teacher code: '+e.message}}
function teacherLogout(){activeTeacherCode='';teacherCode.value='';teacherData.classList.add('hidden');teacherLock.classList.remove('hidden');if(teacherTimer)clearInterval(teacherTimer)}
function fmtNum(v){return v==null?'—':Number(v).toFixed(2)}
function renderRecords(){const key=x=>[(x.student_name||'').trim().toLowerCase(),(x.student_class||x.class_name||'').trim().toLowerCase(),x.test_id,x.practice_mode||'Full Test'].join('|');const attempts={};teacherRows.forEach(x=>attempts[key(x)]=(attempts[key(x)]||0)+1);recordsBody.innerHTML=teacherRows.length?teacherRows.map(x=>`<tr><td>${esc(x.student_name)}</td><td>${esc(x.student_class||x.class_name)}</td><td>${esc(x.test_name)}</td><td>${esc(x.practice_mode)}</td><td><b>${attempts[key(x)]}</b></td><td>${x.percent!=null?Number(x.percent).toFixed(1)+'%':fmtNum(x.score)+' / '+fmtNum(x.max_score)}</td><td>${fmtNum(x.listening)}</td><td>${fmtNum(x.language_in_use)}</td><td>${fmtNum(x.reading)}</td><td>${new Date(x.submitted_at).toLocaleString()}</td></tr>`).join(''):'<tr><td colspan="10" class="muted">No cloud submissions yet.</td></tr>';kpiSub.textContent=teacherRows.length;kpiStu.textContent=new Set(teacherRows.map(x=>(x.student_name+'|'+(x.student_class||'')).toLowerCase())).size;kpiTests.textContent=new Set(teacherRows.map(x=>x.test_id)).size;let ps=teacherRows.map(x=>Number(x.percent)).filter(Number.isFinite);kpiAvg.textContent=ps.length?(ps.reduce((a,b)=>a+b,0)/ps.length).toFixed(1)+'%':'—'}
function exportCSV(){let rows=[['Student','Class','Test','Mode','Attempts','Score','Max score','Percent','Listening','Language in Use','Reading','Submitted'],...teacherRows.map(x=>{const k=[(x.student_name||'').trim().toLowerCase(),(x.student_class||x.class_name||'').trim().toLowerCase(),x.test_id,x.practice_mode||'Full Test'].join('|');const n=teacherRows.filter(y=>[(y.student_name||'').trim().toLowerCase(),(y.student_class||y.class_name||'').trim().toLowerCase(),y.test_id,y.practice_mode||'Full Test'].join('|')===k).length;return[x.student_name,x.student_class||x.class_name,x.test_name,x.practice_mode,n,x.score,x.max_score,x.percent,x.listening,x.language_in_use,x.reading,x.submitted_at]})];let csv=rows.map(a=>a.map(v=>'"'+String(v??'').replace(/"/g,'""')+'"').join(',')).join('\n');let a=document.createElement('a');a.href=URL.createObjectURL(new Blob([csv],{type:'text/csv'}));a.download='Road_to_NEC_2026_cloud_activity.csv';a.click();setTimeout(()=>URL.revokeObjectURL(a.href),1000)}


const GITHUB_OWNER='baotramnguyen1112-afk';
const GITHUB_REPO='Road-to-NEC-2026';
const GITHUB_RESOURCES_PATH='resources';
function prettyResourceTitle(name){return String(name||'').replace(/\.[^.]+$/,'').replace(/[_-]+/g,' ').replace(/\s+/g,' ').trim()}
function guessResourceCategory(name){const s=String(name||'').toLowerCase();if(s.includes('listening'))return 'Listening';if(s.includes('vocab')||s.includes('collocation'))return 'Vocabulary';if(s.includes('grammar')||s.includes('language'))return 'Language in Use';if(s.includes('reading'))return 'Reading';if(s.includes('hsg')||s.includes('de-')||s.includes('test')||s.includes('exam'))return 'Practice Paper';return 'Reference Material'}
function resourceFileType(name){const m=String(name||'').match(/\.([^.]+)$/);return m?m[1].toUpperCase():'FILE'}
async function scanGitHubResources(){
  if(!activeTeacherCode){alert('Unlock the Teacher Dashboard first.');return}
  const box=document.getElementById('githubScanBox'),body=document.getElementById('githubScanBody'),status=document.getElementById('githubScanStatus');
  box.classList.remove('hidden');body.innerHTML='<tr><td colspan="4">Scanning GitHub…</td></tr>';status.textContent='';
  try{
    const api=`https://api.github.com/repos/${GITHUB_OWNER}/${GITHUB_REPO}/contents/${GITHUB_RESOURCES_PATH}`;
    const res=await fetch(api,{headers:{'Accept':'application/vnd.github+json'}});
    if(!res.ok)throw new Error('GitHub API returned '+res.status);
    const files=(await res.json()).filter(x=>x.type==='file'&&!/^README(\.|$)/i.test(x.name));
    const published=await rpc('teacher_nec_resources',{p_teacher_code:activeTeacherCode})||[];
    const publishedPaths=new Set(published.map(r=>String(r.file_url||'').replace(/^\.\//,'').toLowerCase()));
    if(!files.length){body.innerHTML='<tr><td colspan="4">No files found in resources/.</td></tr>';status.textContent='0 files';return}
    status.textContent=`${files.length} file${files.length===1?'':'s'} found`;
    body.innerHTML=files.map((f,i)=>{
      const rel=`resources/${f.name}`; const done=publishedPaths.has(rel.toLowerCase());
      const safeName=escHtml(f.name),safeRel=escHtml(rel),type=resourceFileType(f.name);
      const payload=encodeURIComponent(JSON.stringify({name:f.name,path:rel}));
      return `<tr><td><code>${safeName}</code></td><td>${escHtml(type)}</td><td>${done?'<span style="color:#167d5a;font-weight:800">✓ Published</span>':'<span style="color:#c53030;font-weight:800">Not published</span>'}</td><td>${done?'<button class="btn" disabled>Published</button>':`<button class="btn primary" onclick="publishScannedResource('${payload}')">Publish</button>`}</td></tr>`
    }).join('');
  }catch(e){body.innerHTML='<tr><td colspan="4">Could not scan GitHub: '+escHtml(e.message)+'</td></tr>';status.textContent='Scan failed'}
}
async function publishScannedResource(encoded){
  if(!activeTeacherCode)return;
  const f=JSON.parse(decodeURIComponent(encoded));
  const title=prettyResourceTitle(f.name);
  const category=guessResourceCategory(f.name);
  try{
    await rpc('upsert_nec_resource',{p_teacher_code:activeTeacherCode,p_resource_id:null,p_title:title,p_category:category,p_level:'C1–C2',p_description:'Teacher-provided material for NEC preparation.',p_file_url:f.path,p_is_active:true});
    await refreshTeacherResources();await loadResources();await scanGitHubResources();await refreshTeacherWritingTasks();
  }catch(e){alert('Could not publish resource: '+e.message)}
}

let editingResourceId=null;
function escHtml(v){return String(v??'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]))}
async function loadResources(){const grid=document.getElementById('resourceGrid'),st=document.getElementById('resourceStatus');if(!grid||!st)return;grid.innerHTML='';if(!configured()){st.className='notice';st.innerHTML='<b>Resources:</b> Cloud Setup is required to load the library.';return}try{const rows=await rpc('list_nec_resources',{p_join_code:getCloud().join});if(!rows||!rows.length){st.className='notice';st.innerHTML='<b>Resources:</b> No materials have been published yet.';grid.innerHTML='<div class="resource"><b>Resource Library</b><p class="muted">Teacher-curated materials will appear here.</p></div>';return}st.className='notice oknotice';st.innerHTML='<b>Resources:</b> '+rows.length+' published material'+(rows.length===1?'':'s')+'.';grid.innerHTML=rows.map(r=>{const url=escHtml(r.file_url),title=escHtml(r.title),cat=escHtml(r.category||'Resource'),lvl=escHtml(r.level||''),desc=escHtml(r.description||'Teacher-provided learning material.');return `<div class="resource"><div class="meta">${cat}${lvl?' · '+lvl:''}</div><h3 style="color:var(--navy);margin:8px 0">${title}</h3><p class="muted">${desc}</p><div class="resource-actions"><a href="${url}" target="_blank" rel="noopener">View / Download</a></div></div>`}).join('')}catch(e){st.className='notice badnotice';st.innerHTML='<b>Resources:</b> Could not load library. '+escHtml(e.message)}}
async function refreshTeacherResources(){if(!activeTeacherCode)return;const body=document.getElementById('teacherResourcesBody');if(!body)return;body.innerHTML='<tr><td colspan="6">Loading…</td></tr>';try{const rows=await rpc('teacher_nec_resources',{p_teacher_code:activeTeacherCode});body.innerHTML=(rows||[]).map(r=>`<tr><td>${escHtml(r.title)}</td><td>${escHtml(r.category||'')}</td><td>${escHtml(r.level||'')}</td><td><code>${escHtml(r.file_url)}</code></td><td>${r.is_active?'Published':'Hidden'}</td><td><button class="btn" onclick='editResource(${JSON.stringify(r)})'>Edit</button> <button class="btn" onclick="removeResource(${Number(r.id)})">Delete</button></td></tr>`).join('')||'<tr><td colspan="6">No resources yet.</td></tr>'}catch(e){body.innerHTML='<tr><td colspan="6">Could not load resources: '+escHtml(e.message)+'</td></tr>'}}
function clearResourceForm(){editingResourceId=null;['resTitle','resCategory','resLevel','resUrl','resDescription'].forEach(id=>{const e=document.getElementById(id);if(e)e.value=''})}
function editResource(r){editingResourceId=Number(r.id);resTitle.value=r.title||'';resCategory.value=r.category||'';resLevel.value=r.level||'';resUrl.value=r.file_url||'';resDescription.value=r.description||'';document.getElementById('resourceManager').scrollIntoView({behavior:'smooth'})}
async function publishResource(){if(!activeTeacherCode){alert('Unlock the Teacher Dashboard first.');return}const title=resTitle.value.trim(),url=resUrl.value.trim(),msg=document.getElementById('resourceManagerMessage');msg.className='notice';if(!title||!url){msg.classList.add('badnotice');msg.textContent='Resource title and file path are required.';return}try{await rpc('upsert_nec_resource',{p_teacher_code:activeTeacherCode,p_resource_id:editingResourceId,p_title:title,p_category:resCategory.value.trim(),p_level:resLevel.value.trim(),p_description:resDescription.value.trim(),p_file_url:url,p_is_active:true});msg.classList.add('oknotice');msg.textContent=editingResourceId?'Resource updated successfully.':'Resource published successfully.';clearResourceForm();await refreshTeacherResources();await loadResources()}catch(e){msg.classList.add('badnotice');msg.textContent='Could not publish resource: '+e.message}}
async function removeResource(id){if(!activeTeacherCode||!confirm('Delete this resource from the Resource Library? The file itself will remain on GitHub.'))return;try{await rpc('delete_nec_resource',{p_teacher_code:activeTeacherCode,p_resource_id:Number(id)});await refreshTeacherResources();await loadResources()}catch(e){alert('Could not delete resource: '+e.message)}}



/* ==================== WRITING STUDIO ==================== */
const DEMO_WRITING_TASKS=[
  {id:'demo-data-01',title:'Data Description 01',category:'Data Description',time_limit_minutes:20,word_guidance:'Teacher to specify',difficulty:'NEC',prompt:'Teacher prompt pending. Use Teacher Dashboard → Manage Writing Tasks to paste the exact Data Description task here.',rubric:'Task fulfilment; overview and selection; organisation; vocabulary; grammar and accuracy',is_demo:true},
  {id:'demo-essay-01',title:'Discursive Essay 01',category:'Discursive Essay',time_limit_minutes:40,word_guidance:'Teacher to specify',difficulty:'NEC',prompt:'Teacher prompt pending. Use Teacher Dashboard → Manage Writing Tasks to paste the exact Discursive Essay prompt here.',rubric:'Content and argument; organisation and coherence; lexical resource; grammar and accuracy; style and register',is_demo:true}
];
let writingTasks=[],currentWritingTask=null,writingTimerHandle=null,writingSecondsLeft=0,writingStartedAt=null,writingSubmitted=false,editingWritingTaskId=null;
const WGEM='NEC_GEMINI_API_KEY';
const WRECEIPTS='NEC_WRITING_SUBMISSION_RECEIPTS';
function getWritingReceipts(){try{const a=JSON.parse(localStorage.getItem(WRECEIPTS)||'[]');return Array.isArray(a)?a:[]}catch(e){return []}}
function saveWritingReceipt(r){const a=getWritingReceipts().filter(x=>x.client_submission_id!==r.client_submission_id);a.unshift(r);localStorage.setItem(WRECEIPTS,JSON.stringify(a.slice(0,100)))}
function writingEsc(s){return escHtml(String(s??''))}
function getStudent(){return {name:'Ẩn danh', cls:'Không rõ'}}
async function loadWritingTasks(){const grid=document.getElementById('writingGrid'),st=document.getElementById('writingStatus');if(!grid||!st)return;let rows=[];if(configured()){try{rows=await rpc('list_nec_writing_tasks',{p_join_code:getCloud().join})||[]}catch(e){console.warn('Writing tasks cloud unavailable',e)}}writingTasks=rows.length?rows:DEMO_WRITING_TASKS;st.className='notice '+(rows.length?'oknotice':'');st.innerHTML=rows.length?'<b>✍️ Writing tasks:</b> '+rows.length+' published task'+(rows.length===1?'':'s')+'.':'<b>✍️ Writing preview:</b> Two editable demo slots are shown. Publish your real prompts from Teacher Dashboard.';grid.innerHTML=writingTasks.map(t=>`<div class="writing-card ${t.is_demo?'pending':''}"><div class="wtop"><div class="wicon">${t.category==='Data Description'?'📊':'💬'}</div><span class="badge">${writingEsc(t.category)}</span></div><div class="wmeta">${Number(t.time_limit_minutes)||40} minutes · ${writingEsc(t.difficulty||'NEC')}</div><h3>${writingEsc(t.title)}</h3><p>${writingEsc((t.prompt||'').slice(0,150))}${(t.prompt||'').length>150?'…':''}</p><div class="wstats"><span>⏱ ${Number(t.time_limit_minutes)||40} min</span><span>📝 ${writingEsc(t.word_guidance||'Open word count')}</span><span>↻ Multiple attempts</span></div><button class="btn ${t.category==='Data Description'?'primary':'red'}" onclick='openWritingTask(${JSON.stringify(String(t.id))})'>✍️ Start writing</button></div>`).join('')}
function getStudent(){return {name:(document.getElementById('studentName')?.value||'').trim(),cls:(document.getElementById('studentClass')?.value||'').trim()}}
function findWritingTask(id){return writingTasks.find(t=>String(t.id)===String(id))}
function openWritingTask(id){const st=getStudent();if(!st.name||!st.cls){alert('Please enter and save your full name and class first.');go('tests');return}currentWritingTask=findWritingTask(id);if(!currentWritingTask)return;writingSubmitted=false;document.getElementById('writingModalTitle').textContent='✍️ '+currentWritingTask.title;document.getElementById('writingTaskMeta').textContent=currentWritingTask.category;document.getElementById('writingTaskTitle').textContent=currentWritingTask.title;document.getElementById('writingTaskTime').textContent=(currentWritingTask.time_limit_minutes||40)+' minutes';document.getElementById('writingTaskWords').textContent=currentWritingTask.word_guidance||'Open word count';document.getElementById('writingTaskDifficulty').textContent=currentWritingTask.difficulty||'NEC';document.getElementById('writingTaskPrompt').textContent=currentWritingTask.prompt||'';const wi=document.getElementById('writingTaskImage');if(currentWritingTask.image_url){wi.src=currentWritingTask.image_url;wi.classList.remove('hidden')}else{wi.removeAttribute('src');wi.classList.add('hidden')}document.getElementById('geminiKey').value=localStorage.getItem(WGEM)||'';const saved=localStorage.getItem(writingDraftKey());if(saved){try{const d=JSON.parse(saved);writingPlan.value=d.plan||'';writingResponse.value=d.response||''}catch(e){writingPlan.value='';writingResponse.value=''}}else{writingPlan.value='';writingResponse.value=''}writingInputChanged();document.getElementById('writingSubmitMessage').classList.add('hidden');document.getElementById('aiFeedbackOutput').classList.add('hidden');document.getElementById('aiFeedbackStatus').classList.add('hidden');document.getElementById('aiFeedbackBtn').disabled=true;startWritingTimer();document.getElementById('writingModal').classList.remove('hidden')}
function closeWritingTask(){if(writingTimerHandle)clearInterval(writingTimerHandle);saveWritingDraft();document.getElementById('writingModal').classList.add('hidden')}
function startWritingTimer(){if(writingTimerHandle)clearInterval(writingTimerHandle);writingStartedAt=Date.now();writingSecondsLeft=(Number(currentWritingTask?.time_limit_minutes)||40)*60;renderWritingTimer();writingTimerHandle=setInterval(()=>{writingSecondsLeft--;renderWritingTimer();if(writingSecondsLeft<=0){clearInterval(writingTimerHandle);writingTimerHandle=null;const m=document.getElementById('writingSubmitMessage');m.className='notice badnotice';m.textContent='⏰ Time is up. Finish the sentence you are writing, review quickly, then submit.';m.classList.remove('hidden')}},1000)}
function renderWritingTimer(){const e=document.getElementById('writingTimer');if(!e)return;const v=Math.max(0,writingSecondsLeft),m=Math.floor(v/60),s=v%60;e.textContent=String(m).padStart(2,'0')+':'+String(s).padStart(2,'0');e.classList.toggle('warn',v<=300&&v>60);e.classList.toggle('danger',v<=60)}
function writingInputChanged(){const txt=document.getElementById('writingResponse').value.trim(),wc=txt?txt.split(/\s+/).length:0;document.getElementById('writingWordCount').textContent=wc+' word'+(wc===1?'':'s');saveWritingDraft()}
function saveWritingDraft(show=false){if(!currentWritingTask)return;const d={plan:writingPlan.value,response:writingResponse.value,saved_at:new Date().toISOString()};localStorage.setItem(writingDraftKey(),JSON.stringify(d));document.getElementById('writingSaveState').textContent='Saved '+new Date().toLocaleTimeString([], {hour:'2-digit',minute:'2-digit'});if(show){const m=document.getElementById('writingSubmitMessage');m.className='notice oknotice';m.textContent='Draft saved on this device.';m.classList.remove('hidden')}}
function newWritingAttempt(){if(!currentWritingTask||!confirm('Start a new attempt? Your current draft will be cleared from this device.'))return;localStorage.removeItem(writingDraftKey());writingPlan.value='';writingResponse.value='';writingSubmitted=false;document.getElementById('aiFeedbackBtn').disabled=true;writingInputChanged();startWritingTimer()}
function makeUuid(){return crypto?.randomUUID?crypto.randomUUID():'xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'.replace(/[xy]/g,c=>{const r=Math.random()*16|0,v=c==='x'?r:(r&3|8);return v.toString(16)})}
function makeFeedbackCode(){
  const alphabet='ABCDEFGHJKLMNPQRSTUVWXYZ23456789';
  const bytes=new Uint8Array(8);
  if(window.crypto&&crypto.getRandomValues)crypto.getRandomValues(bytes);else for(let i=0;i<bytes.length;i++)bytes[i]=Math.floor(Math.random()*256);
  let s='';for(let i=0;i<8;i++)s+=alphabet[bytes[i]%alphabet.length];
  return 'NEC-WR-'+s;
}
function normalizeFeedbackCode(v){return String(v||'').trim().toUpperCase().replace(/\s+/g,'')}
function copyFeedbackCode(code){
  if(navigator.clipboard&&window.isSecureContext)navigator.clipboard.writeText(code).then(()=>alert('Feedback Code copied: '+code)).catch(()=>prompt('Copy your Feedback Code:',code));
  else prompt('Copy your Feedback Code:',code);
}
async function submitWritingAttempt(){
  if(!currentWritingTask)return;
  const st=getStudent(),text=writingResponse.value.trim(),msg=document.getElementById('writingSubmitMessage');
  if(currentWritingTask.is_demo){msg.className='notice badnotice';msg.textContent='This is a preview slot. Ask your teacher to publish the real prompt before submitting.';msg.classList.remove('hidden');return}
  const words=text.split(/\s+/).filter(Boolean);
  if(words.length<30){msg.className='notice badnotice';msg.textContent='Your response is too short to submit. Keep writing before you finish the attempt.';msg.classList.remove('hidden');return}
  const elapsed=Math.max(0,Math.round((Date.now()-writingStartedAt)/1000)),wc=words.length,receiptId=makeUuid(),feedbackCode=makeFeedbackCode();
  try{
    if(!configured())throw new Error('Cloud connection is required so your teacher can receive the writing.');
    const result=await rpc('submit_nec_writing_attempt',{p_join_code:getCloud().join,p_task_id:Number(currentWritingTask.id),p_student_name:st.name,p_student_class:st.cls,p_response_text:text,p_word_count:wc,p_elapsed_seconds:elapsed,p_client_submission_id:receiptId,p_feedback_code:feedbackCode});
    saveWritingReceipt({client_submission_id:receiptId,feedback_code:result?.feedback_code||feedbackCode,submission_id:result?.submission_id||null,task_id:Number(currentWritingTask.id),task_title:currentWritingTask.title,category:currentWritingTask.category,student_name:st.name,student_class:st.cls,submitted_at:new Date().toISOString()});
    writingSubmitted=true;if(writingTimerHandle)clearInterval(writingTimerHandle);
    const savedCode=result?.feedback_code||feedbackCode;
    msg.className='notice oknotice';
    msg.innerHTML=`✅ <b>Writing submitted to your teacher.</b><br><br>
      <span class="muted">Your private Feedback Code:</span><br>
      <span style="display:inline-block;margin:7px 0;padding:9px 14px;border:2px dashed var(--blue);border-radius:12px;background:#fff;font-size:1.15rem;font-weight:900;letter-spacing:.08em;color:var(--navy)">${writingEsc(savedCode)}</span>
      <button class="btn secondary" style="padding:7px 10px;margin-left:7px" onclick="copyFeedbackCode('${savedCode}')">Copy code</button><br>
      <span class="muted">Save or screenshot this code. Use it in <b>My Returned Writing</b> to receive your teacher's score and feedback on any device.</span>`;
    msg.classList.remove('hidden');
    document.getElementById('aiFeedbackBtn').disabled=false;saveWritingDraft();
  }catch(e){msg.className='notice badnotice';msg.textContent='Could not submit to the cloud: '+e.message;msg.classList.remove('hidden')}
}
function saveGeminiKey(){const k=document.getElementById('geminiKey').value.trim();if(!k){localStorage.removeItem(WGEM);alert('Gemini API key removed from this browser.');return}localStorage.setItem(WGEM,k);alert('Gemini API key saved on this device only.')}
function openAIKeyHelp(){alert('Gemini API key setup:\n\n1. Open Google AI Studio: https://aistudio.google.com/apikey\n2. Sign in with your Google account.\n3. Create or copy a Gemini API key.\n4. Return to Writing Studio and paste it into the AI Writing Coach box.\n\nNever share your key with classmates or publish it on GitHub.')}
async function requestAIFeedback(){
  if(!writingSubmitted){alert('Submit your writing first.');return}
  const key=(document.getElementById('geminiKey').value.trim()||localStorage.getItem(WGEM)||'');
  if(!key){openAIKeyHelp();return}
  const out=document.getElementById('aiFeedbackOutput'),st=document.getElementById('aiFeedbackStatus');
  st.className='notice';st.textContent='✨ Gemini 3.6 Flash is reviewing your writing…';st.classList.remove('hidden');out.classList.add('hidden');
  const task=currentWritingTask;const response=writingResponse.value.trim();
  const isData=/data description/i.test(task.category||'');
  const rubric=isData
    ? `OFFICIAL PRACTICE RUBRIC — TOTAL 2.0 POINTS
Task Achievement: 0.50 — Accurate overview; select, classify and compare key data; integrate both figures/sources; use projection language correctly.
Coherence & Cohesion: 0.50 — Group information logically; maintain clear progression and cohesive links; avoid mechanical year-by-year listing.
Lexical Resource: 0.50 — Use accurate C1–C2 data-description vocabulary and collocations; avoid repetition.
Grammar Range & Accuracy: 0.50 — Use a varied range of complex structures naturally and maintain near-error-free accuracy.`
    : `OFFICIAL PRACTICE RUBRIC — TOTAL 3.0 POINTS
Task Response: 0.75 — Address all three views; maintain a clear, consistent and nuanced position; support evaluation with specific reasoning/examples.
Coherence & Cohesion: 0.75 — One controlling idea per paragraph; coherent progression; effective referencing and lexical chains; avoid mechanical Firstly/Secondly sequencing.
Lexical Resource: 0.75 — Paraphrase the topic effectively; use precise finance/behaviour lexis and natural C2-level collocations without forced sophistication.
Grammatical Range & Accuracy: 0.75 — Use a wide, controlled range such as inversion, concessive inversion, reduced clauses, clefts and nominalisation where natural; maintain high accuracy.`;
  const total=isData?'2.00':'3.00';
  const per=isData?'0.50':'0.75';
  const prompt=`You are an expert English writing assessor and coach for Vietnamese National Excellent Student (NEC) candidates at C1-C2/C2+ level.

TASK CATEGORY: ${task.category}
TASK TITLE: ${task.title}
TIME LIMIT: ${task.time_limit_minutes} minutes
WORD GUIDANCE: ${task.word_guidance||'Not specified'}
TASK PROMPT:\n${task.prompt}

STUDENT RESPONSE:\n${response}

${rubric}

IMPORTANT SCORING RULES:
- Use ONLY the four criteria above.
- Each criterion is scored from 0 to ${per}.
- Overall score is the exact sum of the four criterion scores, maximum ${total}.
- NEVER convert the score to /10, /9, percentages, IELTS bands, or another scale.
- Give scores to TWO decimal places.
- This is formative practice, not an official NEC grade.

Return feedback in ENGLISH using exactly these sections:
1) SCORE: overall score /${total}, followed by a four-row criterion breakdown with score and concise justification.
2) WHAT WORKED: 3 specific strengths, quoting only short excerpts from the student's writing.
3) PRIORITY FIXES: the 3 most important weaknesses, linked to the rubric.
4) SENTENCE CLINIC: up to 3 short problematic excerpts, an improved version, and the grammar/style rule.
5) VOCABULARY UPGRADE: 5 useful, natural topic-appropriate words/collocations.
6) NEXT ATTEMPT PLAN: exactly 3 concrete actions.
7) ONE-WEEK PRACTICE: a short targeted plan based on this response.
Do not rewrite the entire response. Do not invent facts or data absent from the task materials. For Data Description, verify numerical claims against any supplied task image and penalise inaccurate data reporting under Task Achievement.`;
  try{
    // Latest Interactions API accepts a plain string for text input. This is the most
    // stable browser-side schema and avoids legacy input-part incompatibilities.
    const visualNote=task.image_url?`\n\nTASK VISUAL REFERENCE URL: ${task.image_url}\nIf the numerical information is also present in the task prompt, use the prompt as the source of truth.`:'';
    const r=await fetch('https://generativelanguage.googleapis.com/v1beta/interactions',{
      method:'POST',
      headers:{'Content-Type':'application/json','x-goog-api-key':key},
      body:JSON.stringify({model:'gemini-3.6-flash',input:prompt+visualNote})
    });
    const data=await r.json();
    if(!r.ok)throw new Error(data?.error?.message||('HTTP '+r.status));
    const text=(data.steps||[]).filter(step=>step.type==='model_output').flatMap(step=>step.content||[]).filter(block=>block.type==='text').map(block=>block.text||'').join('\n').trim();
    if(!text)throw new Error('Gemini returned no text.');
    out.textContent=text;out.classList.remove('hidden');st.className='notice oknotice';st.textContent=`AI feedback ready — scored on the ${total}-point task rubric. Treat it as a second opinion and revise critically.`;
  }catch(e){st.className='notice badnotice';st.textContent='AI feedback failed: '+e.message+' Check your API key and internet connection.'}
}

/* Teacher writing manager */
let teacherWritingTasks=[];
async function refreshTeacherWritingTasks(){const body=document.getElementById('teacherWritingTasksBody');if(!body||!activeTeacherCode)return;try{teacherWritingTasks=await rpc('teacher_list_nec_writing_tasks',{p_teacher_code:activeTeacherCode})||[];body.innerHTML=teacherWritingTasks.map(t=>`<tr><td>${writingEsc(t.title)}</td><td>${writingEsc(t.category)}</td><td>${Number(t.time_limit_minutes)||40} min</td><td>${writingEsc(t.difficulty||'')}</td><td>${t.is_active?'Published':'Hidden'}</td><td><button class="btn secondary" style="padding:6px 9px" onclick="editWritingTask(${Number(t.id)})">Edit</button> <button class="btn red" style="padding:6px 9px" onclick="deleteWritingTask(${Number(t.id)})">Delete</button></td></tr>`).join('');if(!teacherWritingTasks.length)body.innerHTML='<tr><td colspan="6">No writing tasks yet.</td></tr>'}catch(e){body.innerHTML='<tr><td colspan="6">Writing manager requires the Writing Studio SQL patch. '+writingEsc(e.message)+'</td></tr>'}}
function clearWritingTaskForm(){editingWritingTaskId=null;wtTitle.value='';wtCategory.value='Data Description';wtTime.value='20';wtDifficulty.value='';wtPrompt.value='';wtImage.value='';wtWords.value='';wtRubric.value=''}
function editWritingTask(id){const t=teacherWritingTasks.find(x=>Number(x.id)===Number(id));if(!t)return;editingWritingTaskId=id;wtTitle.value=t.title||'';wtCategory.value=t.category||'Data Description';wtTime.value=t.time_limit_minutes||40;wtDifficulty.value=t.difficulty||'';wtPrompt.value=t.prompt||'';wtImage.value=t.image_url||'';wtWords.value=t.word_guidance||'';wtRubric.value=t.rubric||'';document.getElementById('writingManager').scrollIntoView({behavior:'smooth'})}
async function saveWritingTask(){if(!activeTeacherCode){alert('Unlock the Teacher Dashboard first.');return}const msg=document.getElementById('writingManagerMessage');if(!wtTitle.value.trim()||!wtPrompt.value.trim()){msg.className='notice badnotice';msg.textContent='Title and task prompt are required.';msg.classList.remove('hidden');return}try{await rpc('upsert_nec_writing_task',{p_teacher_code:activeTeacherCode,p_task_id:editingWritingTaskId,p_title:wtTitle.value.trim(),p_category:wtCategory.value,p_time_limit_minutes:Number(wtTime.value)||40,p_word_guidance:wtWords.value.trim(),p_image_url:wtImage.value.trim(),p_difficulty:wtDifficulty.value.trim(),p_prompt:wtPrompt.value.trim(),p_rubric:wtRubric.value.trim(),p_is_active:true});msg.className='notice oknotice';msg.textContent=editingWritingTaskId?'Writing task updated.':'Writing task published.';msg.classList.remove('hidden');clearWritingTaskForm();await refreshTeacherWritingTasks();await loadWritingTasks()}catch(e){msg.className='notice badnotice';msg.textContent='Could not save writing task: '+e.message;msg.classList.remove('hidden')}}
async function deleteWritingTask(id){if(!activeTeacherCode||!confirm('Delete this writing task? Existing student attempts will remain in the database.'))return;try{await rpc('delete_nec_writing_task',{p_teacher_code:activeTeacherCode,p_task_id:Number(id)});await refreshTeacherWritingTasks();await loadWritingTasks()}catch(e){alert('Could not delete writing task: '+e.message)}}
async function refreshWritingSubmissions(){
  const box=document.getElementById('writingAttemptsBox'),body=document.getElementById('writingAttemptsBody');if(!activeTeacherCode)return;box.classList.remove('hidden');
  try{
    teacherWritingSubmissions=await rpc('teacher_nec_writing_dashboard',{p_teacher_code:activeTeacherCode,p_limit:2000})||[];
    const counts={};teacherWritingSubmissions.forEach(r=>{const k=(r.student_name||'')+'|'+(r.student_class||'')+'|'+r.task_id;counts[k]=(counts[k]||0)+1});
    body.innerHTML=teacherWritingSubmissions.map(r=>{const k=(r.student_name||'')+'|'+(r.student_class||'')+'|'+r.task_id,returned=r.review_status==='returned';return `<tr><td>${writingEsc(r.student_name)}</td><td>${writingEsc(r.student_class||'')}</td><td>${writingEsc(r.task_title)}</td><td>${writingEsc(r.category)}</td><td><code>${writingEsc(r.feedback_code||'—')}</code></td><td>${counts[k]}</td><td>${r.word_count||0}</td><td>${returned?'✅ Returned':'⏳ Submitted'}</td><td>${returned?(Number(r.teacher_score||0).toFixed(2)+' / '+Number(r.teacher_max_score||0).toFixed(2)):'—'}</td><td>${new Date(r.submitted_at).toLocaleString()}</td><td><button class="btn secondary" style="padding:6px 9px" onclick="openWritingReview(${Number(r.submission_id)})">${returned?'Edit review':'Review'}</button></td></tr>`}).join('');
    if(!teacherWritingSubmissions.length)body.innerHTML='<tr><td colspan="11">No writing attempts yet.</td></tr>';
  }catch(e){body.innerHTML='<tr><td colspan="11">Could not load writing attempts: '+writingEsc(e.message)+'</td></tr>'}
}


function renderSingleWritingFeedback(r, fallbackTitle){
  let criteria='';
  const cs=r.teacher_criterion_scores||{};
  if(cs&&typeof cs==='object'&&Object.keys(cs).length){
    criteria='<div style="margin-top:7px">'+Object.entries(cs).map(([k,v])=>`<span class="editor-stat" style="display:inline-block;margin:3px">${writingEsc(k)}: ${Number(v).toFixed(2)}</span>`).join('')+'</div>';
  }
  const returned=r.review_status==='returned';
  return `<div style="margin:10px 0;padding:14px;background:#fff;border:1px solid var(--line);border-radius:13px">
    <div style="display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap"><b>${writingEsc(r.task_title||fallbackTitle||'Writing submission')}</b><code>${writingEsc(r.feedback_code||'')}</code></div>
    <div class="muted">Submitted ${new Date(r.submitted_at).toLocaleString()}</div>
    ${returned?`<div style="margin-top:8px"><span class="badge">✅ Returned by teacher</span> <b style="color:var(--navy)">${Number(r.teacher_score||0).toFixed(2)} / ${Number(r.teacher_max_score||0).toFixed(2)}</b></div>
      ${criteria}
      <div style="white-space:pre-wrap;margin-top:10px;line-height:1.6">${writingEsc(r.teacher_feedback||'No written comment.')}</div>
      <div class="muted" style="margin-top:7px">Reviewed ${r.reviewed_at?new Date(r.reviewed_at).toLocaleString():''}</div>`
      :`<div style="margin-top:8px"><span class="badge">⏳ Awaiting teacher review</span></div>`}
  </div>`;
}

async function checkTeacherWritingFeedbackByCode(){
  const box=document.getElementById('studentWritingFeedbackBox');
  const input=document.getElementById('studentFeedbackCode');
  if(!box||!input)return;
  if(!configured()){box.className='notice badnotice';box.textContent='Cloud connection is required to check teacher feedback.';return}
  const code=normalizeFeedbackCode(input.value);
  if(!/^NEC-WR-[A-Z0-9]{8}$/.test(code)){box.className='notice badnotice';box.textContent='Please enter a valid Feedback Code, for example NEC-WR-7K4P9X2Q.';return}
  input.value=code;box.className='notice';box.textContent='Checking '+code+'…';
  try{
    const rows=await rpc('student_nec_writing_feedback_by_code',{p_join_code:getCloud().join,p_feedback_code:code});
    const r=Array.isArray(rows)?rows[0]:rows;
    if(!r){box.className='notice badnotice';box.textContent='No writing submission was found for this Feedback Code. Check the code and try again.';return}
    box.className='notice oknotice';box.innerHTML=renderSingleWritingFeedback(r);
  }catch(e){box.className='notice badnotice';box.textContent='Could not check feedback: '+e.message}
}

async function checkTeacherWritingFeedback(){
  const box=document.getElementById('studentWritingFeedbackBox');
  if(!box){return}
  if(!configured()){box.className='notice badnotice';box.textContent='Cloud connection is required to check teacher feedback.';return}
  const receipts=getWritingReceipts();
  if(!receipts.length){box.className='notice';box.textContent='No writing submissions from this browser yet.';return}
  box.className='notice';box.textContent='Checking returned feedback…';
  const cards=[];
  for(const rec of receipts.slice(0,30)){
    try{
      const rows=rec.feedback_code
        ? await rpc('student_nec_writing_feedback_by_code',{p_join_code:getCloud().join,p_feedback_code:rec.feedback_code})
        : await rpc('student_nec_writing_feedback',{p_join_code:getCloud().join,p_client_submission_id:rec.client_submission_id});
      const r=Array.isArray(rows)?rows[0]:rows;
      if(!r)continue;
      let criteria='';
      const cs=r.teacher_criterion_scores||{};
      if(cs&&typeof cs==='object'&&Object.keys(cs).length){criteria='<div style="margin-top:7px">'+Object.entries(cs).map(([k,v])=>`<span class="editor-stat" style="display:inline-block;margin:3px">${writingEsc(k)}: ${Number(v).toFixed(2)}</span>`).join('')+'</div>'}
      const returned=r.review_status==='returned';
      cards.push(`<div style="margin:10px 0;padding:14px;background:#fff;border:1px solid var(--line);border-radius:13px"><div style="display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap"><b>${writingEsc(r.task_title||rec.task_title)}</b><code>${writingEsc(r.feedback_code||rec.feedback_code||'')}</code></div><div class="muted">Submitted ${new Date(r.submitted_at).toLocaleString()}</div>${returned?`<div style="margin-top:8px"><span class="badge">✅ Returned</span> <b style="color:var(--navy)">${Number(r.teacher_score||0).toFixed(2)} / ${Number(r.teacher_max_score||0).toFixed(2)}</b></div>${criteria}<div style="white-space:pre-wrap;margin-top:10px;line-height:1.6">${writingEsc(r.teacher_feedback||'No written comment.')}</div><div class="muted" style="margin-top:7px">Reviewed ${r.reviewed_at?new Date(r.reviewed_at).toLocaleString():''}</div>`:`<div style="margin-top:8px"><span class="badge">⏳ Awaiting teacher review</span></div>`}</div>`)
    }catch(e){console.warn('Feedback lookup failed',e)}
  }
  box.className='notice '+(cards.length?'oknotice':'');box.innerHTML=cards.length?cards.join(''):'No matching submissions were found.';
}

let teacherWritingSubmissions=[],currentReviewSubmission=null;
function closeWritingReview(){document.getElementById('writingReviewPanel')?.classList.add('hidden');currentReviewSubmission=null}
function reviewRubricFor(row){
  const data=/data description/i.test(row.category||'');
  return data?{max:2,per:.5,criteria:['Task Achievement','Coherence & Cohesion','Lexical Resource','Grammar Range & Accuracy']}:{max:3,per:.75,criteria:['Task Response','Coherence & Cohesion','Lexical Resource','Grammatical Range & Accuracy']};
}
function openWritingReview(id){
  const r=teacherWritingSubmissions.find(x=>Number(x.submission_id)===Number(id));if(!r)return;currentReviewSubmission=r;
  const rub=reviewRubricFor(r),panel=document.getElementById('writingReviewPanel');panel.classList.remove('hidden');
  document.getElementById('reviewStudentTitle').textContent=`${r.student_name} · ${r.student_class||''}`;
  document.getElementById('reviewTaskTitle').textContent=`${r.task_title} · ${r.category}`;
  document.getElementById('reviewSubmittedAt').textContent=new Date(r.submitted_at).toLocaleString();
  document.getElementById('reviewResponseText').textContent=r.response_text||'';
  const saved=r.teacher_criterion_scores||{};
  document.getElementById('reviewCriteriaBox').innerHTML=rub.criteria.map((c,i)=>`<div><label><b>${writingEsc(c)}</b> <span class="muted">/ ${rub.per.toFixed(2)}</span></label><input class="review-criterion" data-name="${writingEsc(c)}" type="number" min="0" max="${rub.per}" step="0.05" value="${saved[c]!==undefined?Number(saved[c]).toFixed(2):''}" oninput="updateReviewTotal()"></div>`).join('');
  document.getElementById('reviewTeacherFeedback').value=r.teacher_feedback||'';document.getElementById('reviewSaveMessage').classList.add('hidden');updateReviewTotal();panel.scrollIntoView({behavior:'smooth',block:'start'});
}
function updateReviewTotal(){if(!currentReviewSubmission)return;const rub=reviewRubricFor(currentReviewSubmission);let total=0;document.querySelectorAll('.review-criterion').forEach(e=>{let v=Number(e.value)||0;v=Math.max(0,Math.min(rub.per,v));total+=v});document.getElementById('reviewTotalScore').textContent=`${total.toFixed(2)} / ${rub.max.toFixed(2)}`}
async function returnWritingReviewToStudent(){
  if(!activeTeacherCode||!currentReviewSubmission)return;
  const rub=reviewRubricFor(currentReviewSubmission),scores={};let total=0,valid=true;
  document.querySelectorAll('.review-criterion').forEach(e=>{if(e.value==='')valid=false;let v=Number(e.value)||0;if(v<0||v>rub.per)valid=false;scores[e.dataset.name]=v;total+=v});
  const msg=document.getElementById('reviewSaveMessage');msg.classList.remove('hidden');
  if(!valid){msg.className='notice badnotice';msg.textContent=`Enter every criterion score between 0 and ${rub.per.toFixed(2)}.`;return}
  try{await rpc('teacher_review_nec_writing_submission',{p_teacher_code:activeTeacherCode,p_submission_id:Number(currentReviewSubmission.submission_id),p_teacher_score:Number(total.toFixed(2)),p_teacher_max_score:rub.max,p_criterion_scores:scores,p_teacher_feedback:document.getElementById('reviewTeacherFeedback').value.trim()});msg.className='notice oknotice';msg.textContent='✅ Score and feedback returned to the student.';await refreshWritingSubmissions()}catch(e){msg.className='notice badnotice';msg.textContent='Could not return review: '+e.message}
}

renderTests();loadStudent();checkCloud();loadResources();loadWritingTasks();if(!configured())setTimeout(openCloudSetup,500);
</script></body></html>
