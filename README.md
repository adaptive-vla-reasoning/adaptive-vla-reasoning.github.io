# AWARE project page

Static project page for *Think Less, Act Better: Adaptive Reasoning for Vision-Language-Action Models*.

- `index.html` – the whole page (styles and script inline)
- `static/paper.pdf` – the paper
- `static/images/` – figures
- `static/videos/` – overview video and real-robot rollouts with the reasoning drawn on the frames
- `static/data/timelines.js` – per-query reasoning decisions for each rollout

Charts are drawn from the numbers in the `DATA` object at the top of the script in `index.html`.

Preview locally: `python -m http.server 8000` in this folder, then open http://localhost:8000.
