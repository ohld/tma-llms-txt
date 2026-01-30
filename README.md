# Telegram Mini Apps — LLM Developer Guide

Feed these files to AI coding tools to build Telegram Mini Apps.

## Quick Start

1. Open Claude Code, Cursor, or ChatGPT
2. Paste: `https://raw.githubusercontent.com/ohld/tma-llms-txt/main/llms-full.txt`
3. Say: "Build me a Telegram Mini App that does [your idea]"

## Files

| File | What it is |
|------|------------|
| [`llms.txt`](llms.txt) | Index with links — overview for LLMs |
| [`llms-full.txt`](llms-full.txt) | Complete guide (~20K words) — all you need |

## What's Inside

The guide covers the full TMA development stack:

- **Agent Instructions** — decision tree, scaffold steps, top 10 LLM mistakes
- **Getting Started** — BotFather setup, ngrok for local HTTPS, Hello World
- **Frontend** — @tma.js/sdk (official + community), MainButton, theming, storage
- **Authentication** — initData, HMAC-SHA256 validation (Node.js + Python)
- **TON Connect** — wallet connection, TON/jetton transfers, TONAPI
- **Backend** — Express + grammY (Node.js) or FastAPI + aiogram 3 (Python)
- **Deployment** — Docker Compose, Coolify, static hosting
- **Testing** — ngrok, mock initData, debugging on iOS/Android/Desktop

## References

- [Telegram Mini Apps Official Docs](https://core.telegram.org/bots/webapps)
- [Community Docs](https://docs.telegram-mini-apps.com/)
- [TON Connect](https://docs.ton.org/v3/guidelines/ton-connect/frameworks/react)
- [grammY Bot Framework](https://grammy.dev/)
- [Base Mini Apps llms.txt](https://docs.base.org/mini-apps/llms.txt) (format inspiration)
- [Farcaster Mini Apps llms-full.txt](https://miniapps.farcaster.xyz/llms-full.txt) (format inspiration)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

## License

MIT
