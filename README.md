<!doctype html><html lang="en"><head><meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>Road to NEC 2026 · English Excellence Portal (Anonymous)</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Poppins:wght@600;700;800&display=swap" rel="stylesheet">
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
h1,h2,h3,.brand,.btn{font-family:'Poppins','Segoe UI',Arial,sans-serif}
button,input,select{font:inherit}
a{color:var(--blue)}
.wrap{max-width:1180px;margin:auto}
.hidden{display:none!important}
.muted{color:var(--slate)}
code{background:#edf3fc;padding:2px 6px;border-radius:6px;color:#29466f}

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
.btn{
  border:0;border-radius:12px;padding:11px 16px;font-weight:800;cursor:pointer;transition:.15s ease;
}
.btn:hover{transform:translateY(-2px)}
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
.testcard,.resource,.skill{
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

/* NOTICE */
.notice{padding:12px 14px;background:#fff8df;border:1px solid #f4df96;border-left:4px solid var(--gold);border-radius:11px;margin:12px 0;color:#53627c}
.oknotice{background:#e9fbf3;border-color:#bcebd8;border-left-color:var(--green)}
.badnotice{background:#fff0f2;border-color:#f5c4cb;border-left-color:var(--red);color:#7a3039}

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
.resource-actions a{display:inline-flex;align-items:center;gap:6px;border:0;border-radius:10px;padding:9px 12px;font-weight:800;cursor:pointer;text-decoration:none;background:linear-gradient(135deg,var(--blue),var(--blue2));color:#fff!important}
.resource b{color:var(--navy);font-size:1.04rem}
.resource p{color:var(--slate)}

/* FOOTER */
.footer{background:#061943;color:#cbd9f5;padding:34px 20px;text-align:left}
.footer .wrap{display:flex;gap:28px;justify-content:space-between;align-items:center}
.footer .foot-brand{color:#fff;font-weight:800}.footer .foot-quote{max-width:600px;font-style:italic;color:#e8efff}

/* WRITING STUDIO */
.writing-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;margin-top:18px}
.writing-card{background:#fff;border:1px solid var(--line);border-radius:20px;padding:20px;box-shadow:var(--shadow2);position:relative;overflow:hidden}
.writing-card .wtop{display:flex;justify-content:space-between;gap:10px;align-items:flex-start}
.writing-card .wicon{width:48px;height:48px;border-radius:14px;display:grid;place-items:center;font-size:1.45rem;background:var(--soft)}
.writing-card .wmeta{font-size:.76rem;font-weight:800;color:var(--blue);text-transform:uppercase;letter-spacing:.06em}
.writing-card h3{color:var(--navy);margin:10px 0 5px}.writing-card p{color:var(--slate);font-size:.92rem}
.writing-card .wstats{display:flex;flex-wrap:wrap;gap:7px;margin:12px 0}
.writing-card .wstats span{background:#f2f6fc;border:1px solid var(--line);padding:5px 9px;border-radius:999px;font-size:.75rem;font-weight:700;color:var(--slate)}
.writing-intro{display:grid;grid-template-columns:1.4fr .8fr;gap:18px;align-items:stretch}
.ai-card{background:linear-gradient(145deg,#0b2f76,#174da9);color:#fff;border-radius:20px;padding:20px;box-shadow:var(--shadow)}
.ai-card h3{margin:0 0 6px}.ai-card p{color:#dbe8ff;font-size:.9rem}
.writing-modal{width:min(1120px,100%);max-height:94vh}
.writing-layout{display:grid;grid-template-columns:.92fr 1.18fr;gap:18px}
.writing-prompt{background:#f5f8ff;border:1px solid var(--line);border-radius:16px;padding:18px;position:sticky;top:0;align-self:start}
.writing-prompt h3{color:var(--navy);margin-top:0}
.prompt-text{white-space:pre-wrap;font-size:.96rem;line-height:1.65}
.writing-workspace textarea{width:100%;resize:vertical;min-height:110px}
.writing-workspace #writingResponse{min-height:390px;line-height:1.65;font-size:1rem}
.editor-tools{display:flex;gap:8px;flex-wrap:wrap;align-items:center;margin:8px 0}
.editor-stat{background:#eef4ff;border:1px solid var(--line);border-radius:10px;padding:7px 10px;font-weight:800;color:var(--navy);font-size:.82rem}
.timer-chip{background:#fff0f1;color:#b61d32}
.ai-panel{margin-top:18px;background:#f8fbff;border:1px solid #dce7f6;border-radius:16px;padding:16px}
.ai-output{white-space:pre-wrap;background:#fff;border:1px solid var(--line);border-radius:12px;padding:15px;line-height:1.55;max-height:420px;overflow:auto}
.ai-key-row{display:grid;grid-template-columns:1fr auto;gap:9px}
.ai-disclaimer{font-size:.78rem;color:var(--slate);margin-top:7px}

/* MODAL */
.modal-backdrop{position:fixed;inset:0;background:rgba(4,18,50,.72);z-index:100;display:flex;align-items:center;justify-content:center;padding:18px;backdrop-filter:blur(5px)}
.setup-modal{background:#fff;width:min(740px,100%);max-height:91vh;overflow:auto;border-radius:22px;padding:24px;box-shadow:0 26px 70px rgba(0,0,0,.32)}
.setup-modal h2{margin-top:0;color:var(--navy)}
.setup-close{float:right;border:0;background:#edf3fb;border-radius:10px;padding:8px 11px;font-weight:800;cursor:pointer}

@media(max-width:900px){
  .hero .wrap{grid-template-columns:1fr}.hero-card{max-width:620px}
  .skills{grid-template-columns:1fr}.navlinks button{display:none}
}
@media(max-width:650px){
  .site-nav .wrap{padding:0 14px}.brand span{display:none}
  .hero .wrap{padding:48px 18px 58px}.hero h1{font-size:2.65rem}.hero-card{padding:17px}
  .section{padding:42px 16px}.section-head{display:block}
  .actions{grid-template-columns:1fr}
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
    </div>
  </div>
  <div class="nav-flag"><i></i><i></i><i></i><i></i><i></i></div>
</div>

<header class="hero">
  <div class="wrap">
    <div>
      <div class="hero-kicker">🇺🇸 🇬🇧 National English Competition · 2026</div>
      <h1>Train smart.<br><span class="gold">Think bigger.</span><br>Go further.</h1>
      <p>One focused hub for National Excellent Student English preparation — full mock tests, targeted skill practice, and curated resources.</p>
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

<section class="section" id="tests">
  <div class="wrap">
    <div class="section-head">
      <div><div class="eyebrow">Practice Zone</div><h2>Choose your next challenge</h2>
      <p class="lead">Take a complete paper under test conditions, or train one skill at a time safely in offline mode.</p></div>
    </div>
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
    <p class="lead">Build exam-ready writing through timed practice, drafts, and optional AI feedback using your own key.</p></div></div>
    <div class="writing-intro">
      <div class="quote-band" style="margin:0;background:linear-gradient(125deg,#123a9c,#0a2472)"><div class="quote-mark">“</div><div><div class="q">Good writing is rewriting. Strong ideas become stronger through deliberate revision.</div><div class="a">— Writing Studio principle</div></div></div>
      <div class="ai-card"><h3>✨ AI Writing Coach</h3><p>Add your own Gemini API key to receive an indicative score, targeted feedback, corrected examples and a next-step practice plan.</p><button class="btn gold" onclick="openAIKeyHelp()">🔑 Set up Gemini API key</button></div>
    </div>
    <div class="writing-grid" id="writingGrid"></div>
  </div>
</section>

<section class="section" id="library">
  <div class="wrap">
    <div class="section-head"><div><div class="eyebrow">Resource Library</div><h2>Build the knowledge behind the score</h2>
    <p class="lead">Curated materials for NEC preparation.</p></div></div>
    <div class="grid" id="resourceGrid">
      <div class="resource"><div class="meta">Reference</div><h3>NEC Strategy Guide</h3><p class="muted">General tips for approaching advanced English exams.</p></div>
    </div>
  </div>
</section>

<section class="section alt" id="authentic">
  <div class="wrap">
    <div class="section-head"><div><div class="eyebrow">English in the Wild</div><h2>Read authentic English every day</h2>
    <p class="lead">High-level exam performance grows from wide reading. Explore serious journalism, science, culture and ideas from trusted US & UK sources.</p></div></div>
    <div class="grid">
      <div class="resource"><div class="meta">🇬🇧 UK · News</div><b>BBC</b><p class="muted">Current affairs, science, culture and international reporting.</p><div class="resource-actions"><a target="_blank" rel="noopener" href="https://www.bbc.com/news">Open BBC ↗</a></div></div>
      <div class="resource"><div class="meta">🇺🇸 USA · Audio + News</div><b>NPR</b><p class="muted">News, analysis, science, culture and audio journalism.</p><div class="resource-actions"><a target="_blank" rel="noopener" href="https://www.npr.org/">Open NPR ↗</a></div></div>
      <div class="resource"><div class="meta">🇺🇸 USA · Journalism</div><b>The New York Times</b><p class="muted">Long-form reporting, opinion and international coverage.</p><div class="resource-actions"><a target="_blank" rel="noopener" href="https://www.nytimes.com/international/">Open NYT ↗</a></div></div>
    </div>
  </div>
</section>

<div id="writingModal" class="modal-backdrop hidden" role="dialog" aria-modal="true">
  <div class="setup-modal writing-modal">
    <button class="setup-close" onclick="closeWritingTask()">✕ Close</button>
    <h2 id="writingModalTitle">✍️ Writing Studio</h2>
    <div class="writing-layout">
      <aside class="writing-prompt">
        <div id="writingTaskMeta" class="eyebrow">Writing Task</div>
        <h3 id="writingTaskTitle">Task</h3>
        <div class="wstats" style="display:flex;gap:7px;flex-wrap:wrap;margin-bottom:12px">
          <span class="editor-stat" id="writingTaskTime">20 minutes</span>
          <span class="editor-stat" id="writingTaskWords">Word guidance</span>
          <span class="editor-stat" id="writingTaskDifficulty">NEC</span>
        </div>
        <div class="prompt-text" id="writingTaskPrompt"></div>
      </aside>
      <div class="writing-workspace">
        <label><b>🧠 Planning notes</b> <span class="muted">(private draft notes)</span></label>
        <textarea id="writingPlan" placeholder="Thesis / overview / main arguments…"></textarea>
        <div class="editor-tools">
          <span class="editor-stat" id="writingWordCount">0 words</span>
          <span class="editor-stat timer-chip" id="writingTimer">20:00</span>
          <span class="editor-stat">Draft ready</span>
        </div>
        <label><b>📝 Response</b></label>
        <textarea id="writingResponse" placeholder="Write your response here…" oninput="writingInputChanged()"></textarea>
        <div class="ai-panel">
          <h3 style="color:var(--navy);margin-top:0">✨ AI Writing Coach</h3>
          <div class="ai-key-row">
            <input id="geminiKey" type="password" placeholder="Paste your Gemini API key">
            <button class="btn secondary" onclick="saveGeminiKey()">Save key</button>
          </div>
          <div class="ai-disclaimer">Your API key is stored only in this browser and sent directly to Google Gemini.</div>
          <div class="setup-actions" style="margin-top:10px">
            <button class="btn gold" onclick="requestAIFeedback()">✨ Get AI score & feedback</button>
          </div>
          <div id="aiFeedbackStatus" class="notice hidden" style="margin-top:10px"></div>
          <div id="aiFeedbackOutput" class="ai-output hidden" style="margin-top:10px"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="footer">
  <div class="wrap">
    <div>
      <div class="foot-brand">🇺🇸 🇬🇧 Road to NEC 2026 · English Excellence</div>
      <div class="muted" style="color:#9fb4d8;margin-top:4px">Built for focused, anonymous learners.</div>
    </div>
    <div class="foot-quote">“Don’t watch the clock; do what it does. Keep going.” — Sam Levenson</div>
  </div>
</div>

<script>
// Khôi phục đầy đủ danh sách test (từ 1 đến 20)
const TESTS = [
  {id:1, name:'Homework 6.8', file:'Test_01_Homework_6.8.html', status:'Available'},
  {id:2, name:'Homework 7.8', file:'Test_02_Homework_7.8.html', status:'Available'},
  {id:3, name:'Homework 13.8', file:'Test_03_Homework_13.8.html', status:'Available'},
  {id:4, name:'Homework 20.8', file:'Test_04_Homework_20.8.html', status:'Available'},
  {id:5, name:'Homework 24.8', file:'Test_05_Homework_24.8.html', status:'Available'},
  {id:6, name:'Homework 27.8', file:'Test_06_Homework_27.8.html', status:'Available'},
  ...Array.from({length:14}, (_,i) => ({id:i+7, name:'Practice Test '+(i+7), status:'Coming soon'}))
];

function go(id){ document.getElementById(id).scrollIntoView({behavior:'smooth'}) }
function esc(s){ return String(s??'').replace(/[&<>"']/g,m=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[m])) }

function renderTests(){
  const grid = document.getElementById('testGrid');
  if(!grid) return;
  grid.innerHTML = TESTS.map(t => {
    const live = !!t.file;
    return `<div class="testcard">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;gap:10px">
        <span class="badge ${t.status!=='Available'?'soon':''}">${t.status}</span>
        <span>${live?'🎯':'🔒'}</span>
      </div>
      <h3>Test ${String(t.id).padStart(2,'0')} · ${esc(t.name)}</h3>
      <p class="muted" style="font-size:.9rem">🎧 Listening &nbsp;·&nbsp; 🔤 Grammar &nbsp;·&nbsp; 📖 Reading</p>
      <div class="actions">
        <button ${live?'':'disabled'} onclick="openTest(${t.id},'Full Test')">🎯 Full Test</button>
        <button ${live?'':'disabled'} onclick="openTest(${t.id},'Listening')">🎧 Listening</button>
        <button ${live?'':'disabled'} onclick="openTest(${t.id},'Language in Use')">🔤 Grammar</button>
        <button ${live?'':'disabled'} onclick="openTest(${t.id},'Reading')">📖 Reading</button>
      </div>
    </div>`;
  }).join('');
}

function openTest(id, mode){
  let t = TESTS.find(x => x.id === id);
  if(!t || !t.file) return;
  // Gán sẵn thông tin ẩn danh tránh lỗi yêu cầu nhập tên
  let q = new URLSearchParams({practice: mode, student: 'Anonymous', class: 'Offline', join: 'NONE', timer: '60'});
  window.open(t.file + '?' + q.toString(), '_blank');
}

function skillMenu(skill){
  let avail = TESTS.filter(t => t.file);
  let n = prompt('Enter test number for ' + skill + ' practice (' + avail.map(x=>x.id).join(', ') + '):');
  let id = Number(n);
  if(avail.some(x => x.id === id)) openTest(id, skill);
  else if(n !== null) alert('Test not available.');
}

const DEMO_WRITING_TASKS = [
  {id:'demo-data-01', title:'Data Description 01', category:'Data Description', time_limit_minutes:20, word_guidance:'150+ words', difficulty:'NEC', prompt:'Analyze the chart trends provided in your study materials.'},
  {id:'demo-essay-01', title:'Discursive Essay 01', category:'Discursive Essay', time_limit_minutes:40, word_guidance:'350+ words', difficulty:'NEC', prompt:'Discuss the impacts of algorithm-based learning schedules on modern education.'}
];

function loadWritingTasks(){
  const grid = document.getElementById('writingGrid');
  if(!grid) return;
  grid.innerHTML = DEMO_WRITING_TASKS.map(t => `
    <div class="writing-card">
      <div class="wtop"><div class="wicon">📊</div><span class="badge">${esc(t.category)}</span></div>
      <div class="wmeta">${t.time_limit_minutes} minutes · ${esc(t.difficulty)}</div>
      <h3>${esc(t.title)}</h3>
      <p>${esc(t.prompt)}</p>
      <button class="btn primary" style="margin-top:12px" onclick="openWritingTask('${t.id}')">✍️ Start writing</button>
    </div>`).join('');
}

function openWritingTask(id){
  let t = DEMO_WRITING_TASKS.find(x => x.id === id);
  if(!t) return;
  document.getElementById('writingModalTitle').textContent = '✍️ ' + t.title;
  document.getElementById('writingTaskMeta').textContent = t.category;
  document.getElementById('writingTaskTitle').textContent = t.title;
  document.getElementById('writingTaskTime').textContent = t.time_limit_minutes + ' minutes';
  document.getElementById('writingTaskWords').textContent = t.word_guidance;
  document.getElementById('writingTaskPrompt').textContent = t.prompt;
  document.getElementById('writingModal').classList.remove('hidden');
}

function closeWritingTask(){ document.getElementById('writingModal').classList.add('hidden'); }
function writingInputChanged(){
  let txt = document.getElementById('writingResponse').value.trim();
  let wc = txt ? txt.split(/\s+/).length : 0;
  document.getElementById('writingWordCount').textContent = wc + ' words';
}

function saveGeminiKey(){
  let k = document.getElementById('geminiKey').value.trim();
  if(k){ localStorage.setItem('NEC_GEMINI_API_KEY', k); alert('API Key saved locally.'); }
}

function openAIKeyHelp(){
  alert('Gemini API key setup:\n\n1. Open Google AI Studio: https://aistudio.google.com/apikey\n2. Create or copy a Gemini API key.\n3. Paste it into the AI Writing Coach box.');
}

async function requestAIFeedback(){
  let key = document.getElementById('geminiKey').value.trim() || localStorage.getItem('NEC_GEMINI_API_KEY');
  if(!key){ openAIKeyHelp(); return; }
  let response = document.getElementById('writingResponse').value.trim();
  if(!response){ alert('Please write something first.'); return; }
  
  let out = document.getElementById('aiFeedbackOutput'), st = document.getElementById('aiFeedbackStatus');
  st.className = 'notice'; st.textContent = '✨ Gemini is reviewing your text...'; st.classList.remove('hidden');
  
  try{
    let r = await fetch('https://generativelanguage.googleapis.com/v1beta/interactions',{
      method: 'POST',
      headers: {'Content-Type': 'application/json', 'x-goog-api-key': key},
      body: JSON.stringify({model: 'gemini-3.6-flash', input: 'Review this text for an advanced English exam and give constructive feedback:\n\n' + response})
    });
    let data = await r.json();
    if(!r.ok) throw new Error(data?.error?.message || 'API Error');
    let text = (data.steps || []).filter(s => s.type === 'model_output').flatMap(s => s.content || []).map(b => b.text || '').join('\n');
    out.textContent = text || 'No response generated.';
    out.classList.remove('hidden');
    st.className = 'notice oknotice'; st.textContent = 'Review complete.';
  }catch(e){
    st.className = 'notice badnotice'; st.textContent = 'Error: ' + e.message;
  }
}

renderTests();
loadWritingTasks();
</script></body></html>
