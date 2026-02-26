---
title: Chapter 6: Tax Forms Deep Dive
description: Box-by-box guide to the W-2, all major 1099 variants, Form 1040 walkthrough, and deep dives into Schedules A and SE plus Forms 2441, 8606, and 5329.
generated_by: claude skill chapter-content-generator
date: 2026-02-21
version: 0.04
---

# Chapter 6: Tax Forms Deep Dive

## Summary

This chapter demystifies every common tax form you'll encounter. You'll get a box-by-box explanation of the W-2, plain-English breakdowns of the 1099 variants you're most likely to receive (NEC, INT, R, G, K), a line-by-line walkthrough of the Form 1040, and deep dives into Schedule A (itemized deductions) and Schedule SE (self-employment tax). Also covered: Form 2441 (child care), Form 8606 (nondeductible IRA contributions), and Form 5329 (retirement penalties). Note: investment and rental property forms are covered in Chapters 7 and 8 respectively.

## Concepts Covered

This chapter covers the following 15 concepts from the learning graph:

1. W-2 Box by Box Guide
2. W-2 Box 12 Codes
3. W-2 Box 14 Codes
4. 1099-NEC Explained
5. 1099-MISC vs 1099-NEC
6. 1099-INT Explained
7. 1099-R Explained
8. 1099-G Explained
9. 1099-K Reporting Rules
10. 1040 Line by Line Guide
11. Schedule A Itemized Deductions
12. Schedule SE Self-Employment Tax
13. Form 2441 Child Care Credit
14. Form 8606 Nondeductible IRA
15. Form 5329 Retirement Penalties

## Prerequisites

This chapter builds on concepts from:

- [Chapter 1: Understanding Your Tax Situation](../01-understanding-taxes/index.md)
- [Chapter 2: Filing Your Return Step by Step](../02-filing-your-return/index.md)
- [Chapter 3: Legal Tax Reduction Strategies](../03-tax-reduction-strategies/index.md)
- [Chapter 4: Side Hustle & Self-Employment Taxes](../04-side-hustle-taxes/index.md)
- [Chapter 5: Year-Round Tax Planning](../05-year-round-planning/index.md)

---

## Introduction

Tax forms are the IRS's way of collecting the facts about your financial life in a standardized format. Once you understand what each box means and where each number flows, you stop feeling like you're filling out a mystery document and start feeling like you're just transcribing information you already know. This chapter is your decoder ring. We'll work through the forms in a logical order — starting with the documents your employer sends you, then the 1099s that arrive from banks, clients, and brokers, and finally the core filing forms themselves.

Think of the W-2 and 1099s as raw ingredients. Form 1040 is the recipe. The schedules are what you add when your financial life gets more complex. By the end of this chapter, you'll be able to pick up any of these forms, know exactly what you're looking at, and know precisely where that number belongs on your return.

---

## Part 1: The W-2 — Your Employer's Annual Report on You

### W-2 Box by Box Guide

Your employer must mail your W-2 by January 31. If you worked for multiple employers during 2025, you'll get one from each. The form looks dense, but most boxes are either straightforward or irrelevant to most filers. Here's what actually matters:

| Box | Label | What It Means |
|-----|-------|---------------|
| 1 | Wages, tips, other compensation | Your **taxable wages** — already reduced by pre-tax 401(k), health insurance, FSA, and HSA contributions |
| 2 | Federal income tax withheld | What your employer sent to the IRS on your behalf |
| 3 | Social Security wages | Wages subject to SS tax — may be higher than Box 1 (some pre-tax deductions reduce Box 1 but not Box 3) |
| 4 | Social Security tax withheld | Always 6.2% of Box 3, up to the SS wage base ($176,100 for 2025) |
| 5 | Medicare wages | Wages subject to Medicare tax — usually same as or higher than Box 3 |
| 6 | Medicare tax withheld | 1.45% of Box 5 (plus 0.9% Additional Medicare Tax if you hit $200k single/$250k MFJ) |
| 12 | Coded amounts | See Box 12 table below — several important items live here |
| 14 | Other | Informational items — see Box 14 section below |
| 15–17 | State boxes | State wages and withholding — flows to your state return |

Box 1 is the single most important number on your W-2. It's what you report on line 1a of Form 1040. If you had pre-tax deductions — a traditional 401(k), a health insurance premium, an FSA or HSA — your Box 1 is already lower than your gross salary. That's intentional and correct. You don't get to deduct those items again on your return.

!!! tip "Check Your Box 3 and Box 4"
    If you switched jobs mid-year, each employer withholds Social Security tax independently. If combined Box 3 wages across all W-2s exceeded $176,100 in 2025 and combined Box 4 withholding exceeded $10,918.20, you overpaid Social Security tax. Claim the excess as a credit on Schedule 3, line 11. The IRS will refund it — but only if you catch it.

### W-2 Box 12 Codes

Box 12 uses single or double-letter codes to report amounts that affect your tax return in specific ways. Your employer can report up to four items in Box 12 on a single W-2.

| Code | What It Represents | Tax Implication |
|------|--------------------|-----------------|
| D | Traditional 401(k) contributions | Pre-tax; reduces Box 1. Informational — don't deduct again. |
| E | 403(b) contributions (teachers, nonprofits) | Same as D |
| G | 457(b) contributions (government employees) | Same as D |
| W | Employer HSA contributions | Excluded from income. Flows to Form 8889. |
| DD | Cost of employer-sponsored health coverage | Informational only — not taxable, not deductible |
| AA | Roth 401(k) contributions | After-tax; **does not** reduce Box 1. Reported for record-keeping. |
| C | Taxable cost of group-term life over $50,000 | Added to Box 1 — imputed income |
| P | Excludable moving expense reimbursements | Active military only |
| S | SIMPLE IRA contributions | Similar to Code D |

The codes you'll most commonly see are D (or E or G), W, DD, and AA. If you see Code D for $8,500, that's your traditional 401(k) contribution — it already reduced your Box 1, so you're done. If you see Code AA for $5,000, that's your Roth 401(k) — it did NOT reduce Box 1, and you'll never pay tax on those earnings in retirement.

### W-2 Box 14 Codes

Box 14 is a catch-all that employers use to communicate information that doesn't fit elsewhere. It has no standardized coding system — employers can label entries however they like. Common entries include:

- **Union dues** — generally deductible only if you itemize and your state allows it (federal no longer allows misc. itemized deductions)
- **State SDI (State Disability Insurance)** — California, New Jersey, and other states withhold this. It counts toward your state and local taxes (SALT) on Schedule A, subject to the $10,000 cap.
- **PUCC (Personal Use of Company Car)** — the taxable value of personal miles driven in a company vehicle. This amount is already included in Box 1.
- **Imputed income** — domestic partner health benefits, life insurance over $50,000 (though that's technically Box 12, Code C). Also already in Box 1.
- **Educational assistance** — amounts over $5,250 may appear here and may already be included in Box 1.

!!! note "Box 14 Is Usually Just FYI"
    Most Box 14 entries are informational or already captured elsewhere on your W-2. Read the label carefully, but don't panic. If you see "SDI" and a dollar amount, that number might be deductible on Schedule A as a state tax — add it to your other state/local taxes, subject to the $10,000 SALT cap.

---

## Part 2: The 1099 Universe

### 1099-NEC Explained

The 1099-NEC (Nonemployee Compensation) is what businesses send you when they paid you $600 or more for services rendered as an independent contractor. "NEC" stands for Nonemployee Compensation. If you freelance, consult, do gig work, or provide any paid services outside of a traditional W-2 employment relationship, you'll receive this form.

The key number is **Box 1: Nonemployee Compensation**. That amount flows to Schedule C (Profit or Loss from Business), where you subtract your business expenses to arrive at net profit. That net profit is then subject to both income tax and self-employment tax (covered in the Schedule SE section below). You'll receive a 1099-NEC from each business that paid you $600 or more in 2025. But here's the critical point: even if a client paid you only $400 and didn't send a 1099-NEC, that income is still taxable and you must still report it.

!!! warning "No 1099 Doesn't Mean No Tax"
    The $600 threshold only determines who has to send you the form. You owe tax on every dollar of self-employment income, regardless of whether you received a 1099-NEC. If you earned $400 doing freelance design work and no form arrived in January, you still report $400 on Schedule C.

### 1099-MISC vs 1099-NEC

The IRS split what used to be a single 1099-MISC into two forms in 2020, and people still mix them up. Here's the clean distinction:

| Form | Used For | Key Box |
|------|----------|---------|
| 1099-NEC | Payments to independent contractors for services | Box 1: Nonemployee Compensation |
| 1099-MISC | Everything else — rents, prizes, awards, medical payments, crop insurance | Box 3: Other Income; Box 6: Medical payments; Box 10: Crop insurance |

If you won a prize at a conference ($500 Amazon gift card for best pitch), that's a 1099-MISC Box 3, not a 1099-NEC. If you rented your building to a business and received $10,000 in rent, that's 1099-MISC Box 1. If a business paid you $5,000 to redesign their website, that's 1099-NEC. The practical rule: **freelance work and services go on the NEC. Almost everything else uses the MISC.**

### 1099-INT Explained

Banks, credit unions, and brokers send the 1099-INT when you earned $10 or more in interest during 2025. The form has two lines you need to care about:

- **Box 1: Interest Income** — taxable interest from savings accounts, CDs, money market accounts, and most bonds. This flows directly to Form 1040, line 2b (or Schedule B if total interest exceeds $1,500).
- **Box 8: Tax-Exempt Interest** — interest from municipal bonds. This is NOT taxable federally, but you must still report it on line 2a of Form 1040. Why? Because it affects certain calculations like your Modified AGI for the purpose of determining Roth IRA eligibility and the taxation of Social Security benefits.

Other boxes on the 1099-INT (bond premium, market discount, investment expenses) are relevant if you're trading bonds actively — those are covered in Chapter 7.

### 1099-R Explained

The 1099-R reports distributions from retirement accounts — traditional IRAs, 401(k)s, 403(b)s, pensions, and annuities. If money came out of any tax-advantaged retirement account in 2025, you got one of these.

The most important boxes:

- **Box 1: Gross Distribution** — the total amount distributed
- **Box 2a: Taxable Amount** — the portion subject to income tax (may differ from Box 1 if you made nondeductible contributions — that's where Form 8606 comes in)
- **Box 4: Federal Income Tax Withheld** — what the custodian already sent to the IRS
- **Box 7: Distribution Code** — this is the critical one; it tells the IRS why money left the account

| Box 7 Code | Meaning | Default Penalty? |
|------------|---------|------------------|
| 1 | Early distribution, no known exception | 10% early withdrawal penalty applies |
| 2 | Early distribution, exception applies | No penalty (disability, substantially equal payments, etc.) |
| 7 | Normal distribution (age 59½ or older) | No penalty |
| G | Direct rollover | Not taxable, no penalty |
| H | Direct rollover from Roth account | Not taxable, no penalty |

If you see Code 1, the 10% penalty will be calculated on Form 5329 (covered below). If you rolled over a 401(k) from an old job to an IRA and received Code G, you owe nothing — but you still need to report the 1099-R on your return so the IRS can match it.

### 1099-G Explained

The 1099-G covers government payments. The two boxes most people encounter:

- **Box 1: Unemployment Compensation** — fully taxable at the federal level. Every dollar of unemployment benefits you received in 2025 goes on Schedule 1, line 7, and ultimately lands on your 1040. There is no exclusion this year — unlike the temporary COVID-era break in 2021.
- **Box 2: State or Local Income Tax Refunds** — this is only taxable if you itemized deductions in the prior year AND deducted those state taxes. If you took the standard deduction last year, your state refund is not taxable. This is the "tax benefit rule" — you only owe tax on the refund to the extent you got a deduction for it.

!!! info "Withholding from Unemployment"
    You can request federal income tax withholding from unemployment benefits using Form W-4V, withholding 10% flat. Most people who don't do this are unpleasantly surprised at tax time. If you were on unemployment in 2025 and didn't withhold, budget for an April bill or make a Q4 estimated payment.

### 1099-K Reporting Rules

The 1099-K reports payment card and third-party network transactions. For 2025, the threshold is **$600** in gross payments — meaning PayPal, Venmo (for goods/services), eBay, Etsy, Stripe, and similar platforms must send you a 1099-K if they processed $600 or more to you during the year.

This is a source of significant confusion. The 1099-K reports **gross receipts** — it does not subtract your costs, refunds, or fees. If you sold used furniture on Facebook Marketplace for $800 and paid $500 for it originally, you don't owe tax on $800. You owe tax on the $300 gain (or nothing, if you sold it for less than you paid). The 1099-K is just a reporting trigger, not a tax bill.

- If the payments were for a **business** (freelance, side hustle, selling goods), report on Schedule C.
- If the payments were from **selling personal items at a loss** (used clothes, furniture you paid more for), you have no taxable gain — but document your original purchase prices.
- If you received money via Venmo for **splitting a dinner**, that is not taxable income. Request that friends designate it as "personal" — personal transfers don't trigger 1099-K.

!!! warning "Don't Ignore a 1099-K"
    The IRS receives a copy of your 1099-K directly from the payment processor. If the amount on your 1099-K doesn't appear somewhere on your return, an automated notice is likely. Even if you owe no tax (because you sold items at a loss), you need to show your math on your return so the IRS can match it.

---

## Part 3: Form 1040 — The Master Document

### 1040 Line by Line Guide

Form 1040 is two pages and approximately 79 lines. It doesn't do calculations — it aggregates numbers from your W-2s, 1099s, and supporting schedules into a single running total that yields your tax liability or refund. Here's the logical flow:

**Page 1 — Income and Adjustments:**

- **Lines 1a–1z** — Wages, salaries, tips. Line 1a is your W-2 Box 1 total. Other lines cover household employee wages, tip income, scholarship income, etc.
- **Lines 2a–2b** — Tax-exempt interest (2a, informational) and taxable interest (2b, from 1099-INT Box 1)
- **Line 3b** — Ordinary dividends (from 1099-DIV — Chapter 7)
- **Line 4b** — IRA distributions (taxable portion from 1099-R)
- **Line 5b** — Pension and annuity income (taxable portion from 1099-R)
- **Line 6b** — Social Security benefits (taxable portion, 0–85% depending on combined income)
- **Line 7** — Capital gain or loss (from Schedule D — Chapter 7)
- **Line 8** — Additional income from Schedule 1 (self-employment income, alimony, gambling winnings, unemployment, etc.)
- **Line 9** — Total income (sum of all above)
- **Line 10** — Adjustments to income from Schedule 1, Part II (student loan interest, HSA deductions, self-employed health insurance, etc.)
- **Line 11** — **Adjusted Gross Income (AGI)** = Line 9 minus Line 10. This is the most important number on your return.

**Page 2 — Tax Calculation and Credits:**

- **Line 12** — Standard deduction OR itemized deductions (Schedule A)
- **Line 13** — Qualified Business Income (QBI) deduction, if applicable
- **Line 15** — **Taxable Income** = AGI minus deductions
- **Line 16** — Tax (from the tax tables or tax computation worksheets)
- **Line 17** — Alternative Minimum Tax (from Form 6251, if applicable)
- **Line 18** — Total tax before credits
- **Lines 19–24** — Non-refundable credits (child tax credit, education credits, etc.)
- **Line 25** — Federal withholding from W-2s and 1099s
- **Line 26** — Estimated tax payments made
- **Line 27** — Earned Income Tax Credit (EITC), if eligible
- **Line 33** — Total payments
- **Line 37 or 38** — Amount you owe OR refund

The formula is clean:

\[
\text{Tax Owed} = \text{Tax on Taxable Income} - \text{Credits} - \text{Withholding} - \text{Estimated Payments}
\]

If the result is negative, you get a refund. If positive, you owe the difference by April 15.

#### Diagram: 1040 Tax Flow Simulator

<iframe src="../../sims/1040-tax-flow/main.html" width="100%" height="900px" style="border:none;"></iframe>

<details markdown="1">
<summary>1040 Tax Flow Simulator — MicroSim Specification</summary>
Type: microsim

Bloom Level: Apply
Bloom Verb: Calculate

Learning Objective: The learner can trace a dollar of income from a W-2 through the Form 1040 structure — applying the standard deduction, reading from the tax brackets, applying a basic credit, and arriving at a net tax owed or refund — using realistic 2025 numbers.

Layout:
The sim has two panels side by side on desktop, stacked on mobile.
Left panel: input controls (sliders and dropdowns).
Right panel: a vertical "waterfall" diagram showing how income flows down through the 1040 calculation, with each row labeled with the corresponding 1040 line number.

Inputs (left panel):
- Wages (W-2 Box 1): slider from $20,000 to $200,000, default $65,000, step $1,000
- Filing status: dropdown — Single, Married Filing Jointly, Head of Household
- Federal tax withheld: slider from $0 to $40,000, default $8,000, step $500
- Other income (1099s, etc.): numeric input, default $0
- Pre-tax deductions (reduces Box 1 already, informational only): numeric display
- Child Tax Credit eligible children: integer 0–4, default 0

Outputs (right panel waterfall):
Each step is a labeled row with the dollar amount on the right:
1. Gross Wages (line 1a)
2. Other Income (line 8)
3. Total Income (line 9) [subtotal bar]
4. Adjustments to Income (line 10) — shown as $0 for simplicity
5. AGI (line 11) [highlighted subtotal bar]
6. Standard Deduction (line 12) — auto-populated from filing status ($15,000 / $30,000 / $22,500)
7. Taxable Income (line 15) [highlighted]
8. Income Tax (line 16) — computed from 2025 tax brackets
9. Child Tax Credit (lines 19–24) — $2,000 per child, non-refundable
10. Tax After Credits (line 18 adjusted)
11. Federal Withholding (line 25)
12. Net Tax Owed / Refund (line 37 or 38) [large colored result: red for owe, green for refund]

Behavior:
- All values update in real-time as sliders/inputs change.
- The waterfall diagram uses arrows showing flow downward.
- Negative values (deductions, credits, withholding) shown in a muted color with a minus sign.
- Net result row uses bold text; green background if refund, red/orange background if owe.
- Tax bracket calculation uses 2025 rates: 10%, 12%, 22%, 24%, 32%, 35%, 37% applied to taxable income per filing status.
- Tooltip on each row explains what that line represents on the real Form 1040.

Colors:
- Income rows: dark teal (#2E7D6C)
- Deduction rows: slate blue (#4A5568)
- Tax rows: dark orange (#C05621)
- Credit rows: dark green (#276749)
- Result row: green (#22543D) for refund, red (#9B2335) for owe
- Background: light gray (#F7FAFC)
- Waterfall bars: proportional width to maximum value in view

Implementation: HTML/CSS/JS with vanilla JavaScript
</details>

---

## Part 4: Schedules That Do the Heavy Lifting

### Schedule A — Itemized Deductions

Schedule A is where you list deductions to replace the standard deduction — but only if your itemized total exceeds the standard deduction amount for your filing status. For 2025, those thresholds are $15,000 (Single), $30,000 (Married Filing Jointly), and $22,500 (Head of Household). You'll only itemize if your deductions clear those bars.

The major categories on Schedule A:

- **Medical and Dental Expenses** — only the amount exceeding 7.5% of your AGI is deductible. If your AGI is $80,000, only medical expenses above $6,000 count. Most people under 65 with typical AGI won't clear this floor.
- **State and Local Taxes (SALT)** — capped at **$10,000** total ($5,000 if Married Filing Separately). This includes state income tax withheld (or sales tax in no-income-tax states), local income tax, and property taxes. The $10,000 cap remains in place for 2025.
- **Mortgage Interest** — interest on acquisition debt up to $750,000 (for loans after December 15, 2017). Home equity interest is deductible only if the loan was used to buy, build, or substantially improve the home.
- **Charitable Contributions** — cash donations (up to 60% of AGI), non-cash donations (fair market value, Form 8283 if over $500), and qualified conservation easements.

The math test for itemizing:

\[
\text{Itemize if: } (\text{SALT} + \text{Mortgage Interest} + \text{Charitable} + \text{Medical excess}) > \text{Standard Deduction}
\]

For most W-2 earners in moderate cost-of-living areas, the $30,000 MFJ standard deduction is hard to beat. But homeowners with large mortgages in high-tax states often clear it easily. The practical exercise: add up your property tax, state income tax (capped at $10k total), mortgage interest statements (Form 1098), and charitable receipts every January.

!!! example "SALT Cap in Action"
    Maya lives in New Jersey. She paid $8,500 in NJ state income tax and $6,200 in property tax — a combined $14,700 in state and local taxes. Her SALT deduction is capped at $10,000. She also paid $12,000 in mortgage interest. Her itemized total is $22,000. She files as Single. Her standard deduction is $15,000. She should itemize — she saves an extra $7,000 in deductions over the standard amount.

### Schedule SE — Self-Employment Tax

If you have net self-employment income of $400 or more, you must file Schedule SE. This form calculates the self-employment (SE) tax — the equivalent of both the employee and employer sides of Social Security and Medicare taxes that a regular employee splits with their employer.

The formula in two steps:

**Step 1 — Net SE Income:**
\[
\text{Net SE Income} = \text{Net Profit from Schedule C} \times 0.9235
\]

The 0.9235 factor (which equals 1 minus 0.0765) adjusts for the fact that employees only pay half of FICA taxes. You get a comparable adjustment as a self-employed person.

**Step 2 — SE Tax:**
\[
\text{SE Tax} = \text{Net SE Income} \times 0.153
\]

The 15.3% rate is 12.4% Social Security + 2.9% Medicare. Social Security applies only up to the wage base ($176,100 in 2025).

**Example:** You freelanced and netted $60,000 on Schedule C.

\[
\text{Net SE Income} = \$60{,}000 \times 0.9235 = \$55{,}410
\]
\[
\text{SE Tax} = \$55{,}410 \times 0.153 = \$8{,}478
\]

That $8,478 goes on Schedule 2, line 4, and flows to Form 1040, line 17. But here's the good news: you deduct half of your SE tax as an adjustment to income on Schedule 1, line 15. That deduction reduces your AGI — and your income tax bill — by roughly $4,239 (half of $8,478), though not your SE tax itself.

---

## Part 5: Specialized Forms You Need to Know

### Form 2441 — Child and Dependent Care Credit

If you paid someone to watch your child (under age 13) or a dependent who can't care for themselves so that you (and your spouse, if married) could work or look for work, you may qualify for the Child and Dependent Care Credit. This is not the Child Tax Credit — it's a separate credit specifically for care expenses.

Key rules for 2025:

- **Maximum eligible expenses:** $3,000 for one qualifying person, $6,000 for two or more
- **Credit rate:** 20%–35% of eligible expenses, depending on your AGI. The rate phases down as income rises. At AGI above $43,000, the rate is a flat 20%.
- **Maximum credit:** $600 (one person at 20%) to $1,050 (one person at 35%) or $1,200 to $2,100 (two or more)
- **Earned income requirement:** Both spouses must have earned income (wages, self-employment) — unless one is a full-time student or disabled
- **Dependent Care FSA coordination:** If your employer offers a Dependent Care FSA and you contributed pre-tax dollars, those dollars reduce the eligible expenses you can claim on Form 2441. You can't double-dip.

The employer's Dependent Care Assistance Program (DCAP/FSA) is usually the better deal for most people — you get a pre-tax reduction at your marginal rate rather than a 20% credit. But if your care expenses exceed your FSA limit ($5,000 for MFJ), you can claim the credit on the remaining eligible expenses.

| AGI Range | Credit Rate | Max Credit (2 dependents) |
|-----------|-------------|--------------------------|
| Up to $15,000 | 35% | $2,100 |
| $15,001–$43,000 | Phases down from 35% to 20% | $1,200–$2,100 |
| Over $43,000 | 20% | $1,200 |

### Form 8606 — Nondeductible IRA Contributions

Form 8606 is one of the most underused and most important forms in the tax code. You file it whenever you make a **nondeductible contribution** to a traditional IRA — meaning you contributed after-tax dollars because you were covered by a workplace retirement plan and your income was too high to deduct the contribution.

Why does this matter enormously? Because without Form 8606, the IRS assumes all money in your traditional IRA is pre-tax. When you take distributions in retirement, they'll tax the entire amount. But if you tracked your nondeductible basis with Form 8606, only the earnings are taxable — not the principal you already paid tax on.

Form 8606 also drives the **backdoor Roth IRA** strategy:

1. Contribute $7,000 (or $8,000 if 50+) to a traditional IRA (nondeductible — file Form 8606 Part I)
2. Convert the traditional IRA to a Roth IRA (report on Form 8606 Part II)
3. If done with no other pre-tax IRA balances, the conversion is tax-free

!!! warning "The Pro-Rata Rule and Form 8606"
    If you have a mix of pre-tax and after-tax dollars in traditional IRAs when you do a Roth conversion, you can't just convert the after-tax portion. The IRS requires you to treat all traditional IRA money as one pool. The taxable fraction of any conversion equals: pre-tax IRA balance ÷ total IRA balance. Form 8606 Part II does this calculation for you — but get it wrong and you'll pay tax twice on the same dollars.

Form 8606 accumulates over years. Every nondeductible contribution you make gets added to your "basis" — tracked in Part I, line 14. This carryforward continues until all your nondeductible contributions are either converted to Roth or distributed. File Form 8606 every single year you make a nondeductible IRA contribution, even if you owe no additional tax. Losing track of your basis is expensive.

### Form 5329 — Additional Taxes on Retirement Accounts

Form 5329 is the IRS's mechanism for collecting penalties related to retirement accounts. You'll encounter it in two main situations:

**Situation 1 — Early Withdrawal Penalty (Part I)**

If you took money out of a traditional IRA or 401(k) before age 59½ (or 55 for a qualified plan if you separated from service), a 10% penalty applies on top of ordinary income tax. The penalty is calculated on Form 5329, Part I.

\[
\text{Early Withdrawal Penalty} = \text{Taxable Distribution} \times 0.10
\]

However, there are exceptions that zero out the penalty even if your 1099-R shows Code 1 (early, no known exception). You claim the exception on Form 5329 by entering the exception code and the exempt amount:

- Exception 01: Death
- Exception 02: Disability
- Exception 03: Substantially Equal Periodic Payments (SEPP / 72(t))
- Exception 05: Qualified higher education expenses (IRA only)
- Exception 09: Health insurance premiums while unemployed (IRA only)
- Exception 10: First-time home purchase (IRA only, up to $10,000 lifetime)
- Exception 12: Qualified disaster distribution (if applicable)

**Situation 2 — Excess Contribution Penalty (Part III)**

If you contributed more than the annual limit to an IRA (or Roth IRA) in 2025 ($7,000, or $8,000 if age 50+), the excess is hit with a **6% excise tax per year** until it's corrected.

\[
\text{Excess Contribution Penalty} = \text{Excess Amount} \times 0.06
\]

This penalty compounds — you pay 6% every year the excess remains in the account. The fix: withdraw the excess contribution plus earnings attributable to it before the tax filing deadline (including extensions). If you catch it in time, no penalty applies. If you don't, Form 5329 calculates the damage.

!!! example "Excess Contribution Scenario"
    Jordan contributed $7,000 to a Roth IRA in 2025 but her income turned out to be too high — she was above the Roth IRA phase-out limit. The entire $7,000 is an excess contribution. If she doesn't remove it by April 15, 2026 (or October 15 with an extension), she owes $420 (6% × $7,000) for 2025, and another $420 for 2026 if it's still there. She should withdraw the $7,000 plus any earnings now. Or, if eligible, recharacterize it as a traditional IRA contribution.

---

## Putting It All Together

Every document covered in this chapter connects to a specific line on Form 1040. Here's the complete flow at a glance:

| Source Document | Key Box | Where It Goes on 1040 |
|----------------|---------|----------------------|
| W-2 | Box 1 | Line 1a |
| W-2 | Box 2 | Line 25a (withholding) |
| 1099-NEC | Box 1 | Schedule C → Schedule 1, Line 3 → Line 8 |
| 1099-MISC | Box 3 | Schedule 1, Line 8z (other income) |
| 1099-INT | Box 1 | Line 2b |
| 1099-INT | Box 8 | Line 2a (tax-exempt, informational) |
| 1099-R | Box 2a | Line 4b or 5b |
| 1099-G Box 1 | Unemployment | Schedule 1, Line 7 → Line 8 |
| 1099-G Box 2 | State refund | Schedule 1, Line 1 → Line 8 (if taxable) |
| 1099-K | Gross receipts | Schedule C (business) or capital gain/loss |
| Schedule A | Total itemized deductions | Line 12 (if greater than standard deduction) |
| Schedule SE | SE tax | Schedule 2, Line 4 → Line 17 |
| Form 2441 | Child care credit | Schedule 3, Line 2 → Line 20 |
| Form 8606 | Taxable IRA conversion | Line 4b (IRA distributions, taxable amount) |
| Form 5329 | Additional taxes | Schedule 2, Line 8 → Line 17 |

---

## Key Takeaways

- Your **W-2 Box 1** is already reduced by pre-tax contributions. Check Box 12 for the codes that explain what was deducted.
- **Box 14** is informational — read the label, but most entries are already captured elsewhere or simply FYI.
- The **1099-NEC** (not the 1099-MISC) is the form for freelance and contractor pay. All service income over $600 triggers one; all service income under $600 is still taxable.
- **1099-K** reports gross payment volume from platforms — it's a reporting trigger, not a tax bill. You must still show the IRS where those gross receipts appear on your return.
- **Form 1040** has one job: aggregate all your income, subtract your deductions and credits, and compare the resulting tax to what you already paid. The difference is your refund or your bill.
- **Schedule A** is worth using only when your real deductions — SALT (capped at $10k), mortgage interest, and charitable giving — exceed your standard deduction.
- **Schedule SE** calculates your self-employment tax at 15.3% of 92.35% of net profit. Half is deductible against income tax.
- **Form 2441** gives you a credit for dependent care expenses — but coordinate with any Dependent Care FSA you used.
- **Form 8606** tracks your nondeductible IRA basis for life. Every missed filing year costs you.
- **Form 5329** handles early withdrawal penalties (10%) and excess contribution penalties (6%). Exceptions to the early withdrawal penalty must be claimed proactively on this form.

---

## What To Do Right Now

1. Gather every tax document that has arrived so far — W-2s, all 1099s. Create a checklist matching each document to the section in this chapter.
2. Open your W-2 and verify that Box 1 is lower than your gross salary by the amount of your pre-tax 401(k) and health insurance contributions. If the math doesn't work, call your payroll department.
3. Check Box 12 on your W-2. If you see Code D or AA, verify the amount matches your 401(k) statement for the year.
4. If you received a 1099-NEC, list every business expense you paid related to that work. You'll need those for Schedule C.
5. If you received a 1099-K, document the original cost of any items you sold. Gather purchase receipts now before you forget.
6. Run the 1040 Tax Flow Simulator above with your actual numbers. Notice where your biggest tax drivers are — wages, self-employment income, or other sources.
7. Do the Schedule A math: add your property tax + state income tax (capped at $10,000) + Form 1098 mortgage interest + charitable receipts. Compare to your standard deduction. Decide whether to itemize.
8. If you made any IRA contributions for 2025 that were nondeductible, confirm you have (or will file) Form 8606. If you're not sure whether your contributions were deductible, check the IRA deductibility worksheet in Publication 590-A.
9. If you took an early distribution from a retirement account and your 1099-R shows Code 1, check the exception list in the Form 5329 section. If an exception applies, claim it — don't pay a penalty you don't owe.
10. Note any forms in this chapter that apply to your situation for next tax year, and set a calendar reminder in December to verify your withholding covers your expected liability.
