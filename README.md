# STTR Website

Project page for **Compact single-shot ranging and near-far imaging using metasurfaces**.

This site is a static academic webpage built from the Academic Project Page template and customized for the paper, figures, citation, and related works.

## What is in this repo

- `index.html` contains all page content and metadata.
- `static/css/` contains the site styles.
- `static/js/` contains the carousel, dropdown, and utility scripts.
- `static/images/` contains figures, preview assets, and the favicon.
- `static/videos/` and `static/pdfs/` contain media and downloadable files used by the page.

## Local editing

Open `index.html` to update the paper title, authors, abstract, figure captions, links, and citation.

The current page already includes:

- Paper metadata for search engines and social previews
- A short abstract section
- An image carousel for key figures
- A related-works dropdown
- BibTeX citation support

## Preview locally

You can preview the site by opening `index.html` directly in a browser, or by serving the folder with any simple static server.

For example, in PowerShell:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Publishing on GitHub Pages

1. Push the repository to GitHub.
2. In the repository, go to Settings > Pages.
3. Choose the branch and root folder that contains `index.html`.
4. Wait for the deployment to complete.
5. GitHub will show the live URL in the Pages settings page.

The site is typically available at one of these URLs:

- `https://<your-username>.github.io/<repo-name>/`
- `https://<your-username>.github.io/` if the repository name is `<your-username>.github.io`

## Customization notes

- Replace placeholder links in `index.html` with the final DOI, code repository, and author pages.
- Update `static/images/social_preview.png` with a 1200x630 preview image if you want richer social sharing.
- Replace the demo PDF, video, and carousel images with your final project assets.
- Update the related-works dropdown with the final paper titles and venue names.

## Acknowledgments

This page is based on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) and the [Nerfies](https://nerfies.github.io/) project page.

## License

This website follows the license used by the original template unless otherwise noted in the repository.
