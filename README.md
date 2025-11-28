# cineplus
DESCRIPTION
Our project is *Cine Plus*, created using the Python programming language. The purpose of Cine Plus is to provide four screens that guide the user through the system. The windows included are: **Login**, **Ticket Booth**, **Concessions**, and **Final Screen/Ticket**.

The login window is where the user enters their previously registered information. Once the correct data is entered (and if the user presses the exit button, the window closes automatically), the Ticket Booth window opens.
The Ticket Booth window allows the user to view the available movies, showtimes, and the ticket prices for adults and minors. After choosing everything, the user presses the “Next” button, which opens the Concessions window. There is also a “Clear” button, which automatically resets everything the user selected so they can choose again.
In the Concessions window, the user selects what they want to order, such as popcorn, drinks, candy, and more. They can also see the price of each item. Once the user finishes selecting their items, they press the next button again, which opens the Ticket window (and if they press the cancel button, the window closes automatically).
In this final window, the system displays the ticket cost for the movie the user chose. Once the user pays, they can enjoy the movie along with their concessions.

SCREENS
Login Window
The login window is responsible for controlling access to the system. In this window, the user must enter their username and password, and the system verifies that both pieces of information match the data registered beforehand. When the information is correct, the window grants access and shows a confirmation message; if it is incorrect, it notifies the user so they can try again.
Additionally, this window manages the entire entry process. After validating the user’s information, it automatically redirects the user to the Ticket Booth window, where they can manage movie showings, tickets, and all operational functions of the system. It also includes a button to exit or cancel if the user does not wish to continue.

Ticket Booth Window
The Ticket Booth window manages the entire process of selecting and purchasing tickets within the system. Here, the user can choose a movie from a dropdown menu, and once selected, the system automatically displays the corresponding theater room.
The user can also select a showtime using radio buttons, ensuring they choose the exact hour they want to attend. Additionally, the window contains a section that displays promotional images of the movie to help identify it more easily.
This window also manages the number of tickets to purchase, dividing them into adult tickets and minor tickets, each with its own price. As the user enters the quantities, the system automatically calculates the subtotal.
Finally, the Ticket Booth window includes a button to clear all data if the user wants to restart the process, and a “Next” button to proceed when the information is complete.

Concessions Window
This window allows the user to add additional products to their purchase. It displays different combos with their prices, as well as popcorn in various sizes and soft drinks with different flavors and sizes. Each product has a control to set the quantity, and once added, it appears in the “Added Products” list.
While the user selects items, the system automatically calculates the concession subtotal. There is also a button to clear all data and another to continue to the next step.

Ticket Window
The Ticket window clearly displays all the information the user selected in the previous windows. It shows the data from the Ticket Booth window, such as the chosen movie, assigned theater, showtime, and the quantity of adult and minor tickets, along with their subtotal.
It also shows the products selected in the Concessions window, listing the added items and their subtotal. At the end, the window calculates and displays the total amount to pay, combining both the ticket and concession costs.
TECHNOLOGIES USED
The technologies used for this project were Python, Visual Studio Code, and wxGlade, as well as Google Chrome to download the images used in the project.

TEAM MEMBERS
Lesra Alexander Piñeiro Bahena – Product Owner (PO)
Angelica Palma Baltazar – Scrum Master (SM)
Alejandro Olaf Onofre Hernandez - Tester
Angel Manuel León Perez - Designer
Ashly reyes nava - Designer
Ivan Alejandro Sanchez Delgado - Programmer

INSTRUCTIONS TO RUN THE PROJECT
For the correct functioning and execution of the project, it is necessary to download the folder that contains the code and image files.
After that, open Visual Studio Code. Once it is open, locate the “File” menu in the upper-left corner. Click on it, and a list of options will appear. Select **“Open Folder”**, which will open a file explorer window. Then select the project folder and open it.
After the project folder loads, several files will appear in Visual Studio Code. You must open the file named **cineplus.py**. Once opened, you can run the program by clicking the triangular **“play”** icon at the top. Another way to run it is by pressing **Ctrl + F5** on your keyboard.
