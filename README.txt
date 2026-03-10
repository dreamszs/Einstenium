Einstenium 1.1.1 - Portable App
================================

CONTENTS
--------
- roblox-external-executor.exe   Main application (run this)
- web\                            UI files (required; keep next to the exe)

HOW TO RUN
----------
1. Double-click roblox-external-executor.exe
2. Windows may show SmartScreen the first time - choose "More info" then "Run anyway" if you trust the build
3. Requires WebView2 (Windows 10/11 usually have it; otherwise install from Microsoft)

REQUIREMENTS
------------
- Windows 10/11 (64-bit)
- Microsoft Edge WebView2 Runtime (often preinstalled)

PROTECTION & RELIABILITY
-----------------------
- This is a Release build: optimized, no debug symbols in the exe
- For stronger protection (anti-tamper, obfuscation), use external tools after building, e.g.:
  - Code signing (SignTool + certificate) so Windows/SmartScreen trusts it
  - VMProtect / Themida / similar (third-party; add after build)
- Keep the "web" folder next to the exe; the app loads UI from it

DISTRIBUTION
------------
- Zip the entire "Einstenium-App" folder to share as portable version
- Or build an installer: open Einstenium-Setup.iss with Inno Setup (https://jrsoftware.org/isinfo.php) and compile
