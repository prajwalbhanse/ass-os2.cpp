# ass-os2.cpp
Create an input file (e.g., input.txt or 90.txt) with the following format:

The first line contains three integers: K N taskInc
The following N lines each contain N integers representing the Sudoku puzzle.

8 90 20
[<Sudoku grid data...>](<Sudoku grid data...>)

Run the Program:
Execute the compiled binary:
./sudoku_validator

Review the Output:
Check the generated output.txt file for the validation result and performance metrics.

Mutex Algorithm Selection:
Change the spinlock algorithm by modifying the constant mutex_choice in the source code (main.cpp):
const MutexAlgorithm mutex_choice = TAS; // Options: TAS, CAS, BoundedCAS

