# EWMSC Hospital Extensions — installable app for Android and iPhone

This project packages the supplied `EWMSC Extensions.html` directory as a Progressive Web App (PWA). It keeps the directory's extension data, search, category filters, favorites, recent calls, theme toggle, and tap-to-call links.

## Publish using your existing GitHub repository

Repository: https://github.com/sameermanwah-cyber/Max-Extensions-

1. Download and unzip this project on your computer.
2. Open your repository link above and select **Add file → Upload files**.
3. Upload the *contents* of the `EWMSC-PWA-Project` folder to the repository root (upload `index.html`, `manifest.webmanifest`, `sw.js`, `icons/`, and `.github/`). Do not upload only the outer project folder. Ensure hidden `.github` folder is included.
4. Commit the upload to the repository's default branch (usually `main`).
5. Open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source, if prompted.
6. Open **Actions** and wait for **Deploy EWMSC Extensions PWA** to finish successfully. GitHub Pages should then publish at:
   `https://sameermanwah-cyber.github.io/Max-Extensions-/`
   If GitHub shows a different URL under **Settings → Pages**, use the URL GitHub provides.

If GitHub rejects the workflow upload or deployment, check **Settings → Actions → General** and repository Pages permissions. You can also share the error message and I can help troubleshoot.

## Install on Android

1. Open the published HTTPS URL in Chrome on the Android phone.
2. Tap the three-dot menu, then **Install app** or **Add to Home screen**.
3. Confirm installation. The app icon will appear on the home screen/app list.

## Install on iPhone

1. Open the published HTTPS URL in Safari.
2. Tap **Share** → **Add to Home Screen**.
3. Confirm **Add**. Launch EWMSC Extensions from the new home-screen icon.

This is a cross-platform installable web app, not an `.apk` installer or an App Store listing. It does not require a store account. The main files can be cached for offline opening after a successful first visit; making calls still requires phone service. The extension list is reproduced from the supplied HTML and has not been independently verified with EWMSC, so confirm important numbers before relying on them.

## Updating the app

Upload/commit changes to the default branch. The GitHub Actions workflow automatically redeploys the site.
