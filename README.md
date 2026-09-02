# Learn Dzongkha — Site Files

## Adding your Row 1 audio

Drop your 8 recorded MP3 files into the `audio/` folder, using these exact filenames (matching what's already wired into `lessons/lesson-04.html`):

- 01-ka.mp3
- 01a-ka-wa.mp3
- 02-kha.mp3
- 02a-kha.mp3
- 03-ga.mp3
- 03a-gong.mp3
- 04-nga.mp3
- 04a-nga.mp3

Once they're in that folder, open `lessons/lesson-04.html` in a browser — the players will work immediately, no code changes needed.

## Viewing the site locally

Just double-click `index.html` to open it in your browser. Every link and audio file will work as long as the folder structure stays intact (don't move files between folders without updating the paths).

## Publishing it for free — GitHub Pages (recommended)

1. Create a free account at github.com if you don't have one.
2. Create a new repository (e.g. `learn-dzongkha`).
3. Upload all these files/folders, keeping the same structure (`index.html`, `css/`, `lessons/`, `audio/`).
4. Go to the repo's **Settings > Pages**, set the source branch to `main` (or `master`) and folder to `/root`.
5. GitHub gives you a live URL like `https://yourusername.github.io/learn-dzongkha/` within a minute or two.

## Publishing it for free — Netlify (drag-and-drop, no Git needed)

1. Go to app.netlify.com and sign up free.
2. Drag the whole site folder onto the "Deploy manually" area of the dashboard.
3. Netlify gives you a live URL instantly, and lets you set a custom subdomain for free.

## Adding new lessons going forward

Copy `lessons/lesson-04.html` as a template for future lessons (it has the letter-card and audio-row patterns already built), then:
1. Update the `<title>`, heading, and content.
2. Add a new `<li>` entry to `learn.html` and `index.html` linking to it.
3. Add any new audio files to the `audio/` folder.

## Structure

```
index.html          — homepage
learn.html           — full lesson index
about.html           — your personal story
culture.html         — culture notes (placeholder, ready for content)
css/style.css        — all site styling
lessons/lesson-01.html  — Why Learn Dzongkha?
lessons/lesson-02.html  — The Roadmap
lessons/lesson-03.html  — The 30 Consonants
lessons/lesson-04.html  — Row 1 (ka, kha, ga, nga) with audio
audio/               — put your recorded MP3s here
```
