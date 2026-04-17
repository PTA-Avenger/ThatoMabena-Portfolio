# Thato Mabena — Portfolio

Personal portfolio website hosted on GitHub Pages.

## 🚀 Deploying to GitHub Pages

1. **Create a new repo** on GitHub named `your-username.github.io`  
   *(or any repo name — see option 2 below)*

2. **Push this file:**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/PTA-Avenger/PTA-Avenger.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**  
   Go to repo **Settings → Pages → Source → Deploy from branch → main → / (root)**

4. **Your site will be live at:**  
   `https://PTA-Avenger.github.io`

---

### Option 2 — Any repo name (e.g. `portfolio`)

If you use a repo name other than `username.github.io`, your site URL will be:  
`https://PTA-Avenger.github.io/portfolio`

No code changes needed — GitHub Pages handles the path automatically.

---

## ✏️ Customising

All content is in a single `index.html` file — no build tools, no dependencies, no Node.js required.

| What to change | Where to find it |
|---|---|
| Name, bio, location | `#hero` and `#about` sections |
| Projects | `.project-card` blocks in `#projects` |
| Skills | `.skill-pill` items in `#skills` |
| Experience | `.exp-item` blocks in `#experience` |
| Contact links | `.contact-links` in `#contact` |
| Colour scheme | `:root` CSS variables at the top |

## 🎨 Colour variables

```css
--teal:    #00d4aa   /* accent / highlights */
--amber:   #f5a623   /* warning tone */
--bg:      #080c14   /* page background */
--white:   #eaf4ff   /* headings */
```
