# Between the Lines — Setup Guide

## Files in this package

```
index.html          ← your public archive homepage
admin/index.html    ← your private admin panel
fics/index.json     ← your fic data (starts empty)
netlify.toml        ← Netlify config (don't edit)
```

---

## One-time setup (15 minutes, no coding)

### Step 1 — Put files on GitHub

1. Go to github.com and sign in
2. Click the **+** icon → **New repository**
3. Name it `stones-archive`, set to **Public**, click **Create repository**
4. Click **uploading an existing file**
5. Drag ALL these files in — keeping the folder structure intact
6. Click **Commit changes**

### Step 2 — Deploy on Netlify

1. Go to netlify.com → **Add new site** → **Import an existing project**
2. Choose **GitHub**, find `stones-archive`
3. Leave all build settings blank → click **Deploy site**
4. After ~1 minute your site is live at a URL like `jolly-wave-123.netlify.app`

That's it. Your archive is live.

---

## Your daily workflow (adding a fic)

1. Go to `yoursite.netlify.app/admin`
2. Fill in the form and click **Publish**
3. Click **Setup Guide** in the sidebar → **Export fics.json**
4. Go to your GitHub repo → click `fics` folder → click `index.json` → click the pencil (edit) icon → paste the exported content → **Commit changes**
5. Wait ~30 seconds → your site updates automatically

---

## Formatting your fic body

The body field supports basic markdown:

| You type       | Result         |
|----------------|----------------|
| `*italic*`     | *italic*       |
| `**bold**`     | **bold**       |
| `---`          | scene break    |
| blank line     | new paragraph  |
