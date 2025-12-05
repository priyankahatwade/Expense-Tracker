# Daily Expense Tracker

A simple and intuitive web application to track your daily expenses. Built with vanilla HTML, CSS, and JavaScript.

## Features

- **Add Expenses**: Record expenses with amount, description, and date
- **View Expenses**: Display all expenses in a clean list format
- **Edit Expenses**: Click the Edit button to modify an existing expense
- **Delete Expenses**: Remove individual expenses with the Delete button
- **Clear All**: Remove all expenses at once (with confirmation)
- **Total Calculation**: Automatic calculation of total expenses
- **Export to CSV**: Download your expenses as a CSV file
- **Dark Mode**: Toggle between light and dark themes
- **Local Storage**: All data is saved in your browser's local storage
- **Logout**: Clear session and return to login page

## Installation

1. Clone or download this project to your computer
2. Open the `login.html` file in your web browser
3. Sign up with a username and password (saved locally)
4. Log in to access the expense tracker

## File Structure

```
Expense tracker/
├── index.html        # Main expense tracker page
├── login.html        # Login/Sign up page
├── style.css         # Styling for all pages
├── script.js         # Main application logic
└── README.md         # This file
```

## Usage

### Adding an Expense
1. Enter the amount (e.g., 50.00)
2. Enter a description (e.g., "Lunch")
3. Select a date (optional)
4. Click "Add" button

### Managing Expenses
- **Edit**: Click the Edit button next to an expense to modify it
- **Delete**: Click the Delete button to remove an expense
- **Clear All**: Click the Clear All button to remove all expenses

### Export Data
- Click "Export CSV" to download all expenses as a CSV file

### Dark Mode
- Click "Dark Mode" button to toggle between light and dark themes

### Logout
- Click "Logout" to return to the login page

## Data Storage

All expenses are saved in your browser's **localStorage** under the key `expenses_v1`. Your login credentials are also stored locally.

**Note**: Data will persist even after closing the browser, but will be deleted if you clear your browser's cache.

## Browser Support

Works on all modern browsers that support:
- HTML5
- CSS3
- JavaScript ES6
- localStorage API

## Default Styling

- **Background**: Light gray (#f3f4f6)
- **Accent Color**: Blue (#2563eb)
- **Dark Mode**: Dark blue/gray theme
- **Button Colors**: Green (Add), Gray (Clear All), Blue (Actions)

## Future Enhancements

- Cloud sync for data backup
- Monthly/yearly reports
- Category filtering
- Multiple currency support
- Budget limits and alerts
- Data visualization with charts

## License

This project is open source and available for personal use.
