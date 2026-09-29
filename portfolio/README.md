# Ansilin Kumar S M — personal website

One static HTML file (`public/index.html`, about 30 KB, about 7 KB compressed).
No frameworks, no web fonts, no images to download, no animations, and no
external requests. It fits easily within Firebase Hosting's free Spark plan.

## Preview locally

Open `public/index.html` in a browser.

## Deploy to Firebase Hosting (free)

One-time setup:

```bash
npm install -g firebase-tools
firebase login
```

Then, from this `portfolio/` folder:

```bash
firebase use --add            # pick your Firebase project
firebase deploy --only hosting
```

The site is served at `https://<project-id>.web.app`.

## Editing

Change the text directly in `public/index.html` and deploy again. Each section
(`#experience`, `#publications`, `#projects`, …) is a plain HTML block.
