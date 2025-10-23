---
layout: default
title: Artifact 4 — Database Updates
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
</style>

# Artifact 4 — Database Updates

## Enhancements / Improvements
- Added JWT auth and password SALT/HASH on the web app

- Built a TokenStore and a MyApp initializer to load the saved JWT before API calls

- Fixed Retrofit setup so mobile sends the JWT correctly

- Created web controllers to thin out web routes and added cookies to pass userId via token (not query)

- Switched everything to use Passport (userId from JWT instead of query)

- Updated Android to read userId from JWT and added delete event functionality

- Mobile can now add/update/delete events reliably

## Learning & Reflection
Enhancing this artifact taught me how much work goes into connecting front end and back end, especially when a mobile app and a web app share the same server. I learned to configure APIs, handle different data formats (HTML vs. JSON), and use Retrofit to simplify Android calls. A major challenge was returning JSON for mobile while keeping HTML for web, which required restructuring routes and logic in VS Code. This deepened my understanding of API design, HTTP, and data serialization. I strengthened full-stack skills, database integration, and debugging. I also saw how small architectural choices, like response formats or repository structure, impact performance and maintainability. Along the way I implemented JWT with SALT/HASH, built a TokenStore and app initializer, fixed Retrofit/JWT issues, moved to Passport and cookie-based userId, updated Android to use JWT (not query), and added delete on mobile.

## Downloads
- **VS Project (zip):** [Download Artifact 4 VS code](../downloads/artifact-4/Torres_J_CS499_EventTracker_Capstone_Fin.zip)
- **AS Project (zip):** [Download Artifact 4 Android Studio](../downloads/artifact-4/Torres_J_CS499_EventTracker_Capstone_AS_Fin.zip)
- **Narrative (.docx):** [Download Narrative](../downloads/artifact-4/Torres_J_CS499_5_FIN.docx)

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
