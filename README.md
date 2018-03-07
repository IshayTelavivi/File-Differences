# File Differences Project
File Differences is the final project of [Python Data Representations](https://www.coursera.org/learn/python-representation) course by Rice University in coursera. The course is part of [Introduction to Scripting in Python](https://www.coursera.org/specializations/introduction-scripting-in-python) specialization.
The project focused on writing code that finds the location of the first character that differs between two input files.
The program includes 5 fumnction with the following functionality:

* singleline_diff(line1, line2) - The function takes two single line strings and returns the index of the first character that differs between the two lines, or an indication in case that the lines are identical.
* singleline_diff_format(line1, line2, idx) - The function creates a format for presenting the location of the first difference.
* multiline_diff(lines1, lines2) - The function takes two lists of single line strings, and returns a tuple that indicates the line and index within that line where the first difference between the two lists occurs.
* get_file_lines(filename) - The function takes a filename as input and returns a list of single lines as strings.
* file_diff_format(filename1, filename2) - The function takes two filenames as input and returns a formatted string with the location of the first difference between the files.

The code is in the file 'File Differences Project.ipynb'. 
The main files are test files, so one may test the program with them. The files that can be tested against each other are:
* 'Example.txt' and 'Example_b.txt'
* 'file1.txt', 'file2.txt' and 'file3.txt'
* 'file4.txt' and 'file5.txt'
* 'file6.txt' and 'file7.txt'
