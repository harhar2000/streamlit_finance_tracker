# 💰 Finance Tracker

A finance tracking web application built with Streamlit, Pandas and Matplotlib. 
Add and view transactions within a specific date range and visualise income and expenses over time.

Deployed app link - https://harhar2000-finance-tracker-streamlit-tracker-iihkyg.streamlit.app/

## Features

- Add new transactions (Income or Expense)
- View transactions within a specified date range
- Visualise income and expenses over time

## Getting Started

### Prerequisites

- Python 3.x
- Streamlit
- Pandas
- Matplotlib

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/finance_tracker.git
    cd finance_tracker
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

To run the Streamlit application, use the following command:
```bash
streamlit run streamlit_tracker.py
```

## Usage

1. **Add a New Transaction**:
    - Select "Add new transaction" from the sidebar.
    - Enter the date, amount, category, and description (optional) of the transaction.
    - Click "Add Transaction" to save the entry.

<img src="1_add_transaction.png" alt="Add Transaction" width="400"/>

2. **View Transactions and Summary**:
    - Select "View transactions and summary" from the sidebar.
    - Enter the start date and end date for the date range you want to view.
    - Click "Get Transactions" to see the transactions and the summary (total income, total expense, and net savings) for the specified date range.

<img src="2_transaction.png" alt="View Transactions" width="400"/>

3. **Visualise Transactions**:
    - A plot will be generated showing income and expenses over time for the specified date range.

<img src="3_expense.jpg" alt="Visualise Transaction" width="400"/>


## Files

- `streamlit_tracker.py`: The main Streamlit application script.
- `data_entry.py`: Helper functions for data entry (imported in the main script).
- `finance_data.csv`: CSV file used to store transaction data.
