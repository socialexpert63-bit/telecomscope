# TelecomScope

Concept prototype of a telecom market and infrastructure intelligence platform, made for Joyce Telecom Group.

All markets, providers, assets, policy records, clients and figures are **fictional demonstration data**. Nothing is connected to live telecom databases, regulatory feeds or production AI services.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Marketing website with an animated platform walkthrough (links to the dashboard) |
| `dashboard.html` | Interactive dashboard: overview, map, competitors, MDU, due diligence, AI analyst, report builder, policy monitor, client pipeline |
| `logo/` | Logo SVGs: light lockup, dark lockup, icon mark |

Both pages are single self-contained HTML files. They load fonts from Google Fonts and need no build step.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Publish on GitHub Pages

1. Create a repository and upload these files to the root.
2. Go to Settings, then Pages.
3. Under Build and deployment, choose "Deploy from a branch", select `main` and `/ (root)`, and save.
4. The site appears at `https://<your-username>.github.io/<repo-name>/`.

## Notes

The logo wordmark uses live text (Sora). Convert it to outlines in a design tool before using the logo as a final print asset.
