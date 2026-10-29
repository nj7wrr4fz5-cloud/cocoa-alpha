# COCOA-ALPHA v3.5

Live trading terminal for **MOEX** futures:

- **CCX6** — Cocoa (COCOA-11.26)
- **SiZ6** — USD/RUB (hedge)

## Security (v3.5)

**No API keys in the code.**  
Telegram key is entered by the user in Settings and stored only in `localStorage` of their browser.

Previously exposed keys should be rotated.

## Features

- Real-time data from Moscow Exchange (ISS API)
- Dynamic entry / stop / TP levels
- Bias + confidence + GO/WAIT/NO gate
- Position size calculator
- Telegram send (user-provided key)
- Mobile-friendly dark UI

## Live

https://nj7wrr4fz5-cloud.github.io/cocoa-alpha/

(Enable Pages: Settings → Pages → Deploy from branch `main` / root)

## How to enable Telegram

1. Open the app → **Настройки**
2. Paste your `x-api-key`
3. Set chat alias (default `info`)
4. Save
5. Buttons «Статус» / «Полный сигнал» become active

Key never leaves the user's browser.

## Stack

Pure HTML + JS. No build. GitHub Pages ready.
