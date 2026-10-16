EX:MAZE — FESTIVAL EDITION (GitHub Pages / static-only)

FILES
- index.html: game, animated start screen, name entry, timer, maze stages, local leaderboard
- bgm1.mp3, bgm2.mp3, bgm3.mp3: background music
- effect.mp3: sound effect

PUBLISH ON GITHUB PAGES
1. Create/open the GitHub repository for the festival game.
2. Upload index.html and all four MP3 files to the repository root (same folder).
3. Open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Open the Pages URL after deployment finishes.

AT THE FESTIVAL
- Open the published URL on the computer that will run the booth.
- Press F11 to use browser full-screen mode.
- Participants enter a nickname and press GAME START. The timer begins at game start.
- The leaderboard is saved in that browser on that computer using localStorage.
- This static-only version does not require Node, Render, Supabase, or any other server.

IMPORTANT LEADERBOARD LIMIT
Because GitHub Pages is static hosting, records are only shared by the same browser on the same computer. They do not automatically sync between different computers or browsers. Do not clear browser data during the festival, or local records may be lost.

ANIMATION / COMPATIBILITY
The start screen includes animated neon grid drift, pulsing frame, glowing title, brief glitch accent, sweeping highlight, floating registration card, animated start button, and stat/icon motion. Layout responds to desktop, tablet, and phone sizes. Reduced-motion preferences are respected. Actual physical-device testing is still recommended before the event.
