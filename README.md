# Cheikh Tidjani Tweylib — Profile Site

A responsive, bilingual portfolio for an AI Research Engineer, built around a dark technology-focused visual system. The site uses plain HTML, CSS, and JavaScript, so it has no package installation or build step.

## Preview

Open `index.html` in a browser, or serve the folder with any static web server.

## Presentation videos

Both public Google Drive presentation files are embedded for in-page playback. Their individual `/preview` links are configured in `VIDEO_SOURCES` near the top of `script.js`:

```js
const VIDEO_SOURCES = {
  thesis: { src: "GOOGLE_DRIVE_PREVIEW_URL", type: "embed" },
  competition: { src: "GOOGLE_DRIVE_PREVIEW_URL", type: "embed" },
};
```

- Use `type: "video"` for a direct MP4 URL.
- Use `type: "embed"` for a Google Drive `/preview`, YouTube embed, or Vimeo embed URL.

## Main files

- `index.html` — content, metadata, and page structure
- `styles.css` — responsive visual system
- `script.js` — English/French translations, language preference, and video enhancement
- `assets/award-first-place.jpg` — award photograph
