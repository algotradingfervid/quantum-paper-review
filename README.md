# Quantum Paper Review

A Tinder-style paper triage tool for 163 quantum research papers.

## How to host on GitHub Pages (free, no server needed)

1. Create a new GitHub repo (e.g. `quantum-paper-review`)
2. Push this folder:
   ```bash
   cd paper-review
   git init
   git add .
   git commit -m "Initial paper review app"
   git remote add origin https://github.com/YOUR_USERNAME/quantum-paper-review.git
   git push -u origin main
   ```
3. Go to repo **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your app is live at `https://YOUR_USERNAME.github.io/quantum-paper-review`

## Usage

- **Arrow Right** or click ✓ → Accept paper
- **Arrow Left** or click ✗ → Reject paper
- **Z** → Undo last action
- **Drag** the card left/right
- Click any card in the sidebar to read the full summary
- Click the **↩** icon on a sidebar card to move it back to the queue
- **Export** button downloads your accepted/rejected list as JSON
- Progress is saved automatically in your browser (localStorage)

## Files

- `index.html` — the app
- `papers.js` — 163 paper summaries extracted from the literature survey
