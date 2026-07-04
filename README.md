# Yanlu Zhong Academic Website

This is a static GitHub Pages deployment package.

## Deploy on GitHub Pages

1. Create a GitHub repository, for example `yanlu-website` or `Yanlu-Zhong.github.io`.
2. Upload all files in this folder to the repository root.
3. In GitHub, go to Settings → Pages.
4. Set the source to the main branch and root folder.
5. Save and wait for GitHub Pages to publish the site.

## File structure

- `index.html`: main homepage
- `assets/gifs/`: animated project images used on the homepage
- `assets/stills/`: static fallback thumbnails
- `projects/`: individual project pages
- `project-data.json`: structured project metadata backup
- `.nojekyll`: prevents GitHub Pages from ignoring folders/files that begin with underscores

The homepage uses GIF thumbnails for the final deployed version.
