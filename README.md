# Real-Time Currency Converter

This project is a simple Currency Converter application built using Python's Tkinter and the Alpha Vantage API for real-time exchange rates. The application allows users to convert an amount from one currency to another by fetching live exchange rates.

## Features

- Real-time currency exchange rate data using the [Alpha Vantage API](https://www.alphavantage.co).
- Allows conversion between major currencies (EUR, USD, JPY, TRY).
- Simple and intuitive graphical user interface (GUI) built with Tkinter.
- User can select source and target currencies and input an amount to get the converted value.

## Requirements

Before running the application, ensure you have the following Python libraries installed:

- `Tkinter` (Usually comes pre-installed with Python)
- `requests` (To make API requests)

You can install the required library using:

```bash
pip install requests
```

## How to Use

1. Clone the repository or download the `currency_converter.py` file to your local machine.
2. Install required libraries.
3. Run the `currency_converter.py` script in your Python environment.
4. Input the amount you want to convert.
5. Choose the source and target currencies from the dropdown options.
6. Click the "Convert" button to get the result.

## Code Explanation

### Tkinter Interface

- The main interface includes two dropdown menus for selecting the source and target currencies.
- An input field allows users to enter the amount they want to convert.
- A result field shows the converted value based on real-time exchange rates.

### Alpha Vantage API

- The app uses the `CURRENCY_EXCHANGE_RATE` function of the Alpha Vantage API to fetch live exchange rates.
- The API key required for accessing the data is stored in the code. You can replace it with your own key if needed.

### Functions

- **`exchange()`**: Fetches the exchange rate between the selected currencies and performs the conversion.
- **`clear_all()`**: Clears all fields, resetting the selections and input.

## Example

For instance, if you want to convert 100 USD to EUR:

- Enter `100` in the "Amount" field.
- Select `USD` as "From Currency".
- Select `EUR` as "To Currency".
- Press the "Convert" button to get the result.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
