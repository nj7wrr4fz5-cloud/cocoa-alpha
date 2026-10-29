# COCOA-ALPHA v3.4

Live trading terminal for **MOEX** futures:

- **CCX6** — Cocoa (COCOA-11.26)
- **SiZ6** — USD/RUB (hedge)

## Features

- Real-time data from Moscow Exchange (ISS API)
- Dynamic entry / stop / TP levels from session high/low
- Bias + confidence scoring
- GO / WAIT / NO gate filter (edge setups preferred)
- Position size calculator (risk-based)
- One-click Telegram signals to group topic «Информативно»
- Mobile-friendly dark UI

## Live

Open the GitHub Pages site after enabling Pages (Settings → Pages → Deploy from branch `main` / root).

## Telegram

Uses connector:
- URL: `https://telega-send.netlify.app/.netlify/functions/telegram-send`
- Sends to alias `info` (topic 4)

Buttons in the app:
- **Статус** — short snapshot
- **Полный сигнал** — full plan + reasons

## How to use

1. Open the page
2. Wait for LIVE data
3. Look at Gate:
   - **GO** → can consider entry
   - **ЖДАТЬ** → not enough conditions
   - **НЕТ** → no trade
4. Use position calculator (Risk tab)
5. Send signal to Telegram when needed

## Stack

Pure HTML + JS. No build step. Works on GitHub Pages.

---

COCOA-ALPHA · ELITE edge logic · v3.4
