# PursuitVLA project page

This is the anonymous PursuitVLA ICLR project page. It is a static site that can be published directly with GitHub Pages.

## Preview locally

From this directory, run:

```powershell
python -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## GitHub Pages

1. Create a public GitHub repository and upload the contents of this directory.
2. In **Settings -> Pages**, choose **Deploy from a branch**.
3. Select the default branch and the `/ (root)` folder, then save.
4. The public page will be available at `https://<username>.github.io/<repository>/`.

The page can use local compressed MP4 files for all four cases. The current anonymous deployment includes `assets/videos/case1.mp4` through `case4.mp4`.

## Adding the real-world video

The four case slots use responsive HTML5 video players. Replace the corresponding MP4 in `assets/videos/` when a later video revision is ready. Keep each file below GitHub's 100 MB single-file limit.

For the eventual Google Sites embed, the HTML page and video must be served from a public HTTPS origin. Recommended options are a static host such as GitHub Pages, Cloudflare Pages, or Netlify. Imgur can host short media, but it is less predictable for a long-term research demo page and should not be the source of record for the videos.

## Files

- `index.html`: page structure and anonymous research copy
- `styles.css`: responsive academic layout
- `script.js`: section highlighting, result tabs, and BibTeX copy action
- `assets/figures/`: local paper figures used by the prototype
- `assets/videos/`: future MP4/WebM demo files
