# DairyCheck 🥛

A simple web app I built to help farmers and dairy owners check milk quality on the spot — no lab needed.

## Why I built this

Milk adulteration is a real problem. Farmers often don't have an easy way to check if their milk meets quality standards before selling it. I wanted to build something practical that anyone could use on their phone, without needing any special equipment.

## What it does

- Register your farm and sign in
- Enter basic milk parameters — density, temperature, fat content, pH, and SNF
- Get an instant Grade A / B / C result with a quality score
- See what's wrong if the milk fails (e.g. density too low = possible water adulteration)
- Track all your past tests in one place
- Generate a summary report for any date range

## How to use it

Just open the link, register your farm, and start testing. No installation needed — works on any phone or computer.

**Live app:** https://daksh01-tech.github.io/dairycheck

## Parameters checked

| Parameter | Normal range |
|-----------|-------------|
| Density | 1.028 – 1.034 g/mL |
| Temperature | 2 – 6°C |
| Fat content | 3.0 – 4.5% |
| pH level | 6.6 – 6.8 |
| SNF | 8.0 – 9.0% |

## Grading

- **Grade A** — 85 to 100 — Fresh and safe for sale
- **Grade B** — 65 to 84 — Acceptable, use with caution  
- **Grade C** — Below 65 — Rejected, not fit for sale
