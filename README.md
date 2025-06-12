✈️ Flight Ticket Booking System using python
🔹 Project Overview
The Flight Ticket Booking System (FTBS) is a command-line based application developed using the Python programming language. It enables users to book flight tickets, manage passenger data, and handle reservations in an efficient and automated manner. The system provides core functionalities like booking, cancellation, rescheduling, and viewing records, making it ideal for small-scale travel agencies or educational projects.

🔹 Problem Definition
This project addresses the need for an automated reservation system for managing flight ticket bookings. It includes features to handle flight schedules, fares, passenger details, and ticket issuance. The system stores relevant passenger information like name, Aadhaar number, mobile number, and email ID. It also supports discounted fares for senior citizens, students, and armed forces. Additionally, it offers functionalities to cancel or reschedule a booking by updating the date and time of travel.

🔹 Key Functionalities
Book tickets and assign seats based on availability

Store and manage passenger details

Provide discounts for special categories (senior citizens, students, armed forces)

Allow cancellation or rescheduling of existing bookings

Generate and display e-tickets

Maintain and retrieve historical records of bookings

🔹 Rescheduling & Cancellation
For cancellation/rescheduling, the user must input their name, seat number, and number of seats.

In the case of rescheduling, the user also provides the new date and time, and an updated ticket is displayed.

💻 Hardware and Software Requirements
Hardware:

Processor: Intel i3 or higher

RAM: 4 GB or above

Storage: 64 GB or more

Software:

Operating System: Windows 7 or higher / macOS / Linux

Python Version: Python 3.6 or higher

Editor: VS Code / PyCharm / IDLE / Jupyter Notebook

Optional Libraries: datetime, pickle or json for file storage

🔁 Algorithm (System Flow)
Step 1: Start the program
Step 2: Display the main menu:

Reservation

Cancellation / Rescheduling

Booking Details

View All Records

Exit

Step 3: If Reservation is selected:

Input source, destination, travel date, seat class, number of passengers

Choose airline:

Air India

Indigo

Vistara

TruJet

Go Air

SpiceJet

Check seat availability

If available:

Input passenger details

Apply discounts (if applicable)

Display total amount and generate e-ticket

Step 4: If Cancellation / Rescheduling selected:

Reschedule

Cancel

Back to Main Menu

Step 5: If Reschedule:

Input passenger name, seat number, number of seats

Input new travel date and time

Display updated ticket

Step 6: If Cancel:

Input passenger name, seat number, number of seats

Confirm and display cancellation message

Step 7: If Booking Details:

Enter name

Retrieve and display stored ticket details

Step 8: If View Records:

Display all previous booking data (if stored using file handling)

Step 9: Exit the program

✅ Conclusion
The Flight Ticket Booking System developed in Python demonstrates practical usage of programming concepts such as conditional logic, loops, file handling, and data structures (like dictionaries and lists). This project offers an effective solution for managing flight bookings through a simple console interface and can be further expanded with a GUI or database integration in the future.

