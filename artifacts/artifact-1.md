---
layout: default
title: Artifact 1 — Mobile Event Tracker (CS 360) Pre-Updates
---

<style>
:root { color-scheme: dark; }
body { background:#0a2f1f; color:#e5e7eb; } /* dark green */
a { color:#86efac; }
hr { border-color:#134e33; }

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

# Artifact 1 — Mobile Event Tracker (CS 360) Pre-Updates

## Artifact Description
The artifact I selected is my mobile event tracker application from CS 360 (Mobile Architecture and Programming). It was originally created in Android Studio using Java and XML. The app lets a user sign up or log in, choose SMS notification permission, and then view an event page where events can be added, updated, or deleted. The application uses two SQLite databases: one for users and one for events. 

## Why I Selected This Artifact
I chose this artifact because it was a solid starting point but not fully complete, which made it a good candidate for enhancements. It already showed my ability to design and build working applications, but by improving it, I can also show that I can refactor and restructure code, apply best practices, and prepare an application for modern deployment.

## Downloads
- **Project (zip):** [Download Artifact 1](../downloads/artifact-1/Torres_J_CS360_Proj2_2EventTracker_PreUpdates.zip)
- **Narrative (.docx):** [Download Narrative](../downloads/artifact-1/CS_499_ART_1_details_plans.docx)

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
