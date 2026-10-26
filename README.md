# Predictive Risk and Operation Intelligence — ORD

A client-facing, interactive desktop dashboard prototype for Operator Routine Duties (ORD) in Oil & Gas.

## Run locally

This is a standalone HTML prototype and requires no Node.js, dependencies, or build step.

1. Download or clone this repository.
2. Open `index.html` in a modern browser (Chrome or Edge recommended).

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and `.nojekyll` from this folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish and open the URL shown in Settings → Pages.

## Prototype notes

- Designed for a 1440 px desktop dashboard layout.
- Uses illustrative asset, prediction, and performance data. Predicted values are not operational recommendations.
- Predicted risk supports, and does not replace, routine and physical inspections.
- This is a front-end prototype, not connected to a live database, prediction model, or authentication system.
- Since it is plain HTML/CSS/JavaScript, edit `index.html` directly to customise the UI.

## Suggested repository structure

```text
ord-dashboard/
├── index.html
├── README.md
└── .nojekyll
```
