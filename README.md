# FOLD POP!

Compiled Godot WebAssembly / WebGL2 game. This repository contains only the public browser build and its Pages workflow, not the independent private Godot source.

GitHub Pages deploys `site/` on pushes to `main`. No build credentials, Android integrations, analytics, accounts or live advertisements are included. Drag or use arrows/WASD; Escape pauses. Touch swipe on mobile. High scores/settings stay in browser storage when permitted.

Maintainers: export/validate the independent local Web project, then use `scripts/publish_web.ps1` there. It copies only the compiled allowlist, commits and pushes this checkout; it never synchronizes the Android project. Do not edit generated engine files by hand. Source art/game content retain their existing ownership; third-party software notices are in site/THIRD_PARTY_NOTICES.txt. No license grant for extracting/reusing game assets is implied.
