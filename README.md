# Medical-Supply-Management-System

## About the Project
Hey folks,  
This project is designed for medical purposes where medical shop owners can order medicines and products from pharmacy suppliers. The system allows pharmacy suppliers to manage the orders and products through a web interface.

### Features:
1. *Authentication System* - Access restricted to registered pharmacy suppliers.
2. *Medical Registrations* - Register medical shops for ordering medicines and products.
3. *CRUD Operations* - Create, Read, Update, and Delete records related to medicines, products, and orders.
4. *Search Functionality* - Search for medicines and products using filters.
5. *Triggers and Stored Procedures* - Database triggers and stored procedures to ensure data integrity.
6. *Add Products and Medicines* - Suppliers can add new products and medicines.
7. *View Records* - View records of all registered medical shops and products.
8. *Sell Medicines & Products* - Process the sale of medicines and products.

---

## Tech Stack

*Frontend*  
- HTML
- CSS
- Bootstrap
- JavaScript

*Backend*  
- Flask (Python)
- Flask-SQLAlchemy (ORM)
- MySQL

---

## Getting Started

### Prerequisites
Before you begin, ensure you have installed Python 3.x on your system. Then, install the necessary dependencies as described below.

### Installation

1. *Clone the repository*:
    bash
    git clone https://github.com/your-username/medical-shop-ordering-system.git
    cd medical-shop-ordering-system
    

2. *Install the required modules*:
    Open your command prompt or terminal and run the following commands:
    bash
    pip install flask
    pip install Flask-SQLAlchemy
    pip install mysqlclient
    pip install Flask-Login
    

3. *Database Setup*:
   - Create a MySQL database and configure the connection in the Flask app.
   - Run the database migrations or import the provided SQL schema.

4. *Run the Application*:
    bash
    python app.py
    

5. *Access the Application*:
   - Open your browser and go to http://localhost:5000/.

---

## Usage

- *Authentication*: Only registered pharmacy suppliers can log in.
- *Registration*: Medical shop owners can register with their details for placing orders.
- *Add Products/Medicines*: Suppliers can add new products and medicines into the system.
- *View Records*: See all registered shops and products.
- *Search*: Search for specific medicines and products by name or category.
- *Triggers and Stored Procedures*: Manage inventory efficiently using pre-defined database actions.
- *Sell Medicines/Products*: Process and track the sale of products.

---

## Folder Structure

bash
.
├── app.py                   # Main Flask application
├── templates/               # HTML templates
├── static/                  # Static files (CSS, JS, images)
├── models.py                # Database models and schema
├── config.py                # Configuration file for the app
├── requirements.txt         # List of dependencies
└── README.md                # Project documentation


---

## Contributing

Contributions are welcome!  
Feel free to fork this project and submit pull requests to improve functionality or fix bugs.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

If you have any questions or feedback, feel free to reach out at [nihalkanchan888@gmail.com].

---
