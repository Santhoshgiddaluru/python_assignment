# python_assignment

What is Git?
Git is an open-source distributed version control system. It is designed to handle minor to major projects with high speed and efficiency. It is developed to co-ordinate the work among the developers. The version control allows us to track and work together with our team members at the same workspace.

What Is GitHub? 
GitHub is a for-profit company that offers a cloud-based Git repository hosting service. Essentially, it makes it a lot easier for individuals and teams to use Git for version control and collaboration. GitHub’s interface is user-friendly enough so even novice coders can take advantage of Git. Without GitHub, using Git generally requires a bit more technical savvy and use of the command line.

What Is Version Control?
 Version control helps developers track and manage changes to a software project’s code. As a software project grows, version control becomes essential. Take WordPress… At this point, WordPress is a pretty big project. If a core developer wanted to work on one specific part of the WordPress codebase, it wouldn’t be safe or efficient to have them directly edit the “official” source code. Instead, version control lets developers safely work through branching and merging.

Repository:
 A repository contains all of your project's files and each file's revision history. You can discuss and manage your project's work within the repository. When you create a repository, you can choose to make the repository public or private. Repositories in organizations that use GitHub Enterprise Cloud and are owned by an enterprise account can also be created with internal visibility.

How are softwares are using github? Git is used to tracking changes in the source code. The distributed version control tool is used for source code management. It allows multiple developers to work together. It supports non-linear development through its thousands of parallel branches.

DESCRIPTION OF CODES 

1:angle.mbc:

This is a Python code that calculates the length of the hypotenuse of a right triangle and the angle opposite to the shorter leg (MBC) based on the input provided by the user for the lengths of the sides AB and BC.

The math module in Python is used to perform the necessary calculations, specifically the sqrt function to calculate the square root, the atan function to calculate the arctangent of AB/BC, and the degrees function to convert the angle from radians to degrees.

The output of the code is the angle MBC in degrees. However, there is a mistake in the calculation of the hypotenuse length. The formula used should be AC = math.sqrt(AB**2 + BC**2) instead of AC = math.sqrt(AB*2 + BC*2).
2:electric bill:
This Python code calculates the electricity bill for a customer based on their current meter readings and previous readings. It calculates the total number of units consumed and uses an if-elif-else statement to determine the total bill amount based on the number of units consumed. The rates increase as the number of units consumed increases. The output is the total bill amount in rupees.

3.leap year
This Python code checks if a given year is a leap year or not. It uses a function called is_leap that takes the year as an argument and returns True if it is a leap year and False if it is not.

To determine if a year is a leap year, the code checks if it is divisible by 4 using the modulo operator (%). If it is, the variable leap is set to True. If the year is divisible by 100, leap is set to False. However, if the year is divisible by both 100 and 400, leap is set to True.

The output of the code is the Boolean value True or False depending on whether the input year is a leap year or not.

4.list comprehensions
This Python code generates a list of all possible (x, y, z) coordinates within a 3D space where each coordinate value is less than or equal to the user-specified values of x, y, and z.

The code uses a list comprehension to generate the coordinates. It iterates through all possible combinations of x, y, and z values using three nested for loops. For each combination, it checks if the sum of the values is not equal to a user-specified value n. If the sum is not equal to n, the coordinate is added to the list of coordinates.

The output is a list of all possible coordinates that satisfy the condition, where each coordinate is represented as a list containing the x, y, and z values.

5.matrix script
This Python code takes a matrix of strings as input and decodes it into a message by transposing the matrix, concatenating each row into a string, removing non-alphanumeric characters except spaces, and replacing consecutive non-alphanumeric characters with a single space.

The input() function takes two integers as input, n and m, which represent the number of rows and columns in the matrix, respectively. The matrix list is created by iterating through n and taking input for each row.

The zip() function is used to transpose the matrix, which means that the rows become columns and vice versa. This transposed matrix is then concatenated into a single string called decoded by iterating through each row of the transposed matrix and joining them together.

The re module is used to remove any non-alphanumeric characters from the string except for spaces. The re.sub() function is used twice to achieve this, with the first call removing all non-alphanumeric characters except spaces, and the second call replacing consecutive non-alphanumeric characters with a single space.

Finally, the decoded message is printed to the console.

6.maximise.it
This code prompts the user to input the number of lists to be entered, a value for mul, and multiple lists of integers. It then finds the maximum value of each list, squares each maximum value, adds up the squared maximum values, and takes the result modulo mul. The result is then printed as the maximized number.

In short, this code finds the maximized number based on the maximum values of multiple lists of integers entered by the user.
7.no idea
The program takes two input values n and m, followed by a list arr of integers, and two sets A and B containing integers. It then calculates the happiness score as the number of times an integer in arr appears in A minus the number of times an integer in arr appears in B, and prints the result.

8.pascal triangle
This code prints out Pascal's triangle with a specified number of rows. The user inputs the number of rows, and then the code iterates through each row, first printing out the appropriate number of spaces to center the row, and then iterating through each column in the row, calculating the value for that column using the formula for Pascal's triangle (n choose k), and then printing it out in a formatted string.

9.postal code
This program validates a user-input postal code using regular expressions. It defines two regular expressions for validating the format and for checking that there are no alternating repetitive digit pairs. The user is prompted to input a postal code, which is then validated using the regular expressions. If the postal code is valid, it prints "Valid postal code"; otherwise, it prints "Invalid postal code".

10.prime number
The program takes an integer as input and checks whether it is a prime number or not using a for loop. If the number is divisible by any number other than 1 and itself, the program counts it and determines that the number is not prime. Otherwise, the program determines that the number is prime. The output is printed to the console.















