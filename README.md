Read Me file

# Restaurant Menu App

A React Native application that allows users to view, add, and delete items from a restaurant's menu. It also provides features to calculate average prices for menu categories and filter menu items.

## Features

- Homepage:
  - Displays the full menu with dish details such as name, description, course, and price.
  - Allows users to delete a dish from the menu.
  - Displays the average price for each menu course (e.g., Starter, Main, Dessert).

- Chef Page:
  - Allows chefs to add new dishes to the menu.
  - Newly added dishes appear on the homepage in real-time.

- Filter Page:
  - Enables filtering of menu items based on various criteria.

## Installation

1. Clone the Repository
   
   git clone <repository-url>
   cd restaurant-menu-app
2. Install Dependencies

    npm install


3. Run the Application

    npm start

4. Launch the App

Run the app on an Android or iOS emulator using:

   npm run android
   or
   npm run ios


Project Structure

src/
│
├── components/
│   ├── Homepage.tsx     # Displays the full menu and handles item deletion.
│   ├── ChefPage.tsx     # Handles adding new dishes to the menu.
│   └── FilterPage.tsx   # Implements filtering of the menu.
│
├── context/
│   └── MenuContext.tsx  # Provides shared state for the menu items across the app.
│
├── App.tsx              # Main entry point of the application.
│
└── styles/
    └── commonStyles.ts  # Shared styles for the application.
Usage
Adding a Dish
Navigate to the Chef Page.
Enter the dish name, description, course, and price.
Press the "Add Dish" button to add the dish to the menu.
Deleting a Dish
Navigate to the Homepage.
Find the dish you want to remove.
Press the "Delete" button next to the dish.
Filtering Menu
Navigate to the Filter Page.
Apply filters such as course type or price range.
Viewing Average Prices
The average price for each course is displayed at the bottom of the Homepage.


