# Urban Drive: Open-World Prototype

A free browser-based 3D driving/action game starter. It uses Three.js from a public CDN and original procedural geometry (no paid assets).

## Run locally
1. Download and extract this ZIP.
2. Open `index.html` in a modern browser while connected to the internet.
3. If your browser blocks ES modules from `file://`, use VS Code with the free **Live Server** extension and choose **Open with Live Server**.

## Publish free with GitHub Pages
1. Create a new public repository named `urban-drive-open-world`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then **Save**.
6. Wait for deployment and open the URL shown on the Pages settings screen.

## Controls
- WASD / arrow keys: move or drive
- E: enter/exit the car when nearby
- Shift: sprint on foot
- Space: handbrake
- R: reset car position

## Current prototype features
- Procedurally generated 3D city grid
- Third-person walking and driving
- Enter/exit vehicle
- Delivery marker and cash rewards
- Simple patrol/wanted-level prototype
- HUD and follow camera

## Notes
This is a first playable prototype, not a full GTA V-scale game. It requires an internet connection to load Three.js from jsDelivr. Keep the project original; do not copy GTA V game files, maps, characters, logos, or other proprietary assets.
