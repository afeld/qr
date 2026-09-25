# QR Codes

A small, mobile-first web page for sharing your email, website, or phone number as a QR code.

- Save named entries of three types:
  - **Website** – encodes the URL (adds `https://` if missing)
  - **Email** – encodes a `mailto:` link, with an optional subject
  - **Phone** – encodes a vCard contact card, so scanning adds a contact rather than dialing
- Tap an entry to show its QR code full-screen for someone else to scan.
- Entries are stored only in the browser's `localStorage`; nothing is sent anywhere.

## Running

Just open `index.html` in a browser.

## License

[MIT](LICENSE)
