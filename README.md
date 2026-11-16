# Currency Converter

A Python 3 console-based currency converter that converts amounts between four supported currencies using fixed exchange rates stored in a dictionary.

## Project Details

- **Project Title:** Currency Converter
- **Problem Statement Number:** 25
- **Name:** Riya Samant
- **ERP Number:** RU-26-01668
- **Programming Language:** Python 3

## Project Description

The Currency Converter is a simple Python application that allows users to convert amounts between INR, USD, EUR and GBP.

The program uses INR as the base currency for every conversion and stores the exchange rates in a Python dictionary.

## Supported Currencies and Exchange Rates

| Currency | Rate in INR |
|---|---:|
| INR | 1 |
| USD | 83 |
| EUR | 90 |
| GBP | 105 |

## Features

- Converts between four supported currencies.
- Uses a dictionary to store exchange rates.
- Uses functions to perform conversions.
- Validates currency codes entered by the user.
- Handles invalid and negative amounts.
- Displays converted results rounded to two decimal places.
- Uses INR as the base currency for all conversions.

## Python Concepts Used

- Functions
- Conditional Statements (if-else)
- Operators
- Dictionaries
- Exception Handling
- Decimal Module

## How to Run the Program

1. Make sure Python 3 is installed.
2. Open the project folder in VS Code.
3. Open the terminal.
4. Run the following command:

```bash
python Currency_Converter.py
```

5. Enter the amount, source currency and target currency when prompted.

## Project Structure

```text
Currency-converter/
│
├── Codebase/
│   ├── Currency_Converter.py
│   └── README.md
│
└── Testcases/
    └── Test case screenshots
```

## Conclusion

This project demonstrates the use of fundamental Python concepts to develop a functional console-based currency converter. It provides a simple way to perform currency conversions while handling invalid inputs and displaying accurate results to two decimal places.
