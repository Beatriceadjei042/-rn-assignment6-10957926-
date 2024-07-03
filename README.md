React Native Assignment 6

This is a simple React Native application for managing a product list and a shopping cart. The app allows users to view a list of available products, add products to their cart, remove products from their cart, and view the items in their cart. The selected items are stored locally on the device using AsyncStorage.

Features

- HomeScreen: Displays a list of available products.
- CartScreen: Displays the selected items in the cart.
- Add to Cart: Allows users to add products to their cart.
- Remove from Cart: Allows users to remove products from their cart.
- Local Storage: Uses AsyncStorage to store selected items locally on the device.

Installation

1. Clone the repository:

   git clone https://github.com/your-username/rn-assignment6-ID.git
   cd rn-assignment6-ID

2. Install dependencies:

 
   npm install


3. Run the application:
   npm start
 

   This will start the Metro Bundler. You can then run the app on an emulator or a physical device.

Project Structure

- `App.js`: The main entry point of the application.
- `Screens/`: Contains the `HomeScreen` and `CartScreen` components.
- `components/`: Contains reusable components such as `ProductItem`.
- `assets/`: Contains images and other assets used in the application.

 Data Storage

The application uses AsyncStorage to store the selected items locally on the device. This allows the cart to persist even if the app is closed or the device is restarted.

Design Choices

- UI/UX: The design follows a simple and intuitive layout for easy navigation and interaction. The product list and cart are displayed using FlatList for performance and scalability.
- State Management: The app uses React's built-in state management with hooks to manage the state of the cart and product list.
- Local Storage: AsyncStorage is used for local storage due to its simplicity and ease of use with React Native.

10957926
Adjei Beatrice
