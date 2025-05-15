# python-assessment-1
 function add(a, b)
    RETURN a + b
function subtract(a, b)
    RETURN a - b
function multiply(a, b)
    RETURN a * b
function divide(a, b)
    RETURN a / b 
operations = { "+": add, "-": subtract, "*": multiply, "/": divide }
PRINT "Enter the first number:"
SET first_number = USER_INPUT
PRINT "Enter the second number:"
SET second_number = USER_INPUT
PRINT "Enter the operation (+, -, *, /):"
SET operation = USER_INPUT
result = operations[operation](first_number, second_number)
PRINT "The result of", first_number, operation, second_number, "is", result
