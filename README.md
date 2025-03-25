# Getting Started with Create React App
# Investment Calculator


🚀 Project Description
A simple web application that calculates investments over the years based on user inputs, such as initial capital, yearly contribution, expected return, and investment duration. The app displays the results in a well-formatted table.


# 🏗️ Main Components
-Header.jsx 🏷️: Displays the app title along with the logo.
-UserInput.jsx 🎛️: Contains the form where users enter investment details.
-ResultsTable.jsx 📊: Displays the calculated yearly data in a structured table.
-App.js 🏠: The main component that connects all parts, manages data, and handles calculations.


# Hooks Used
useState → Stores user input data and updates results dynamically.


# Important Functions
-calculateHandler(userInput) 📊 Computes yearly investment growth and updates the yearlyData array.
-submitHandler(event) 📩 Calls props.onCalculate(userInput) to process the investment calculation.
-resetHandler() 🔄 Resets the input fields to their default values.
-inputChangeHandler(input, value) 🔢 Dynamically updates user input values.


### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
