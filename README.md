# Expense Tracker

A desktop-based Expense Tracker application built using Python and Tkinter. It allows users to manage daily expenses, search records, split bills, and visualize monthly spending. Expense records are stored locally using SQLite.

## Features

- **Add Expenses:** Record expenses with date, payee, description, amount, and payment method.
- **View Expenses:** Display saved expense records in a table.
- **Edit Expenses:** Update existing expense records.
- **Delete Expenses:** Delete selected records or clear all records.
- **Search Expenses:** Search by payee, description, or amount.
- **Monthly Expense Chart:** Visualize monthly expenses using a bar chart.
- **Split Expenses:** Divide expenses equally or using custom percentages.
- **Expense Summary:** Convert expense details into a readable sentence.
- **Calculator:** Open the Windows Calculator.
- **Clear Fields:** Reset the input fields.

## Screenshots

### Main Dashboard
<img width="1410" height="676" alt="image" src="https://github.com/user-attachments/assets/19faed54-6967-469d-bd1b-7e3bbef30568" />

### Expense Records
<img width="1332" height="638" alt="image" src="https://github.com/user-attachments/assets/c7df4e76-74b8-4da0-bfe4-3af06f9f2958" />

### Monthly Expense Chart
<img width="1325" height="639" alt="image" src="https://github.com/user-attachments/assets/68dd719b-41e2-442c-ae18-ac43ee4b80bb" />

## Technologies Used

- Python
- Tkinter – GUI development
- SQLite – Database management
- TkCalendar – Date selection
- Matplotlib – Expense visualization

## Installation and Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/jomiw/Expense-Tracker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Expense-Tracker
   ```

3. Install the required libraries:

   ```bash
   pip install tkcalendar matplotlib
   ```

4. Run the application:

   ```bash
   python expense_tracker.py
   ```

## Project Structure

```text
Expense-Tracker/
│
├── expense_tracker.py
├── searchicon.png
├── Expense_Tracker.db
├── screenshots/
│   ├── dashboard.png
│   ├── records.png
│   └── monthly-chart.png
│
└── README.md
```

**Note:** The SQLite database is created automatically when the application runs for the first time. Keep `searchicon.png` in the same directory as `expense_tracker.py`.

## Supported Payment Methods

- Cash
- Cheque
- Credit Card
- Debit Card
- UPI
- Paytm
- Google Pay
- PhonePe
- Razorpay

## Platform Compatibility

The application is designed for desktop use. The calculator feature uses Windows Calculator (`calc.exe`), so that feature is Windows-specific.

## Future Improvements

- Expense categories
- Advanced spending reports
- Export expenses to CSV or Excel
- Improved input validation
