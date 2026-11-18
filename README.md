# Website template

A white-background academic site in the style of mkenwick.com, with Home, CV, Research, Teaching, Flags, and Contact pages. Your photo, bio, and CV are already in. The other sections are empty and ready for you to fill in.

## Fill it in

- **Photo:** to change it, replace `profile.jpg`, keeping the same file name.
- **CV:** to update it, replace `cv.pdf` with your new PDF, keeping the same file name. The CV page shows it in a scrolling window with a download button. The files `pdf.min.mjs` and `pdf.worker.min.mjs` are PDF.js, the free viewer that draws the pages; leave them in place.
- **Previewing on your computer:** opening `cv.html` straight from a folder won't draw the CV, because browsers block that for local files. It works once the site is on GitHub. To preview locally, run `python3 -m http.server` in this folder and go to `http://localhost:8000`.
- **Text:** type between the `<p>` and `</p>` tags. Comments (`<!-- ... -->`) mark where things go and include an example block you can copy. Comments never show up on the site.

## Publish on GitHub Pages

1. Create a public repository named `yourusername.github.io`.
2. Upload everything in this folder, including the hidden `.nojekyll` file.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
