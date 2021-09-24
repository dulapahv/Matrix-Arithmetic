# Matrix-Arithmetic
An individual project for KMITL Software Engineering, Year 1, Semester 1

Created by **Dulapah Vibulsanti (64011388)**

# Project Description
This project aims to create a matrix computing program that runs in the terminal. The key features are:
 1. Wide varitety of operation
	 - Addition
	 - Subtraction
	 - Multiplication
	 - Determinant
	 - Transposition
	 - Inverse
	 - Adjoint
	 - Solving simultaneous equations (coming soon)

	*Program will also automatically detect matrix compatibility when performing certain operation.
	
2. Answer are automatically stored in 'Matrix Answer' so that it can be used to compute or perform further operation later on.

3. User can view each stored matrix value (max 7)

4. Answer are automatically output in the 'output.txt' with proper formatting (coming soon)

5. User has an option to clear selected/all matrix value (coming soon)

# Program Flow
    > What would you like to do
    [1] Define Matrix
        > Select a matrix to define
        [1] Matrix A
    
            Number of Rows: 2 
            Number of Columns: 2
            Enter value:
                1 2 3
                4 5 6
                7 8 9
    
            Matrix [selected matrix] successfully defined
    
            Press any key to continue...
    
        [2] Matrix B
        [3] Matrix C
        [4] Matrix D
        [5] Matrix E
        [6] Matrix F
        [7] Go back
    
    
    [2] View Matrix
        > Select a matrix to view
        [1] Matrix A
        [2] Matrix B
        [3] Matrix C
        [4] Matrix D
        [5] Matrix E
        [6] Matrix F
        [7] Matrix Answer
        [8] Go back
    
            (If selected matrix is not empty)
            Value:
            1.00    2.00    3.00
            4.00    5.00    6.00
            7.00    8.00    9.00
            
            Press any key to continue...
    
            (If selected matrix is empty)
            Value:
            [Empty]
            
            Press any key to continue...
    
    
    [3] Compute Matrix
    
            > What operation would you like to perform
            [1] Addition
                > Select matrixes to add
                [1] Matrix A
                [2] Matrix B
                [3] Matrix C
                [4] Matrix D
                [5] Matrix E
                [6] Matrix F
                [7] Matrix Answer
                [8] Go back
        
                Choice--> 1
        
                [1] Matrix A
                [2] Matrix B
                [3] Matrix C
                [4] Matrix D
                [5] Matrix E
                [6] Matrix F
                [7] Matrix Answer
                [8] Go back
        
                Choice--> 1
        
                    (If matrixes are compatible)
                    > The sum is
                    2.00    4.00    6.00
                    8.00    10.00   12.00
                    14.00   16.00   18.00
        
                    Press any key to continue...
        
                    (If matrixes are incompatible)
                    Incompatible matrixes!
        
                    Press any key to continue...
        
            [2] Subtraction
            [3] Multiplication
            [4] Determinant
            [5] Transposition
            [6] Inverse
            [7] Adjoint
            [8] Go back
        
        [4] Solve simultaneous equations (coming soon)
        
        [5] Exit
        
        Choice-->
