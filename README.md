# TOG Wallet

The official wallet for **$TOG**, the native coin of [The Only Grid](https://github.com/vahidzekic/The-Only-Grid).
It uses the same TOG account as TOG Drive and the TOG Console; the key that signs your transactions is made and kept on
your device.

- Site: https://vahidzekic.github.io/theonlygrid-wallet/ (Serbian, English: `/en/`)
- Downloads: [Releases](https://github.com/vahidzekic/theonlygrid-wallet/releases/latest) (Windows, macOS, Linux)
- Privacy policy: [`privatnost.html`](privatnost.html), [`en/privacy.html`](en/privacy.html)
- Specification: [TOG-SPEC-0023](https://github.com/vahidzekic/The-Only-Grid/blob/main/docs/specs/0023-tog-wallet.md)

The app's source is in the main repository under `apps/tog-wallet`; this repository holds the public site and the
release builds. It is a test version on the testnet: test-TOG has no monetary value.

## Site

Static HTML and one stylesheet, no build step and no external JavaScript. Light and dark follow the system.
GitHub Pages: Settings → Pages → *Deploy from a branch* → `main` / `(root)`.
