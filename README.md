# Pinotage desktop releases

Installers and update manifests for the Pinotage desktop app. This repository
holds release assets only; it contains no source code.

Every macOS build is signed with Pinotage Health's Developer ID and notarized
by Apple. Each update archive also carries a signature that installed apps
verify against a key built into them, so an archive that was not signed by
Pinotage Health is refused.

Installed apps check `releases/latest/download/latest.json` here for updates.
Releases are published by CI; do not edit or upload assets by hand.
