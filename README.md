# Payment Receipt Generator

A simple and elegant payment receipt generator built with Streamlit.

## Overview

This application provides an easy-to-use interface for generating payment receipts. Users can enter customer details, payment amount, and select a payment method to generate a formatted receipt.

## Features

- 📝 **Customer Information**: Enter customer name for the receipt
- 💰 **Amount Input**: Specify the payment amount with decimal precision
- 💳 **Payment Methods**: Choose from multiple payment options:
  - Credit Card
  - Debit Card
  - PayPal
  - Cash
- 🧾 **Receipt Generation**: Generate formatted receipts instantly

## Installation

1. Clone the repository:
```bash
git clone https://github.com/samarthrana027/Payment_Receipt.git
cd Payment_Receipt
```

2. Install required dependencies:
```bash
pip install streamlit
```

## Usage

Run the application using Streamlit:

```bash
streamlit run streamlit_pro_paymentreceipt.py
```

The application will open in your default web browser at `http://localhost:8501`

### Steps to Generate a Receipt:

1. Enter the customer's name in the text input field
2. Enter the payment amount using the number input
3. Select a payment method from the dropdown menu
4. Click the "Generate Receipt" button
5. Your formatted receipt will be displayed on the screen

## Project Structure

```
Payment_Receipt/
├── streamlit_pro_paymentreceipt.py
└── README.md
```

## Code Structure

### PaymentReceipt Class

The core class that handles receipt generation:

- `__init__()`: Initializes the receipt with customer details
- `generate_receipt()`: Creates a formatted receipt string

### main() Function

Contains the Streamlit UI logic:
- Text input for customer name
- Number input for payment amount
- Dropdown selector for payment methods
- Button to trigger receipt generation

## Requirements

- Python 3.7+
- Streamlit 1.0+

## Technical Details

- **Language**: Python
- **Framework**: Streamlit
- **Purpose**: Payment receipt generation and display

## Contributing

Feel free to fork this repository and submit pull requests with improvements or new features.

## License

This project is open source and available for personal and commercial use.

## Author

Created by samarthrana027

## Support

For issues or questions, please open an issue in the repository.
