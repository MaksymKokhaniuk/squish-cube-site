# Squish Cube Legal Website

Ready-to-publish GitHub Pages website for **Squish Cube**.

## Files

- `index.html` — landing page
- `privacy/index.html` — Privacy Policy
- `terms/index.html` — Terms of Use
- `styles.css` — shared design

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `squish-cube-site`.
2. Upload everything from this folder to the root of the repository.
3. Commit the files to the `main` branch.
4. Open the repository on GitHub.
5. Go to **Settings → Pages**.
6. Under **Build and deployment** choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
7. Click **Save**.
8. Wait for GitHub Pages to deploy.

Expected URLs:

- Website: `https://maksymkokhaniuk.github.io/squish-cube-site/`
- Privacy Policy: `https://maksymkokhaniuk.github.io/squish-cube-site/privacy/`
- Terms of Use: `https://maksymkokhaniuk.github.io/squish-cube-site/terms/`

## Important checks after deployment

Open both legal URLs in a private/incognito browser window and confirm that:

- they load without signing in;
- the page is HTTPS;
- Privacy Policy and Terms links work;
- the contact email is correct.

## AdMob

Use this as the Privacy Policy URL:

`https://maksymkokhaniuk.github.io/squish-cube-site/privacy/`

## Squish Cube app

After the website is live, replace the current placeholder legal URLs in
`Features/Settings/Presentation/SettingsViewModel.swift` with:

- Terms: `https://maksymkokhaniuk.github.io/squish-cube-site/terms/`
- Privacy: `https://maksymkokhaniuk.github.io/squish-cube-site/privacy/`

## Developer details used

- Developer: Maksym Kokhaniuk
- Contact: maxkokhanuk69@gmail.com
- Effective date: August 17, 2026

Before release, update this site whenever the app's SDKs, data collection,
account system, analytics, backend, advertising providers, or purchase model changes.
