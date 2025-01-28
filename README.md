# Car Rental System

A user-friendly car rental web application developed using PHP, MySQL, HTML, CSS, and JavaScript. This project allows users to book cars from a list of available vehicles, and administrators can manage bookings via the admin panel.

## 🚀 Technologies Used
- **XAMPP/WAMP Server**: Used to run the project locally.
- **PHP**: Backend programming language to handle business logic.
- **MySQL**: Database management system to store data such as bookings and car listings.
- **HTML/CSS**: Frontend technologies for creating the structure and design of the web application.
- **JavaScript**: Adds client-side interactivity.
- **PHPMyAdmin**: Manages MySQL databases and tables.

## 🛠 Features
- **User Side**:
  - View available cars with detailed descriptions.
  - Book a car by filling in the necessary booking details.
- **Admin Panel**:
  - Manage car listings and booking details.
  - View all bookings made by users.

## 📝 Setup Instructions

### Prerequisites
1. Install **XAMPP** or **WAMP** on your local machine.
2. Ensure that **Apache** and **MySQL** services are running.

### Steps to Run the Project
1. Clone the repository or download the project files to your local machine.
2. Copy the project folder into the **htdocs** (XAMPP) or **www** (WAMP) directory.
3. Open **PHPMyAdmin** (accessible through `localhost/phpmyadmin`).
4. Create a new database, e.g., `carrentalsystem`.
5. Import the SQL file (found in the project folder) to create the necessary tables (e.g., booking, cars).
6. Ensure MySQL and Apache are running.
7. In your browser, visit `localhost/your-folder-name/index.php` to access the application.

## 📂 Project Structure
/css - Contains the styling files. /js - Contains JavaScript files for interactivity. /images - Stores images for car listings. /includes - Contains PHP files for common functionalities like database connection. /admin - Contains files for the admin panel. /index.php - Main landing page where users can view and book cars. /booking.php - Page for booking details and form submission.

## 🎮 How It Works
1. **Booking Cars**: Users can browse the list of cars available for rent and make a booking.
2. **Database**: All booking and car details are stored in the MySQL database.
3. **Admin Panel**: Admins can manage bookings and car listings via the admin interface.

   ## 📸 Screenshots
- **Homepage**: Displays the list of available cars.
  ![image](https://github.com/user-attachments/assets/ce28ebaf-cb30-4768-92d2-5177166f21a9)
- **Booking Form**: Users can enter their details and confirm bookings.
  !![image](https://github.com/user-attachments/assets/020ef45a-b6a8-4152-9d84-885d09788579)

- **Admin Panel**: Admins can manage car listings and view bookings.
 ![image](https://github.com/user-attachments/assets/e0f100b3-fdb3-43e4-be4d-b21c4a8317a4)

## 📜 License
This project is open-source and available under the **MIT License**.

## 💬 Contact
Feel free to open an issue or submit a pull request. You can also reach out for any questions or improvements.
