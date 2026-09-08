# PARAL Lab Website

Simple static website for PARAL Lab (DePaul University).

## Files

- `index.html`: Homepage with DePaul campus hero image.
- `get-start.html`: Maintainable onboarding page for new students.
- `styles.css`: Shared styles for both pages.

## Update Workflow

1. Edit `get-start.html` to add onboarding content (papers, tasks, milestones).
2. Edit `index.html` if you want to change homepage text or links.
3. Edit `styles.css` for design updates.

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Open repository settings on GitHub.
3. Go to **Pages**.
4. Set **Source** to deploy from branch `main` and folder `/ (root)`.
5. Save and wait for the site URL to be generated.

## CSC 503 — Fall 2026

The course site is at `teaching/csc503/fall2026/` and has Home, Assignments, Policy, AI Policy, Preparing, and Schedule pages. It uses its own `assets/course.css`; editing it does not restyle the lab pages. All course links are relative and work under the GitHub Pages repository prefix. There is no build step or JavaScript requirement.

Expected course URL after publishing: https://lottiewang.github.io/PARAL-Lab/teaching/csc503/fall2026/

Edit the individual HTML files to update content. The lecture dates are nominal Monday slots, not a confirmed start arrangement. Before releasing a final syllabus, finalize office details, TA/grader, actual delivery schedule, grading weights, assignment links, due dates, and assignment-specific collaboration rules.

Sources checked September 8, 2026:

- Reference organization and topic progression: https://www.cs.ucr.edu/~yihans/teaching/214/W25/ and its four subpages. The DePaul pages use newly written text.
- CSC 503 prerequisite, sections, meeting time, and classroom: https://www.cdm.depaul.edu/academics/Pages/courseinfo.aspx?Subject=CSC&CatalogNbr=503
- Quarter dates: https://academics.depaul.edu/calendar/Pages/default.aspx (embedded Autumn Term 2026–2027 records).
- Instructor contact: https://sites.google.com/view/letong-wang/home
- Academic integrity: https://offices.depaul.edu/academic-affairs/faculty-resources/academic-integrity/Pages/default.aspx
- Coursework and private-repository/Gradescope submission workflow: instructor's existing course planning materials.

The original course's institutional staff details, calendars, sanctions, grade weights, and deadlines are not adopted as DePaul policy.


The AI policy is at `teaching/csc503/fall2026/ai-policy/`, with a summary on the Policy page. Both pages credit Stanford CS336 and link to its original AI policy guide. The policy describes the AGENTS.md files to be supplied in assignment repositories; this website change does not create or modify those separate repositories.
