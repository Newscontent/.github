# Security

Report security issues privately to **support@eyenewz.com**. Do not open a public GitHub issue for secrets, keys, or user data.

## Do not commit

- `.env`, `secrets/`, SMTP passwords, API keys
- Android `release.keystore`, `keystore.properties`, `google-services.json`
- Firebase Admin SDK JSON
- VPS SSH private keys

## Production

The news API runs on a VPS (`https://api.eyenewz.com`). The Play Store app is `com.prod.contentnews`. We do **not** publish GitHub Packages.

If you accidentally pushed a secret, rotate it on the VPS / Play Console / provider dashboard and tell an org owner. Do not paste the value into Slack or a ticket.
