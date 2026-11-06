# KARD Lab website

Knowledge and Reasoning for Discovery Lab — Iowa State University.

Static HTML/CSS website, ready for GitHub Pages. No build step or dependencies.

## Publish

1. Create a GitHub repository (for example `kard-lab`).
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select **main** and **/ (root)**, then Save.

The project URL will be `https://<owner>.github.io/<repository>/`.
All site links are relative, so project Pages subpaths work without changes.
Do not set a custom domain unless you intend to change DNS.

## Edit content

- `index.html`: biography, research interests and news
- `research.html`: research directions
- `people.html`: people and researcher profiles
- `publications.html`: papers and author markers
- `teaching.html`: courses
- `service.html`: professional service
- `join.html`: recruiting
- `style.css`: appearance
- `assets/`: images and logo

`lab.html` redirects older links to `people.html`.
