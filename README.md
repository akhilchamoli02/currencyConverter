# Currency Converter

This repository contains a currency converter application built with React.js and styled using Tailwind CSS. The application allows users to convert an amount from one currency to another using real-time exchange rates.

# Features

1. **Real-time Exchange Rates**: Fetches the latest exchange rates from a reliable API.
2.  **Multiple Currencies**: Supports conversion between various currencies.
3. **Responsive Design**: Responsive user interface built with Tailwind CSS.
4. **User-friendly Interface**: Easy-to-use interface for quick conversions.
5.  **Error Handling**: Handles errors gracefully, including network issues and invalid input.

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling.
```sh
API Service: https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/${currency}.json
```
- **JavaScript**: The programming language used for application logic.
- **HTML5**: The standard markup language for creating web pages.

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/akhilchamoli02/currencyConverter.git
   ```
   
2. **Navigate to the Project Directory**:
   ```sh
   cd currencyConverter
   ```

3. **Install Dependencies**:
   ```sh
   npm install
   ```

## Usage

1. **Start the Application**:
   ```sh
   npm start dev
   ```
2. **Update vite.config.js**:
    ```sh
    import { defineConfig } from 'vite'
    import react from '@vitejs/plugin-react'
    // https://vitejs.dev/config/
    export default defineConfig({
    plugins: [react()],
    })
    ```

3. **Open in Browser**:
   Open your web browser and navigate to `http://localhost:5173`.

4. **Convert Currency**:
   - Select the base currency and target currency from the dropdown menus.
   - Enter the amount to convert.
   - Click the "Convert" button to see the converted amount.

## Acknowledgements

- [React.js](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Exchange Rates API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/${currency}.json)