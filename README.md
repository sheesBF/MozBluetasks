# MozBlue Task Tracker

Offline-capable task tracker for MozBlue (VCS-CCB pathway to issuance, CCB PD drafting, monitoring, grant applications).

## Host on GitHub Pages
1. Create a repository and upload all files in this folder to its root (keep `.nojekyll`).
2. Settings > Pages > Build and deployment: Source "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Open `https://<your-user>.github.io/<repo>/` on your phone and use "Add to Home Screen".

Tasks are stored in the browser on each device. Use Data > Download backup regularly.
The plan in `seed.js` loads on first open; on a device that already has tasks, it adds only the missing plan tasks.
