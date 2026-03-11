# Planned files for "Roblox-ish" extended demo

Client (static site)
- index.html         — updated Three.js scene + avatar editor UI
- styles.css         — UI styles
- script.js          — client logic: movement, camera, avatar editor, networking
- network.js         — networking client (socket.io client + interpolation)
- physics.js         — optional physics integration (cannon-es wrapper)
- README.md          — run & deploy instructions (client)

Server (Node.js)
- server/package.json — dependencies (express, socket.io)
- server/index.js     — minimal authoritative server (rooms, player state)
- server/README.md    — server run & deploy instructions

Deployment
- docs/ or build/    — (optional) for project-site GitHub Pages if chosen
- Procfile / Dockerfile — optional for chosen host (Railway/Render)
