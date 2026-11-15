# TG-FileStreamBot (psbmlabs)

Telegram bot that turns any file into a direct **download** link, an inline **stream** link
and a **browser watch page** (`/watch/...`).

Customized and maintained by **Engr. Prothes** (psbmlabs).

## Env vars
`API_ID`, `API_HASH`, `BOT_TOKEN`, `BIN_CHANNEL`, `PORT=8080`, `FQDN`, `HAS_SSL=True`, `NO_PORT=True`
(optional: `DATABASE_URI`, `ALLOWED_USERS`, ...see `WebStreamer/vars.py`)

## Links the bot returns
- `/watch/<id><hash>/<filename>` browser player page
- `/s/<id><hash>/<filename>` inline stream (VLC / MX Player / `<video src>`)
- `/<id><hash>/<filename>` download

## Credits & license
Based on [GouthamSER/TG-FileStreamBot](https://github.com/GouthamSER/TG-FileStreamBot)
(which builds on EverythingSuckz/TG-FileStreamBot and eyaadh/megadlbot_oss).
Licensed under the GNU AGPL-3.0, see `LICENSE`. Original copyright notices are retained as the license requires.
Modifications by Engr. Prothes.
