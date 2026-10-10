# TS Personal OS — v29.14 Original Sunflower Icon

This package keeps the TS app and uses your original sunflower-only picture as the app icon. There are no letters or extra graphics added to the icon. The GitHub Pages paths are relative, so the repository can have any name.

## Exact structure

```text
YOUR-REPO/
├── index.html
├── manifest.json
├── README.md
├── sw.js
└── icons/
    ├── apple-touch-icon.png
    ├── favicon-64.png
    ├── icon-192.png
    ├── icon-512.png
    └── icon-maskable-512.png
```

## Upload from a new GitHub repository
1. Create a **Public** repository. You can choose any repository name. Leave it empty (do not create a README).
2. Download this ZIP and choose **Extract All** on your computer.
3. Open the extracted `TS-v29.14-OG-SUNFLOWER-ICON` folder.
4. Select the four root files (`index.html`, `manifest.json`, `README.md`, `sw.js`) **and the `icons` folder itself**.
5. Drag all five selected items together onto GitHub's **Add file → Upload files** page. Do not drag the ZIP file and do not open the `icons` folder before selecting.
6. GitHub's upload preview should list `index.html`, `manifest.json`, `README.md`, `sw.js`, and paths beginning with `/icons/`. That is correct; GitHub creates the `icons` folder from those paths.
7. Click **Commit changes**. The order shown by GitHub does not matter.
8. Go to **Settings → Pages**. Set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, then Save. Wait for deployment.
9. Open `https://YOUR-USERNAME.github.io/YOUR-REPO/` on your phone. Use Chrome's menu to install/add to home screen. If an older icon persists, remove the old home-screen shortcut and install again after the new page has loaded.

## Updating an existing repo
Back up your current files first. Replace `index.html`, `manifest.json`, and `sw.js`; then replace all five files inside the existing `icons/` folder. Leave the root structure as shown above.
