# python-control-structures-tasks
**Task 1**

a = int(input("Enter a number:"))
input("Enter a number:") – Prompts the user to type something into the console.

int(...) – Converts the user's input (which is a string) into an integer.

a = – Stores the integer value in a variable named a.

if a % 2 == 0:
This line checks whether the number is divisible by 2.

a % 2 calculates the remainder when a is divided by 2.

== 0 means "is the remainder zero?" If so, the number is even.

print(a, "is an even number.")
If the if condition is true, this line runs.

It prints that the number is even, using the value stored in a.

else:
This runs if the if condition is false—meaning the number is not divisible by 2.

print(a, "is an odd number")
If the number is not even, this line prints that it's odd.

**Task2**

i = 0
Initializes a variable i to store the running total.

Starts at 0 because we haven’t added any numbers yet.

for x in range(1, 51):
This line creates a loop that runs from 1 to 50 (inclusive).

range(1, 51) generates numbers starting from 1 up to 50 (Python excludes the last number).

x will take each value from 1 to 50, one at a time.

i = i + x
Adds the current number x to the running total i.

This is how the program calculates the sum of all numbers from 1 to 50.

print("The sum of numbers from 1 to 50 is:", i)
After the loop finishes, this prints the final total sum.

It will display:
The sum of numbers from 1 to 50 is: 1275



