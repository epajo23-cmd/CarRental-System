Car Rental System

A desktop-based Car Rental System built using **Java** and **JavaFX**, following an MVC architecture. The system allows users to browse cars, make bookings, and manage rentals, while administrators and workers can manage the platform. This project was done by Eden Pajo(github.com/epajo23-cmd) and Thomas Kroj(github.com/tthomas2512) and uploaded to github after being finished.


Features

### User
- Sign up / Log in
- Browse available cars
- Book a car for a selected date range
- View booking history
- Manage personal account

### Admin / Worker
- Manage cars (add, edit, delete)
- View and manage bookings
- Handle users
- Generate invoices

## Technologies Used

- Java
- JavaFX
- Maven
- File-based storage (binary `.dat` files)


## Data Storage

The system uses local binary files to store data:
- `cars.dat`
- `users.dat`
- `bookings.dat`
- Generated invoices


## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/car-rental-system.git
2.Open the project in IntelliJ IDEA (or any Java IDE)
3.Make sure Maven dependencies are loaded
4.Run the application:Main.java


