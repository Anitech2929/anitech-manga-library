# AniTech manga library

Page images for the AniTech app's Manga page.

Layout:
- one folder per series, e.g. `one-piece/`
- inside a series folder, one folder per chapter (optional), e.g. `one-piece/chapter-001/`
- page images named in reading order: `001.jpg`, `002.jpg`, ...
- supported image types: png, jpg, jpeg, webp, gif, avif

Point the app at this repository in Settings → Manga resources, then the Manga page
browses these folders and shows the images.

The `sample/` folder holds one generated placeholder page so you can confirm the
pipeline renders; delete it once your own pages are in.