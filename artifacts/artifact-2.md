---
layout: default
title: Artifact 2 — Software Design and Engineering Updates
---

<style>
:root { color-scheme: dark; }
body { background:#1e293b; color:#e5e7eb; }   /* dark blue base, light text */
h1,h2,h3 { color:#f8fafc; }
a { color:#93c5fd; }
a:hover, a:focus { color:#bfdbfe; }

.site-header { background:#0b1220; border:0; }
.site-title, .site-title:visited { color:#ffffff !important; }
.site-nav .page-link { color:#e5e7eb !important; }
.site-nav .page-link:hover, .site-nav .page-link:focus {
  color:#ffffff !important; text-decoration: underline;
}

hr { border-color: rgba(255,255,255,0.12); }

/* ==== Fix Minima mobile dropdown contrast on dark pages ==== */

/* Make the header dark on all widths */
.site-header { background:#0b1220 !important; border:0; }

/* Desktop links */
.site-title, .site-title:visited { color:#fff !important; }
.site-nav .page-link { color:#e5e7eb !important; }
.site-nav .page-link:hover, .site-nav .page-link:focus {
  color:#ffffff !important; text-decoration: underline;
}

/* Mobile dropdown (Minima uses .trigger as the menu panel) */
@media (max-width: 600px) {
  .site-nav .trigger {
    background:#0b1220 !important;              /* dark panel */
    border: 1px solid rgba(255,255,255,0.08);   /* subtle border */
    box-shadow: 0 8px 24px rgba(0,0,0,0.35);
  }
  .site-nav .page-link {
    color:#e5e7eb !important;                   /* readable links */
    padding: 0.6rem 0.8rem;
    display: block;
  }
  .site-nav .page-link:hover, .site-nav .page-link:focus {
    color:#ffffff !important;
    background: rgba(255,255,255,0.06);         /* hover row highlight */
    text-decoration: none;
  }
  /* Hamburger icon color */
  .site-nav label[for="nav-trigger"] {
    color:#e5e7eb !important;
  }
  /* Dropdown caret/triangle (if any) */
  .site-nav .trigger::before { display:none; }
}
</style>

# Artifact 2 — Software Design and Engineering Updates 

## Artifact Description
This artifact is the same event tracking app that was created in android studio, but re-created in visual studio code as a web application.It utilizes js and node.js, express, using a MVC approac with HBS and JSON

## Enhancements / Improvements
-	Modern development: I recreated the app in Visual Studio Code as a Node.js/Express project using MVC architecture with Handlebars templates. This shows proper separation of concerns and aligns with industry best practices.
-	Preparation for future work: I scaffolded the project for MongoDB integration, which will be addressed more fully in the Databases milestone.

## Learning & Reflection
Through this enhancement, I gained more experience with JavaScript, Express, and Handlebars, which expanded my skill set beyond Android development. I learned how to set up MVC folder structures, manage routes and controllers, and prepare a project for database migration.
One challenge I faced was when creating the main folders for the Node.js app. At first, I was unsure of the correct commands to scaffold the structure, but by practicing with the terminal and using Express Generator, I learned how to build the setup properly. This gave me more confidence in working across both Java and JavaScript ecosystems.

## Downloads
- **Project (zip):** [Download Artifact 2](../downloads/artifact-2/Torres_J_CS499_ET_Capstone_VSC.zip)
- **Narrative (.docx):** [Download Narrative](../downloads/artifact-2/Torres_J_CS499_3_2.docx)

[Back to Home](/)

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
