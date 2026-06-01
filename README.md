# CryptoLearn — Crypto Trading Challenges

An interactive browser-based learning app for beginner crypto traders. Work through 12 structured challenges covering market structure, technical analysis, risk management, and trading psychology.

## Features

- 12 progressive challenges across 4 sections: Foundations, Technical Skills, Risk & Strategy, Mindset & Review
- **Read first** — learning material with key concepts and watch-out callouts before each challenge
- **Task checklists** — tick off practical steps as you go
- **Knowledge quizzes** — multiple choice with explanations, unlocking one at a time
- **Answer checker** — write your reflection and get scored feedback (smart local rubric, or full AI feedback with an API key)
- **XP system** — earn points as you complete challenges
- **Market scanner** — simulated signal dashboard for context
- **Strategy library** — recommended strategies for beginners with Claude's take

## Usage

Just open `index.html` in any browser — no server, no install, no dependencies.

### Optional: AI-powered answer feedback

Paste your [Anthropic API key](https://console.anthropic.com/) into the field at the bottom of the sidebar. It's saved to localStorage so you only enter it once. Without a key, the app uses a smart local rubric checker instead.

## Sections

| # | Section | Challenges |
|---|---------|-----------|
| 1–3 | Foundations | Market structure, Candlestick charts, Order types |
| 4–6 | Technical Skills | Support & resistance, Indicators (RSI/EMA), Multi-timeframe analysis |
| 7–9 | Risk & Strategy | Risk rules, Paper trading, Risk:Reward ratio |
| 10–12 | Mindset & Review | Trade journal, Famous blow-ups, Define your edge |

## Deploying

Works as a static site on any host. Recommended: drag `index.html` to [Netlify Drop](https://app.netlify.com/drop) for an instant public URL, or connect this repo to Netlify/Vercel for auto-deploy on push.

## Stack

Single-file vanilla HTML/CSS/JS — no frameworks, no build step, no dependencies.
