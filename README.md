# Daily Reflections

A private, offline-first daily journal that lives in your browser. No accounts, no cloud, no ads. Just you and your thoughts.

**[Open Daily Reflections](https://yaninatrekhleb.com/daily-reflections/)**

<p align="center">
  <img src="daily-reflections-live.gif" alt="Daily Reflections Demo" width="300">
</p>

---

## Why this journal is different

Most journaling apps want your email, push you toward a subscription, or store your private thoughts on someone else's server. Daily Reflections does none of that.

- **Your data never leaves your device.** Everything is stored in your browser's localStorage. There is no server, no database, no analytics. Nobody can read your journal — not even us.
- **It works offline.** Install it on your phone and write on the train, on a plane, in bed at 2am. No internet needed.
- **Simple prompts, not blank pages.** Instead of staring at an empty screen, you get structure: what went well, what didn't, one closing thought, and a rotating bonus prompt. Fill in what feels right, skip the rest.
- **See your patterns.** Mood trends, good-vs-bad ratios, your most-used word, journaling consistency heatmap, and "Then vs Now" — showing what you wrote exactly 1 week, 1 month, or 1 year ago.
- **No account required.** Open the link. Start writing. That's it.

---

## Features

**Writing**
- 3-5 good things + 3-5 bad things (expandable)
- Closing thought
- 55 rotating bonus prompts
- Free-write section
- Up to 6 photos per entry
- 7 mood options (Happy, Calm, Reflective, Sad, Angry, Anxious, Tired)

**Navigation**
- Scrollable date strip (swipe through weeks)
- Monthly calendar picker (jump to any past date)
- Edit past entries

**Insights (Mood tab)**
- Weekly summary card (days journaled, words written, good:bad ratio, your word)
- Mood bar chart with animated pill bars
- Mood trend line (canvas chart mapping emotions over time)
- Good vs Bad balance per day
- GitHub-style journaling consistency heatmap
- Daily mood emoji timeline
- "Then vs Now" — resurfaces what you wrote 1 week, 1 month, or 1 year ago

**Extras**
- Full-text search across all entries
- Monthly PDF export
- JSON backup & import
- Weekly backup reminder
- Day streak & word count stats
- Hand-drawn SVG illustrations (tea cup, moon & stars, letter, vine dividers, vase with flowers)

---

## Install as an app

### iPhone / iPad
1. Open [yaninatrekhleb.com/daily-reflections](https://yaninatrekhleb.com/daily-reflections/) in **Safari**
2. Tap the **Share** button (the square with an arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — the app icon appears on your home screen
5. Open it from there — it runs fullscreen like a native app, works offline

### Android
1. Open the link in **Chrome**
2. Tap the **three dots menu** (top right)
3. Tap **"Add to Home screen"** or **"Install app"**
4. Done — works offline from your home screen

### Desktop (Chrome / Edge)
1. Open the link in Chrome or Edge
2. Click the **install icon** in the address bar (or Menu > "Install Daily Reflections")
3. The app opens in its own window, works offline

---

## Privacy

- All data is stored locally in your browser's `localStorage`
- Nothing is sent to any server — ever
- No cookies, no tracking, no analytics
- If you clear your browser data, your entries are gone (that's why the backup button exists)
- Other people opening the same URL see a completely empty journal — they cannot access yours

---

## Back up your data

Your journal lives only in your browser. If you switch devices, clear browser data, or uninstall the app, your entries will be lost. To prevent this:

1. Go to the **sidebar** (desktop) or **Entries** tab (mobile)
2. Tap **Backup** — downloads a `.json` file with all your entries
3. Save it to iCloud, Google Drive, or wherever you keep important files
4. To restore: tap **Import** and select your backup file

The app will gently remind you if you haven't backed up in 7 days.

---

## Tech

Zero dependencies. No build step. No framework. One HTML file + a service worker + a manifest.

- Pure HTML / CSS / JavaScript
- Canvas API for mood trend charts
- Service Worker for offline caching
- Web App Manifest for PWA install
- localStorage for data persistence
- Inline SVG illustrations (original hand-drawn style)

---

## License

MIT — use it however you like.
