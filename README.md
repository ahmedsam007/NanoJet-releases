# NanoJet for macOS

NanoJet is a fast, lightweight download manager for macOS.

- Accelerated downloads with robust retry/resume
- Optional browser integration (Chrome/Chromium-based, Firefox)
- Connection diagnostics and simple, clean UI

## Download

- Latest release: https://github.com/ahmedsam007/NanoJet-releases/releases/latest
- All releases: https://github.com/ahmedsam007/NanoJet-releases/releases

## System requirements
- macOS 13.0 (Ventura) or later

## Install
1) Download the latest `.zip` from the Releases page
2) Extract and drag `NanoJet.app` to `Applications`
3) First launch (Gatekeeper): right‑click `NanoJet.app` → Open → Open
   - If blocked, System Settings → Privacy & Security → Open Anyway

## Browser extension
- Chrome/Edge/Brave/Opera: use the extension zip included in each release asset
  - Open `chrome://extensions/` → enable Developer mode → Load unpacked → select extracted folder
- Firefox: install the `.xpi` from the release assets via `about:addons` → gear → Install Add-on From File…
- Safari: use the Mac App Store distribution (sideloading not supported)

## Verify download
Each release includes a SHA‑256 checksum. To verify:

```bash
shasum -a 256 NanoJet-vX.Y.Z.zip
```

## Privacy & license
- No analytics or tracking; downloads remain on your device
- Proprietary license; source code is not publicly available

## Support
Open an issue on the releases repository or contact the developer.

---

## Release notes
See the per‑release notes on the Releases page. Each release lists what’s included and any changes.
