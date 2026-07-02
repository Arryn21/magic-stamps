# 🔏 The Five Magic Stamps

**DSA, ECDSA, ECDSA-SK, Ed25519, and Ed25519-SK — explained like you're five.**

An interactive, single-page explainer that teaches digital signature algorithms (the ones you pick from when running `ssh-keygen`) using magic stamps, lockboxes, and one very sneaky raccoon. 🦝

## 🌐 Live demo

Once GitHub Pages is enabled (see below), the site is available at:

```
https://<your-username>.github.io/magic-stamps/
```

## 🧠 What it covers

| Character | Algorithm | The idea |
|---|---|---|
| 🧓 Grandpa Stamp | **DSA** | The original, now-legacy signature algorithm. Big keys, slow, retired. |
| 😎 Curvy Stamp | **ECDSA** | DSA rebuilt on elliptic curves — tiny keys, same security. |
| 😎🔐 Curvy + Lockbox | **ECDSA-SK** | ECDSA with the private key locked inside a hardware security key (FIDO2). |
| 🚀 Rocket Stamp | **Ed25519** | Modern EdDSA over Curve25519 — fast, small, hard to misuse. The recommended default. |
| 🚀🔐 Rocket + Lockbox | **Ed25519-SK** | Ed25519 + hardware key. The champion combo. |

Every character card has a **"show grown-up words"** toggle that swaps the kid-friendly story for the real technical explanation.

## 🛠️ How it works

One `index.html` file, zero build step:

- React 18 (UMD via CDN)
- Babel Standalone compiles the JSX right in the browser
- No dependencies to install, nothing to run — just open the file

## 🚀 Run it locally

Clone the repo and open `index.html` in any browser. That's it.

```bash
git clone https://github.com/<your-username>/magic-stamps.git
cd magic-stamps
open index.html        # macOS
# or: xdg-open index.html (Linux) / start index.html (Windows)
```

## 📄 License

MIT — use it, remix it, teach with it.
