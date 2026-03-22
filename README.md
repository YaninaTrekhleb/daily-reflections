# 🪶 Journal

A beautiful, private daily journaling app with psychologist-backed prompts, photo collages, and mood tracking.

**[→ Try it live](https://yourusername.github.io/journal/)**

## Features

- **Guided prompts** — Four rotating question sets inspired by CBT, gratitude journaling, and expressive writing techniques
- **Photo collages** — Add up to 6 photos per entry to capture your day visually
- **Mood tracking** — Tag entries with 8 moods (Inspired, Happy, Calm, Reflective, Sad, Frustrated, Anxious, Tired) and search by mood later
- **Full-text search** — Find any entry by keyword, mood, or prompt content
- **Day streaks & word count** — Track your consistency and writing volume
- **Export/Import** — Back up your journal as JSON and restore it anytime
- **Works offline** — Installable as a PWA on iPhone, Android, and desktop
- **100% private** — All data stays in your browser's localStorage. Nothing is sent anywhere.

## Install on iPhone

1. Open the app in Safari
2. Tap the Share button (↑)
3. Tap **"Add to Home Screen"**
4. Done — it works like a native app, even offline

## Deploy to GitHub Pages

1. Create a new repo on GitHub
2. Upload all files from this folder (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`)
3. Go to **Settings → Pages → Source → Deploy from a branch → main → / (root)**
4. Your journal will be live at `https://yourusername.github.io/repo-name/`

## The Prompts

The journal rotates through 5 sets of 4 prompts, drawing from:

- **CBT (Cognitive Behavioral Therapy)** — Identifying thoughts, reframing, noticing patterns
- **Gratitude journaling** (Seligman) — What went well and why
- **Expressive writing** (Pennebaker) — Processing emotions through free writing
- **Self-compassion** — What you need, how you're growing

You don't have to answer all prompts — fill in what feels right, skip the rest.

## Tech

Pure HTML/CSS/JS — no build step, no dependencies, no framework. Just open `index.html`.

## License

MIT — use it however you like.
