#Trades by Sean Scoring System
V1 - 12/4/2025

# Stock Scoring System

Score each stock by answering the following 25 questions. Sum all points for the total score.

---

## Q1. Sales Growth
**Data needed:** Annual Sales Growth % | Quarterly Sales (most recent) | Quarterly Sales (same quarter last year)

Calculate quarterly YoY growth: (Recent Quarter - Year-Ago Quarter) / Year-Ago Quarter

| Condition | Points |
|-----------|--------|
| Annual ≥50% AND Quarterly YoY > Annual | 5 |
| Annual ≥50% AND Quarterly YoY positive but ≤ Annual | 4 |
| Annual 20-49% AND Quarterly YoY > Annual | 4 |
| Annual 20-49% AND Quarterly YoY positive but ≤ Annual | 3 |
| Annual 1-19% AND Quarterly YoY positive | 2 |
| Annual 0% AND Quarterly YoY positive | 1 |
| Annual positive AND Quarterly YoY negative | 1 |
| Annual negative AND Quarterly YoY positive | 1 |
| Annual negative AND Quarterly YoY negative | 0 |

---

## Q2. Operating Income Growth
**Data needed:** Annual Operating Income Growth % | Quarterly Operating Income (most recent) | Quarterly Operating Income (same quarter last year)

Calculate quarterly YoY growth: (Recent Quarter - Year-Ago Quarter) / Year-Ago Quarter

| Condition | Points |
|-----------|--------|
| Annual ≥50% AND Quarterly YoY > Annual | 5 |
| Annual ≥50% AND Quarterly YoY positive but ≤ Annual | 4 |
| Annual 20-49% AND Quarterly YoY > Annual | 4 |
| Annual 20-49% AND Quarterly YoY positive but ≤ Annual | 3 |
| Annual 1-19% AND Quarterly YoY positive | 2 |
| Annual 0% AND Quarterly YoY positive | 1 |
| Annual positive AND Quarterly YoY negative | 1 |
| Annual negative AND Quarterly YoY positive | 1 |
| Annual negative AND Quarterly YoY negative | 0 |

---

## Q3. Cash Flow Growth
**Data needed:** Annual Operating Cash Flow Growth % | Quarterly Operating Cash Flow (most recent) | Quarterly Operating Cash Flow (same quarter last year)

Calculate quarterly YoY growth: (Recent Quarter - Year-Ago Quarter) / Year-Ago Quarter

| Condition | Points |
|-----------|--------|
| Annual ≥50% AND Quarterly YoY > Annual | 5 |
| Annual ≥50% AND Quarterly YoY positive but ≤ Annual | 4 |
| Annual 20-49% AND Quarterly YoY > Annual | 4 |
| Annual 20-49% AND Quarterly YoY positive but ≤ Annual | 3 |
| Annual 1-19% AND Quarterly YoY positive | 2 |
| Annual 0% AND Quarterly YoY positive | 1 |
| Annual positive AND Quarterly YoY negative | 1 |
| Annual negative AND Quarterly YoY positive | 1 |
| Annual negative AND Quarterly YoY negative | 0 |

---

## Q4. Valuation (P/E Ratio)
**Data needed:** Price-to-Earnings Ratio (TTM - Trailing Twelve Months)

| P/E TTM | Points |
|---------|--------|
| 1–60 | 4 |
| 61–100 | 3 |
| 101–150 | 2 |
| 151–199 | 1 |
| 200–399 or Zero/N/A | 0 |
| ≥400 | -6 |

---

## Q5. Profit Margin
**Data needed:** Net Profit Margin %

| Profit Margin | Points |
|---------------|--------|
| >50% | 5 |
| 30–50% | 4 |
| 15–29% | 3 |
| 5–14% | 2 |
| 0–4.9% | 1 |
| <0% (Unprofitable) | 0 |

---

## Q6. 1-Month Price Change
**Data needed:** Stock Price % Change over last 1 month

| 1-Month Change | Points |
|----------------|--------|
| >10% | 3 |
| 5–10% | 2 |
| 0–4.9% | 1 |
| <0% | 0 |

---

## Q7. 10-Day Price Change
**Data needed:** Stock Price % Change over last 10 trading days

| 10-Day Change | Points |
|---------------|--------|
| >15% | 3 |
| 5–14% | 2 |
| 0–4% | 1 |
| <0% | 0 |

---

## Q8. Relative Volume
**Data needed:** Today's Volume | 20-Day Average Volume

Calculate: Today's Volume ÷ 20-Day Average Volume

| Relative Volume | Points |
|-----------------|--------|
| >1.5× | 3 |
| 1.1–1.5× | 2 |
| 0.8–1.0× | 1 |
| <0.8× | 0 |

---

## Q9. Price vs Moving Averages
**Data needed:** Current Price | 50-Day Moving Average | 200-Day Moving Average

| Condition | Points |
|-----------|--------|
| Price above both 50D and 200D MA | 3 |
| Price above one MA | 2 |
| Price below both but at least one within 5% | 1 |
| Price below both by more than 5% | 0 |

---

## Q10. Average Daily Volume
**Data needed:** 20-Day Average Volume

| Avg Volume | Points |
|------------|--------|
| >1,000,000 | 3 |
| 500,000–1,000,000 | 2 |
| 200,000–500,000 | 1 |
| <200,000 | 0 |

---

## Q11. Ownership & Analyst Coverage
**Data needed:** Insider Ownership % | Institutional Ownership % | Number of Analysts Covering

| Condition | Points |
|-----------|--------|
| Insider Ownership > 0% | +1 |
| Institutional Ownership > 20% | +1 |
| Analyst Coverage > 5 analysts | +1 |

(Max 3 points total)

---

## Q12. Debt-to-Equity Ratio
**Data needed:** Debt-to-Equity Ratio

| Debt/Equity | Points |
|-------------|--------|
| <0 (Negative Equity) | -5 |
| >3.0 | -3 |
| 1.5–3.0 | 1 |
| 0.5–1.5 | 2 |
| <0.5 | 3 |

---

## Q13. Weighted Alpha
**Data needed:** Weighted Alpha (1-year price performance weighted toward recent activity)

| Weighted Alpha | Points |
|----------------|--------|
| >80 | 3 |
| 40–79 | 2 |
| 0–39 | 1 |
| <0 | 0 |

---

## Q14. EPS Growth (Prior Year)
**Data needed:** Earnings Per Share Growth % (most recent fiscal year vs. prior year)

| EPS Growth | Points |
|------------|--------|
| >100% | 4 |
| 50–100% | 3 |
| 20–49% | 2 |
| 1–19% | 1 |
| ≤0% | 0 |

---

## Q15. Return on Equity (ROE)
**Data needed:** Return on Equity %

| ROE | Points |
|-----|--------|
| >20% | 3 |
| 10–20% | 2 |
| 5–10% | 1 |
| <5% | 0 |

---

## Q16. Return on Assets (ROA)
**Data needed:** Return on Assets %

| ROA | Points |
|-----|--------|
| >15% | 3 |
| 10–14.9% | 2 |
| 5–9.9% | 1 |
| <5% | 0 |

---

## Q17. Range Position
**Data needed:** Current Price | First Resistance Level | First Support Level

Calculate: (Price - Support) ÷ (Resistance - Support)

| Position | Points |
|----------|--------|
| Breakout: Price > Resistance | 4 |
| Buy Zone: Ratio ≤ 0.20 (bottom 20% of range) | 3 |
| Mid-Range: Ratio 0.21–0.80 | 2 |
| Trap: Ratio ≥ 0.81 but Price ≤ Resistance | 0 |

---

## Q18. Options Available
**Data needed:** Does the stock have listed options?

| Options | Points |
|---------|--------|
| Yes | 1 |
| No | 0 |

---

## Q19. Country of Domicile
**Data needed:** Country where company is headquartered/domiciled

| Country | Points |
|---------|--------|
| United States | 1 |
| Other | -5 |

---

## Q20. Profitability & Growth Check
**Data needed:** Net Profit Margin % | Annual Sales Growth %

| Condition | Points |
|-----------|--------|
| Profit Margin ≥ 0% | 0 |
| Profit Margin < 0% AND Sales Growth ≥ 25% | 0 |
| Profit Margin < 0% AND Sales Growth < 25% | -5 |

---

## Q21. Cash Burn Risk
**Data needed:** Net Profit Margin % | Quarterly Operating Cash Flow (most recent) | Market Cap

| Condition | Points |
|-----------|--------|
| Profit Margin ≥ 0% | 0 |
| Profit Margin < 0% AND Quarterly Cash Flow ≥ 0 | 0 |
| Profit Margin < 0% AND Quarterly Cash Flow < 0 AND Market Cap ≥ $10B | 0 |
| Profit Margin < 0% AND Quarterly Cash Flow < 0 AND Market Cap < $10B | -5 |

---

## Q22. Deterioration Check
**Data needed:** Net Profit Margin % | Weighted Alpha

| Condition | Points |
|-----------|--------|
| Profit Margin ≥ -25% | 0 |
| Profit Margin < -25% AND Weighted Alpha ≥ 0 | 0 |
| Profit Margin < -25% AND Weighted Alpha < 0 | -5 |

---

## Q23. Trend Consistency
**Data needed:** 3-Month Price Change % | 52-Week Price Change %

| Condition | Points |
|-----------|--------|
| Both positive AND 52W > 3M (steady climb) | 3 |
| Both positive AND 3M > 52W (accelerating) | 3 |
| Only one positive | 1 |
| Both negative | 0 |

---

## Q24. Financial Strength
**Data needed:** Net Profit Margin % | Return on Equity % | Debt-to-Equity Ratio

| Condition | Points |
|-----------|--------|
| Profit ≥ 20% AND ROE ≥ 20% AND Debt/Equity < 0.5 | 3 |
| Profit ≥ 15% AND ROE ≥ 15% AND Debt/Equity < 1.0 | 2 |
| Profit ≥ 10% AND ROE ≥ 10% AND Debt/Equity < 1.5 | 1 |
| Otherwise | 0 |

---

## Q25. Sector Preference
**Data needed:** Company Sector/Industry

| Sector | Points |
|--------|--------|
| Technology, Computers, Software | 4 |
| Aerospace, Defense | 3 |
| Finance, Business Services | 2 |
| Energy, Industrials, Basic Materials, Transportation, Utilities, Construction | 1 |
| Consumer Staples, Consumer Discretionary, Automotive, Retail, Healthcare/Medical | 0 |

---

## Score Range

- **Maximum possible:** 74 points
- **Minimum possible:** -31 points (if all penalties apply)
