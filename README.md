# BUS Ticket Booking System

This project was developed as part of my 1st year, 2nd semester Software Engineering I course at university. The system is implemented in C and provides a simple command-line interface for booking, canceling, and managing bus tickets.

## Project Overview

The BUS Ticket Booking System allows users to:

- View bus details
- Reserve seats on a bus
- Cancel reservations
- Change ticket prices (admin only)

The system uses basic C structures and file operations to manage bookings and bus information.

## Features

- Seat reservation and cancellation
- Admin password-protected ticket price change
- Simple menu-driven interface
- Stores passenger details (name, phone, seat, ID)

## How It Works

Below is a simple diagram showing the main flow of the system:

```
+-------------------+
|   Main Menu       |
+-------------------+
        |
        v
+-------------------+
| 1. Change Price   |<-- Admin only
| 2. View Details   |
| 3. Reserve Ticket |
| 4. Cancel Ticket  |
| 5. Exit           |
+-------------------+
```

## File Structure

- `main.c` - Main program logic and menu
- `busdetails.c` - Structure for passenger details
- `decleration.c` - Function declarations

## How to Run

1. Compile the program:
   ```sh
   gcc main.c -o bus_ticket_booking
   ```
2. Run the executable:
   ```sh
   ./bus_ticket_booking
   ```

## License

This project is licensed under the MIT License.

---

_Developed for academic purposes as a university course project._
