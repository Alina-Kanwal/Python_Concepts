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
Ali Jawwad Mcqs Concepts
1) Machine code is the lowest-level programming language, made up of binary digits (0s and 1s), that a computer’s CPU can directly understand and execute.
2) A base number system (also called a radix) is a way of representing numbers using a specific number of digits and a base. It tells you how many different digits are used and what each digit's place value means.
3) every code we write in python it change into bytecode before running. When you run a script, Python creates a .pyc file (compiled Python file) in the __pycache__ folder. This .pyc file contains the bytecode.But it's still not machine code — it's an intermediate step
4) memoryview is a Python object that allows you to directly view and manipulate binary data (such as bytes or bytearray) without copying it.
This improves memory efficiency, especially when you are working with large files or data buffers. Python kea save krrhaa hy memory may wo show krta hy
5) None is Python's way of representing "no value" or "nothing." It's similar to null in other programming languages.
Single instance: There is only one instance of None in Python, and it is of the NoneType data type.
Default return value: If a function does not explicitly return a value, it returns None by default.
Comparison: None is often used to signify that a variable is empty or hasn't been set yet.
6) String interning is a method in Python that helps save memory and makes programs faster.
When a string is interned, Python stores it only once in memory. So, instead of creating a new copy of the same string each time, Python reuses the same memory space for all copies of that string.
String interning works only for hardcoded, static strings—those that are directly written in the code. Python can't automatically intern strings created at runtime because their values are not known in advance.
1) Python automatically interns some strings to save memory.
   But this auto-interning is mostly done for
   Short strings
   Strings that look like identifiers (only letters, numbers, and underscores)
   Strings used at compile-time
7) What happens if a Python function does not have a return statement   
It returns None.

   




