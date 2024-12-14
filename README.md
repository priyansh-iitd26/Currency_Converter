# Currency_Converter
**Project Overview**

The Currency Converter is a web application developed purely using HTML, CSS, and JavaScript. This project enables users to convert between various currencies using real-time exchange rates fetched from the [currencyapi](https://currencyapi.com/) API. The application provides a user-friendly interface and accurate currency conversion calculations.

**Features**

- Real-time currency conversion using the currencyapi API.
- User-friendly and responsive interface.
- Support for multiple currencies.

**Technologies Used**

- HTML: For structuring the web page.
- CSS: For styling the web page.
- JavaScript (JS): For implementing the conversion logic and fetching data from the API.
- currencyapi API: For obtaining real-time exchange rates.

**Project Structure**


```
Currency-Converter/
├── index.html
├── style.css
├── script.js
├── README.md

```

- index.html: The main HTML file containing the structure of the web page.
- styles.css: The CSS file for styling the web page.
- script.js: The JavaScript file containing the logic for fetching exchange rates and performing currency conversion.
- README.md: This file.

**Setup and Usage**

1. Clone the repository to your local machine.
```
git clone https://github.com/yourusername/currency-converter.git
```
2. Navigate to the project directory.
```
cd currency-converter
```
3. Open **index.html** in your web browser to view the application.
4. Enter the amount and select the base currency you want to convert from.
5. Click the **Submit** button to see the converted amount.

**API Integration**

The application uses the [currencyapi](https://currencyapi.com/) API to fetch real-time exchange rates. You need to obtain an API key from the currencyapi website and replace the **url** placeholder in the **script.js** file with your **actual API key**.

```
// script.js
const url = 'your_currencyapi_api_key';
```
**Contributing**

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

**Acknowledgements**
- [currencyapi](https://currencyapi.com/) for providing latest & real-time exchange rates.
