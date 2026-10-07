# Prometheus website — GitHub and Vercel package

## Upload to GitHub
1. Unzip prometheus-github-upload.zip on your computer.
2. Open the extracted prometheus-github-upload folder.
3. In your GitHub repository choose Add file → Upload files.
4. Drag the CONTENTS of this folder (public, vercel.json, README.md) into the upload area and commit.

Do not upload the ZIP itself. Keep the public/assets folder intact. Upload image and font files as files; do not paste their contents into GitHub’s text editor.

Your repository root should contain:

    README.md
    vercel.json
    public/
        index.html
        styles.css
        app.js
        config.js
        assets/

## Deploy on Vercel
Import the GitHub repository. Leave Root Directory at the repository root. Framework Preset is Other; no build command is needed. Output Directory is public. The included vercel.json sets these options automatically. Deploy.

If replacing an existing project, clear old build settings and ensure Root Directory is not dist or public. The vercel.json file must be at the repository root.

## Updating the site
Edit or replace files inside public, keeping names and folder structure unchanged. GitHub filenames are case-sensitive on deployment.

## Contact form
This is currently a visual preview: the contact form is not connected to an inbox. Configure form delivery separately before expecting submissions.
