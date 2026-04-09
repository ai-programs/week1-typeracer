# 🌐 Publish Your Game to the Internet

Right now your game only lives inside Codespaces. You can play it, but nobody else can. Let's fix that.

By the end of this guide, your game will have its own URL that you can share with anyone — friends, family, the whole world.

We'll use **GitHub Pages** — a free feature that turns your code into a live website.

---

## Enable GitHub Pages

This is the step that makes your code into a live website.

1. Go to your repository on GitHub (the one created from the template)
2. Click **Settings** (the tab at the top, not the gear icon)
3. In the left sidebar, click **Pages**
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, select **main** and **/ (root)**
6. Click **Save**

Wait 1-2 minutes. GitHub is building your site.

---

## Visit Your Site

Your game is now live at:

```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

Bookmark it. Share it. Send it to your friends. This is YOUR game, live on the internet. 🎉

---

## Updating Your Game Later

Every time you make changes and want to update the live version:

1. Ask Cline to commit your changes: "Commit my changes with message 'Added new feature'"
2. Ask Cline to push to GitHub: "Push my code to GitHub"

GitHub Pages will automatically update within a minute or two.

---

## Troubleshooting

**"The page shows a 404"**
- Check that you selected the right branch (`main`) and folder (`/ root`) in GitHub Pages settings
- Make sure your file is called `index.html` (not `Index.html` or `home.html`)
- Wait a few minutes — it can take a bit the first time

**"Cline says authentication failed"**
- You need a Personal Access Token instead of your password. Ask Arjun or Sérgio for help.

**"I see my files on GitHub but the site doesn't work"**
- Go to Settings → Pages and check that the source is set correctly
- Make sure the repo is **Public**, not Private

**"My Firebase data doesn't work on the live site"**
- It should work! Firebase doesn't care where your site is hosted. If it doesn't, check the browser console (F12) for errors.
