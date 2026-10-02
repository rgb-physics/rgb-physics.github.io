# Personal website

A four-page website made with plain HTML and one shared stylesheet. It has no build step or external dependencies, so GitHub Pages can serve it directly.

## Files

- `index.html` — landing page and short introduction
- `research.html` — research overview and photo gallery
- `programming.html` — programming experience and projects
- `teaching.html` — teaching and outreach
- `style.css` — shared layout, colors, and font settings

## Edit the site

Replace the bracketed prompts and sample text in each HTML file. To change fonts, edit `--font-body` and `--font-heading` near the top of `style.css`. The default fonts are installed on most computers, so the site needs no font downloads.

For photos, create an `images` folder beside the HTML files and add:

- `profile.jpg` — your portrait
- `research-1.jpg` and `research-2.jpg` — research photos

You can use different filenames by updating the `src` value in the corresponding `<img>` element. Update each `alt` description and caption to match the photo.

## Publish on GitHub Pages

Copy the HTML files and `style.css` into the root of the `rgb-physics.github.io` repository, and add your `images` folder. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select the main branch and `/ (root)`, then save. GitHub Pages will publish the site at `https://rgb-physics.github.io/` after deployment completes.
