# Roblox-ish Demo (Three.js)

This is a tiny "Roblox-ish" blocky demo built with Three.js. It demonstrates a simple 3D scene, a block avatar, WASD movement, jump, and a follow camera.

Preview locally:
1. Serve the folder with a static server (e.g. `npx http-server` or `python -m http.server 8000`).
2. Open http://localhost:8080 (or the port your server uses).

Deploy to GitHub Pages (user site):
1. Create a GitHub repo named exactly: `ilan538.github.io`
2. Commit these files to the repo root.
3. Push to GitHub.

Example git commands:
```bash
# from local project directory
git init
git add .
git commit -m "Initial Roblox-ish demo"
git branch -M main
# create remote repo on GitHub named ilan538.github.io, then:
git remote add origin https://github.com/ilan538/ilan538.github.io.git
git push -u origin main
```

After push, GitHub Pages will serve the site automatically at:
https://ilan538.github.io/

If Pages doesn't appear immediately, wait a few minutes or check the repository's Pages settings.

Notes and limitations
- This is a web demo, not the Roblox client or multiplayer Roblox places.
- If you want multiplayer features, we can add WebRTC or WebSocket hooks and a small server.
- Want a Roblox-themed UI, avatar editor, or terrain builder? Tell me which features and I’ll extend the demo.
