# QR Generator

Generate QR codes entirely in your browser. Optional center logo, no uploads, no account.

## Features

- URL or any text
- Optional logo (drag-and-drop or file picker)
- Logo size and opacity controls
- Error correction levels (L / M / Q / H)
- Custom foreground / background colors
- Download PNG or copy image to clipboard
- 100% client-side — nothing leaves your device

## Logo tips

- Keep the logo relatively small (default ~18% of the code)
- Prefer simple, high-contrast logos
- Use **H (High)** error correction when a logo is present (selected automatically if you were on L/M)
- Lower opacity lets more QR modules show through; that can help scanning but makes the logo fainter
- Always test-scan on a phone before printing a large batch

## Deploy

Same as any static site: upload `index.html` to GitHub Pages, Cloudflare Pages, Netlify, etc.

## Tech

- [qrcode](https://github.com/soldair/node-qrcode) (browser build via CDN)
- Vanilla HTML / CSS / JS

## License

MIT
