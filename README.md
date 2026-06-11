# Password Strength Meter

This tool estimates a password's entropy in bits and a rough offline crack time, scoring it from very weak to very strong. It runs only in your browser; the password is never transmitted, stored, or saved.

**Live demo:** https://0xelitesystem.github.io/password-strength-meter/

## What it does

Type or paste a password. The tool estimates entropy as the length multiplied by the bits per character implied by the character types present, lowercase, uppercase, digits, and symbols. It shows the bit count, a grade, a five-segment meter, a crack-time estimate, and which character classes and length thresholds are met.

The crack time assumes a fast offline guessing rate and is an order-of-magnitude figure, not a guarantee. Because everything stays in the browser, nothing leaves the page; still, avoid pasting a live password on a machine you do not trust.

## Aesthetic

A brushed-steel safe panel with a combination dial and tick ring drawn in SVG, a glowing segmented readout, and class indicators.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
