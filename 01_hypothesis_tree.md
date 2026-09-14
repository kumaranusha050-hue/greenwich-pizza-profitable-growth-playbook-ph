# Greenwich Growth Playbook (Philippines)
Defending and scaling a local champion vs. Domino's using three margin-safe initiatives:
1) Student Combo (₱149 personal meal, 2–5 PM weekdays)  
2) Flash Sale (4–6 PM, Wed & Fri, app-only personal + 1 topping)  
3) Kids + Family Bundle (ear-shaped mini pizza + side + drink + dessert)

## Why this matters
Domino's runs frequent deep discounts (e.g., 50% off windows, BOGO). Competing on blanket discounts erodes margin. Greenwich can win by owning local occasions (after-class, family dinners) with bundled value that protects contribution. [81][84][85]

## Hypothesis
A bundled, segment-specific playbook will:
- Increase contribution profit via higher frequency and ticket size  
- Grow app-based loyalty (student sign-ups, family repeats)  
- Avoid cannibalizing peak dinner traffic through daypart and channel guardrails

## Repo contents
- `docs/` – market context, initiative designs, financial assumptions  
- `data/` – sample menu prices and promo benchmarks (Greenwich vs. Domino's PH)  
- `notebooks/` – market sizing, initiative simulator (base/upside/downside), A/B test design  
- `src/` – contribution margin models and visualization helpers  
- `outputs/` – 1-page executive summary and slide deck PDFs

## How to use
1) Review `docs/initiative_designs.md` for mechanics and guardrails.  
2) Run `notebooks/02_initiative_simulator.ipynb` to see contribution impact by scenario.  
3) Adapt price points and food-cost assumptions to your city cluster and re-run.

## KPIs we track
- Contribution per order (by initiative)  
- New app sign-ups and 30-day repeat rate  
- Cannibalization-adjusted net promotion contribution [68]  
- Family ticket lift and kids' bundle attachment rate [77][78]
