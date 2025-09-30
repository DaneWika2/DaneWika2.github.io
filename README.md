# Dane Wika — Portfolio

This repository holds my personal portfolio site. It is a static site designed for **GitHub Pages**.

## How to publish (GitHub Pages)

1. Create a repository named `<your-username>.github.io` on GitHub.
2. Upload these files to the root of the repository.
3. Go to **Settings → Pages** → under **Source** choose **Deploy from a branch**.
4. Under **Branch** select `main` and **/ (root)**, then **Save**.
5. After the build finishes, the site will be live at `https://<your-username>.github.io`.

## Custom domain (optional)
- In **Settings → Pages**, set your **Custom domain** (e.g., `danewika.com`) and **Save**.
- In your DNS, point the apex domain to GitHub Pages A records and `www` to a CNAME of `<your-username>.github.io`.
- Turn on **Enforce HTTPS** in **Settings → Pages** once the certificate is issued.

## Notes
- The file `.nojekyll` disables Jekyll processing (useful if you ever add folders starting with underscores).
- Replace `resume.pdf` with your actual resume (keep the same filename so the link works).

© 2025 Dane Wika
