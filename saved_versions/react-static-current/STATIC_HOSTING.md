# Static Hosting / GitHub Pages

This frontend is now a static React site. It does not require the FastAPI backend or MongoDB to run.

## Build locally
```bash
yarn install
yarn build
```

## What to upload to GitHub Pages
Upload or deploy the contents of:
```bash
frontend/build/
```

The build uses relative asset paths via `"homepage": "."`, so it can work on GitHub Pages project URLs such as:
```text
https://yourusername.github.io/your-repo-name/
```

## GitHub Pages option
1. Push the frontend project to GitHub.
2. Run `yarn build`.
3. Deploy the `build` folder using GitHub Pages, a `gh-pages` branch, or GitHub Actions.

## Notes
- Contact buttons are static links: phone, Gmail compose, and Google Form.
- Images are loaded from public stock/logo URLs, so no backend server is needed.
