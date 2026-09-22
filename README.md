# Snapdock (frontend)

This is just the frontend. It talks to a Snapdock server running on
`http://localhost:3000` on whatever machine has this page open — so
it only works when *you* open this GitHub Pages link *and* the server
from the main [snapdock](../) repo is running locally at the same time.

It won't work for random visitors — that's by design. The server never
leaves your machine.

## Deploy it

1. Push this folder to a GitHub repo (root, or a branch — see main steps).
2. In the repo: **Settings → Pages → Deploy from a branch** → pick the
   branch/folder this file lives in.
3. GitHub gives you a URL like `https://<you>.github.io/<repo>/`.
4. Start the server locally (`npm start` in the main project).
5. Open the GitHub Pages URL on the same computer. It'll reach your
   local server automatically.

Running the server on a different port? Edit the `API_BASE` line near
the top of the `<script>` in `index.html`.
