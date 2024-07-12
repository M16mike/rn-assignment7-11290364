# rn-assignment7-11290364

# React Native E-commerce App-OpenFashion App

## Overview

This React Native application is an e-commerce platform that allows users to browse products, view product details, add items to their cart, and manage their shopping cart. The app fetches product data from an external API and uses local storage to persist the user's cart information.

## Features

- Browse a list of products on the home screen
- View detailed information about each product
- Add products to the shopping cart
- Remove products from the shopping cart
- View all items in the shopping cart
- Navigate through the app using a drawer component

## Screens

1. **HomeScreen**: Displays a list of available products fetched from an external API.
2. **ProductDetailScreen**: Shows detailed information about a selected product.
3. **CartScreen**: Displays all items added to the shopping cart.

## Implementation Details

### Data Fetching
- Used [Fetch API/Axios] to retrieve product data from an external API.
- Implemented asynchronous operations using [async/await/Promises].

### State Management
- Utilized [Redux/Context API/MobX] for global state management.

### Local Storage
- Implemented [AsyncStorage/SecureStore/FileSystem] to store cart items locally on the device.

### Navigation
- Used React Navigation for handling navigation between screens.
- Implemented a drawer navigation component for easy access to different app sections.

### UI Components
- Developed custom components for product lists, product details, and cart items.
- Implemented "Add to Cart" and "Remove from Cart" buttons for each product.

## Screenshots

![photo_10_2024-07-12_23-24-57](https://github.com/user-attachments/assets/8272b9e5-ba24-4c15-9b99-00a1f61440e6)
![photo_9_2024-07-12_23-24-57](https://github.com/user-attachments/assets/8b2c4d84-9448-4417-8c86-ead9da6bff62)
![photo_8_2024-07-12_23-24-57](https://github.com/user-attachments/assets/3c64d01d-8cc1-47d5-87e5-935715dfb4c6)
![photo_7_2024-07-12_23-24-57](https://github.com/user-attachments/assets/96b7e17d-dacb-4693-94be-8acba1d5d7f2)
![photo_6_2024-07-12_23-24-57](https://github.com/user-attachments/assets/392680c1-7e69-4145-806b-699c47574b63)
![photo_5_2024-07-12_23-24-57](https://github.com/user-attachments/assets/6b25ab73-dda4-4b92-bd26-08d53e973659)
![photo_4_2024-07-12_23-24-57](https://github.com/user-attachments/assets/7ab32c59-384e-4fa1-a27c-9a92ca569d74)
![photo_3_2024-07-12_23-24-57](https://github.com/user-attachments/assets/6379d5f5-ec7f-48c5-86ff-4918ec0b13e6)
![photo_2_2024-07-12_23-24-57](https://github.com/user-attachments/assets/2d89db53-aca7-44a1-8575-d80cdc69ca14)
![photo_1_2024-07-12_23-24-57](https://github.com/user-attachments/assets/ed7cd185-7150-4d77-88f7-07962a3e8d60)


## Design Choices

used a basic white background for the colour scheme and copied other design patterns and rendering from the UI mockup

## How to Run

1. Clone the repository
2. Install dependencies with `npm install`
3. Run the app with `npm start`
   
## Future Improvements

- Implement user authentication
- Add a checkout process
- Implement product categories and filtering
