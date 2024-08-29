# OIBSIP-Project-1---Online-Reservation-System-using-java
Oasis Infobyte Internship - Task 1 :-
Project Title: Online Reservation System
Project Overview:
The Online Reservation System is a simple Java console application designed to manage seat reservations. It provides users with a straightforward interface to view the current seat map, reserve a seat, cancel a reservation, and exit the application. This project demonstrates fundamental programming concepts such as arrays, loops, conditionals, and user input handling in Java.

Features:
View Seat Map:

Displays the current status of all seats.
Reserved seats are marked with an "X".
Available seats are displayed with their corresponding seat numbers (1-10).
Reserve Seat:

Allows the user to reserve a seat by entering a seat number.
Validates the seat number to ensure it's within the allowed range (1-10).
Prevents double booking by checking if the seat is already reserved.
Cancel Reservation:

Allows the user to cancel a reservation by entering the seat number.
Validates the seat number to ensure it's within the allowed range (1-10).
Ensures that only reserved seats can be canceled.
Exit:

Provides an option to exit the application.
Functional Requirements:
Seat Management: The system manages a fixed number of 10 seats, with each seat having either a reserved or available status.
User Input: The system continuously prompts the user to select an option from the menu until the user chooses to exit.
Validation: The system includes input validation to ensure that the user can only select valid seat numbers (1-10) and options from the menu.
Technical Details:
Programming Language: Java
IDE: Any Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans)
Array Usage: A boolean array (seats[]) is used to represent the seat status, where true indicates a reserved seat and false indicates an available seat.
Control Flow: The program utilizes loops (while) and conditional statements (if-else, switch-case) to handle user interaction and seat management.
