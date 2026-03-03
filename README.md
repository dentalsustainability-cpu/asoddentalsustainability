# ASOD Dental Sustainability Club Website

A clean, minimal multi-page website for the ASOD Dental Sustainability Club built with HTML, CSS, and vanilla JavaScript.

## Pages

- **index.html** — Landing page
- **about.html** — About Us
- **board.html** — Executive Board
- **blog.html** — Blog
- **photos.html** — Photo Gallery
- **events.html** — Events

---

## 🚀 How to Deploy with GitHub Pages

Follow these steps to get your website live for free using GitHub Pages.

### Step 1: Create a GitHub Account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2: Create a New Repository
1. Click the **+** icon in the top right → **New repository**
2. Name it: `asod-sustainability` (or any name you like)
3. Set it to **Public**
4. Do **not** check "Initialize this repository with a README" (we'll upload our own files)
5. Click **Create repository**

### Step 3: Upload Your Files
**Option A — Upload via Browser (easiest):**
1. On your new repository page, click **uploading an existing file**
2. Drag and drop ALL the website files:
   - `index.html`
   - `about.html`
   - `board.html`
   - `blog.html`
   - `photos.html`
   - `events.html`
   - `styles.css`
   - `main.js`
   - `README.md`
3. Scroll down and click **Commit changes**

**Option B — Using Git (for developers):**
```bash
git init
git add .
git commit -m "Initial website commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/asod-sustainability.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. In your repository, click **Settings** (top navigation)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, choose **main** and folder **/ (root)**
5. Click **Save**

### Step 5: Visit Your Live Website!
After 1–2 minutes, your site will be live at:
```
https://YOUR_USERNAME.github.io/asod-sustainability/
```

GitHub will show you the exact URL at the top of the Pages settings.

---

## ✏️ How to Edit Your Website

### Update Board Members
Open `board.html` and find the board cards. Replace the placeholder text with real names, roles, and bios. You can also replace the emoji avatars with real photos:

```html
<!-- Replace emoji avatar with an image: -->
<div class="board-avatar">
  <img src="images/name.jpg" alt="Name" style="width:100%; height:100%; object-fit:cover; border-radius:50%;">
</div>
```

### Add Real Photos
1. Create an `images/` folder in your repository
2. Upload your photos there
3. In `photos.html`, replace `<div class="photo-placeholder">🌿</div>` with:
```html
<img src="images/your-photo.jpg" alt="Description" style="border-radius:12px; width:100%; aspect-ratio:1; object-fit:cover;">
```

### Add Blog Posts
Open `blog.html` and duplicate an existing `.blog-card` block, then update the title, description, tag, and date. You can link to a separate HTML file for full post content.

### Update Events
Open `events.html` and edit the `.event-card` blocks — update the month, day, title, description, and location for each event.

### Change Colors
Open `styles.css` and find the `:root` section at the top. You can adjust the color variables:
```css
:root {
  --sage: #8aac8a;       /* main green */
  --beige: #f5f0e8;      /* background */
  --blue: #6e90a8;       /* accent blue */
}
```

---

## 🛠 Tech Stack

- Pure HTML5, CSS3, Vanilla JavaScript
- Google Fonts: Cormorant Garamond + DM Sans
- No frameworks or dependencies required
- Mobile responsive

---

*Made with 🌿 for ASOD Dental Sustainability Club*
