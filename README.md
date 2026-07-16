# AquaMesh — Live Demo

This repository hosts the **published, end-to-end encrypted** AquaMesh product demo
for GitHub Pages. It contains **only ciphertext** — the application source is not
in this repository.

- `/` → Process Water demo
- `/wastewater/` → Wastewater (WRRF) demo

Each page is a self-contained AES-256-GCM encrypted bundle (key stretched from a
passphrase via PBKDF2-SHA256, 600,000 iterations). Without the passphrase there is
nothing to run — the app never exists in plaintext on the host.

Access passphrase is shared privately by the AquaMesh team.
