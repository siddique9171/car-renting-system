
markdown
Copy code
# Car Rental Management System

This repository contains a **Python-based Car Rental Management System** that helps manage vehicle rentals, returns, and transaction records for a car rental business. It offers a user-friendly menu for performing essential tasks such as listing available cars, renting cars, and calculating earnings.

---

## Features

- **List Available Cars**  
  View cars that are not currently rented.

- **Rent a Car**  
  - Allows customers to rent cars by providing a registration number and personal details.
  - Validates age (18-80 years), name formatting, and email address.
  - Ensures the car is not already rented.

- **Return a Car**  
  - Calculates rental duration and cost based on the daily rental rate.
  - Updates records to reflect the return and logs the transaction.

- **Earnings Calculation**  
  - Summarizes total revenue from all completed rentals.

- **Data Storage**  
  - All data is saved in text files (`vehicles.txt`, `customers.txt`, `rentedVehicles.txt`, and `transActions.txt`) for easy management and persistence.

---

## File Structure

- `vehicles.txt`:  
  Contains vehicle details in the format:  
  `RegistrationNumber,Model,DailyRate`  
  Example:  
ABC123,Toyota Corolla,40 XYZ789,Honda Civic,50

markdown
Copy code

- `customers.txt`:  
Stores customer details:  
`BirthDate,FirstName,LastName,Email`  
Example:  
01/01/1990,John,Doe,john.doe@example.com

markdown
Copy code

- `rentedVehicles.txt`:  
Tracks ongoing rentals:  
`RegistrationNumber,BirthDate,RentStart`  
Example:  
ABC123,01/01/1990,25/11/2024 10:30

markdown
Copy code

- `transActions.txt`:  
Records completed rental transactions:  
`RegistrationNumber,BirthDate,RentStart,RentEnd,DaysRented,Cost`  
Example:  
ABC123,01/01/1990,25/11/2024 10:30,26/11/2024 12:00,2,80.00

yaml
Copy code

---

## How to Use

1. **Clone the Repository**  
 ```bash
 git clone https://github.com/yourusername/car-rental-management-system.git
 cd car-rental-management-system
Add Necessary Files
Ensure vehicles.txt, customers.txt, rentedVehicles.txt, and transActions.txt are present in the directory. Populate these files with the required data as per the format above.

Run the Script
Execute the Python program:

bash
Copy code
python car_rental_management.py
Follow Menu Options
Use the menu-driven interface to manage car rentals and transactions.

Prerequisites
Python 3.6 or later
Install Python from python.org.
Future Enhancements
Implement a graphical user interface (GUI).
Add AI-powered features such as dynamic pricing and customer analytics.
Migrate to a database system for scalable and secure data storage.
Contributing
Contributions are welcome! Fork the repository and create a pull request with your improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.

vbnet
Copy code

Save this text as `README.md` and include it in your project folder before uploading to GitHub. Let me know if you need additional changes!





