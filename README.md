# PesaCheck — Kenya's Financial Intelligence Platform

> 32 free financial tools. Zero data uploaded. 100% private. Works on any phone.

**Live at:** [pesacheck.vercel.app](https://pesacheck.vercel.app) · Built by [WealthWise](https://youtube.com/@wealthwisefinancestate)

---

## What is PesaCheck?

PesaCheck is a free financial tools platform built for Kenyans and the world. Every tool answers one specific financial question — instantly, privately, in Swahili or English.

All calculations happen in your browser. Nothing is uploaded to any server. Your M-Pesa statement, salary, debts, and goals never leave your device.

---

## Tools (32 total)

### Personal Finance
| Tool | What it does |
|------|-------------|
| M-Pesa Statement Analyzer | Upload your statement PDF for a full Financial Identity Card, loan spiral detection, invisible tax, and 12-month trajectory |
| PAYE Decoder | Exact 2026 deductions: NSSF, SHIF, Housing Levy, PAYE — and how to legally reduce them |
| Salary Reality Check | Are you underpaid? Compare your salary against Kenyan market data |
| Can I Afford This? | One number in, honest verdict out |
| Survival Fund Calculator | How many days would you survive if income stopped tomorrow? |
| Budget Builder | 50/30/20 rule with live tracking |
| Net Worth Tracker | Assets minus liabilities — your real financial position |

### Debt & Loans
| Tool | What it does |
|------|-------------|
| Loan Checker | True total cost of any loan — Tala, Branch, bank, SACCO |
| Debt Snowball Planner | Your exact debt-free date and payoff sequence |

### Saving & Investing
| Tool | What it does |
|------|-------------|
| Investment Calculator | Compound growth projection up to 30 years |
| T-Bill & M-Akiba Tracker | Exact yield, maturity date, comparison vs SACCOs and MMFs |
| Financial Goal Planner | Weekly savings plan with countdown for any goal |
| 52-Week Savings Challenge | Progressive savings tracker — KES 137,800 in one year |
| Inflation Calculator | How much purchasing power your cash is losing |

### Business
| Tool | What it does |
|------|-------------|
| Side Hustle Profit Calculator | Real hourly rate after all costs |
| Business Break-Even Calculator | Exact units needed to profit |
| Self-Employed Tax Calculator | KRA turnover tax, income tax, filing deadlines |
| Property Rental Yield | Gross and net yield, ROI timeline, vs T-bills |

### Life Planning
| Tool | What it does |
|------|-------------|
| School Fees Planner | Week-by-week savings plan per term |
| Retirement Reality Check | NSSF gap, nest egg needed, monthly savings required |
| Rent vs Buy Calculator | 20-year wealth comparison for both paths |
| Car Total Cost Calculator | True monthly cost including depreciation |
| Wedding & Event Budget Planner | Full cost breakdown, monthly savings target |
| Insurance Needs Calculator | Life cover, NHIF tier, education fund |
| Harambee & Giving Planner | Sustainable giving budget |

### Community & Groups
| Tool | What it does |
|------|-------------|
| Chama Group Tracker | Member contributions, shares, group health score |
| Bill Split Calculator | Equal, custom, or percentage splits — WhatsApp-ready |

### Protection
| Tool | What it does |
|------|-------------|
| Investment Scam Detector | Risk score for any investment offer |
| Diaspora Remittance Comparator | Best service for sending money home |

### Wellbeing
| Tool | What it does |
|------|-------------|
| Monthly Financial Health Score | 10-question monthly check-in, score out of 100 |
| Lifestyle Rich or Actually Rich? | 7-question wealth quiz |

---

## Tech Stack

- **Pure HTML/CSS/JavaScript** — no frameworks, no build process
- **PDF.js** (Mozilla, Apache 2.0) — for M-Pesa statement parsing, runs in browser
- **Vercel** — hosting with edge CDN
- **Formspree** — form handling for waitlist and newsletter
- **Service Worker** — offline capability after first visit
- **PWA Manifest** — installable on Android and iPhone home screens

All financial calculations are client-side only. There is no backend.

---

## Privacy

PesaCheck does not collect, transmit, or store any financial data. The only data that may leave your device is:
- Your email if you voluntarily join the Pro waitlist or newsletter
- Anonymous usage statistics via Vercel Analytics (page visits only, no personal data)

Full privacy policy: [pesacheck.vercel.app/privacy](https://pesacheck.vercel.app)

---

## Data Sources

All calculations use publicly available official data:
- **PAYE / NSSF / SHIF / Housing Levy**: Kenya Revenue Authority (kra.go.ke) — 2026 rates
- **T-bill yields**: Central Bank of Kenya (cbk.go.ke) — weekly auction averages
- **Inflation**: Kenya National Bureau of Statistics (knbs.or.ke)
- **CMA licensed investments**: Capital Markets Authority (cma.or.ke)

---

## License

MIT License — © 2026 WealthWise

Permission is hereby granted, free of charge, to any person obtaining a copy of this software to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions.

---

## Follow WealthWise

- **YouTube**: [@wealthwisefinancestate](https://youtube.com/@wealthwisefinancestate)
- **Email**: investwithwealthwise@gmail.com

> PesaCheck is a financial education tool, not a licensed financial advisor. Results are for informational purposes only.
