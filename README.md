# Orbit

A responsive, dependency-free career-exploration website for students, with an AI-chat demo, privacy-first interest matching, specific college-major suggestions, self-guided activities, and a personal learning plan.

## Run it

Open `index.html` in a browser, or start a local static server from this directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish

Pushing to `main` deploys the site with GitHub Pages. Once deployment finishes, the default site URL is `https://kadvi0216-collab.github.io/The-domain/`.

To use `orbitstudyguide.com`, first register the domain and configure its DNS to point to GitHub Pages, then set it as the custom domain in the repository's Pages settings. The domain is not currently registered or resolving, so it cannot be activated yet.

The chat demo uses keyword matching and prewritten career-guide content; it is not connected to an AI model or external service. Chat messages and quiz answers are not sent or saved. The quiz ranks majors from selected interests; it is a reflection tool, not a validated assessment, ability measure, or career prediction. The learning plan stays on the page until it is refreshed or closed; use the print/save option to keep a copy. Nothing is shared.
