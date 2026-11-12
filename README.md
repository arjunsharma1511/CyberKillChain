# Operation Seven Locks — Cyber Kill Chain CTF

A static, beginner-friendly investigation that teaches the seven phases of the Cyber Kill Chain through a fictional Northstar Research incident.

## GitHub Pages

This folder has no dependencies or build step. To host it as part of this repository:

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Visit `https://<username>.github.io/<repository>/cyber%20kill%20chain/`.

If this folder becomes its own repository, upload its three files to that repository root and use the root Pages URL.

## Learning design

- Seven dossiers mirror Reconnaissance, Weaponization, Delivery, Exploitation, Installation, Command & Control, and Actions on Objectives.
- Three contextual clues per dossier produce 21 total challenges.
- Dossiers unlock at 0, 7, 15, 23, 31, 39, and 47 active minutes.
- The completion certificate requires all clues plus 60 active minutes. Time counts only while the page is open and visible.
- Progress is stored in `localStorage`, so refreshes and ordinary browser restarts do not bypass pacing.

The hour minimum is enforced by the interface, but—as with any client-only GitHub Pages activity—a technically motivated learner can inspect or alter browser code. For supervised learning, ask participants to solve in good faith.

## Editing

Content lives in the `phases` array at the top of `script.js`. Each phase contains its description, defense guidance, case story, evidence, questions, accepted answers, hint, and explanation. Adjust `MIN` and `UNLOCK` only if you intentionally want to change the pacing.

## Local preview

Open `index.html` directly, or serve this folder with any static web server. No information is transmitted anywhere.
