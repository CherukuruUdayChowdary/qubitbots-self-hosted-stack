# Qubitbots internship handover

Code and Docker config for everything built during Uday Chowdary Cherukuru's
internship (ended Oct 2026). On the VPS each project lives in /opt/qubitbots/<name>.
Read the handover guide in docs/ first.

| Folder in projects/ | System |
| --- | --- |
| hermes | Hermes Agent + Telegram bot "Agenza" |
| whatsapp-webjs | WhatsApp REST API (whatsapp-web.js) |
| openwa | open-wa WhatsApp API |
| nextcloud | Nextcloud stack (app, cron, db, redis) |
| paperless | Paperless-ngx + paperless-mcp |
| docmost | Docmost wiki |
| jellyfin | Jellyfin media server (R2 media at /mnt/r2media) |
| browser-use | browser-use web UI |

All secrets are replaced with <PLACEHOLDER>. Real values are handed over separately.
Start any project: cd /opt/qubitbots/<name> && docker compose up -d

OpenWA source code: https://github.com/rmyndharis/OpenWA (only our docker-compose.yml, Dockerfile and .env.example are in projects/openwa).
