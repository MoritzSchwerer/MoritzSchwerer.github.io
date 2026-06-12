# Robot Portfolio Site

A minimal static portfolio for robot skill videos. It is designed to work with
GitHub Pages without a build step.

## Local preview

```sh
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Replace placeholders

- Update your name, email, GitHub, LinkedIn, and CV link in `index.html`.
- Replace each `.video-placeholder` block with an embedded video.

Example YouTube embed:

```html
<div class="video-frame">
  <iframe
    src="https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID"
    title="Short description of this robot demo"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>
```
- Rewrite each project title, description, robot, and role.
- Put `cv.pdf` in `assets/` if you want the CV link to work.

## GitHub Pages

Create a repository named `<your-github-username>.github.io`, push these files,
and enable Pages from the repository settings if GitHub does not publish it
automatically.
