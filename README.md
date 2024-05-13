Task 1 (collatz function): First a function named collatz(number) is created then conditions are checked if the number is odd or even.
If the number is even, the number is equals to number//2.
If the number is odd, the number is equal to 3*number+1.
In main function we have taken the value of number from user and performed the remaining task.
A variable 'a' is assigned the value of the function and while loop is given so that the loop runs till function is not equals to 1.
The value of 'a' is changed everytime and if 'a' is 1 then the loop breaks.

Task 2 (Coin experiment): The module random is imported as we want to generate a random list. The loop is given to run this program 1000 times.
The values of variables is initialized as 0 and an empty list is created.
The user is asked for the input and the loop will run till the number of tosses. If randint() generated 0, the list will be appended with H other it will be appended with T.
Again loop will run for all elements in list and The values of the variables are incremented accordingly and if the totalH is 6, then it is counted as 1 streak of head.
similarly we will do for streak of tails and  at the end we will print the desired output.
