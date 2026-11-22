# Monthly Expense Tracker

A small Excel tracker for one month of student spending (October 2026). The data is made up, and I built this while learning Excel.

## Problem
I wanted to see where a month of spending actually goes, and spot the big expenses fast instead of scrolling through a long list.

## Screenshot
 (monthly-expense-tracker.png)

## What I used
- Data entry for 30 made-up expenses (date, item, category, amount)
- Date format and ₹ currency format
- SUM for the total
- SUMIF for the total spent in each category
- COUNTIF for the number of expenses in each category
- Conditional formatting to highlight any expense above ₹500 in red

## How to use it
1. Download and open `monthly-expense-tracker.xlsx`.
2. The expenses are in columns A to D and the summary is on the right.
3. Change an amount and the totals update. Red means the expense is above ₹500.

## Results (made-up data)
Total ₹6,487: Food ₹2,005, Travel ₹790, Study ₹2,204, Other ₹1,488.

## What I learned
- I learned SUMIF and COUNTIF (range, criteria, sum_range) while building this.
- My Study total was wrong at first. I caught it because my four category totals didn't add up to the grand total. Now I always check that the parts add up to the whole.
- A formula that points at its own cell causes a circular reference. Mine turned a date into 00-01-1900.
- The $ sign locks a range so it doesn't shift when I copy a formula.

## What I'd improve
- The formulas only cover rows 3 to 32, so new expenses need the ranges updated. I want to make them grow automatically.
- Add a chart once I learn charts.

