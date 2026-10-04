# Cookie Clicker stream-ready build

This directory mirrors the supplied Cookie Clicker source package.

The following changes were made for CDN/iframe hosting:
- `main.js` sets `Game.resPath` and `DataDir` to the GitHub/jsDelivr repository.
- The official-host iframe check was removed so the game can initialize inside an embed.
- `index.html` includes a `<base>` URL so relative scripts, CSS, images, sounds, and localization files resolve from the CDN.
- `google-sites-loader.html` is a small fetch-and-launch page suitable for use as the logic behind a Google Sites HTML embed.

Repository expected:
https://github.com/swithred/cookie-clicker-stream
