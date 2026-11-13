SANDBOXELS OFFLINE
==================

MAIN FILE
---------
Open "index.html" in Chrome to try the game directly.

If some features (especially language loading or mod loading) do not work
when opened directly, use the local server method below.

LOCAL SERVER METHOD (recommended)
---------------------------------
Windows:
  1. Open this folder in File Explorer.
  2. Click the address bar, type cmd, and press Enter.
  3. Run: py -m http.server 8000
     (If that command is unavailable, try: python -m http.server 8000)
  4. Open http://localhost:8000 in Chrome.

ChromeOS / Linux:
  1. Open a terminal in this folder.
  2. Run: python3 -m http.server 8000
  3. Open http://localhost:8000 in Chrome.

To stop the server, return to the terminal and press Ctrl+C.

WHAT IS INCLUDED
----------------
- index.html: your uploaded customized Sandboxels HTML
- style.css: game styling
- icons, backgrounds, fonts: visual assets
- lang: translation files
- mods: local mod files and dependencies
- scripts: repository scripts

OFFLINE NOTES
-------------
- The automatic advertising and Google Analytics loaders have been removed.
- Built-in local mod and language paths now point to this folder.
- Optional features that fetch online content (such as featured community
  saves, newsletter signup, external mod URLs, and external links) still
  require an internet connection.
- This package does not require a connection for the core game assets.
- Local browser security restrictions can make direct file opening behave
  differently from serving the folder on localhost. Use the local server
  instructions if needed.

This is a local-use package based on your uploaded HTML and the repository
ZIP you supplied. It is not an official release from the Sandboxels authors.
