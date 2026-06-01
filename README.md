# 🧑‍💻 Moe Kyaw Aung — Portfolio Website

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square&logo=github)](https://dev-moe-kyawaung.github.io/mka-portfolio/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Certificates](https://img.shields.io/badge/Certificates-82%2B-lime?style=flat-square)](https://www.programminghub.io/)

> Personal portfolio showcasing 82+ verified certificates across 9 technology domains from Programming Hub.

---

## 🌐 Live Demo

**👉 [https://dev-moe-kyawaung.github.io/mka-portfolio/](https://dev-moe-kyawaung.github.io/mka-portfolio/)**

---

## ✨ Features

- 🖥️ **3-Column App Layout** — Sidebar navigation, profile panel, certificate grid
- 🔍 **Real-time Search** — Filter certificates instantly by name
- 🏷️ **Category Filter** — Browse by 9 technology domains
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop
- ✅ **Verified Links** — Each certificate links directly to Programming Hub for verification
- 🖼️ **Embedded Photo** — No external image files needed
- ⚡ **Zero Dependencies** — Pure HTML, CSS, JavaScript — no frameworks, no build step

---

## 📁 Project Structure

```
mka-portfolio/
├── index.html          # Main portfolio (self-contained)
├── .nojekyll           # Disables Jekyll on GitHub Pages
├── README.md           # This file
└── assets/             # Optional: replace embedded photo with file
    └── profile.jpg     # (optional — see Customization below)
```

> **Note:** `index.html` is fully self-contained. The profile photo is embedded as Base64 — no separate image file is required.

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Create the repository
```
Repository name:  mka-portfolio
Visibility:       Public
```

### Step 2 — Upload files
Upload these files to the repo root:
```
index.html
.nojekyll
README.md
```

### Step 3 — Enable GitHub Pages
```
Settings → Pages → Source → Deploy from branch
Branch: main  /  Folder: / (root)
→ Save
```

### Step 4 — Done ✅
Your site will be live at:
```
https://<your-github-username>.github.io/mka-portfolio/
```

---

## ✏️ Customization Guide

### 🎨 Change Colors
Open `index.html` and edit the CSS variables at the top:
```css
:root {
  --lime:   #c6f135;   /* Main accent — change to any color */
  --cyan:   #35f1c6;   /* Secondary accent */
  --bg:     #0b0e17;   /* Page background */
  --panel:  #111520;   /* Sidebar / panel background */
}
```

### 📸 Replace Profile Photo
**Option A — Keep embedded (current):**
No action needed. Photo is already embedded in the HTML.

**Option B — Use external file (smaller HTML):**
1. Add your photo as `assets/profile.jpg`
2. In `index.html`, find:
   ```html
   <img class="pp-photo" src="data:image/jpeg;base64,..." />
   ```
3. Replace the entire `src` value with:
   ```html
   <img class="pp-photo" src="assets/profile.jpg" />
   ```

### 📝 Update Personal Info
Search for these placeholders in `index.html` and replace:

| Placeholder | Replace with |
|---|---|
| `your@email.com` | Your real email address |
| `Dev-moe-kyawaung` | Your GitHub username |
| `moekyawaung2026` | Your Gravatar / website username |
| `Full-Stack Developer` | Your actual role/title |

### ➕ Add New Certificates
Find the relevant `cgroup` section in `index.html` and add a new card:
```html
<a class="cc" href="https://www.programminghub.io/certificate?id=YOUR_CERT_ID"
   target="_blank" data-cat="Category Name" data-name="certificate name lowercase">
  <span class="cc-badge">VERIFIED</span>
  <span class="cc-name">Certificate Name</span>
  <span class="cc-foot">
    <span class="cc-date">📅 Month DD, YYYY</span>
    <span class="cc-link">View ↗</span>
  </span>
</a>
```

---

## 🏆 Certificate Domains

| Domain | Count |
|---|---|
| ⌨️ Programming Languages | 13 |
| 🌐 Web Development | 13 |
| 📱 Mobile & App Dev | 7 |
| 🗄️ Databases | 6 |
| 🤖 AI & Data Science | 11 |
| 🔐 Security & DevOps | 10 |
| ⛓️ Blockchain | 4 |
| 🛠️ Software Engineering | 7 |
| 📈 Marketing & Business | 11 |
| **Total** | **82+** |

---

## 🛠️ Built With

- **HTML5** — Structure
- **CSS3** — Styling (CSS Grid, Flexbox, Custom Properties)
- **Vanilla JavaScript** — Search & filter logic
- **Google Fonts** — Space Grotesk, Space Mono
- **Programming Hub** — Certificate platform

---

## 📜 License

This project is open source under the [MIT License](LICENSE).

---

## 📬 Contact

- **GitHub:** [github.com/Dev-moe-kyawaung](https://github.com/Dev-moe-kyawaung)
- **Email:** your@email.com

---

<p align="center">Made with ❤️ by Moe Kyaw Aung</p>
