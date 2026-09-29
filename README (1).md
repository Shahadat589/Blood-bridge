# Blood Bridge

A community blood donation website (pilot with Star blood group), built for CSC 5301 Project Management.

Single-file site: `index.html` (HTML, CSS and JavaScript, no build step).

## Deploy on GitHub Pages

1. Create a new repository on GitHub (for example `blood-bridge`).
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose branch `main` and folder `/ (root)`, then click **Save**.
5. After a minute your site is live at `https://<your-username>.github.io/blood-bridge/`.

## Notes

- Donors, requests and stock are sample data stored in the browser (localStorage). Use "Reset demo data" in the admin section to restore them.
- SMS/email alerts are simulated. A real version needs a backend and a messaging gateway.
- The admin section has no login in this demo.
