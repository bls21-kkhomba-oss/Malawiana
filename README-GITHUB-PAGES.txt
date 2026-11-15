# Malawiana website — GitHub Pages package

## Upload these files
Upload the contents of this folder to the **root** of your GitHub repository, keeping the `images` folder and its contents together:

- `index.html`
- `styles.css`
- `app.js`
- `images/` (all 29 local photographs)

Do not upload the ZIP file by itself and expect GitHub Pages to unpack it. Extract it first, then upload the files and the complete `images` folder.

## Enable GitHub Pages
In your repository open **Settings → Pages**. Under Build and deployment choose **Deploy from a branch**, select your main branch and `/ (root)`, then Save. Wait for the Pages deployment to finish and open the published URL.

## Image troubleshooting
GitHub Pages paths are case-sensitive. Do not rename image files unless you also update the matching path in `app.js` or `index.html`. The website uses relative paths such as `images/lake-malawi-sunset.jpg`, so the photographs are served from your own repository and do not depend on third-party image hosts.
