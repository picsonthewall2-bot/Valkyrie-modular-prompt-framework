# Valkyrie Modular Prompt Framework

> A structured AI decision-making system for high-volatility investment analysis. Built from scratch by a self-taught developer across 6 major iterations.

---

## What Is Valkyrie?

Valkyrie is a modular prompt engineering framework designed to bring structured, multi-stage reasoning to complex, high-stakes decisions — specifically micro-cap stocks in defense, AI, and drone sectors (SPAI, RCAT, KTOS, AVAV, BBAI).

Instead of asking an AI a single question and hoping for a good answer, Valkyrie breaks every analysis into four enforced stages:

1. **Risk Assessment Module** — Identifies 3–5 key downside risks, stop-loss levels, and potential drawdown range
2. **Opportunity Analysis Module** — Catalysts, asymmetric upside, and probabilistic 1-year scenarios
3. **Validation & Controls Layer** — Fact-checks assumptions, presents counter-thesis, assigns confidence levels
4. **Strategic Synthesis** — Clear recommendation (Buy / Accumulate / Hold / Trim / Sell / Avoid) with probability-weighted return outlook

---

## Why I Built This

I was using ChatGPT, Gemini, and Grok for stock research but getting inconsistent, unstructured outputs. I needed a system that forced the AI to think in a disciplined sequence — risk first, opportunity second, validation third — before making any recommendation.

Valkyrie evolved from a simple metaphorical prompt (V1) into a full corporate governance-style decision framework (V6) with Python integration for quantitative support.

---

## Technical Stack

- **Prompt Engineering:** Chain-of-Thought, few-shot, zero-shot, role prompting, self-critique loops
- **Python:** yfinance (data), NumPy (Monte Carlo simulations), Pandas (analysis)
- **LLMs Tested On:** ChatGPT (GPT-4), Google Gemini, xAI Grok, Anthropic Claude
- **Quantitative Methods:** Monte Carlo simulation, annualized volatility, max drawdown, Value at Risk (VaR 5%)

---

## Repository Structure

```
Valkyrie-modular-prompt-framework/
├── README.md                  # This file
├── Valkyrie_sample            # Sample output / prompt template
└── examples/                  # Example analyses and outputs
```

---

## How To Use

**Option 1 — Paste into any AI:**
Copy the master system prompt from `Valkyrie_sample` and paste it into ChatGPT, Claude, or Gemini. The AI will activate Valkyrie mode and respond to stock queries in the structured 4-stage format.

**Option 2 — Run quantitative analysis locally:**
```bash
pip install numpy pandas yfinance
python valkyrie_sentinel.py
```
This runs Monte Carlo simulations and risk calculations on any ticker and outputs a structured recommendation.

---

## Project Evolution

| Version | Key Change |
|---------|------------|
| V1–V2 | Metaphorical warrior-based prompt structure |
| V3–V4 | Modular layering (Armour / Sword / Shield) |
| V5 | Python integration for quantitative support |
| V6 | Full corporate governance framework, professional tone, Monte Carlo simulations |

---

## About The Developer

James Keeling — Self-taught AI and prompt engineering specialist based in Blue Ridge, GA.
Built this project independently with no formal computer science background.
Open to remote roles in AI, prompt engineering, research, or data analysis.

📧 picsonthewall2@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/james-keeling)

---

*This project is for educational and research purposes. Nothing here constitutes financial advice.*
