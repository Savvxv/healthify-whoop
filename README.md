# Healthify WHOOP setup

Public privacy policy website for Healthify, an independent app in development.

Privacy policy URL: https://savvxv.github.io/healthify-whoop/

GitHub Pages publishes `index.html` from the root of `main`.

## OAuth callback still required

This repository hosts a static privacy policy, not an OAuth backend. Do not use the privacy page as the OAuth redirect URL. Healthify must implement a callback on its own backend and register that exact HTTPS address in WHOOP's developer dashboard. A local backend can use a suitable HTTPS development tunnel. The app must validate OAuth state and exchange authorization codes server-side. Do not put client secrets, tokens, or health records in this repository or in browser code.

Update the privacy policy to match the actual hosting, storage, retention, contact channel, and deletion controls before inviting other users to connect.

WHOOP documentation: https://developer.whoop.com/docs/developing/oauth/
