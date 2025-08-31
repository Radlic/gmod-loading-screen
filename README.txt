GMod Loading Screen (static)
================================

Files:
- index.html  -> the loading page you should host
- (no images required) uses gradient background and inline CSS

How to use:
1) Upload `index.html` to a web host (GitHub Pages, Netlify, Vercel, or your own web server).
2) Set this in your Garry's Mod server.cfg:
   sv_loadingurl "https://YOUR-DOMAIN/index.html"

Optional dynamic query parameters:
- You can append `?steam=STEAMID&map=MAPNAME&gm=GAMEMODE` and the page will display them.
  Example:
  sv_loadingurl "https://YOUR-DOMAIN/index.html?steam=%s&map=%m&gm=%gamemode%"

(Replace placeholders to whatever your server passes; the page will simply read any params present.)

