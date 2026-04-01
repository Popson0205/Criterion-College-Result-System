# Criterion College Result Management System

## Deploy on Render.com (Free Static Site)

### Steps:
1. Upload this folder to a GitHub repository (public or private)
2. Go to https://render.com → New → Static Site
3. Connect your GitHub repo
4. Settings:
   - **Name:** criterion-college-result-system
   - **Branch:** main
   - **Publish directory:** . (root)
   - **Build command:** (leave empty)
5. Click **Create Static Site**
6. Your site will be live at: https://criterion-college-result-system.onrender.com

### Default Login:
- Username: `admin`
- Password: `criterion2025`

### Notes:
- All data is stored in the browser's localStorage
- Data persists on the same device/browser
- To share data across devices, use the Export/Import feature (coming soon)
- The stamp image must be re-uploaded in Settings on each new device

### Files:
- index.html    — Main app shell
- app.js        — Application logic & routing
- data.js       — Data layer (localStorage)
- print.js      — Regular class print engine
- creche_print.js — Creche/Nursery print engine
- logo.js       — School logo (base64 embedded)
- styles.css    — Design system
- theme.js      — Light/dark mode
- render.yaml   — Render.com deploy config
