# Requirements
#### a. Java 15 or higher required to run .jar file of this project
#### b. Intellij IDEA / Any Preferred IDE

# AirLineReservationSystem
A Java-based airline reservation system that uses Object-Oriented Programming. The system can manage customers, admins, flight booking and cancellation.
It also includes many other features implemented in Java using OOP concepts like inheritance, encapsulation, association, and composition.

# Features
The reservation system demonstrates the role of both the admin and the passenger. The admin sets up and manages the reservation system, while passengers use it to make reservations.
## 1. Customer Registration
In order to get started with the program, you need to register first. Make sure you remember your login information, as you will need it to sign in.
Registration screen can be seen in the image below:
## 2. Customer Login
You can access all the features of the program by logging in with your credentials. After successful login, you can avail all the features offered by the program.
### a. Book Flight
This module helps customers book a flight. Customers must enter the flight number and the number of tickets for the flight in order to make a reservation. An example is shown in the image below:
### b. Update Data
This section allows users to modify their bio-data. Data includes name, email, phone number, address and age.
If the user edits his data, logouts eventually and tries to log in with the old email, he won't be able to log in as his old email has been replaced.
### c. Delete Account
If a user decides to delete their account, they can do so and all the data related to the account will be deleted. However, any flights that were registered by the user before they deleted their account will still be in the records.
### d. Random Flight Schedule
This segment of the program shows the scheduled flights for this instance. The schedule may change as the program runs again. The number of flights in the schedule can be adjusted by adjusting the value of the **numOfFlights** variable in the **Flight class's flightScheduler()** method.
### e. Cancel Flight
Users can cancel a registered flight by specifying the number of tickets to cancel. These tickets will then be returned to the main flight scheduler.
### f. Flights Registered By Customer
This section displays info about the flights registered by the logged in customer and also shows the flight status. Flights status updates as a scheduled flight is cancelled/deleted by the admin.
## 3. Admin Registration & Login
The administration bears a heavy responsibility as they've to manage the entire system. An admin can perform **CRUD operations**, manage flights and customers. Following are the responsibilities of the admin for this reservation system.
### a. CRUD Operations

### b. Delete a Flight
### c. Display All Passengers
### d. Display All Flights Registered By a Passenger
### e. Display All Registered Passengers In a Flight
