# Urban Drive: Open World v0.2

Free browser-based 3D open-world driving prototype. It uses Three.js from a public CDN and procedural geometry, with no paid assets.

## What's new in v0.2
- More trees and sidewalk greenery
- Procedural shop fronts with colorful signs
- Pedestrian NPCs walking around the city
- Multiple vehicle types: sports car, sedan, taxi, van, truck, plus traffic cars and a police cruiser
- Enter nearby parked vehicles with E; use Q to identify a nearby vehicle
- Delivery jobs, cash rewards, wanted level and follow camera

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser while connected to the internet.
3. If the browser blocks ES modules from `file://`, use VS Code with the free Live Server extension.

## Publish using free GitHub Pages
1. Create a public repository named `urban-drive-open-world`.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to Settings -> Pages.
4. Choose Deploy from a branch, branch `main`, folder `/(root)`, then Save.
5. Open the URL GitHub Pages shows after deployment.

## Controls
- WASD / arrow keys: move or drive
- E: enter or exit nearest vehicle
- Q: identify nearby vehicle
- Shift: sprint on foot
- Space: handbrake
- R: reset position

This is an evolving prototype, not a full GTA V-scale game. It requires internet to load Three.js from jsDelivr. Use original assets and avoid copying GTA V proprietary maps, characters, logos, or game files.
