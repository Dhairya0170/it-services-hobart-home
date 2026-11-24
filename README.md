# IT Services Hobart website

## Folder structure

- `index.html` - webpage
- `assets/images/` - all extracted images
- `assets/videos/` - place the five MP4 files listed below
- `IMAGE-MAP.csv` - image name and usage guide

## Required video files

Place these files in `assets/videos/`:

1. `hero-bg.mp4`
2. `project-01.mp4`
3. `project-02.mp4`
4. `project-03.mp4`
5. `project-04.mp4`

The HTML uses repository-relative paths such as `assets/videos/hero-bg.mp4`, which work on GitHub Pages, Vercel, Netlify, and a normal web server when this structure is preserved.

## GitHub upload

Upload the contents of this folder to the repository root. Do not upload the outer folder as a nested folder unless you want the website at that nested path. Enable GitHub Pages under Settings > Pages > Deploy from a branch, then select `main` and `/ (root)`.
