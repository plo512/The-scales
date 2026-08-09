# The Scales — Modes, Scales & Boxes

> Characterize every scale and mode, with fretboard diagrams, pentatonic boxes, and audio — for any root.

Part of a five-app practice system. This is the scale & mode encyclopedia that feeds the others.

## What's inside
- **Scales** — pick any root, then browse all thirteen scales: the seven **major-scale modes** (Ionian, Dorian, Phrygian, Lydian, Mixolydian, Aeolian, Locrian), **major/minor pentatonic and blues**, and **harmonic minor, melodic minor, and Phrygian dominant**. Each shows its note names, degree formula, W/H step pattern, mood, characteristic note, what to play it over, a **fretboard diagram**, and a **Hear it** button
- **Chords** — harmonizes the current scale into its diatonic chords: stacks **1‑3‑5** (and 7ths) on every degree, names each chord, shows its Roman numeral / Nashville number, its notes, its tones on the neck, and the common progressions in the key
- **Boxes** — the chosen pentatonic (major or minor) laid out as the **five movable positions** across the neck, transposing live with the root
- **Guide** — how scales and modes actually work: formulas, the parent-scale idea, relative vs parallel thinking, characteristic notes, and how pentatonics fit inside the modes
- Works **offline**

## Live app
https://plo512.github.io/the-scales/  *(update this link if your repo has a different name)*

## Install on your phone (Android / Chrome)
1. Open the live link in **Chrome** (a normal tab).
2. Tap **⋮ menu → Install app** (or the in-app **Install** button).
3. It lands on your home screen. Tap once to unlock sound.

## Updating
Upload a new `index.html` over the old one and commit. This app ships with a **network-first** service worker, so new versions appear automatically when you're online. To force a refresh, bump the version string on line 1 of `sw.js`.

## Tech
Single-file HTML/CSS/JS progressive web app (PWA). No build step or dependencies. Scale note names use sharp spellings; interval/degree labels are the primary reference. Offline via a service worker.

## Files
`index.html` · `manifest.json` · `sw.js` · `icon-192.png` · `icon-512.png` · `apple-touch-icon.png`

## The full set
- **The Hour** — session timer
- **The Plan** — daily guide + full reference
- **The Neck** — fretboard note memorization game
- **The Language** — phrasing, CAGED, Nashville numbers & the circle of fifths
- **The Scales** — modes, scales & pentatonic boxes (this app)
