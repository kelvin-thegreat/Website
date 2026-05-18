# Isabella & James — Wedding Website

A beautiful, single-page wedding website built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step — just open `index.html` or deploy straight to GitHub Pages.

## Features

- Animated hero section with couple's names
- Live countdown timer to the wedding date
- Our Story narrative section
- Interactive journey timeline
- Wedding day details grid (ceremony, venue, reception, attire, accommodation, registry)
- Photo gallery mosaic
- RSVP form with attendance, guest count, and dietary fields
- Fully responsive (mobile-friendly)
- Smooth scroll-reveal animations

## Deploy to GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click **+** → **New repository**
3. Name it something like `wedding` or `isabella-james-wedding`
4. Set it to **Public** (required for free GitHub Pages)
5. Click **Create repository**

### Step 2 — Upload your files

**Option A — via the GitHub website (easiest):**
1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop both `index.html` and `README.md`
3. Click **Commit changes**

**Option B — via Git (command line):**
```bash
git init
git add index.html README.md
git commit -m "Initial commit: wedding website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repo, go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Set branch to **main** and folder to **/ (root)**
4. Click **Save**

### Step 4 — Your site is live!

After about 1–2 minutes, your website will be live at:

<a href="https://euphonious-zuccutto-cd1cbb.netlify.app/" target="_blank">Wedding website</a>


GitHub will show you the exact URL in the Pages settings once it's deployed.

---

## 🎨 Customisation

All content is in `index.html`. Search for these placeholders to personalise:

| What to change | Find this text in the file |
|---|---|
| Couple's names | `Isabella` / `James` |
| Wedding date | `June 14th, 2025` / `2025-06-14T15:00:00` |
| Venue | `Villa Rosa` / `Greve in Chianti` |
| Story text | Inside `<section id="story">` |
| Timeline milestones | Inside `<section id="timeline">` |
| Detail cards | Inside `<section id="details">` |
| Gallery photos | Replace `.gallery-fill` divs with `<img>` tags |
| RSVP deadline | `May 1st, 2025` |
| Hotel / shuttle info | Inside the detail cards |

### Adding real photos to the gallery

Replace any gallery placeholder div like this:

```html
<!-- Before -->
<div class="gallery-fill g1">Florence, 2020</div>

<!-- After -->
<img src="photos/florence.jpg" alt="Florence 2020" style="width:100%;height:100%;object-fit:cover;position:absolute;inset:0;">
```

Upload your photos into a `photos/` folder alongside `index.html`.

---

## File Structure

```
/
├── index.html      # The entire website (self-contained)
├── README.md       # This file
└── photos/         # (optional) Add your own images here
```

---

*Made with love for Isabella & James ♡*
