
A mini python project on parking lot system, where a parking lot can be created of definite size and different types of operations like, parking, leaving the parking lot, checking status, getting the slot number from registration number, getting the registration numbers of particular colour of car, getting the slot numbers of particular colour of cars, can be executed. 

This project is based upon basic implementation of python language. It contains different types of operations. This system can fulfil all the requirements of basic parking lot system. This program has following features:
•	Create a parking lot of required capacity
•	Park a car 
•	Leave parking lot
•	Check the status of parking lot
•	Get the nearest available slot
•	Get registration numbers of all cars of same colour
•	Get the slot numbers of all cars of same colour
•	Get the slot number of car by registration number

Inputs to run the program is of three different mode-
•	User driven inputs – user interactive approach, where user will type commands manually 
•	Text file based inputs – program will automatically run all the commands at once by taking the inputs from file.
•	Menu based inputs - user interactive approach where he /she will choose options from inbuilt menu to run the commands


Technologies used:
•	Python 3.8
•	Object-oriented programming
•	User defined modules

Requirements:
User needs to install python in their system. User can get the latest version of python from the URL https://www.python.org/downloads/

Set up:
•	Clone the repository
•	Go to root directory where this app.py file is present.
•	Run it in your command prompt or VS code or IDLE and type- python app.py
•	To run this program as user interactive 
i)	Press 1 to run this program by the predefined file inputs
ii)	Press 2 to run this program by menu driven inputs
iii)	Press 3 to run this command manually
•	To pass input run this app.py file by running the command
python app.py

How to run the project
To run the project, navigate into the folder which contains source code files, by your command prompt and execute the command
		python app.py
After running the above command the output screen will show you 3 options to choose any of them. One is for text file inputs, second is menu driven input and third one is user driven inputs.

Let’s choose each option and see the results:
If user have chosen option 1. The code will run for text file inputs. User nothing has to do. It will take input from file automatically and will show you the output for each operation.

Now, If user have chosen the choice 2.The code will get executed according to the menu driven. In this menu for different operations, user doesn’t have to type whole command, he or she will just choose the numeric option for each operation.

And at last, if user have chosen the option 3, then user has to enter all commands manually.
Commands for different operations are:

To create a parking lot of size n command is 
create_parking_lot [size]
To park a car 
		park [registration_number] [colour_of_the_car]
To leave slot 
leave [slot_number]
To get the status of parking lot
		status
To get registration numbers of cars, of same colour:
		registration_numbers_for_cars_with_colour [colour_name]
To get the slot numbers of parked cars, of having same colour:
		slot_numbers_for_cars_with_colour [colour_name]
To get the slot number of parked car by it’s registration number:
		slot_number_for_registration_number [registration_num]
Output of this method can be seen like below clips:
 

By these modes of input, user can know the efficiency of this project. The project can be used in different parking lot system to make the arrangement of parking convenient. For example- Hospitals, Banks, etc.



