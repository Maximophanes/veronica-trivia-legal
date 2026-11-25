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
- Both pages carry November 24, 2026 for the planned same-day publication. Verify the date at authorized publication and update both pages if the release moves. The seven-day delivery-receipt correction has passed local application validation.
- Intended GitHub Pages base URL after owner approval is [https://maximophanes.github.io/veronica-trivia-legal/](https://maximophanes.github.io/veronica-trivia-legal/). Confirm the contact channel is monitored for the response commitments in the policy before publishing.
- The local Latin WOFF2 faces are Chakra Petch 700 and IBM Plex Sans 400, distributed by Fontsource 5.3.0 under the SIL Open Font License 1.1. Keep the [Chakra Petch notice](fonts/chakra-petch-OFL.txt) and the [IBM Plex Sans notice](fonts/ibm-plex-sans-OFL.txt) with their files.
