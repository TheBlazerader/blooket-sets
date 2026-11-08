SNOW RIDER 3D — OFFLINE FILE PACKAGE

All game/build files in this package are stored locally. No CDN links are used.

HOW TO RUN ON CHROMEBOOK (ChromeOS)
1. Extract this ZIP into a folder in the Linux files area.
2. Open the Linux Terminal.
3. Change to the extracted folder. For example:
   cd ~/Downloads/snowrider_offline_package
   (Adjust the path if you extracted it somewhere else.)
4. Start a local web server:
   python3 -m http.server 8000
5. In Chrome, open:
   http://localhost:8000

Keep the Terminal window open while playing. To stop the server, press Ctrl+C.

IMPORTANT
Do not open index.html by double-clicking it (file://). Unity WebGL builds commonly
need to be served over HTTP, and browsers may block required file loading otherwise.
The game files are local; after the package is extracted, the game should not need
an internet connection to load. Browser support and graphics drivers still apply.
