# NBCC Team List Generator

Static web page that fills in the weekly team list graphic. Everything runs in the browser, so there's no server.

## Hosting on GitHub Pages
1. Create a new repo and upload everything in this folder (`index.html`, `template.jpg`, `fonts/`).
2. In the repo, go to **Settings → Pages → Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. After a minute it's live at `https://<your-username>.github.io/<repo-name>/`.

## Editing
- Text positions, sizes and colours are constants at the top of the `<script>` in `index.html`.
- `template.jpg` is the club graphic with the text removed. If you swap it, keep it 1024×1536.
- Fonts: Roboto (Apache 2.0, see `fonts/LICENSE.txt`).
