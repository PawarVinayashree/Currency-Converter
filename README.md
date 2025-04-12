# Currency Converter

## Overview
This program allows users to convert one currency to another using real-time exchange rates from the Fixer.io API. The exchange rates are fetched dynamically and reflect the most recent rates available.

## Features
- Converts currencies based on live data from the Fixer.io API.
- Supports a wide range of currencies from all over the world.
- Allows users to input the amount of currency they want to convert, along with the source and target currencies.
- Displays the conversion result in a user-friendly format.
- Provides an option to view a list of available currencies.
- Users can quit the program at any time.

## Requirements
- Python 3.x
- `requests` library (for API requests)

You can install the required library using the following command:
```
pip install requests
```

## How It Works
1. The program fetches live currency exchange rates from the Fixer.io API.
2. The user is prompted to enter the amount of currency they wish to convert, along with the source currency and target currency.
3. The program then calculates and displays the conversion result.
4. If the user wants to see the list of available currencies, they can type `SHOW`.
5. To quit the program, simply type `Q`.

## Usage
1. **Run the program:**
   After running the script, you will be prompted to input the amount of currency you want to convert.

   Example input:
   ```
   100 USD EUR
   ```

2. **View available currencies:**
   Type `SHOW` to display a list of supported currencies.

3. **Quit the program:**
   Type `Q` to exit the program.

## Example Interaction
```
Please specify the amount of currency to convert, from currency, to currency (with space in between).
Press SHOW to see list of currencies available. 
Press Q to quit. 
100 USD EUR
100 of currency USD amounts to 93.5 of currency EUR today

Press any key to continue...
```
## Error Handling
- If the user enters an invalid currency code or an incorrect format, the program will prompt them to retry.
- The program will handle errors related to the input, ensuring the user can easily re-enter their query.

## Disclaimer
- This program uses the Fixer.io API for real-time exchange rates. The accuracy and availability of the data depend on the API's performance.
- You will need a valid API key from Fixer.io to run this program. 

## Contributing
Feel free to fork this repository and make improvements! Pull requests are welcome.
