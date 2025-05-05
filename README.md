# Inventory Management System

A simple yet effective command-line inventory management system built with Python, using JSON for data storage and retrieval.

[Screenshot 2025-05-05 211151](https://github.com/user-attachments/assets/c97e7cc9-30f5-41c9-bdbf-d08945960297)


##  Overview

This inventory management system allows store owners to manage their product inventory through a simple command-line interface. The system stores product information in a JSON file and provides functionalities for viewing products, making purchases, and automatically updating inventory levels.

##  Features

- **Product Catalog Display**: View all available products with their IDs, names, prices, and quantities
- **Purchase Processing**: Buy products by specifying the product ID and desired quantity
- **Insufficient Stock Handling**: Option to purchase available stock when requested quantity exceeds available
- **Automated Billing**: Generate bills for completed purchases
- **Real-time Inventory Updates**: Automatically update product quantities after purchases
- **Data Persistence**: Store all inventory data in a JSON file for persistence between sessions

##  Technical Implementation

The system is built using:
- **Python** for core functionality and business logic
- **JSON** for data storage and management
- **Command-line interface** for user interaction

##  Getting Started

### Prerequisites

- Python 3.6 or higher
- No external dependencies required

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/inventory-management-system.git
   cd inventory-management-system
   ```

2. Make sure you have a properly formatted inventory JSON file named `inventory mgmt sys.json` in the project directory.

### Sample JSON Structure

The system expects a JSON file with the following structure:

```json
{
  "1001": {
    "Name": "5 Star",
    "Price": 10,
    "Qn": 147
  },
  "1002": {
    "Name": "Bar-One",
    "Price": 20,
    "Qn": 50
  },
  "1003": {
    "Name": "Candy",
    "Price": 2,
    "Qn": 985
  },
  "1004": {
    "Name": "Chocolate Cake",
    "Price": 550,
    "Qn": 6
  },
  "1005": {
    "Name": "Blueberry Cake",
    "Price": 650,
    "Qn": 3
  }
}
```

### Usage

Run the program using Python:

```
python inventory_management.py
```

Follow the on-screen prompts to:
1. View the product catalog
2. Enter a product ID to purchase
3. Specify the quantity desired
4. Complete the purchase or handle insufficient stock scenarios

## 🔄 Workflow

1. The system loads the inventory data from the JSON file
2. Displays all products in a formatted menu
3. Prompts the user to enter a product ID and quantity
4. Checks if sufficient quantity is available
   - If yes, processes the purchase and generates a bill
   - If no, offers the option to purchase available stock
5. Updates the inventory file with new quantities

## 📝 Future Enhancements

- Add admin interface for adding new products
- Implement user authentication
- Add sales reporting and analytics
- Create a graphical user interface
- Implement barcode scanning functionality

## 📊 Project Structure

```
inventory-management-system/
│
├── inventory_management.py - Main program file
├── inventory mgmt sys.json - Inventory data storage
└── README.md - Project documentation
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

 ## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

 ## Author

- [Muskan maddhesiya](https://github.com/yourusername)

---

Made with ❤️ and Python
