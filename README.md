## Next.js Shopping Cart App

## Overview

This project is a Next.js-based shopping cart application that uses the Context API for state management. It includes a homepage and a shop page with a shopping cart that updates dynamically. The application fetches product data from an external API and allows users to add, remove, and adjust quantities of items in their cart.

## Features

Navigation Bar: Present on all pages, displaying the number of items in the cart.

Homepage: Displays basic information or images.

Shop Page:

Fetches products from FakeStore API or a similar source.

Displays product cards with titles, quantity selection, and an "Add to Cart" button.

Users can manually enter a quantity or use increment/decrement buttons.

The shopping cart updates dynamically when an order is placed.

Cart Page:

Shows the number of items in the cart.

State Management: Uses React Context API to manage the cart state globally.

Styling: Custom styles are applied for a polished user experience.

## Installation & Setup

Clone the repository:

git clone git@github.com:AlexVNep/shoppingCcart.git
cd shoppingCart

Install dependencies:

npm install

Start the development server:

npm run dev

Open the app in your browser at http://localhost:3000/.

## API Usage

This application fetches product data from FakeStore API
