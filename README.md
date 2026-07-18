# Alexander Meienberger — Research Website

Personal academic website of Dr. Alexander Meienberger, Managing Director of the
Center for Governance and Culture in Europe (GCE-HSG) at the University of St.Gallen.

Research focus: Russian literature of the 19th–21st centuries and medical humanities,
at the intersection of East European studies, literary and cultural studies, and
biomedical ethics.

## Live site

Once GitHub Pages is enabled (see below), the site is available at:

```
https://<your-username>.github.io/<repository-name>/
```

## Structure

```
.
└── index.html   # single-file site — all HTML, CSS and JS inline, no build step needed
```

## Updating content

Open `index.html` in any text editor and edit directly:

- **Profile** — intro text near the top (`<section class="hero">`)
- **Projects** — `<section id="projects">`
- **CV** — education, professional experience, teaching, memberships, editorial board
  (`<section id="cv">`)
- **Publications & Talks** — `<section id="publications">`
- **Contact** — `<section id="contact">`

No build tools, frameworks, or dependencies are required — just save the file and
push the change; GitHub Pages redeploys automatically within a minute or two.

## Deploying updates

```bash
git add index.html
git commit -m "Update content"
git push
```

## Enabling GitHub Pages (first-time setup)

1. Go to the repository on GitHub → **Settings** → **Pages**.
2. Under **Branch**, select `main` and folder `/ (root)`.
3. Click **Save**. The site will be live within a couple of minutes.

## License

Content © Alexander Meienberger. Feel free to reuse the page structure/CSS as a template.
