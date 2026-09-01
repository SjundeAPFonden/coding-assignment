# Coding Assignment – Junior Developer AP7

Welcome to the technical assignment for the Junior Developer position at AP7. This assignment is designed to evaluate how you approach code structure, data modelling, and problem solving in a realistic but simplified domain. We are not looking for perfection — we are looking for clean, well-structured code, and thoughtful design decisions.

**Estimated time: 2–5 hours**

> **A note on scope:** This assignment is intentionally time-boxed. You will need to prioritize what to build, simplify, or skip. We expect trade-offs, rough edges, and unimplemented bonus items — that's completely fine. What matters more is that you can explain *what* you prioritized and *why*, and what you'd do differently with more time. Please leave a short note in your README (e.g. "Given more time, I would...") — it gives us something concrete to discuss together afterwards.

## What to Build

Your application should support the following functionality:

### Portfolios and instruments
- Create and list portfolios
- Create and list instruments

### Trades
- Record a trade (buy or sell) for a given instrument and portfolio
- List all trades, with optional filtering by portfolio or instrument

### P&L calculation
- Calculate the profit and loss (P&L) for a given portfolio based on recorded trades
- Assume a simplified model: calculate the net position value based on trade history. You are free to define and document your assumptions.

A command-line interface is sufficient. A GUI is not required.

## Data Model

The following is a suggested starting point. You are free to extend or adjust it as you see fit — and if you do, briefly explain why.

| Entity | Suggested fields |
|---|---|
| Portfolio | name, currency |
| Instrument | name, instrument type (e.g. stock, bond, future) |
| Trade | instrument, portfolio, quantity, price, timestamp, direction (buy/sell) |

You may assume:
- All instruments trade in the portfolio's currency (no FX needed)
- Trades are valid unless otherwise handled by your application

If you introduce additional assumptions, please document them.

## Technical Requirements

- Python 3.x
- Include a `README.md` with clear instructions on how to install dependencies (if any) and run the application
- Code should be well-structured, easy to follow, and appropriately commented

## Bonus

- Unit tests
- Input validation with helpful error messages
- Data persistence

## Evaluation Criteria

We will assess your submission on:

| Area | What we look for |
|---|---|
| Code structure | Logical separation of concerns; appropriate use of classes, modules, or functions |
| Readability | Naming, clarity, and appropriate use of comments |
| Data modelling | Logical and consistent representation of the domain. Proper handling of relationships. |
| Input handling | Behaviour with invalid or unexpected input and quality of error messages |
| P&L logic | Correctness and clarity of the calculation and clear explanation of assumptions |
| Trade-offs & prioritization | Given the 2–5h time-box, did you make sensible choices about what to build, simplify, or skip — and can you explain those choices and what you'd do next with more time? |
| README | Clear instructions on how to install and run the application, as well as explanation of key design decisions and assumptions |
| Tests (bonus) | Relevance and coverage of edge cases |

## Submission

Submit your code as a Git repository — either a link to GitHub or a zipped folder containing the `.git` history. We want to see your commit history, not just the final result.

If you have any questions, please don't hesitate to reach out to the hiring manager or to utvecklare@ap7.se. Good luck!
