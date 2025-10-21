# MMT Finance — Momentum Quiz

This is a static HTML quiz about MMT Finance. It can be run locally, in GitHub Codespaces, or deployed to Vercel.

## Run locally
1. Install Node.js (if not installed).
2. Install http-server globally: `npm i -g http-server`
3. Start: `http-server -c-1 . -p 3000`
4. Open: `http://localhost:3000`

## Open in GitHub Codespaces (recommended)
1. Push this repository to GitHub (create a repo named `mmt-quiz`).
2. On GitHub, click the green **Code** button → **Codespaces** → **Create codespace on main**.
3. Codespaces will honor the `.devcontainer/devcontainer.json` config and install `http-server`.
4. In the Codespace terminal run: `http-server -c-1 . -p 3000`
5. Click the forwarded port (3000) in the Codespaces toolbar to open the site preview.

## Deploy to Vercel
- Connect this GitHub repo to Vercel (Import Project). Framework: Other. Output directory: `/`.

## Notes
- The project is static (no build). Any changes pushed to GitHub will be picked up by Vercel if connected.