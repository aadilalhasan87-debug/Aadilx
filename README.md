# AADILX — Evolved Portfolio

A responsive, single-page portfolio for Aadil Al Hasan, built with semantic HTML, CSS and vanilla JavaScript.

## Project structure

```text
aadilx-evolved/
├── index.html   # Complete website: structure, styles and interactions
└── README.md    # Setup and deployment notes
```

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or run a local static server from this directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel

1. Create a Git repository and add `index.html` and `README.md` at the repository root.
2. Push the repository to GitHub.
3. In Vercel, choose **Add New → Project**, then import the repository.
4. Select **Other** as the framework preset if Vercel asks.
5. Leave Build Command and Output Directory empty/default for a static HTML site. No build command is required.
6. Deploy. Vercel will serve the root `index.html`.

You can also deploy the project with the Vercel CLI from this directory using `vercel` and follow its prompts.

## Notes

- The original project was a single HTML file and this upgrade intentionally keeps that architecture.
- The original `aadil.png` profile image was referenced by the source but was not included in the uploaded project. The upgraded hero therefore uses original CSS/SVG-free abstract identity artwork instead of showing a broken image. Add a real, optimized portrait only when you have selected the exact image you want to publish.
- Google Fonts are loaded remotely. The page has local system-font fallbacks if Google Fonts cannot load.
- There is no contact form because no verified contact destination or backend was supplied. No fake submission behavior has been added.
