# TalentFlow AI — AI-Powered Recruitment System

A mobile-responsive MCA portfolio project built with HTML, CSS and vanilla JavaScript.

## Features
- Candidate profile and skill entry
- Skill-overlap job recommendations with transparent match percentages
- Save/unsave demo roles, persisted in browser localStorage
- Recruiter studio for publishing custom demo jobs
- Resume file selection; local TXT keyword scanning (PDF/DOC require manual skill entry in this version)
- Responsive dashboard and mobile navigation

## Run
Open `index.html` in a modern browser, or deploy the files with GitHub Pages.

## GitHub Pages deployment
1. Create a public repository, e.g. `talentflow-ai-recruitment`.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the root.
3. Open Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Wait for publishing; your URL will be `https://YOUR-USERNAME.github.io/talentflow-ai-recruitment/`.

## Honest scope
This is a working front-end prototype. Matching is rule-based skill overlap, not a trained AI model; there is no backend, real authentication, server database, or real job feed. Do not use it to make real hiring decisions. A production version should add a secure backend, PostgreSQL, authentication, consent-based document processing, semantic matching evaluation, testing, and fairness/privacy controls.
