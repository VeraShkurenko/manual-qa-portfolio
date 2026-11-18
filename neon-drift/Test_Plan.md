# Test Plan – Neon Drift

**Product:** [Neon Drift](https://github.com/VeraShkurenko/neon-drift) – multiplayer browser game (desktop + mobile)
**Build:** d8aced3

## What to test
- Main menu (nickname, color)
- Gameplay (movement, orbs, boost, absorbing, mines, arena border)
- HUD (score, leaderboard, kill feed, minimap)
- Death screen
- Network (server offline, slow internet, 2 players)
- Mobile (portrait, landscape, interruptions)

## Not tested
- Load testing
- Server code

## Types of testing
Functional, UI, exploratory, mobile, network

## Environment
| Device | Browser |
|---|---|
| MacBook, macOS 15 | Chrome |
| Mobile emulation 375x812, 844x390 | Chrome DevTools |
| Android / iPhone | planned |

## Tools
Chrome DevTools, Charles Proxy, Google Sheets

## Documents
- Checklist, test cases, bug reports – [NeonDrift_Testing.xlsx](NeonDrift_Testing.xlsx)
- Screenshots – [screenshots](screenshots/)
