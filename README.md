# Smart Personal Finance Manager

Smart Personal Finance Manager is a Python-based desktop personal finance application designed to help users manage income, expenses, budgets, reports, analytics, and CSV exports through a modular and professional architecture.

## Features

- User registration and secure login
- Income management with add, view, update, delete, search, and filter capabilities
- Expense management with categories and filters
- Monthly budget setting, updates, and remaining-budget analysis
- Reports for monthly, income, expense, savings, and category-wise summaries
- Analytics with bar charts, pie charts, monthly trend summaries, and savings analysis
- CSV export for income, expenses, and reports

## Project Structure

- main.py: Application entry point
- login.py: Authentication and session handling
- dashboard.py: Main console navigation and dashboard
- income.py: Income management logic
- expense.py: Expense management logic
- budget.py: Monthly budget management
- reports.py: Report generation
- analytics.py: Chart generation and analysis
- export.py: CSV export functions
- utils.py: Shared helpers and formatting
- data/: JSON storage for application data, including users, income, expenses, budgets, reports, and settings
- charts/: Generated chart images
- exports/: Exported CSV files

## Installation

1. Install Python 3.10+.
2. Navigate to the project directory.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the desktop application:

```bash
python main.py
```

The app opens a polished window with:
- Login and registration screens
- a dashboard summary
- income and expense entry forms
- budget setup
- CSV export buttons



## Sample Workflow

1. Register a new user or log in with the demo account.
2. Add income and expenses.
3. Create or update budgets.
4. Review reports and charts.
5. Export data to CSV.

## Testing

Potential test cases include:

- Successful registration and login
- Invalid login attempts
- Duplicate username registration
- Budget overrun detection
- Empty expense and income lists
- CSV export generation

## Future Enhancements

- Add password reset support
- Add recurring transactions
- Add multi-user role support
- Add advanced dashboard visualizations
- Add category budgeting and forecasting
