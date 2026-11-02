# shikiray.

Personal site — static, no build step. Open `index.html` or serve the folder (GitHub Pages works as-is).

```
index.html               page, styles and scripts in one file
assets/banner.mp4        header video   (banner.jpg — poster)
assets/avatar.mp4        avatar video   (avatar.jpg — poster / og:image)
assets/hurt-me-more.m4a  background track: Flerian — hurt me more
assets/cover.jpg         track cover for the player and lock-screen controls
```

- Projects and GitHub activity load live from the GitHub API (user `spelsinx`), with a fallback if it's unreachable.
- Music starts on the visitor's first click/keypress (browsers block sound before that); if they pause it, the choice is remembered.
- Keys: `/` jump to the console, `m` toggle music. Type `help` in the console for commands.
- To change the track: replace `assets/hurt-me-more.m4a` and `assets/cover.jpg`, then edit the title/artist in `index.html` (search for `hurt me more`).
