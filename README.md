# Shivang Rana — Portfolio Website

A bold, dark-themed personal portfolio built with pure HTML, CSS & JavaScript.
No frameworks, no build steps — just open and go.

---

## 📁 Project Structure

```
shivang-portfolio/
├── index.html          ← Main HTML file (all sections)
├── css/
│   └── style.css       ← All styles, variables, responsive
├── js/
│   └── main.js         ← Navbar, animations, form, scroll
├── assets/             ← Put your photo here (photo.jpg)
└── README.md
```

---

## 🚀 Getting Started in VS Code

### Step 1 — Open the project
```
File → Open Folder → select shivang-portfolio/
```

### Step 2 — Install Live Server (one-time setup)
- Press `Ctrl+Shift+X` to open Extensions
- Search: **Live Server** by Ritwick Dey
- Click Install

### Step 3 — Run locally
- Right-click `index.html` in the Explorer panel
- Click **"Open with Live Server"**
- Your portfolio opens at `http://127.0.0.1:5500`

---

## ✏️ What to Update

Open `index.html` and search for these comments to fill in your details:

| Comment tag | What to add |
|---|---|
| `<!-- ADD: Your school name here -->` | Class X / XII school name |
| `<!-- ADD: Percentage / Grade -->` | Your board exam marks |
| `<!-- ADD: Describe your second project -->` | Project 2 name + description |
| `<!-- ADD: Describe your data analytics project -->` | Project 3 details |
| `<!-- ADD: Replace shivang@email.com -->` | Your real email address |

### Add your photo
1. Copy your photo to the `assets/` folder — name it `photo.jpg`
2. In `index.html`, find the `avatar-box` div and replace:
   ```html
   <div class="avatar-placeholder">SR</div>
   ```
   with:
   ```html
   <img src="assets/photo.jpg" alt="Shivang Rana" />
   ```

---

## 🌐 Deploy for Free (GitHub Pages)

1. Push this folder to a GitHub repository
2. Go to repo **Settings → Pages**
3. Source: **Deploy from branch → main → / (root)**
4. Your site goes live at: `https://shivangrana1.github.io/portfolio/`

---

## 🎨 Customization

All colors are CSS variables in `css/style.css` at the top:

```css
:root {
  --hot:    #FF3CAC;   /* Pink/magenta accent */
  --gold:   #F9CB28;   /* Gold accent */
  --cyan:   #00E5FF;   /* Cyan accent */
  --purple: #7B2FFF;   /* Purple accent */
}
```

Change any value and the whole site updates instantly.

---

Built with ❤️ by Shivang Rana
