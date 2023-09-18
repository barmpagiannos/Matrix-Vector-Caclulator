# Matrix-Vector-Caclulator
An app that can perform multiple mathematical operations on matrices and vectors. A project that i worked during my first semester at university.

Let's see how you can use the app.

The main concern of the program is to assist the user in operations between matrices and vectors.

The program allows the user to choose which operation they want to perform, both between matrices and between vectors.

Regarding matrices, the user must initially provide the dimensions of the two matrices. The dimensions should be given in the form dimension1xdimension2. The maximum dimension that the matrices can have is 5x5. If the user provides dimensions larger than this, a prompt message will appear notifying the user to enter correct dimensions. At this point, there is a while loop that creates an infinite loop until the user inputs the correct dimensions (or a runtime error occurs).

If the user enters the same dimensions for a matrix, the program will display on the screen, in addition to the given dimensions, the information that the matrix is square. Then, the user will be given an option to either fill the matrices themselves or have the computer fill them with random numbers. If the user chooses to fill them themselves, they must enter numbers in the range [0, 10] to avoid extremes. Similarly, pseudo-random numbers will also be in the same range. Afterward, the matrices filled by the user will be displayed on the screen.

As for the operations between matrices, we have:

Addition
Subtraction
Multiplication
Display of the transpose
Calculation of the trace
If the user does not wish to perform any operation between the matrices, they can type the number 0 and proceed. If they enter any other integer from those displayed on the screen, an error message will appear, and the user will need to re-enter the appropriate choice.

If the dimensions of the two matrices are different, addition and subtraction operations cannot be performed. Similarly, if the number of rows in the first matrix does not match the number of columns in the second matrix, multiplication is not possible. In general, the principles of linear algebra apply. Each time the user performs an operation, the corresponding result will be displayed on the screen.

Regarding vectors, the user must initially provide the dimensions of the two vectors. The dimensions should be in the range [1, 5] to avoid extremes. The further instructions are similar to those for matrices. We will list the operations between vectors:

Addition
Subtraction
Dot product
Magnitude of the first vector
Magnitude of the second vector
Angle between the vectors
Again, if the user does not wish to perform any operation, they can enter the number 0, and the program will terminate this time.

Note that all operations except 4 and 5 pertain to vectors of the same dimensions. If the vectors form a 90-degree angle, instead of displaying "angle of 90 degrees" to the user, the program will indicate that the vectors are "orthogonal." If all operations can be performed and the user chooses to calculate the angle between the vectors first, the program will display a message informing them that this operation cannot be calculated unless operations 3, 4, and 5 are performed first. Each time the user performs an operation, the corresponding result will be displayed on the screen.

2022 All Rights Reserved ©
