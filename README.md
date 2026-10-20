# Net Control Log

A phone-friendly logger for running directed amateur radio nets: step-by-step net scripts, check-ins, the comments queue, and PDF/Excel exports that match the paper net log.

## Hosting on GitHub Pages

1. Create a repository (for example `net-control-log`) and upload everything in this folder: `index.html`, the icon files, `manifest.webmanifest`, `.nojekyll` and this README.
2. In the repository, go to Settings → Pages. Under "Build and deployment", pick "Deploy from a branch", choose `main` and `/ (root)`, and save.
3. After a minute the app is live at `https://<your-username>.github.io/net-control-log/`.

On iPhone, open that address in Safari and use Share → Add to Home Screen. It gets the log-and-net icon and opens full screen like an app.

## Good to know

- Everything is saved in the browser on each device. Nothing syncs between phones, and clearing Safari's website data erases your nets and logs, so export logs after each net.
- Each person starts with an empty station directory. It fills in as they log check-ins.
- Tidy notes needs the club server (phase two) and is hidden here. Listen (speech to text) works in Safari and Chrome.
- To update the app, replace `index.html` with the new version and commit.
