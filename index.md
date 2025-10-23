---
layout: default
title: Home
---

<style>
:root { color-scheme: dark; }
body { background:#0b1220; color:#e5e7eb; }   /* dark navy base */
h1,h2,h3 { color:#f8fafc; }

.site-header { background:rgba(11,18,32,0.98); border:0; }
.site-title, .site-title:visited { color:#ffffff !important; }
.site-nav .page-link { color:#e5e7eb !important; }
.site-nav .page-link:hover, .site-nav .page-link:focus {
  color:#ffffff !important; text-decoration: underline;
}
  .page-content a { /* lighter on hover just in main content area */
  color:#93c5fd;
}
.page-content a:hover,
.page-content a:focus {
  color:#ffffff;
}
  
.hero {
  position: relative;
  min-height: 80vh;
  display: grid;
  place-items: center;
  text-align: center;
  color: #fff;
  overflow: hidden;
  border-radius: 12px;
}
.hero::before {
  content: "";
  position: absolute; inset: 0;
  background: url('/assets/img/background.jpg') center/cover no-repeat;
  filter: brightness(0.45);
}
.hero-inner {
  position: relative;
  padding: 2rem;
  max-width: 880px;
}
.hero h1 {
  font-size: clamp(2rem, 4vw, 3.25rem);
  margin: 0 0 0.5rem 0;
}
.hero p.lede {
  font-size: clamp(1rem, 1.6vw, 1.25rem);
  opacity: 0.95;
  margin-bottom: 1.5rem;
}
.profile {
  width: 140px; height: 140px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid rgba(255,255,255,0.85);
  box-shadow: 0 8px 24px rgba(0,0,0,0.35);
  margin-bottom: 1rem;
}
.cta {
  display: inline-block;
  padding: 0.75rem 1.25rem;
  border-radius: 999px;
  text-decoration: none;
  font-weight: 600;
  background: #2563eb;
  color: #fff !important;
  box-shadow: 0 8px 24px rgba(37,99,235,0.35);
}
.cta.secondary { background: rgba(255,255,255,0.15); margin-left: 0.75rem; }
.grid {
  display: grid; gap: 1rem; margin-top: 2rem;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
}
.card {
  background: #0f172a; color: #e2e8f0;
  border-radius: 12px; padding: 1rem; text-align: left;
  border: 1px solid rgba(255,255,255,0.08);
}
.card h3{ margin:.25rem 0 .5rem }
</style>

<div class="hero">
  <div class="hero-inner">
    <img class="profile" src="/assets/img/profile_pict.jpeg" alt="Jake Torres headshot" />
    <h1>Hello, I'm Jake Torres</h1>
    <p class="lede">
      Software engineer focused on full-stack web & mobile.  
      I build reliable, secure apps and love shipping real products.
    </p>
    <p>
      <a class="cta" href="/portfolio/">Enter ePortfolio</a>
      <a class="cta secondary" href="https://www.linkedin.com/in/jake-a-torres">LinkedIn</a>
      <a class="cta secondary" href="https://github.com/tjake459">GitHub</a>
      <a class="cta secondary" href="mailto:tjake459@gmail.com">Contact</a>
    </p>

    <div class="grid">
      <div class="card">
        <h3>What I Do</h3>
        <p>Node/Express, MongoDB, React Native/Android, and secure APIs (bcrypt + JWT). + more </p>
      </div>
      <div class="card">
        <h3>Recent Work</h3>
        <p>Event Tracker app and a full-stack MERN capstone.</p>
      </div>
      <div class="card">
        <h3>Next Step</h3>
        <p>Continuing my education at UT Austin for a masters in Computer Science.</p>
      </div>
    </div>
  </div>
</div>

---

## Capstone Overview
- **Video walkthrough:** [Watch the code review video »](/video)
- **Artifacts:**
  1. [Artifact 1 — Mobile Event Tracker (CS 360) Pre-updates](/artifacts/artifact-1)
  2. [Artifact 2 — (Software Design and Engineering Updates)](/artifacts/artifact-2)
  3. [Artifact 3 — (Algorithms and Data Structures Updates)](/artifacts/artifact-3)
  4. [Artifact 4 — (Database Updates)](/artifacts/artifact-4)

---

## How to Navigate
Use the links above or the site header to view the video and artifact pages. Each artifact page includes:
- a brief description
- enhancement summary and learning reflection
- **download links** to the zipped project and the narrative (.docx)


