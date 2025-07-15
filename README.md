# Skaker-Restaurant-Application
Skaker is a Python-based graphical user interface (GUI) application developed using Tkinter as a first-semester university project. It enables users to order candies from a dessert store menu, featuring an aesthetically pleasing pink-themed interface with dessert icons, menu display, cart management, and bill calculation. The application integrates with an Excel file for menu data and provides a seamless user experience for browsing and ordering sweets.

## Project Structure

- **Skaker-Restaurant/**: Root project folder.
  - **src/**: Contains the main Python script.
    - `Skaker Restaurant.py`: Core script for the Tkinter GUI, menu display, cart, and bill calculation.
  - **data/**: Stores the menu data.
    - `Menu.xlsx`: Excel file with menu items (columns: name, category, price, optional imagePath).
 - **images/**: Directory for GUI images.
      - `logo.png`: Application logo.
      - `cupcake.png`: Dessert icon for UI.
      - `candy.png`: Another dessert icon.
      - etc
  - **README.md**: Project documentation.
  - **requirements.txt**: Lists Python dependencies (`tkinter`, `pillow`, `pandas`, `openpyxl`).


## Features
- **Interactive Menu**: View a categorized menu of sweets loaded from an Excel file (`Menu.xlsx`).
- **Cart Management**: Add items to a cart with customizable quantities using a spinbox.
- **Bill Calculation**: View a detailed bill with the total amount for selected items.
- **Themed Interface**: A pink-themed GUI with dessert icons (cupcakes, candy, etc.) for a delightful user experience.
- **Navigation**: Easily switch between the home screen, menu, and cart.

## Installation
- Download the project file (Skaker Restaurant.py), data, and images in the same folder.
- Install python 3.6+ on your device.
- Instal the required python libraries (tkinter pillow pandas openpyxl) by using pip install tkinter pillow pandas openpyxl.


## Usage
- **Launch the Application:**
    - Run Skaker Restaurant.py to open the home screen with a pink-themed interface.
- **Navigate the Home Screen:**
    - Click Show Menu to view the dessert menu.
    - Click Your Cart to see the current cart and bill.  
- **Browse the Menu:**
    - In the menu window, view items loaded from Menu.xlsx.
    - Use the spinbox to select quantities for desired items.
    - Click Add to cart to add items to the cart.
    - Click Proceed to checkout to view the bill or Back to Home to return to the main screen.
- **View and Manage Cart:**
    - In the cart window, review selected items, quantities, and the total bill.
    - Return to the home screen to continue browsing or finalize the order.
  
## Team Members
- **Mariam Elbadry:** Designed and implemented the GUI and home page.
- **Dareen Hassan:** Developed functionality to display items from the Excel sheet and add them to the cart.
- **Merna Adly:** Implemented the bill calculation for the user.






