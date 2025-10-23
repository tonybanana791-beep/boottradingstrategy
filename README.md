# Boot-Mainnet (Replit-ready)

Scaffolded Node.js (Express) project for autonomous ICO administration.

## Features included
- Blind Admin mode enabled by default (server/config/config.js)
- Masked wallet display (server/config/ui-wallet.json)
- Notification stubs for SMTP and Telegram (server/api/notifications.js)
- Admin-protected endpoints requiring `x-admin-key` header to access sensitive data
- Simple static dashboard (dashboard/src/index.html)

## How to run on Replit / locally
1. Copy `.env.example` to `.env` and set `ADMIN_MASTER_KEY` and other credentials.
2. `npm install`
3. `npm start`

## Security notes
- Do NOT commit real private keys.
- Use strong `ADMIN_MASTER_KEY` and store secrets securely.
- For production use hardware wallets / multisig / secure key management.

