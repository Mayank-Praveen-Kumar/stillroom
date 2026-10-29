# Stillroom — Your space to focus

A browser-based focus space with a timer, focus and break counters, tasks, Spotify controls, lyrics, and animated backgrounds.

## Run locally

This export uses HTML, CSS, and JavaScript directly. No npm install or build step is required.

With Git and Python installed:

```sh
git clone https://github.com/Mayank-Praveen-Kumar/stillroom.git
cd stillroom
python -m http.server 8000 --bind 127.0.0.1 --directory dist
```

Open http://127.0.0.1:8000/ in your browser. On Windows, use `py` instead of `python` if needed.

## Connect Spotify

Open the Spotify connection dialog in Stillroom and enter your Spotify app's client ID. Register the exact redirect URL displayed by Stillroom in that app's Spotify developer settings before connecting. No client secret is needed by this browser client.

Spotify sign-in is stored in the current browser. External music, lyrics, fonts, and background services require an internet connection.

## Versions and history

All 17 original versions are preserved as chronological commits with matching tags **v1–v17**. The latest imported version is **v17**.

- [Browse commits](https://github.com/Mayank-Praveen-Kumar/stillroom/commits/main/)
- [Browse or download a version](https://github.com/Mayank-Praveen-Kumar/stillroom/tags)

To inspect an older version locally:

```sh
git switch --detach v10
```

Return to the latest branch with `git switch main`. Commit or stash local edits before switching versions.

The original commits retain their original messages, “Update Site source”; use the version tags to identify each snapshot. Setup and import commits are also retained.

## Project layout

- `dist/index.html` — application markup, styles, and scripts.
- `dist/assets/` — local application assets.
- `LICENSE` — MIT license.

The temporary import workflow and history bundle are absent from the current source tree; they remain in Git history.

## License

[MIT](LICENSE).
