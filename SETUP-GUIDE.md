# Family Wallet — Installation Guide

## What you're setting up
A free, private web app that installs on both your and your husband's phones like a native app.

---

## Step 1 — Create a free GitHub account
1. Go to **github.com**
2. Click **Sign up** — use any email
3. Choose the **Free** plan

---

## Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `family-wallet`
3. Set to **Public** (required for free GitHub Pages)
4. Click **Create repository**

---

## Step 3 — Upload the app files
1. In your new repository, click **uploading an existing file**
2. Upload ALL these files (drag them all at once):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - The `icons/` folder (icon-192.png and icon-512.png)
3. Click **Commit changes**

---

## Step 4 — Turn on GitHub Pages
1. In your repository, go to **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** / Folder: **/ (root)**
5. Click **Save**
6. Wait ~2 minutes, then your app is live at:
   **`https://YOUR-USERNAME.github.io/family-wallet`**

---

## Step 5 — Install on YOUR iPhone
1. Open **Safari** (must be Safari, not Chrome)
2. Go to your app URL above
3. Tap the **Share** button (box with arrow at bottom)
4. Tap **"Add to Home Screen"**
5. Name it **Family Wallet** → tap **Add**
6. ✅ It now appears on your home screen like a real app!

---

## Step 6 — Share with your husband
1. Send him the URL: `https://YOUR-USERNAME.github.io/family-wallet`
2. He opens it in **Safari** on his iPhone
3. Same steps: Share → Add to Home Screen → Add
4. ✅ He has the same app!

---

## ⚠️ Important note on data
Each phone saves its own transaction data locally. If you both upload statements, the data stays on each device separately. This is actually fine for your workflow — whoever uploads the weekly statements will have the full picture.

**To share data between phones:** Whoever uploads the PDFs each Sunday becomes the "tracker" — the other person can check in anytime on that same phone, or you can both upload the same statement to keep both phones in sync.

---

## Sunday Reminder setup
The app has a **Send Reminder** button on the dashboard that emails you via Gmail as a reminder to upload. For automatic weekly reminders every Sunday, you can also set a repeating reminder in your iPhone Reminders app:
- "Upload bank statements to Family Wallet"
- Repeats: Every week on Sunday

---

## Need help?
The app works on any modern browser. If you run into issues:
- Make sure you're using **Safari** on iPhone to install (Chrome doesn't support Add to Home Screen on iOS)
- On Android, use **Chrome** — it shows an "Install App" popup automatically
