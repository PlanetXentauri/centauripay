 # CentauriPay 🪐 

The Centauri family's shared **To-Do & To-Pay** list — Dreco, Brittany (Mama Bear), Anabella & Orion. Same design as [GSD](https://planetxentauri.github.io/to-do-list/), built for the whole family.

## What's different from GSD

- **Family member pills** at the top — filter everything by Dreco 🪐, Brittany 🐻, Anabella 🌸, or Orion ⭐
- **Assign tasks and bills** to a member, or leave them as **Family** so they show for everyone
- Adding an item while a member pill is selected auto-assigns it to them
- Uses the **same Firebase project** as GSD but its own `cp_` collections — the two apps never mix data, and sync works immediately with zero setup
- To-Do + To-Pay only (no credit tracker)

## Deploy to GitHub Pages (5 minutes)

1. Go to https://github.com/new and create a repo named `centauripay` (public)
2. Upload these files: `index.html`, `logo.png`, `manifest.json`, `icon-192.png`, `icon-512.png`, `README.md`
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save
4. In a minute it's live at: **https://planetxentauri.github.io/centauripay/**
5. Open that URL on everyone's phone → Share → **Add to Home Screen** — it installs like an app

No Firebase setup needed — it reuses your existing `todo-107e0` project.

## Share to CentauriPay 📥

Share a link or text from any app and CentauriPay walks you through: **To-Do or To-Pay? → Who's on it (Planet Centauri / Dreco / Brittany)? → For + category + details** — then it lands in the list with the link attached.

### Android

1. Open the site in **Chrome** → menu (⋮) → **Add to Home screen → Install**
2. That's it — "CentauriPay" now appears in the system **Share** sheet

### iPhone / iPad

iOS doesn't let websites into the share sheet directly, so make a one-time Shortcut (2 minutes, do it on each person's phone):

1. Open the **Shortcuts** app → **+** to create a new shortcut
2. Add the action **URL Encode** and set its input to **Shortcut Input**
3. Add the action **URL** and set it to:
   `https://planetxentauri.github.io/centauripay/?share=` then tap right after the `=` and insert the **URL Encoded Text** variable
4. Add the action **Open URLs**
5. Tap the shortcut name → rename it **CentauriPay** (pick the icon you like)
6. Tap ⓘ (info) → turn on **Show in Share Sheet** → under "Receives", allow **URLs, Safari web pages, and Text**

Now in Safari or any app: **Share → CentauriPay** → the wizard opens and asks To-Do or To-Pay, who it's for, and the details.

