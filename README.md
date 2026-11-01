# Starhive Defense — iPhone app

Neon arcade alien shooter. This repo builds in the cloud with Codemagic (no Mac needed).

- `Game/` the game (HTML5 canvas)
- `Sources/` SwiftUI + WKWebView app shell
- `project.yml` XcodeGen spec (generates the Xcode project during the build)
- `codemagic.yaml` cloud build: fonts → project → signing → TestFlight upload
- `docs/` support and privacy pages (GitHub Pages, folder /docs)
- `store-screenshots/` 1290×2796 App Store screenshots

Bundle ID: `io.starhive.defense` (change in both project.yml and codemagic.yaml).
