# Python_Concepts
Mode	Behavior if file exists
"w"	Overwrites the file
"a"	Appends to the file
"r"	Opens for reading; error if file doesn’t exist
"x"	❌ Error if file does exist ✔️
The "r+" mode in file handling is used for reading and writing to an existing file.
The "b" mode in file handling stands for binary mode, It tells Python to read or write the file as binary data instead of text. We use it when Any file that’s not plain text like images, Videos.
To read all lines from a file into a list in Python, you can use the readlines() method.
What will happen if you forget to close a file after performing file operations?
1) Data may not be saved properly (especially in write mode)
2) File remains locked or in use:
3) Memory/resource leak:
4) File descriptor limit: Systems have a limit on how many files can be open at once.
  To copy content from one file to another in Python, you can read from the source file and write to the destination file. 
The correct way to open a file in exclusive creation mode is by using the mode: X


