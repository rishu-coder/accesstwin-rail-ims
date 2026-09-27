# AccessTwin Rail IMS

A deployment-ready React/Vite demonstration of a railway-station digital twin, predictive maintenance forecasts, 2D/3D asset maps, live operational indicators and exportable reports.

## Run locally

```bash
npm install
npm run dev
```

## Production test

```bash
npm run build
npm run preview
```

## Deploy with GitHub Pages

1. Create an empty GitHub repository.
2. Upload all files in this folder, including `.github/workflows/deploy.yml` and `package-lock.json`.
3. In the repository, open **Settings > Pages**.
4. Set **Source** to **GitHub Actions**.
5. Push to the `main` branch. The included workflow builds and deploys the site.

## Data notice

All values are illustrative interface data. Replace `assets` and `zones` in `src/App.jsx` with validated APIs or project data before operational use.
