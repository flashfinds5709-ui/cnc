# C&C Property Care Static Website

This folder is a simple, GitHub Pages-ready static website. It does not require React, Node, a backend, MongoDB, Emergent, or any build step.

## File Structure

```text
cc-property-care-static/
├── index.html              # Main homepage GitHub Pages will load
├── css/
│   └── styles.css          # All website styling
├── js/
│   └── main.js             # Small optional JavaScript file
└── assets/
    ├── logo.png
    ├── hero-pressure-washing.jpg
    ├── service-garbage-cans.jpg
    ├── service-fences.jpg
    ├── service-driveways.jpg
    ├── service-wooden-decks.jpg
    ├── service-custom.jpg
    ├── proof-walkway-before.jpg
    ├── proof-house-after.jpg
    ├── proof-patio-after.jpg
    └── about-house.jpg
```

## How to Publish on GitHub Pages

### Option A: Publish from repository root
1. Create a GitHub repository.
2. Copy the contents of this folder into the root of the repository, so `index.html` is at the top level.
3. Commit and push.
4. In GitHub: Settings → Pages.
5. Source: Deploy from branch.
6. Branch: `main`, folder: `/root`.
7. Save.

### Option B: Publish from `/docs`
1. Rename this folder to `docs`.
2. Put `docs` in the repository root.
3. In GitHub: Settings → Pages.
4. Source: Deploy from branch.
5. Branch: `main`, folder: `/docs`.
6. Save.

## External Integrations Used

Allowed/simple external integrations only:
- Google Fonts for typography
- Google Form booking link: https://forms.gle/11TXTAgdrrRsnP749

No Emergent badge, PostHog, backend API, React build, or image CDN dependency is required.
