
SAT Based Sudoku Solver in Python
====

A project to solve sudoku problem based on Boolean Satisfiability (SAT) solver.

The sudoku problems are generated from http://websudoku.com

Basially what the program do are:
1. Reduces Sudoku to a SAT clauses 
2. Solve the SAT clauses using python SAT Solver (https://pypi.python.org/pypi/pycosat)
3. Show the sudoku answer

Usage
====

```ruby
python sudoku.py --easy #easy level sudoku problem

python sudoku.py --medium #medium level sudoku problem

python sudoku.py --hard #hard level sudoku problem

python sudoku.py --evil #extra hard level sudoku problem
```