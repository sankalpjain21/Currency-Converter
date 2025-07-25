# Currency-Converter
Currency Converter Web Application

This is a simple and responsive currency converter built using HTML, CSS, and JavaScript. It fetches real-time exchange rates using the Fawaz Ahmed Currency API and displays corresponding country flags using the Flags API.

Live Demo

You can run the project locally or host it using platforms like GitHub Pages, Netlify, or Vercel.

Project Structure

currency-converter/
├── index.html            - Main HTML page
├── styleFile.css         - Styling for the application
├── javascriptApi.js      - JavaScript logic and API integration
├── countryList.js        - Mapping of currency codes to country codes
└── README.md             - Project overview and documentation

Features

- Convert between multiple international currencies
- Real-time exchange rate updates using a free API
- Automatically updates country flags based on currency selection
- Responsive and mobile-friendly user interface
- Pre-set default conversion from USD to INR on page load

APIs Used

Currency Exchange API  
Provided by Fawaz Ahmed Currency API  
Endpoint format:  
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/{currency}.json

Flags API  
Provided by FlagsAPI  
Format:  
https://flagsapi.com/{COUNTRY_CODE}/flat/64.png

How to Use

1. Clone the repository to your local machine:
   git clone https://github.com/yourusername/currency-converter.git

2. Navigate to the project directory and open index.html in a browser:
   cd currency-converter

   Then, open the file manually or run:
   start index.html

No additional setup or dependencies are required. The application runs entirely in the browser.

Future Improvements

- Add a search/filter option to quickly find currencies in dropdowns
- Display the last updated timestamp for exchange rates
- Add support for saving recent conversions
- Introduce a dark mode toggle

