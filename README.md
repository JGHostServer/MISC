# MISC

Password-protected static publication of the Mathematics Journal Atlas.

The published repository contains only an AES-256-GCM encrypted HTML payload. The journal page is decrypted locally in the visitor's browser after the shared password is entered.

## Publication

GitHub Pages publishes `index.html` from the `main` branch root. The `.nojekyll` marker disables Jekyll processing.

## Security note

This is static client-side encryption with a high-entropy shared password. It protects the plaintext from casual browsing and repository inspection, but it does not provide server-side rate limiting or individual user accounts.
