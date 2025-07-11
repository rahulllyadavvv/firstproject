# firstproject

Currency Converter App — Project Description
📝 Overview
Hi ,Rahul this side its my first frontend project which isa a curreny converter app .
The  App is a responsive, single-page application built with React and styled using Tailwind CSS. It allows users to convert an amount from one currency to another using real-time exchange rates fetched from the ExchangeRate-API. The app features a smooth UI with live conversions, input validation, and a swap functionality to reverse the currencies.

🔧 Technologies Used
Technology	Purpose
React	Frontend framework for building the UI and components
Tailwind CSS	Utility-first CSS framework for styling and layout
ExchangeRate-API	API to fetch real-time currency exchange rates
React Hooks	useState, useEffect, and useId for state and logic handling
Custom Hooks	useCurrencyInfo for reusable API-fetching logic
JavaScript (ES6)	Core language for logic and interactivity
Vite	Fast React development build tool (instead of CRA)

🔑 Key Features
💸 Currency Conversion: Convert any numeric amount between two currencies

🔁 Swap Button: Swap source and target currencies in one click

📡 Live Exchange Rates: Data fetched in real-time from ExchangeRate-API

🧩 Reusable Components: Custom InputBox component for better modularity

🧠 Custom Hook: useCurrencyInfo(currency) to encapsulate data-fetching logic

💅 Responsive Design: Mobile-friendly UI using Tailwind's utility classes

🔐 Input Control: Disable/enable amount or currency fields as needed

📁 Project Structure

currencyconverter/
├── assets/
│   └── components/
│       └── Inputbox.jsx
├── hooks/
│   └── usecurrencyinfo.js
├── App.jsx
├── App.css
├── vite.config.js
└── index.html

