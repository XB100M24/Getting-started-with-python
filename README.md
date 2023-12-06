# Getting-started-with-python
# install python from https://www.pythn.org/downloads
# select your code editor
# in this repository, we are gonna make a calculator that displays on the console
# this will take in user input and do some basic calculations then provide the user with processed output.
print("Enter 1 for ADDITION")
print("Enter 2 for SUBTRACTION")
print("Enter 3 for DIVITION")
print("Enter 4 for MULTIPLICATION")
print("Enter the first number, second number and operator as bellow")
# prompting the user to input the first number, second number and operator into the program
# the int() function is used to convert the sting into integer
first_number = int(Input("Enter the first number: ")
second_number = int(Input("Enter the second number: ") 
operator = Input("Enter Operator: ")
# the if statements to do the arithmetic
if operator == "1":
  answer = first_number + second_number
  print(answer)

elif operator == "2":
  answer = first_number - second_number
  print(answer)

elif operator == "3":
  answer = first_number / second_number
  print(answer)

elif operator == "1":
  answer = first_number * second_number
  print(answer)
# giving the error value if a wrong operator is entered!
else:
  print("Error!" + "Unknown operator")

# thank you for reading this, you can copy the code or you can apply the knowledge to fit your preference.


