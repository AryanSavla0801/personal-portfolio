# Aryan Savla — Personal Portfolio

A responsive, dark-themed personal portfolio for a B.Tech Data Science student at NMIMS. Built with plain HTML, CSS, and JavaScript so it can be hosted for free on GitHub Pages.

## Sections

- Intro / hero
- About
- Technical skills
- Selected projects
- Education and experience
- Contact links

## Files

- `index.html` — content and page structure
- `style.css` — layout, colors, responsive styles
- `script.js` — mobile navigation and dynamic footer year

## Before publishing

Search the project for placeholders and update them:

1. Replace `YOUR_EMAIL@example.com` in `index.html` with your preferred contact email.
2. Replace generic GitHub and LinkedIn links with your actual profiles.
3. Each project currently uses a generic GitHub link. Replace each `https://github.com/` project link with the actual repository URL, or remove the link until the repository exists.
4. Verify every project description and its status. The IPO dashboard is described as a concept; other cards are overview templates and should reflect what you have actually built.
5. Update skills so you can confidently explain each one in an interview or viva.
6. Review your education and experience details for accuracy.

## Run locally

Open `index.html` in a browser. For a local development server, you can use VS Code's Live Server extension, or from the project directory run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish using GitHub Pages

### 1. Create a repository

1. Sign in to [GitHub](https://github.com/).
2. Create a new repository named `personal-portfolio`.
3. For a simple public portfolio, set the repository to **Public**.
4. Do not initialize with another README if you plan to upload these files as-is.

### 2. Upload the files

**Option A — GitHub website:** Open the repository, choose **Add file → Upload files**, upload `index.html`, `style.css`, `script.js`, and `README.md`, then commit to the `main` branch.

**Option B — Git from Terminal:** From inside this folder, run:

```bash
git init
git add index.html style.css script.js README.md
git commit -m "Build personal portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/personal-portfolio.git
git push -u origin main
```

Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username. If Git asks you to authenticate, follow GitHub's current sign-in instructions.

### 3. Enable GitHub Pages

1. In the repository, open **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch `main` and folder `/(root)`.
5. Click **Save**.

### 4. Open your live website

After the Pages build completes, the site should be available at:

`https://YOUR_GITHUB_USERNAME.github.io/personal-portfolio/`

The source repository will be:

`https://github.com/YOUR_GITHUB_USERNAME/personal-portfolio`

Replace the placeholder username with your own. The live URL may take a few minutes to become available after the first deployment.

## Notes

- The site has no build step or package dependencies.
- The site uses Google Fonts; if fonts cannot load, system sans-serif fallbacks are used.
- The contact form is intentionally omitted so the site does not imply a backend service. The email button opens the visitor's email app.
