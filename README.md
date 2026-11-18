# xTang OAuth relay

Static callback page for the xTang Workbench. It forwards an OAuth
response to `http://127.0.0.1:17890/oauth/callback` on the same machine.

No server, no storage, no logging. PKCE keeps a stolen code useless.

Register this exact URL in each platform developer console:

    https://xMacin.github.io/xtang-oauth-relay/index.html

Deploy: enable GitHub Pages for this repository (branch `main`, folder `/`).
