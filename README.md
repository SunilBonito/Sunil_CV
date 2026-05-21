# Sunil Kumar CR — Interactive CV

A clean, professional, interactive CV that lives on the web.

**Live URL (once you publish):** `https://sunilbonito.github.io/cv/`

---

## How to publish it (15 minutes, one time)

You already use GitHub Pages for `sunilbonito.github.io/ec-audit`, so this is the same workflow.

### Step 1 — Create the repository
1. Go to **github.com** and sign in as `sunilbonito`
2. Click the **+** icon (top right) → **New repository**
3. Repository name: `cv`
4. Set to **Public**
5. Tick **Add a README file**
6. Click **Create repository**

### Step 2 — Upload the CV files
1. Inside the new `cv` repo, click **Add file → Upload files**
2. Drag in **`index.html`** (this file)
3. Optional but recommended: drag in a square photo of yourself, **named exactly `photo.jpg`**
4. Scroll down → click **Commit changes**

### Step 3 — Turn on GitHub Pages
1. In the repo, go to **Settings** (top tab) → **Pages** (left menu)
2. Under **Source**, pick **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`, click **Save**
4. Wait ~1 minute → live at **`https://sunilbonito.github.io/cv/`**

Share that link on LinkedIn, in emails, on your resume PDF, anywhere.

---

## How to update it later

Anytime you want to edit a project, change a description, or add a new role:

1. Open `index.html` in the `cv` repo on GitHub
2. Click the pencil icon (Edit)
3. Find the section, edit the text directly
4. Scroll down → **Commit changes**
5. Refresh your live URL in 30 seconds — done

---

## Replacing the SVG mockups with real screenshots (optional)

The six project cards currently show clean SVG mockups that visually represent each tool — task list, dashboard with bars and donut, NPS trend, sales analytics, scanner phone, branded email.

If you want to use real screenshots instead, just upload PNG files with these exact names to the same `cv` repo:

| Project | File name |
|---|---|
| iLab Task Manager | `ilab-tasks.png` |
| Experience Centre Audit System | `ec-audit.png` |
| NPS Intelligence Dashboard | `nps.png` |
| PKO Sales Dashboard | `pko.png` |
| Material Audit Scanner | `scanner.png` |
| iLab Email Template System | `email.png` |

Recommended image size: **640 × 360 px (16:9 aspect ratio)** or larger. Crop a clean screenshot of each tool — the CV will automatically replace the SVG mockup with your image. If a file isn't found, the SVG stays. So you can replace them one at a time at your own pace.

---

## What's interactive about it

- **Tap any project card** to expand and see the full feature list
- **Sticky sidebar** with section nav — click to jump
- **Mobile menu** — on phones, sidebar slides in from the left when you tap the menu button
- **Save as PDF button** (bottom right) — opens print dialog with a clean print layout
- **Fully responsive** — phone, tablet, desktop all handled
- **Live SVG mockups** for each project — visual previews built right into the page

---

## What's on the CV

1. **Profile** — updated summary with four highlight metrics
2. **Experience** — Bonito Designs (Category Manager → Catalog Manager), Myntra Jabong, Myntra Designs
3. **Projects & Initiatives** — six cards with SVG mockups, stack badges, expandable details:
   - iLab Department Task Manager (React PWA)
   - Experience Centre Audit System (multi-location dashboard)
   - NPS Intelligence Dashboard
   - PKO Sales Dashboard
   - Material Audit Scanner (QR-based)
   - iLab Email Template System
4. **Core Competencies** — 12-tile grid
5. **Technical Skills** — split across four blocks (web/app dev, data/hosting, design/ecom, productivity)
6. **Education** — same as before

---

## Tech under the hood

- Pure HTML, CSS, and a tiny bit of JavaScript — no build step, no framework
- Two Google Fonts (Fraunces for headings, Inter for body) loaded from Google Fonts CDN
- Fully self-contained — no external dependencies, no API calls, no tracking
- SVG mockups embedded inline so they load instantly

You can open `index.html` directly in any browser to preview before pushing.
