# Blood Bank Management System

A simple blood bank management project implemented using SQL, designed to help manage blood donations, blood inventory, donation camps and blood requests.

## Features

- **Donor Management**: Store and manage donor information, including name, contact details, blood type, and donation history.
- **Inventory Management**: Track the available blood units for each blood type, including the quantity, storage location, and expiry dates.
- **Blood Requests**: Handle blood requests from hospitals or patients, matching the requested blood type with available units in the inventory.
- **Organisation Management**: Stores the information of various organisations, including name, location and contact details. 

## Database Schema

The project uses a relational database with the following tables:

- **Donors**: Stores donor information, including donor ID, name, contact details, blood type, and donation history.
- **Recepients**: Stores recepient information, including ID, name, contact details, and blood type.
- **Inventory**: Keeps track of the blood units in the inventory, including the blood type, quantity, storage location, and expiry date.
- **Requests**: Manages blood requests, including the requesting organization, blood type, quantity, and status.

## ER Diagram

You can check the ER Diagram given in this repository.

## Technologies Used

LiveSQL: The project is built using Oracle's LiveSQL, a web-based SQL development and deployment environment.

## Installation and setup

1. Clone the repository:

   ```shell
   git clone https://github.com/AartiM03/Blood-Bank-Management-System.git
   ```
2. Open your LiveSQL environment. You may need to create an account on Oracle's LiveSQL.
3. Create a new project or open an existing project.
4. Import the SQL script cloned repository.(Or just click on the sql script file to open the script)

## License

This project is licensed under the [MIT License](LICENSE).
