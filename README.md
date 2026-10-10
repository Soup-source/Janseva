# JanSeva (installable web app)

Private, on-device scheme eligibility navigator. 13 languages. Works offline after the first visit.

## Files
- `index.html` the whole app (rules and 10 schemes are inside)
- `manifest.webmanifest` app name, colors, icons
- `sw.js` offline support
- `icons/` app icons
- `.nojekyll` tells GitHub Pages to serve files as they are

## Put it online with GitHub Pages
1. On github.com, click **+** (top right) > **New repository**.
2. Name it `janseva`, choose **Public**, click **Create repository**.
3. On the new repo page click **uploading an existing file**.
4. Unzip this package. Open the unzipped folder and drag **everything inside it** (index.html, manifest.webmanifest, sw.js, .nojekyll and the icons folder) into the upload box. Do not drag the outer folder itself, or the link will have an extra folder in it.
   - If `.nojekyll` is hidden on your computer, skip it. The app still works.
5. Click **Commit changes**.
6. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then **Save**.
7. Wait 1 to 2 minutes and refresh. The page shows your link:
   `https://YOUR-USERNAME.github.io/janseva/`

## Install on a phone
1. Open the link in **Chrome** on Android.
2. Tap the menu (three dots) > **Install app** (or **Add to Home screen**).
3. Open JanSeva from the new home screen icon. After one visit it works offline.

On iPhone use **Safari**: Share > **Add to Home Screen**.

## Update later
Replace `index.html` in the repo (**Add file > Upload files**, same file name, commit). Phones pick up the new version the next time they open the app with internet.

## Netlify alternative
Go to app.netlify.com/drop and drag the unzipped folder onto the page. You get a link right away.
