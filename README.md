# odin-calculator

-add event listener for each button
-a method should assign each button press and its id to the relevant variable and/or begin its function

operandNumberOrFunc(id):
    switch(id):
        case if its a number:
            concatenate the number to the global number variable

        case if operand:
            -possible states
            if there is no number assigned to global number variable, do nothing
            if there are two operands and an existing operator (haven't pressed enter):
                evaluate the current expression
            if there is one operand and no existing operator (operator after typing first number):
                assign the operator to the global operator variable
            if there is one operand and an existing operator (back to back operators):
                swap/assign the new operator to the global operator variable
            
        