# Repository instructions for Claude

## Branch policy

- You may commit and push directly to the `main` branch in this repository.
- You do not need to develop on a feature branch or open a pull request unless the user explicitly asks for one.
- Default to committing each completed change directly to `main`.

## Project notes

- This is a single-file static site (`index.html`) deployed via GitHub Pages.
- The HMM is trained in-browser; there is no server component to deploy.
- QQQ price data is fetched through a Cloudflare Worker proxy at `qqq-macroswing.gulagmonke.workers.dev` which forwards to Yahoo Finance.
