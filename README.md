# Sethu S — Data Science Portfolio

A static portfolio website built with pure HTML/CSS/JS — no frameworks, no build step.  
Deployed for **free** on GitHub Pages.

---

## 🚀 Deploy to GitHub Pages (Free) — 5 Steps

### Step 1 — Create a GitHub repository
Go to [github.com](https://github.com) → **New repository**  
Name it exactly: `yourusername.github.io`  
(e.g. `itsmesethus.github.io`)  
Set it to **Public** → click **Create repository**

### Step 2 — Upload your files
Your repository must have this exact folder structure:

```
itsmesethus.github.io/
├── index.html              ← The main file (this portfolio)
├── resume/
│   └── res.pdf             ← Your resume PDF
├── pictures/
│   └── 111.png             ← Your profile photo
├── projects/
│   ├── time series/
│   │   └── light.jpg
│   ├── cognizant/
│   │   ├── 1.jpg
│   │   └── video app for gala.webm
│   ├── bcg/
│   │   └── 1.jpg
│   ├── quantium/
│   │   └── 12.jpg
│   ├── imdb/
│   │   └── 1.jpg
│   └── multi diseaase/
│       └── 1.jpg
└── img certifi/
    ├── 1.jpg
    ├── 1.1.jpg
    ├── ... (all certification images)
    └── 4.9.jpg
```

Upload all files via **Add file → Upload files** on GitHub,  
or use Git:

```bash
git clone https://github.com/itsmesethus/itsmesethus.github.io
# copy all your files in
git add .
git commit -m "Initial portfolio"
git push
```

### Step 3 — Enable GitHub Pages
Go to your repo → **Settings** → **Pages**  
Under **Source**, select **Deploy from a branch**  
Branch: `main` | Folder: `/ (root)` → **Save**

### Step 4 — Wait ~60 seconds
GitHub will build and deploy. You'll see a green banner:  
**"Your site is live at https://itsmesethus.github.io"**

### Step 5 — Visit your site
Open `https://itsmesethus.github.io` in your browser 🎉

---

## ✏️ How to Update Content

All content is in `index.html` — open it in any text editor.

- **Change bio text** → search for `about-bio` section
- **Add a new project** → find the `projects` array in the `<script>` tag and add a new object
- **Add skills** → find the `allSkills` array
- **Update certifications** → put new `.jpg` files in `img certifi/` and add filenames to the `certFiles` array

---

## 📦 Features

- ✅ Fully scrollable single-page layout
- ✅ Fixed sidebar with active-section highlighting
- ✅ Smooth scroll anchor navigation
- ✅ Round profile photo with glow effect
- ✅ Embedded Power BI dashboards (iframes)
- ✅ Video demo player
- ✅ Expandable project details (toggle)
- ✅ Unified skills tag cloud
- ✅ Certifications image grid with hover zoom
- ✅ Resume PDF download link
- ✅ Mobile responsive with hamburger menu
- ✅ Zero dependencies — pure HTML/CSS/JS
- ✅ Free hosting on GitHub Pages

---

*Built with Syne + Space Mono + DM Sans · Dark theme · © 2026 Sethu S*
