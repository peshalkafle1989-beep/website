# Peshal Kaphle Portfolio

A GitHub Pages-ready portfolio website for a visual editor / video editor.

## Features

- Responsive portfolio design
- YouTube videos with automatic thumbnails
- YouTube videos open and play inside the website
- Local MP4 reel playback in a vertical 9:16 player
- Image gallery
- About, skills and contact sections
- No build process required
- Works with GitHub Pages

## How to customize

### 1. Add your YouTube videos

Open `index.html` and find:

```js
const youtubeProjects = [
```

Replace the sample YouTube URLs with your own links.

The website supports:

- `https://www.youtube.com/watch?v=VIDEO_ID`
- `https://youtu.be/VIDEO_ID`
- `https://www.youtube.com/shorts/VIDEO_ID`

The thumbnail will be generated automatically.

### 2. Add your reel videos

Put your MP4 files inside the `videos` folder and name them:

- `reel1.mp4`
- `reel2.mp4`
- `reel3.mp4`
- `reel4.mp4`

Or edit the filenames in `index.html`.

For smaller GitHub repositories, you may prefer hosting large videos on YouTube/Vimeo instead of storing very large MP4 files in GitHub.

### 3. Replace the sample images

Replace the files inside the `images` folder or change their filenames in `index.html`.

You can use JPG, PNG, WEBP or SVG files.

### 4. Change contact details

Open `index.html` and change:

```html
href="mailto:your@email.com"
```

Also replace the Instagram, YouTube and LinkedIn `href="#"` values with your actual profile links.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this project.
3. Open repository **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder.
7. Save.
8. GitHub will provide your portfolio URL.

Example:

`https://yourusername.github.io/peshal-kaphle-portfolio/`

## Folder structure

```text
peshal-kaphle-portfolio/
├── index.html
├── README.md
├── .gitignore
├── images/
│   ├── peshal.svg
│   ├── reel1.svg
│   ├── reel2.svg
│   ├── reel3.svg
│   ├── reel4.svg
│   ├── work1.svg
│   ├── work2.svg
│   ├── work3.svg
│   ├── work4.svg
│   ├── work5.svg
│   └── work6.svg
└── videos/
    └── README.txt
```
