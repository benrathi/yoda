# yoda

The stable link to YODA while it runs on a laptop: **https://benrathi.github.io/yoda**

`index.html` reads `tunnel.json` (through the GitHub API, so it is never stale) and forwards to the Cloudflare quick tunnel that is current right now. `tunnel.json` is rewritten by `start_tunnel.sh` in the 01 Advisors workspace every time the tunnel restarts; `{"url": ""}` means offline, and the page says so instead of erroring.

Nothing here is the app: no code, no data, just the one pointer. Share the GitHub Pages link (or a short link to it), never the tunnel address itself — that one changes.
