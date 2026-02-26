# 1040 Tax Flow Simulator

Trace your money through every key line of Form 1040 — from gross income down to your final refund or balance due — in one interactive visual flow.

<iframe src="./main.html" width="100%" height="680px" style="border:none;"></iframe>

[View Fullscreen](./main.html){ .md-button .md-button--primary }

## Overview

Form 1040 can feel like a black box: income goes in, a number comes out, and it's not always clear why. This simulator makes the path transparent. Enter your wages, filing status, withholding, and credits, and watch how each line of the return feeds into the next — income → adjustments → AGI → deductions → taxable income → tax → credits → payments → refund/owed.

The flow visualization is especially useful for understanding *why* your refund went up or down compared to last year, or for modeling the impact of a single change like adding an IRA contribution or claiming a new dependent.

## How to Use

1. **Enter wages** (W-2 Box 1) and **filing status**
2. **Enter federal tax withheld** (W-2 Box 2) — this is the amount already prepaid
3. **Add other income** — 1099s, side gig income, etc.
4. **Enter child tax credit eligible children** if applicable
5. **Watch the 1040 flow** update in real time — each node shows the dollar amount at that point in the return

## Key Concepts

- Gross Income → minus Adjustments = **AGI**
- AGI → minus Standard or Itemized Deductions = **Taxable Income**
- Taxable Income × bracket rates = **Income Tax**
- Income Tax − Non-Refundable Credits = **Net Tax**
- Net Tax − Withholding − Refundable Credits = **Refund (negative) or Amount Owed**

## Related Chapter

- [Chapter 6: Tax Forms Deep Dive](../../chapters/06-tax-forms-deep-dive/index.md)
