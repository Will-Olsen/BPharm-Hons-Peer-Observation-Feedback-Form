# Peer Observation Feedback Form

A clean, print-friendly HTML form for collecting structured peer observation feedback in the BPharm(Hons) program.

## Features

✅ **Responsive Design** – Works on desktop, tablet, and mobile  
✅ **Print Optimized** – Beautiful print layout that hides controls and formats for paper  
✅ **No Dependencies** – Pure HTML + CSS, no frameworks or libraries required  
✅ **GitHub Pages Ready** – Deploy directly from your repository  

## Form Sections

1. **Positive Aspects** – Pedagogical design, student engagement, blended learning approach
2. **Areas for Improvement** – Engagement issues, UQ Extend material cross-over
3. **Opportunities for Change** – Alternative approaches, novel teaching methods, best practices
4. **Key Takeaways** – Ideas the observer wants to try in their own teaching

Plus metadata fields for observer name, date, presenter, and session/unit.

## Quick Start (Local)

### Option 1: Open in Browser
Simply open `index.html` in your web browser:
```bash
open index.html
```

### Option 2: Live Server (Python)
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

### Option 3: Live Server (Node.js)
If you have Node.js installed:
```bash
npx http-server
```

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com/new](https://github.com/new) and create a new repository
2. Name it whatever you like (e.g., `peer-observation-form`)
3. Make it **Public** so it's accessible online
4. Click **Create repository**

### Step 2: Upload Files
You have two options:

**Option A: Via GitHub Web Interface**
1. Click **Add file** → **Upload files**
2. Drag and drop (or select) your files:
   - `index.html`
   - `styles.css`
3. Commit the changes
4. Wait ~1 minute for the site to deploy

**Option B: Via Command Line (Git)**
```bash
# Navigate to your project directory
cd /path/to/your/form

# Initialize git
git init

# Add remote (replace USERNAME and REPO_NAME)
git remote add origin https://github.com/USERNAME/REPO_NAME.git

# Stage, commit, and push files
git add .
git commit -m "Initial commit: peer observation feedback form"
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/root** folder
5. Click **Save**
6. Wait ~1-2 minutes for deployment
7. Your site will be live at `https://USERNAME.github.io/REPO_NAME`

### Step 4: Share the Link
Your form is now live and ready to use! Share the URL with observers.

## Usage

1. **Fill the Form** – Observer enters their name, date, presenter, and session info
2. **Answer Questions** – Complete each of the four feedback sections
3. **Print or Save** – Click the **Print** button to:
   - Print directly to paper (forms automatically hide buttons and optimize layout)
   - Save as PDF (use "Save as PDF" in the print dialog)
4. **Submit** – Email the PDF or printed form to the relevant coordinator

## Customization

**Change colors:**
- Edit `styles.css` and look for `#0052cc` (the primary blue) – replace with your preferred hex color

**Add/remove fields:**
- Edit `index.html` to add or remove form sections

**Change fonts:**
- Modify the `font-family` property in `styles.css`

**Add institution branding:**
- Update the header text and colors in `index.html` and `styles.css`

## Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## License

Free to use and modify for educational purposes.

---

**Questions?** Check that your repository is public and GitHub Pages is enabled in Settings → Pages.
