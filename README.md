# Anthropology
https://communications-anthropology.vercel.app/

# How Culture Shapes the Way We Speak

**What was said vs. what was meant.** An interactive, single-page website and poster on the anthropology of communication, built for FAST University (National University of Computer & Emerging Sciences).

---

## About the project

Words rarely mean only what they say. This project explores how culture shapes language, gesture, space and silence, and what is lost when those signals are misread. The site turns the topic into an experience: a cinematic intro, interactive demonstrations and a short game.

### Topics covered

1. **The words we choose, the meaning we hide:** high-context and low-context communication, saving face, and the Sapir–Whorf idea of language and thought.
2. **Gestures, glances and personal space:** Hall's four proxemic zones, eye contact, gestures and touch.
3. **The power of silence:** what silence can mean, the Japanese idea of *ma*, and Keith Basso's work on Western Apache silence.
4. **The cost of misleading cultural communication:** the impact in business, healthcare, education and diplomacy, and cultural humility as the cure.

---

## Team

**Presented by**

- Hammad Ahmed
- Arsum Ali
- Zunair Azeem
- Taha Islam

**Under the supervision of**

Dr. Shahnawaz Muhammad Khan
PhD (Int. Rel.), FUUAST, Islamabad
Instructor

---

## Features

- **Cinematic intro:** a title card with an "Enter the experience" button, followed by a curtain reveal.
- **Live "said vs. meant" hero:** a phrase is typed, struck through, and its real meaning appears.
- **Decoder:** pick a common phrase and see what it often really means.
- **Proxemics slider:** change the distance between two people and watch the zone change from intimate to public.
- **Silence timer:** stay silent and see how the feeling of the pause changes over time.
- **Game, "Decode the Culture":** six real-life situations, a 15-second timer, streaks, a score and a final rank (Fresh Tourist, Curious Traveller, Cultural Diplomat, Master Decoder).
- **Motion design:** split-text reveals, scroll parallax, 3D tilt, magnetic buttons, a custom cursor and gold particle effects.
- **Team section:** photo frames for the instructor and each presenter.
- **Accessible by default:** keyboard focus styles, responsive layout, and animations switch off automatically for users who prefer reduced motion.

---

## Project structure

```
anthropology/
├── index.html      # The whole website (HTML, CSS and JavaScript in one file)
├── photos/         # Optional team photos (see below)
│   ├── instructor.jpg
│   ├── hammad.jpg
│   ├── arsum.jpg
│   ├── zunair.jpg
│   └── taha.jpg
└── README.md
```

There is no build step and no dependencies to install. The university logo is embedded inside `index.html`, so the file works on its own.

---

## Run locally

1. Download or clone the repository.
2. Double-click `index.html` to open it in a browser.

Fonts (Fraunces and Manrope) load from Google Fonts, so an internet connection gives the intended look. Without one, the site falls back to Georgia and Arial.

---

## Add team photos

Put square or portrait photos in the `photos/` folder using the exact file names above (`.jpg`). When a photo exists, it appears inside the gold frame automatically. When it is missing, the frame shows the person's initials instead.

---

## Deploy for free

### Option 1: Vercel

1. Push this project to GitHub.
2. Import the repository in [Vercel](https://vercel.com) and deploy. No build settings are needed.
3. Use the free `.vercel.app` link that Vercel gives the project.
4. If the link asks for a login, turn off Deployment Protection for the project so everyone can open it.

### Option 2: GitHub Pages

1. Open the repository **Settings**, then **Pages**.
2. Under **Source**, choose the main branch and the root folder.
3. Save, then open the link GitHub shows.

---

## Poster

A printable A3 poster, `Culture_and_Communication_Poster.pptx`, accompanies the website. It carries the same four topics, the team, the supervisor and a QR code that points to the website. Text, photos and the QR code are all editable in PowerPoint.

---

## Built with

- HTML, CSS and vanilla JavaScript (no frameworks)
- Google Fonts: Fraunces and Manrope

---

## Key ideas and sources

- Edward T. Hall: high-context and low-context cultures, and proxemics
- Penelope Brown and Stephen Levinson: politeness theory and "face"
- Edward Sapir and Benjamin Lee Whorf: linguistic relativity
- Keith Basso: silence in Western Apache culture

---

## Notes

This is an academic project created for coursework at FAST University. The examples in the decoder and the game are simplified illustrations. Real meaning always depends on tone, relationship and context.
