# ResCue

Project page for **ResCue: Residual Spatial Cueing for Language-Conditioned
Imitation Learning**.

The published page is available at:

<https://carbonleot.github.io/rescue-il/>

## Local preview

Run a small static server from the repository root:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Add the demo video

1. Encode the video as an H.264/AAC MP4 with a 16:9 aspect ratio.
2. Place it at `static/videos/rescue-demo.mp4`.
3. In `index.html`, replace the `video-placeholder` block with the commented
   `<video>` block directly below it.

Keep the video reasonably small so the page loads reliably from GitHub Pages.

## Deployment

The site is a static page with no build step. GitHub Pages should publish from
the `main` branch and the repository root. Updates become available after
pushing changes to `main`.
