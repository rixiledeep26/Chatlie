EURO20 500-ODDS OVERSEER — FINAL ANDROID V3 (RENDER DOCKER READY)
=================================================================

This package uses Render's Docker runtime so deployment does not depend on Render's host npm command.

FILES ARE ROOT-LEVEL.

RENDER SETUP
- Service type: Web Service
- Runtime: Docker (Render detects Dockerfile)
- Root Directory: blank
- Plan: Free
- No Build Command is needed.
- No Start Command is needed.
- Health check: /health
- Optional environment variable: ODDS_API_IO_KEY
- Alternative: PARLAY_API_KEY

If creating the service manually, select Docker as the runtime. Render builds Dockerfile and starts the container with node server.js.

ANDROID
After Render shows Live, open the HTTPS onrender.com URL in Chrome on Android and use Chrome's menu to install/add the app to the home screen.

SAFETY
Analysis/prediction only. No Betway login, bet placement, cash-out, or stake management.
