---
layout: default
title: Artifact 3 — Algorithms and Data Structures Updates
---


<style>
:root { color-scheme: dark; }
body { background:#4c1d95; color:#f3f4f6; }   /* dark purple */
a { color:#fca5a5; }
hr { border-color:#5b1515; }
</style>

# Artifact 3 — Algorithms and Data Structures Updates

## Enhancements / Improvements
- Custom MongoDB Models: I created user and event models to represent data consistently across web and mobile platforms.
- Efficient Algorithms: I replaced simplistic full-table scans with indexed queries that support filtering by date ranges, case-insensitive title searches, and sorting by fields such as startAt, title, and priority.
- Compound Indexes: I added indexes on { userId, startAt } and { userId, titleLower }, ensuring that queries use logarithmic time lookups (O(log n)) rather than linear scans (O(n)), demonstrating my knowledge of algorithmic optimization.
- Pagination: I introduced pagination to improve scalability. Instead of returning all results at once, queries return one page at a time, reducing complexity from O(n) responses to O(k) per request, where k is the page size.


## Learning & Reflection
Enhancing this artifact taught me valuable lessons about the relationship between algorithms and database structures. At first, the app relied on simple queries that worked but were inefficient at scale. By adding compound indexes, I learned how databases internally use IXSCAN (index scans) instead of costly COLLSCAN (collection scans). This reinforced the importance of analyzing time complexity in practical systems.
For this section, my work focused on the web application side. I designed and implemented features such as case-insensitive title searches, date filtering, sorting, and pagination. These enhancements demonstrated how algorithmic choices directly impact efficiency and scalability when managing larger datasets.
I have not yet connected the database to the mobile application. The original artifact was built with SQLite on Android, and I plan to replace that connection with MongoDB so both the mobile and web applications share the same backend. This step will be addressed in the next section, Databases. At that stage, I will focus on ensuring consistency across platforms so that events created on mobile are immediately available on the web, and vice versa.
Challenges in this phase included debugging query validation (such as invalid date ranges or ObjectIds) and integrating pagination without breaking the existing flow of results. These challenges deepened my understanding of MongoDB’s query planner and reinforced the need to combine clean design with algorithmic efficiency.


## Downloads
- **Project (zip):** [Download Artifact 3](../downloads/artifact-3/Torres_J_CS499_ET_Capstone_VSC_2.zip)
- **Narrative (.docx):** [Download Narrative](../downloads/artifact-3/Torres_J_CS499_4_2.docx)

[Back to Home](/)
