# TrackBot 1 — Project Hub

Autonomous Warehouse Logistics Robot — SSIP Funding Proposal

**Live site:** `https://YOUR-USERNAME.github.io/trackbot`

## File structure
```
trackbot/
├── index.html    ← Main hub page
├── style.css     ← All styles
├── assets/       ← Put your photos here
└── README.md
```

## How to add a photo
1. Drop image into `assets/` folder
2. In index.html, replace a placeholder card's `<div class="photo-placeholder">` block with `<img src="assets/your-photo.jpg" alt="...">`
3. Update the title and description below

## How to add an idea card
Copy this inside the `.ideas-grid` div:
```html
<div class="idea-card">
  <div class="idea-status status-planned">Planned</div>
  <div class="idea-title">Your Idea</div>
  <div class="idea-desc">Description here.</div>
</div>
```
Status: status-planned / status-progress / status-done

## How to add a reference
Copy this inside `.ref-list`:
```html
<div class="ref-item">
  <span class="ref-num">08</span>
  <div class="ref-content">
    <div class="rc-title">Title</div>
    <div class="rc-type">TYPE · <a href="https://..." target="_blank">source.com</a></div>
  </div>
</div>
```

## Team
| Member | Role |
|--------|------|
| AI Student 1 | Navigation — encoder, A*, PID |
| AI Student 2 | Mission + FSM |
| AI Student 3 | Dashboard + comms |
| Food Processing Student | Hardware + testing |

Budget: ₹18,634 | SSIP Ask: ₹20,000