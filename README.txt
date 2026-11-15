NEON SNAKE — ARCADE GAME
Designed & Developed by Saika Malhi © 2026

PROJECT STRUCTURE
NEON-SNAKE/
  index.html
  css/style.css
  js/game.js
  assets/sounds/README.txt
  README.txt

RUN THE GAME
1. Extract this ZIP file.
2. Open the NEON-SNAKE folder.
3. Double-click index.html.
4. The game opens in your browser. No Python, Flask, Node.js,
   server, or software installation is required.

CONTROLS
Arrow Keys or W/A/S/D : Move
Space                 : Pause / Resume
On-screen arrows      : Touch controls
Start Game            : Begin a run
Restart               : Start a fresh run
Sound button          : Mute / unmute generated sound

GAME RULES
Collect cyan energy cells to earn 10 points and grow longer.
The game gets faster as your score increases. Every 50 points
raises the displayed level. Hitting a wall or your own body ends
the game. Your high score is saved in this browser on this device.

TECHNICAL NOTES
- HTML5 Canvas, CSS3 and vanilla JavaScript.
- No JavaScript frameworks or external libraries.
- Works offline after extraction; Google Fonts are optional and
  system fonts are used when offline.
- Sound is generated through Web Audio API where supported.
- High score uses localStorage. If browser storage is disabled,
  gameplay still works but the score may not persist.
- Older browsers without HTML5 Canvas or modern JavaScript support
  may not run the game fully. Windows 7 compatibility depends on
  the installed browser version.

This is a front-end browser game; it has no server, user accounts,
online leaderboard or cloud score storage.
