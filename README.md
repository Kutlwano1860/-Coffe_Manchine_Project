Coffee Machine Project ☕
=========================
Overview
This Coffee Machine Project is a C# console application simulating the functionality of a real-world coffee machine. The program allows users to select different types of coffee, specify sugar and milk preferences, and process payments. The project showcases object-oriented programming (OOP) principles and is designed to be modular, reusable, and easily extensible.


Features
=========
Menu Options: Offers various coffee types like Espresso, Latte, and Cappuccino.
Customization: Allows users to adjust sugar and milk levels.
Payment Processing: Simulates payment using a simple validation mechanism.
Inventory Management: Tracks available resources (water, coffee, milk).
Error Handling: Provides feedback for invalid inputs or insufficient resources.


Prerequisites
=========
To run this project, you need:

.NET SDK: Version 6.0 or higher
IDE: Visual Studio, Rider, or any code editor with C# support
Operating System: Windows, macOS, or Linux


How to Run
==========
Clone the Repository:
git clone https://github.com/YourUsername/CoffeeMachineProject.git
Navigate to the Project Directory:
cd CoffeeMachineProject
Build the Project:
dotnet build
Run the Application:
dotnet run

Code Structure
==============

Program.cs: Entry point of the application.
Models/: Contains classes representing coffee types and resources.
Coffee.cs: Defines the coffee properties (e.g., name, price).
Inventory.cs: Manages resources like water and coffee beans.
Services/: Contains the core logic for the coffee machine.
OrderService.cs: Handles user input and coffee preparation.
PaymentService.cs: Processes payments.
Utils/: Utility functions for input validation and error handling.

How to Use
==========
Start the Program:
Run the application and follow the on-screen prompts.
Select Coffee:
Choose from the menu of coffee options.
Customize Your Drink:
Add sugar and milk according to your preference.
Process Payment:
Enter the amount, and the program will validate and dispense your coffee.

Example Interaction
====================

Welcome to the Coffee Machine!
1. Espresso
2. Latte
3. Cappuccino

Enter your choice: 2
Would you like to add sugar? (yes/no): yes
How much sugar? (1-3): 2
Would you like to add milk? (yes/no): yes

The total cost is R3. Enter payment amount: 3
Dispensing your Latte... Enjoy your coffee!

Future Enhancements
===================
Add support for more coffee types.
Implement a GUI for better user interaction.
Enable card payments simulation.
Add multilingual support.

Contributing
=============
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

License
======
This project is licensed under the GNU General Public License v3.0.

Contact
For questions or suggestions, feel free to reach out:

Email: lufunomanyikana315@gmail.com
GitHub:Lufuno Kutlwano Manyikana
Kutlwano1860
