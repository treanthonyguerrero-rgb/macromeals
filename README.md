# Macro Meals — Legal Pages

This repository hosts the Privacy Policy and Terms & Conditions for the Macro Meals iOS app.

## Pages

- **Privacy Policy:** `privacy.html`
- **Terms & Conditions:** `terms.html`

## Setup Instructions (GitHub Pages)

Follow these steps to get your legal pages live:

### Step 1 — Create a GitHub Account
Go to https://github.com and sign up for a free account if you don't have one.

### Step 2 — Create a New Repository
1. Click the **+** icon in the top right → **New repository**
2. Name it: `macromeals-legal` (or any name you prefer)
3. Set it to **Public** (required for GitHub Pages)
4. Click **Create repository**

### Step 3 — Upload the Files
1. On your new repository page, click **uploading an existing file**
2. Drag and drop `privacy.html`, `terms.html`, and `index.html` into the upload area
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes for the site to deploy

### Step 5 — Get Your URLs
Your pages will be live at:
- `https://YOURUSERNAME.github.io/macromeals-legal/privacy`
- `https://YOURUSERNAME.github.io/macromeals-legal/terms`

Replace `YOURUSERNAME` with your actual GitHub username.

### Step 6 — Update the App
Replace the placeholder URLs in two files:

**OnboardingView.swift** — search for `macromeals.app/terms` and `macromeals.app/privacy` and replace with your GitHub Pages URLs.

**SettingsView.swift** — same search and replace.

Then rebuild and your app will link to the live pages.

## Updating the Pages

To update content:
1. Go to your repository on GitHub
2. Click the file you want to edit (e.g. `privacy.html`)
3. Click the pencil icon to edit
4. Make your changes and click **Commit changes**
5. Changes go live automatically within a minute or two

## Important

Before publishing to the App Store, update the following in the HTML files:
- Replace `privacy@macromeals.app` with your actual contact email
- Replace `legal@macromeals.app` with your actual contact email
- Update the **Effective Date** and **Last Updated** date if needed
- Update the governing law state if you are not in Texas
