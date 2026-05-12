# 80/20 Barbell Portfolio

An interactive single-page web app for visualizing and simulating an **80% bear / 20% bull barbell portfolio** strategy.

## Strategy Overview

This is a Nassim Taleb-inspired barbell approach:
- **80% Bear Leg** — Inverse ETFs (SQQQ, SPXU, SDS, TZA, SH) + defensive safe-havens (GLD, TLT, XLP)
- **20% Bull Leg** — High-velocity instruments targeting ≥2%/day (TQQQ, UPRO, SOXL, NVDA, TSLA, MSTR)

## Features

- 📊 **Overview** — KPI cards, donut allocation chart, filterable holdings table
- 🐻 **Bear Leg** — Instrument breakdown + volatility decay simulation
- 🐂 **Bull Leg** — Per-instrument cards + daily move range chart
- 🧮 **Return Simulator** — Interactive sliders for daily return, trading days, capital, and allocation with live compounding math
- 🛡️ **Risk Analysis** — Color-coded risk matrix + scenario outcome chart
- ⚙️ **Customize** — Toggle individual instruments on/off

## Usage

Open `barbell-portfolio.html` directly in any modern browser — no build step, no server needed.

Or deploy to [Netlify](https://netlify.com) by dragging the file into the Netlify dashboard.

## Stack

- Vanilla HTML/CSS/JS (single file, zero dependencies installed)
- [Chart.js](https://www.chartjs.org/) for data visualization
- [Lucide](https://lucide.dev/) for icons
- Google Fonts (Inter + JetBrains Mono)

## Disclaimer

This is a **simulation tool for educational purposes only**. Nothing here constitutes financial advice. Past performance of any instrument does not guarantee future results. Leveraged and inverse ETFs carry significant risks and are not suitable for long-term buy-and-hold strategies.
