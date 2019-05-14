# Assembly-Pocket-Calculator
This pocket calculator was built in a programming language called Mano that has been taught throughout the semester.
The calculator performs four basic arithmetic operations which are:
1. addition
2. subtraction
3. multiplication
4. division

The program greets the user with an intro, explaining for the user about how to use the calculator.

After that it asks the user to enter an operator and two integers. The user can only enter one of the above four operations and two integers, otherwise the user will receive an error message to the screen.

The calculator then executes the arithmetic operation and prints the desired number to the screen.

To finish using the calculator, the user must press "X" and "Enter" when it asks for op, then the program will print "Bye" and will stop.

Additional points:

•	The program checks if the input digits are in the right range (between 0-9 for decimal input and +-/* for op) if not the program will print an error. 

•	Over & under-flow: The program knows how to check extreme inputs so if the result is larger than 32767 and -32768 , the user will receive an error message on the screen accordingly.
