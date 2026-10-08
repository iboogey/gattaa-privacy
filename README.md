# Gattaa privacy site

The public privacy policy and account deletion pages for the قطاعة (Gattaa) app, in Arabic and English. Plain HTML and CSS, no build step, no scripts, no trackers.

## Pages

| Page | Path | Use it for |
|---|---|---|
| Privacy policy (Arabic) | `/` | App Store Connect "Privacy Policy URL", Google Play, the in-app link |
| Privacy policy (English) | `/en/` | The in-app link when the app is in English |
| Delete your account (Arabic) | `/delete-account/` | Google Play "Delete account URL" |
| Delete your account (English) | `/en/delete-account/` | The same, in English |

## Publish on GitHub Pages

1. Create a public repository on GitHub, for example `gattaa-privacy`.
2. Push this folder to the repository's `main` branch.
3. In the repository, open **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-github-username>.github.io/gattaa-privacy/`.

The `.nojekyll` file tells GitHub Pages to serve the files as they are.

## Updating the policy

- Change the text in both languages, in the policy and the delete page if needed.
- Update the "Last updated" date on every page you change.
- If the change is significant (new data, new third party), tell users in the app before it takes effect.

Rubik is bundled under the SIL Open Font License (`assets/fonts/OFL.txt`), so the pages load no third-party fonts.
