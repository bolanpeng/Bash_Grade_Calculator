#Usage
Before running this program, make sure that you are using Bash as your shell.

`stats {-rows|-cols} [input_file]`

You must choose either -rows or -cols:
* -rows calculates the average and median across the rows
* -cols calculates the average and median down the columns

[input_file] is optional. If you specify an input_file the data is read from that file; otherwise, it is read from standard input.

An input file named *test_file* is provided for testing purpose.

# Example
```
$ stats -rows test_file
 Average Median
 1       1
 5       5
 7       7
 5       6
 3       3
 6       6
```
