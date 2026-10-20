# SeatWise AI — Exam Seating Arrangement System

A responsive, browser-based prototype for managing exam candidates, configuring rooms, generating a seating plan, exporting CSV files, and printing/saving the plan as PDF.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. Use **Load demo** to test, or add candidates and rooms yourself.

No terminal, installation, or server is required.

## Deploy free with GitHub Pages
1. Sign in at https://github.com and create a **public** repository, for example `ai-exam-seating`.
2. Upload `index.html` (and optionally this README) to the repository's root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for publishing, then open the URL shown in the Pages section. It will usually look like `https://YOUR-USERNAME.github.io/ai-exam-seating/`.

Official guide: https://docs.github.com/en/pages/quickstart

## Important limitations
- This is a front-end prototype. Candidate data stays in the current browser session and is not shared between devices or users.
- It has no login, server database, automatic cloud backup, or institution-wide access control.
- Allocation uses deterministic, rule-based sorting by department and roll number. It is not a trained AI model; describe it as an AI-inspired prototype unless you add a real optimisation/AI backend.
- Do not enter real student personal data on a public demo. GitHub Pages sites are publicly accessible.
