[pm_meston chevalier_candidature_symrise.html](https://github.com/user-attachments/files/28103363/pm_meston.chevalier_candidature_symrise.html)

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Pierre-Marie Meston — Global Creative Design Lead</title>
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;1,300;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --navy:#0D1F3C;
  --navy-mid:#1A3560;
  --navy-light:#2E5090;
  --navy-pale:#E8EDF5;
  --navy-ultra:#F2F5FA;
  --ink:#111827;
  --ink-mid:#374151;
  --ink-soft:#6B7280;
  --white:#FFFFFF;
  --rule:#D1D9E8;
  --serif:'Cormorant Garamond',Georgia,serif;
  --sans:'DM Sans',system-ui,sans-serif;
}
html{scroll-behavior:smooth;font-size:16px}
body{font-family:var(--sans);background:var(--white);color:var(--ink);line-height:1.6;-webkit-font-smoothing:antialiased}

nav{
  position:fixed;top:0;left:0;right:0;z-index:100;
  display:flex;align-items:center;justify-content:space-between;
  padding:1.25rem 3rem;
  background:rgba(255,255,255,0.88);
  backdrop-filter:blur(16px);
  border-bottom:0.5px solid var(--rule);
}
.nav-logo{font-family:var(--serif);font-size:1.1rem;font-weight:400;letter-spacing:0.04em;color:var(--navy)}
.nav-links{display:flex;gap:2rem}
.nav-links a{font-size:0.78rem;letter-spacing:0.08em;text-transform:uppercase;color:var(--ink-soft);text-decoration:none;transition:color .2s}
.nav-links a:hover{color:var(--navy)}

section{padding:6rem 3rem}
.container{max-width:860px;margin:0 auto}
.container-wide{max-width:1040px;margin:0 auto}

.hero{
  padding-top:10rem;padding-bottom:8rem;
  background:var(--white);
}
.hero-tag{
  display:inline-block;
  font-size:0.72rem;letter-spacing:0.14em;text-transform:uppercase;
  color:var(--navy-light);border:0.5px solid var(--navy-light);
  padding:0.4rem 1rem;border-radius:2rem;margin-bottom:2.5rem;
}
.hero-name{
  font-family:var(--serif);font-size:clamp(2.8rem,6vw,4.5rem);
  font-weight:300;line-height:1.08;color:var(--ink);letter-spacing:-0.01em;
  margin-bottom:1.5rem;
}
.hero-name em{font-style:italic;color:var(--navy)}
.hero-line{
  width:40px;height:1px;background:var(--navy);margin:2rem 0;
}
.hero-tagline{
  font-family:var(--serif);font-size:1.35rem;font-weight:300;font-style:italic;
  color:var(--ink-mid);max-width:520px;line-height:1.5;margin-bottom:2.5rem;
}
.hero-sub{
  font-size:0.9rem;color:var(--ink-soft);max-width:420px;line-height:1.8;
  margin-bottom:3rem;
}
.btn-primary{
  display:inline-flex;align-items:center;gap:0.5rem;
  background:var(--navy);color:var(--white);
  font-size:0.8rem;letter-spacing:0.06em;text-transform:uppercase;
  padding:0.9rem 2rem;text-decoration:none;border-radius:2rem;
  transition:background .2s,transform .15s;
}
.btn-primary:hover{background:var(--navy-mid);transform:translateY(-1px)}
.btn-ghost{
  display:inline-flex;align-items:center;gap:0.5rem;
  color:var(--navy);border:0.5px solid var(--navy);
  font-size:0.8rem;letter-spacing:0.06em;text-transform:uppercase;
  padding:0.9rem 2rem;text-decoration:none;border-radius:2rem;margin-left:1rem;
  transition:background .2s;
}
.btn-ghost:hover{background:var(--navy-ultra)}

.section-label{
  font-size:0.7rem;letter-spacing:0.14em;text-transform:uppercase;
  color:var(--navy-light);margin-bottom:1rem;
}
.section-title{
  font-family:var(--serif);font-size:clamp(2rem,4vw,3rem);
  font-weight:300;line-height:1.12;color:var(--ink);margin-bottom:1.5rem;
}
.section-title em{font-style:italic;color:var(--navy)}
.divider{width:32px;height:1px;background:var(--navy);margin:0 0 2.5rem}

.bg-soft{background:var(--navy-ultra)}
.bg-navy{background:var(--navy)}

.why-grid{display:grid;grid-template-columns:1fr 1fr;gap:0;border:0.5px solid var(--rule);border-radius:12px;overflow:hidden;margin-top:3rem}
.why-item{padding:2.5rem;border-right:0.5px solid var(--rule);border-bottom:0.5px solid var(--rule)}
.why-item:nth-child(2n){border-right:none}
.why-item:nth-last-child(-n+2){border-bottom:none}
.why-num{font-family:var(--serif);font-size:2rem;font-weight:300;color:var(--navy-pale);line-height:1;margin-bottom:1rem}
.why-title{font-size:0.9rem;font-weight:500;color:var(--ink);margin-bottom:0.5rem;letter-spacing:0.02em}
.why-text{font-size:0.85rem;color:var(--ink-soft);line-height:1.7}

.brings-list{display:flex;flex-direction:column;gap:1px;background:var(--rule);border-radius:8px;overflow:hidden;margin-top:3rem}
.brings-item{
  display:flex;align-items:flex-start;gap:1.5rem;
  background:var(--white);padding:1.75rem 2rem;
  transition:background .15s;
}
.brings-item:hover{background:var(--navy-ultra)}
.brings-dot{width:6px;height:6px;border-radius:50%;background:var(--navy);flex-shrink:0;margin-top:0.5rem}
.brings-body{}
.brings-title{font-size:0.9rem;font-weight:500;color:var(--ink);margin-bottom:0.25rem}
.brings-text{font-size:0.85rem;color:var(--ink-soft);line-height:1.7}

.projects-grid{display:flex;flex-direction:column;gap:2px;background:var(--rule);border-radius:12px;overflow:hidden;margin-top:3rem}
.project-card{background:var(--white);padding:2.5rem 2.5rem;display:grid;grid-template-columns:1fr auto;gap:2rem;align-items:start;transition:background .15s;cursor:default}
.project-card:hover{background:var(--navy-ultra)}
.project-tag{font-size:0.68rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--navy-light);margin-bottom:0.75rem}
.project-title{font-family:var(--serif);font-size:1.5rem;font-weight:400;color:var(--ink);margin-bottom:0.75rem;line-height:1.2}
.project-desc{font-size:0.85rem;color:var(--ink-soft);line-height:1.75;max-width:560px}
.project-outcome{
  font-size:0.78rem;letter-spacing:0.04em;color:var(--navy);
  border-left:2px solid var(--navy-light);padding-left:0.75rem;margin-top:1.25rem;
  font-style:italic;
}
.project-year{font-family:var(--serif);font-size:2.5rem;font-weight:300;color:var(--rule);align-self:center}

.philosophy-block{
  border-left:1px solid var(--navy);padding:2.5rem 3rem;
  margin:3rem 0;background:var(--navy-ultra);border-radius:0 8px 8px 0;
}
.philosophy-quote{
  font-family:var(--serif);font-size:1.6rem;font-weight:300;font-style:italic;
  color:var(--ink);line-height:1.4;margin-bottom:1.5rem;
}
.philosophy-text{font-size:0.88rem;color:var(--ink-soft);line-height:1.8;max-width:560px}

.exp-list{display:flex;flex-direction:column;gap:0;margin-top:3rem}
.exp-item{display:grid;grid-template-columns:140px 1fr;gap:2rem;padding:2rem 0;border-bottom:0.5px solid var(--rule)}
.exp-item:last-child{border-bottom:none}
.exp-date{font-size:0.78rem;color:var(--ink-soft);padding-top:0.2rem;letter-spacing:0.02em}
.exp-role{font-size:0.95rem;font-weight:500;color:var(--ink);margin-bottom:0.2rem}
.exp-company{font-size:0.82rem;color:var(--navy);margin-bottom:0.6rem;font-style:italic}
.exp-desc{font-size:0.82rem;color:var(--ink-soft);line-height:1.7}

.letter-section{background:var(--navy)}
.letter-inner{max-width:680px;margin:0 auto;padding:4rem 3rem}
.letter-label{font-size:0.7rem;letter-spacing:0.14em;text-transform:uppercase;color:rgba(255,255,255,0.4);margin-bottom:2rem}
.letter-text{font-family:var(--serif);font-size:1.15rem;font-weight:300;color:rgba(255,255,255,0.9);line-height:1.85;margin-bottom:1.5rem}
.letter-sig{font-family:var(--serif);font-size:1.4rem;font-style:italic;color:rgba(255,255,255,0.6);margin-top:2rem}

.footer{padding:3rem;text-align:center;border-top:0.5px solid var(--rule)}
.footer-name{font-family:var(--serif);font-size:1.5rem;font-weight:300;color:var(--ink);margin-bottom:0.5rem}
.footer-links{display:flex;justify-content:center;gap:2rem;margin-top:1.5rem}
.footer-links a{font-size:0.78rem;letter-spacing:0.06em;text-transform:uppercase;color:var(--ink-soft);text-decoration:none}
.footer-links a:hover{color:var(--navy)}

.fade-in{opacity:0;transform:translateY(18px);transition:opacity .7s ease,transform .7s ease}
.fade-in.visible{opacity:1;transform:none}

@media(max-width:700px){
  nav{padding:1rem 1.5rem}
  section{padding:4rem 1.5rem}
  .hero{padding-top:8rem;padding-bottom:5rem}
  .why-grid{grid-template-columns:1fr}
  .why-item{border-right:none}
  .project-card{grid-template-columns:1fr}
  .project-year{display:none}
  .exp-item{grid-template-columns:1fr;gap:0.5rem}
  .nav-links{gap:1rem}
  .nav-links a{font-size:0.7rem}
}
</style>
</head>
<body>

<nav>
  <span class="nav-logo">PM Meston</span>
  <div class="nav-links">
    <a href="#why">Why this role</a>
    <a href="#projects">Projects</a>
    <a href="#philosophy">Philosophy</a>
    <a href="#experience">Experience</a>
    <a href="#letter">Letter</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="container">
    <div class="hero-tag fade-in">Candidate · Global Creative Design Lead</div>
    <h1 class="hero-name fade-in">Pierre-Marie<br /><em>Meston.</em></h1>
    <div class="hero-line fade-in"></div>
    <p class="hero-tagline fade-in">"Making complex corporate stories clear, coherent and emotionally resonant."</p>
    <p class="hero-sub fade-in">Internal Communications & Creative Design — Symrise · Rennes<br/>Committed to elevating the visual and narrative quality of global corporate communication.</p>
    <div class="fade-in">
      <a class="btn-primary" href="#why">Explore my candidacy</a>
      <a class="btn-ghost" href="https://www.linkedin.com/in/pm-meston" target="_blank">LinkedIn →</a>
    </div>
  </div>
</section>

<!-- WHY THIS ROLE -->
<section id="why" class="bg-soft">
  <div class="container">
    <p class="section-label fade-in">Why this role</p>
    <h2 class="section-title fade-in">A natural next<br /><em>step forward.</em></h2>
    <div class="divider fade-in"></div>
    <p class="fade-in" style="font-size:.93rem;color:var(--ink-mid);max-width:540px;line-height:1.85;margin-bottom:0">
      After several years building communication tools, visual systems and editorial frameworks inside Symrise, I am ready to take the creative lead at a global scale. This role is not a leap — it is the role I have been building toward.
    </p>
    <div class="why-grid fade-in">
      <div class="why-item">
        <div class="why-num">01</div>
        <div class="why-title">Deep company knowledge</div>
        <div class="why-text">I understand Symrise's brand, culture, strategic priorities and communication ecosystem from the inside. No ramp-up time needed — I am already fluent.</div>
      </div>
      <div class="why-item">
        <div class="why-num">02</div>
        <div class="why-title">Proven creative output</div>
        <div class="why-text">I have delivered premium visual systems, structured content platforms and brand-aligned materials that meet the expectations of a global corporation.</div>
      </div>
      <div class="why-item">
        <div class="why-num">03</div>
        <div class="why-title">Cross-functional mindset</div>
        <div class="why-text">I work fluently across branding, digital, UX, editorial and internal communications — bridging disciplines rather than operating within a single one.</div>
      </div>
      <div class="why-item">
        <div class="why-num">04</div>
        <div class="why-title">Global creative ambition</div>
        <div class="why-text">My standard is set by the best — Apple, Braun, Dieter Rams — and I bring that level of intention and precision to every project I lead.</div>
      </div>
    </div>
  </div>
</section>

<!-- WHAT I BRING -->
<section id="brings">
  <div class="container">
    <p class="section-label fade-in">What I bring</p>
    <h2 class="section-title fade-in">Seven capabilities,<br /><em>one coherent vision.</em></h2>
    <div class="divider fade-in"></div>
    <div class="brings-list fade-in">
      <div class="brings-item">
        <div class="brings-dot"></div>
        <div class="brings-body">
          <div class="brings-title">Visual Systems Architecture</div>
          <div class="brings-text">Building coherent graphic systems — templates, guidelines, design tokens — that scale across formats, languages and audiences without losing identity.</div>
        </div>
      </div>
      <div class="brings-item">
        <div class="brings-dot"></div>
        <div class="brings-body">
          <div class="brings-title">Content & Platform Structuring</div>
          <div class="brings-text">Organising information architectures — intranets, DAM platforms, media libraries — so that content becomes an asset, not a liability.</div>
        </div>
      </div>
      <div class="brings-item">
        <div class="brings-dot"></div>
        <div class="brings-body">
          <div class="brings-title">Corporate Storytelling & Editorial Direction</div>
          <div class="brings-text">Translating strategy, data and complexity into clear, compelling narratives — presentations, infographics, reports — designed to land with any audience.</div>
        </div>
      </div>
      <div class="brings-item">
        <div class="brings-dot"></div>
        <div class="brings-body">
          <div class="brings-title">Brand Consistency & Creative Standards</div>
          <div class="brings-text">Acting as a guardian of visual excellence: raising the bar on every output while making quality accessible and reproducible at scale.</div>
        </div>
      </div>
      <div class="brings-item">
        <div class="brings-dot"></div>
        <div class="brings-body">
          <div class="brings-title">Internal Communication Design</div>
          <div class="brings-text">Creating employee-facing experiences — screen visuals, intranet pages, digital campaigns — that inform, engage and reflect the company's identity.</div>
        </div>
      </div>
      <div class="brings-item">
        <div class="brings-dot"></div>
        <div class="brings-body">
          <div class="brings-title">Cross-Disciplinary Leadership</div>
          <div class="brings-text">Bridging communication, design, digital and business stakeholders — coordinating diverse contributors toward a unified creative outcome.</div>
        </div>
      </div>
      <div class="brings-item">
        <div class="brings-dot"></div>
        <div class="brings-body">
          <div class="brings-title">UX-Informed Creative Thinking</div>
          <div class="brings-text">Approaching every brief with the user's experience in mind — clarity before aesthetics, function before form, impact before decoration.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="bg-soft">
  <div class="container-wide">
    <div class="container" style="padding:0">
      <p class="section-label fade-in">Selected projects</p>
      <h2 class="section-title fade-in">Work that<br /><em>left a mark.</em></h2>
      <div class="divider fade-in"></div>
    </div>
    <div class="projects-grid fade-in">

      <div class="project-card">
        <div>
          <div class="project-tag">DAM · Information Architecture · UX</div>
          <div class="project-title">Media Center / DAM Restructuration</div>
          <div class="project-desc">Led the strategic redesign of Symrise's digital asset management platform — rethinking taxonomy, navigation logic and metadata frameworks to make corporate assets truly findable, usable and governed. The project touched every content type: photography, templates, brand materials, video.</div>
          <div class="project-outcome">From a scattered file library to a coherent, governed media ecosystem — significantly reducing friction for global teams.</div>
        </div>
        <div class="project-year">01</div>
      </div>

      <div class="project-card">
        <div>
          <div class="project-tag">Intranet · Editorial Design · Employee Experience</div>
          <div class="project-title">Intranet Content Platform</div>
          <div class="project-desc">Structured, designed and populated key intranet sections — bringing editorial rigour to internal communication pages. Defined content hierarchies, tone frameworks, visual templates and editorial guidelines to elevate the employee experience at every touchpoint.</div>
          <div class="project-outcome">A cleaner, more navigable internal environment reflecting Symrise's brand values and communication ambitions.</div>
        </div>
        <div class="project-year">02</div>
      </div>

      <div class="project-card">
        <div>
          <div class="project-tag">Brand · Visual Identity · Guidelines</div>
          <div class="project-title">Corporate Visual Standards & Templates</div>
          <div class="project-desc">Developed and maintained brand-consistent templates, design guidelines and visual standards across corporate communication formats — from executive presentations to internal signage and screen campaigns. Created tools that make quality achievable by non-designers.</div>
          <div class="project-outcome">A repeatable, scalable system that raises visual consistency across geographies and teams.</div>
        </div>
        <div class="project-year">03</div>
      </div>

      <div class="project-card">
        <div>
          <div class="project-tag">Internal Campaign · Motion · Storytelling</div>
          <div class="project-title">ONE Symrise Strategic Communication</div>
          <div class="project-desc">Contributed to the visual and editorial identity of ONE Symrise / ONE SYM — a major internal transformation initiative. Designed communication materials, screen visuals and narrative frameworks to embed the programme into day-to-day employee culture with clarity and emotional resonance.</div>
          <div class="project-outcome">Strategic messaging made tangible and human through considered design and consistent visual language.</div>
        </div>
        <div class="project-year">04</div>
      </div>

      <div class="project-card">
        <div>
          <div class="project-tag">Data Visualisation · Infographic · Premium Storytelling</div>
          <div class="project-title">Executive Presentations & Infographics</div>
          <div class="project-desc">Transformed complex data, strategy documents and business narratives into premium visual presentations and infographics — bridging analytical content and aesthetic quality. Built for board-level audiences, leadership reviews and global communication events.</div>
          <div class="project-outcome">Complex ideas made visible, credible and memorable through precise visual craft.</div>
        </div>
        <div class="project-year">05</div>
      </div>

    </div>
  </div>
</section>

<!-- PHILOSOPHY -->
<section id="philosophy">
  <div class="container">
    <p class="section-label fade-in">Creative philosophy</p>
    <h2 class="section-title fade-in">Design as<br /><em>clarity.</em></h2>
    <div class="divider fade-in"></div>
    <div class="philosophy-block fade-in">
      <div class="philosophy-quote">"Good design is not decoration. It is the clearest possible expression of an idea."</div>
      <div class="philosophy-text">I believe in the discipline of removing — cutting everything that does not serve the message, until only the essential remains. This is not minimalism for its own sake. It is respect for the audience's attention and intelligence.<br/><br/>Inspired by Jony Ive's approach at Apple, and Dieter Rams' ten principles, I bring the same rigour to corporate communication: every colour chosen with intent, every typeface chosen for clarity, every word chosen for precision.<br/><br/>The goal is never a beautiful artefact. The goal is an idea, understood.</div>
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:2rem;margin-top:3rem" class="fade-in">
      <div>
        <div style="font-family:var(--serif);font-size:1.1rem;font-weight:400;color:var(--navy);margin-bottom:.5rem">Simplicity</div>
        <div style="font-size:.82rem;color:var(--ink-soft);line-height:1.7">Complex subjects deserve simple expressions. Complexity in the output signals confusion in the thinking.</div>
      </div>
      <div>
        <div style="font-family:var(--serif);font-size:1.1rem;font-weight:400;color:var(--navy);margin-bottom:.5rem">Coherence</div>
        <div style="font-size:.82rem;color:var(--ink-soft);line-height:1.7">Every element should belong. Visual systems only work when every decision reinforces the whole.</div>
      </div>
      <div>
        <div style="font-family:var(--serif);font-size:1.1rem;font-weight:400;color:var(--navy);margin-bottom:.5rem">Emotion</div>
        <div style="font-size:.82rem;color:var(--ink-soft);line-height:1.7">Information without emotion is noise. The best communication makes people feel something — even inside a corporation.</div>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience" class="bg-soft">
  <div class="container">
    <p class="section-label fade-in">Experience</p>
    <h2 class="section-title fade-in">Built from<br /><em>the inside.</em></h2>
    <div class="divider fade-in"></div>
    <div class="exp-list fade-in">
      <div class="exp-item">
        <div class="exp-date">2020 → present</div>
        <div>
          <div class="exp-role">Internal Communications Officer<br/>Corporate Communications</div>
          <div class="exp-company">Symrise AG · Rennes, France</div>
          <div class="exp-desc">Leading creative and editorial projects across internal communication, brand design, digital content and platform structuring. Key contributor to DAM / Media Center restructuration, intranet development, ONE Symrise strategic communication and corporate visual standards.</div>
        </div>
      </div>
      <div class="exp-item">
        <div class="exp-date">Earlier</div>
        <div>
          <div class="exp-role">Communication & Design</div>
          <div class="exp-company">Symrise · Progressive roles</div>
          <div class="exp-desc">Gradual evolution from operational communication roles toward creative and strategic responsibilities within the Corporate Communications function — building expertise in visual design, content strategy and brand communication along the way.</div>
        </div>
      </div>
      <div class="exp-item">
        <div class="exp-date">Education</div>
        <div>
          <div class="exp-role">MBA — Communication & Marketing</div>
          <div class="exp-company">MBway · France</div>
          <div class="exp-desc">Advanced training in marketing strategy, brand management, communication planning and business fundamentals — providing the strategic foundation for a creative leadership role.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- LETTER -->
<section id="letter" class="letter-section">
  <div class="letter-inner">
    <div class="letter-label">A letter of intent</div>
    <p class="letter-text">
      I have spent several years at Symrise learning, building and delivering — quietly raising the standard of what internal communication can look and feel like inside this company.
    </p>
    <p class="letter-text">
      The Global Creative Design Lead role represents exactly the challenge I am ready for: to bring coherence, ambition and visual leadership to our corporate communication at a global scale. Not as an executor, but as the creative force that shapes how we express ourselves to the world — and to each other.
    </p>
    <p class="letter-text">
      I know this company. I know its brand, its culture, its complexity. And I know precisely how to turn that complexity into something clear, elegant and worth paying attention to. That is what I do — and I would like to do it, fully, in this role.
    </p>
    <p class="letter-text">
      I am available to discuss my candidacy at your convenience.
    </p>
    <div class="letter-sig">Pierre-Marie Meston</div>
  </div>
</section>

<!-- FOOTER -->
<footer class="footer">
  <div class="footer-name">Pierre-Marie Meston</div>
  <div style="font-size:.8rem;color:var(--ink-soft);margin-top:.25rem">Global Creative Design Lead · Symrise · Rennes</div>
  <div class="footer-links">
    <a href="https://www.linkedin.com/in/pm-meston" target="_blank">LinkedIn</a>
    <a href="mailto:pierre-marie.meston@symrise.com">Email</a>
  </div>
</footer>

<script>
const obs = new IntersectionObserver((entries) => {
  entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('visible') });
}, { threshold: 0.08 });
document.querySelectorAll('.fade-in').forEach(el => obs.observe(el));
</script>
</body>
</html>
