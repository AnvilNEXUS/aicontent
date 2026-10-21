# SOVRAEG Learning Velocity Framework — Interactive Library

Three chapters derived from the three user/assistant exchanges in the Learning Velocity conversation.

## Files

- `index.html` — library landing page
- `01-learning-velocity.html` — initial LV framework + live calculator/chart
- `02-vector-effectiveness.html` — effectiveness comparison + reward allocation simulator
- `03-mastery-learning.html` — mastery states + grade translation simulator
- `assets/style.css` — responsive styling
- `assets/app.js` — dependency-free JavaScript charts and interactions
- `assets/img/*.svg` — editable, resolution-independent original diagrams

## iPhone

Download and unpack the ZIP in the Files app. Because iOS file previews sometimes isolate local file access, the most reliable way to test full navigation is to publish to GitHub Pages. You can also view each standalone HTML file after unzipping; some Files/Quick Look viewers restrict JavaScript.

## GitHub Pages deployment

1. Create a public GitHub repository, for example `learning-velocity`.
2. Upload **the contents of this directory** to the repository root, including `assets/`.
3. Navigate to **Settings → Pages**.
4. In **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/(root)`.
5. Save, then open `https://YOURUSERNAME.github.io/learning-velocity/` when GitHub finishes deployment.

Alternatively publish through a `docs/` subfolder if configured for that route.

## Notes

- Edited web-publication adaptations rather than full verbatim copies of the original assistant responses.
- Data shown in charts and simulators is illustrative, never empirical evidence.
- No external scripts, trackers or network requests.
- SVGs are editable source-format image assets.
- No backend, account setup or license-protected dependencies needed.
