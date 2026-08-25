# Hanieh's Sabbatical Countdown

A single-page countdown to the **last day of classes at the University of Delaware**
(Tuesday, December 8, 2026, 10:00 p.m. ET) — the moment a nine-month sabbatical begins.

Everything lives in `index.html`: no build step, no dependencies, no tracking.

## What it shows

- Live days / hours / minutes / seconds to the final class bell
- Semester progress bar (Aug 26 → Dec 8, 2026)
- MWF class days remaining (Hanieh teaches Mon/Wed/Fri), minus Labor Day (Sep 7)
  and Thanksgiving break (Nov 23–27)
- Weeks left, Mondays left
- Sabbatical span: Dec 8, 2026 → Wed Aug 25, 2027 — the assumed first day of Fall 2027
  (last Wednesday of August; UD hasn't published the 2027–28 calendar yet)
- Confetti (click anywhere for more; a big burst when the clock hits zero)

## Publish on GitHub Pages

1. Create an empty repo on GitHub (e.g. `sabbatical-countdown`), no README.
2. From this folder:

   ```
   git remote add origin https://github.com/<you>/sabbatical-countdown.git
   git branch -M main
   git push -u origin main
   ```

3. Repo → **Settings → Pages** → Source: **Deploy from a branch**, Branch: `main` / `/ (root)` → Save.
4. A minute later it is live at `https://<you>.github.io/sabbatical-countdown/`.

## Dates

From the [UD Registrar's academic calendar](https://www.udel.edu/academics/registrar/calendar/):
classes begin Wed Aug 26, 2026; classes end 10:00 p.m. Tue Dec 8, 2026; Reading Day Dec 9;
finals Dec 10–14.
