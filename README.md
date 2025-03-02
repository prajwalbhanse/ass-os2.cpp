# ass-os2.cpp
Prepare an Input File:
Create an input file (e.g., 90.txt) with the following format:

The first line contains three integers: K N taskInc
The following N lines each contain N integers representing the Sudoku puzzle.
Example:

8 90 20
<Sudoku grid data...>
Run the Program:
Execute the compiled binary:
./sudoku_validator

Review the Output:
After execution, check the output.txt file for the validation result and performance metrics.

Configuration
Mutex Algorithm Selection:
Change the spinlock algorithm by modifying the constant mutex_choice in the code:
const MutexAlgorithm mutex_choice = TAS; // Options: TAS, CAS, BoundedCAS
