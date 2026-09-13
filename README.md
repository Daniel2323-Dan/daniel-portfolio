# John Daniel C. Paroligan — Portfolio

A single-page Virtual Assistant portfolio. One file, no build step, no dependencies.
Send the live link to employers — or just the `index.html` file.

---

## ✏️ How to edit (everything is in one place)

Open [`index.html`](index.html) in any text editor (Notepad, Notepad++, VS Code — anything).
Scroll to the block that starts with **`const CONFIG = {`** (it's clearly marked with a
big box comment, search for "EDIT YOUR SITE HERE").

In there, in one place, you can change:

| Want to change… | Edit this field |
|---|---|
| Email shown on the buttons | `email` |
| LinkedIn link | `linkedin` |
| Facebook link | `facebook` |
| WhatsApp number | `whatsapp` |
| OnlineJobs.ph profile | `onlinejobs` |
| Your name in the headline | `shortName` |
| Tagline under your name | `tagline` |
| "About" paragraph | `about` |
| Service cards on page | `services` |
| Skill chips, grouped | `skills` |
| Work history | `experience` |
| The "side builds" cards | `portfolio` (add/remove freely; set `showPortfolio: false` to hide the whole section) |

Keep the `" "` quotes and the `,` commas where they are. Save the file — that's it.

### Add your photo (optional)
1. Create a folder named `assets` next to `index.html`.
2. Put your photo inside it and name it **`headshot.jpg`**.
3. Reload the page — the "JD" monogram tile in the hero becomes your photo.
   (No photo? The stylized "JD" tile shows instead — it still looks intentional.)

---

## 🚀 How to deploy (make it live)

The whole site is one file, so publishing it is a 1-minute job — you don't need any
server or build tools.

### Option A — Netlify drag & drop (fastest, free, recommended)
1. Go to <https://app.netlify.com/drop>
2. Sign in (free, with email / GitHub / Google).
3. Drag the **whole `portfolio` folder** (or just `index.html`) onto the page.
4. Netlify instantly gives you a live URL like `https://random-name.netlify.app`.
   That's your shareable portfolio link.
5. Dragging the folder again anytime = a new version goes live.

### Option B — GitHub Pages (needs a free GitHub account)
1. Create a repo at <https://github.com/new> (public).
2. Upload `index.html` (+ `assets/` if you added a photo) to the repo.
3. Repo **Settings → Pages → Source: main branch → Save**.
4. After a minute, your URL is `https://<your-username>.github.io/<repo-name>/`.

### Option C — any static host
`index.html` has zero external requirements beyond itself: upload to Vercel,
Cloudflare Pages, your own hosting, or even email the file directly to an employer
(it opens fine from disk).

---

## ✅ Pre-flight check before sending to employers

- All contact links are already wired to your real profiles — just review the copy.
- Open the page, scroll all 6 sections, tap every button (Email, LinkedIn, Facebook, WhatsApp, OnlineJobs.ph).
- Test on your phone too (it's responsive).

## 📁 Files
```
portfolio/
  index.html    ← the entire website
  assets/       ← (optional) put headshot.jpg here
  README.md     ← this file
```