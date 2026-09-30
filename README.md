The objective of Day 2 was to use Excel functions, PivotTables, and charts to analyse financial performance, compare actual expenditure with budget, and generate management insights from the accounting dataset.

  Analysis Performed
- Prepared a financial summary showing total revenue, total expenses, profit/loss, and profit margin.
- Analysed monthly revenue, expenses, and profit using SUMIFS.
- Compared actual expenses with budget by department and expense category.
- Calculated budget variance and variance percentage.
- Used PivotTables to analyse expenses by category and department.
- Identified the top three expense categories.
- Created three charts to visualise financial performance and budget comparisons.
- Prepared a financial analysis dashboard.

 Formulas Used
- Total Revenue: `SUMIFS`
- Total Expenses: `SUMIFS`
- Profit = Total Revenue - Total Expenses
- Profit Margin = Profit / Total Revenue
- Variance = Actual - Budget
- Variance % = Variance / Budget
- `IFERROR` was used to handle categories with zero budget values.
- `UNIQUE` was used to generate distinct department and category lists.

Management Insights

1. Total revenue was GHS 318,721, while total expenses were GHS 456,287, resulting in a loss of GHS 137,566. This indicates that expenses exceeded the revenue generated during the period and should be reviewed for opportunities to improve profitability.
2. Office Supplies was the highest expense category at GHS 105,273, followed by Software at GHS 94,089 and Marketing at GHS 82,806. These three categories accounted for a significant portion of total expenses and should be key areas for cost monitoring.
3. Sales recorded the highest departmental expenses at GHS 134,953, followed by Finance at GHS 126,197. Operations and Administration recorded GHS 98,095 and GHS 97,042 respectively, indicating that Sales and Finance were the two largest departmental cost centres during the period.
4. All four departments remained below budget. Finance had the largest underspend at GHS 5,668 (4.30% below budget), followed by Operations at GHS 3,931 (3.85%), Sales at GHS 3,352 (2.42%), and Administration at GHS 3,055 (3.05%).
5. Utilities and Software recorded the largest percentage underspends among the active expense categories at 6.83% and 5.69% below budget respectively. Utilities was GHS 3,583 below budget, while Software was GHS 5,676 below budget.
6. Marketing recorded actual expenses of GHS 82,806 against a budget of GHS 83,090, resulting in an underspend of only GHS 284 (0.34%). This was the closest actual-to-budget performance among the active expense categories.

  Visualisations Created
- Monthly Revenue and Expense Trend
- Expenses by Category
- Actual vs Budget by Department

  Day 2 Task
- `excel/day2_financial_analysis.xlsx`
- `screenshots/day2_dashboard.png`
