# Deadline Runway

An interactive university / competition deadline tracker for October 2026 through January 2027. Built as a static website with no framework, tracking scripts or external dependencies.

## Files

- `index.html` — all design and interaction code; GitHub Pages entry point.
- `events.js` — **authoritative shared milestone list**. Edit this file to publish future additions and changes.
- `.nojekyll` — standard GitHub Pages static-site marker.

## Publishing on GitHub Pages

1. On GitHub, create a **public** repository called `deadline-runway` (or another name). Public means the milestones in `events.js` are visible to anyone. Do not place private admissions documents or login details here.
2. Upload `index.html`, `events.js`, `.nojekyll` to the **root** of the `main` branch.
3. Go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, **main**, **/(root)**. Save.
4. After the deployment completes, the typical URL is `https://USERNAME.github.io/deadline-runway/` (replace USERNAME with your actual GitHub username). GitHub's Pages tab shows the authoritative URL.
5. Connect or authorize the GitHub app for the repository in ChatGPT, then ask ChatGPT to add or update a deadline in this repo. It can update `events.js` once write access is available.

## Updates and persistence

- The dashboard's **published dates** come directly from `events.js`. When GitHub Pages refreshes after a commit, all visitors see those new shared dates.
- Custom items, status checkmarks, and edits made inside the browser are stored in that **browser's localStorage**, not your GitHub account. They do **not** sync across browsers/devices, and local edits override upstream changes to that particular event.
- Use **Backup** and **Import** for your personal data. For permanent shared changes, ask ChatGPT to update `events.js` in the repository, or edit it yourself on GitHub.
- Important: GitHub Pages hosting alone does not provide cross-device user accounts or synchronized personal progress. That would require a backend or a separate cloud integration.
- Original organization-specific timezones are noted per event. When in doubt, follow the official source link and verify times before submitting.

## Date verification

Dates were populated on October 27, 2026 from published sources, including Princeton, UAT-UK, College Board, COMAP HiMCM, AMC, UCAS, Swiss Youth in Science, Veritas, Junction, MIT, Stanford, Yale, Penn and Harvard. Personal prep targets are labeled `personal` and decision-window placeholders `estimate`.

**Alert**: The Swiss Youth in Science official German portal lists October 31, 2026, but an official English page lists October 27, 2026. Verify immediately with the organizer before relying on the later date.
