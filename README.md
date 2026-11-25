# Veronica Trivia legal website

This repository contains the public-facing Privacy Policy and Terms of Service for Veronica Trivia. It serves three static HTML pages using one shared stylesheet and local fonts.

## Local preview

From this repository, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1 --directory .
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/). The pages also open directly from disk using their relative links. No install or build step is needed.

## Maintenance

- Keep `index.html`, `privacy.html`, `terms.html`, and `style.css` at the repository root. Use relative links for files on the site so navigation works under the GitHub Pages repository path.
- Keep the approved wording and the `[Date of publication]` placeholders during local review. Set the dates only for an authorized release, after the seven-day delivery-receipt expiration correction in the game has been implemented and validated.
- Intended GitHub Pages base URL after owner approval is [https://maximophanes.github.io/veronica-trivia-legal/](https://maximophanes.github.io/veronica-trivia-legal/). Confirm the contact channel is monitored for the response commitments in the policy before publishing.
- The local Latin WOFF2 faces are Chakra Petch 700 and IBM Plex Sans 400, distributed by Fontsource 5.3.0 under the SIL Open Font License 1.1. Keep the [Chakra Petch notice](fonts/chakra-petch-OFL.txt) and the [IBM Plex Sans notice](fonts/ibm-plex-sans-OFL.txt) with their files.
