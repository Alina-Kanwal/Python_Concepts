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
2) The base number system (or numeral system) is just a way of representing numbers using a set of digits and a base value. The base tells you how many digits there are before you "carry over" to the next place value. Base 10 (Decimal) – What we use every day. Digits: 0–9.
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
pYTHON does not save memory on same same location when
Spaces " ",
Special characters like "!", "@", "%" are used.
sys.intern() is used to save memory in same location if python does not save it on same location.
1) Python automatically interns some strings to save memory.
   But this auto-interning is mostly done for
   Short strings
   Strings that look like identifiers (only letters, numbers, and underscores)
   Strings used at compile-time
7) What happens if a Python function does not have a return statement   
It returns None.
//////////////////////////////////////////////////////////////////////////////////OPERATOR
9) the ** operator is right-associative. That means it evaluates from right to left.
10) Python automatically promotes the result to a float if one of the operands is a float. int(5.8) + float(3) output = 8.0
AND operator return true if both operands are true, OR operator returns true if at least one operand is True.
not True → False ,,, not False → True
11){ASCII Value (Decimal)} Capital letter A starts with 65, and Samall a starts with 97, 0 starts with 48,
12) ASCII Value (Hex) Capital letter A starts with 41, and Samall a starts with 61, 0 starts with 30,
13) {ASCII Value (Decimal)} Space ! is 33, @ 64, ~ is 126 ASCII Value (Hex) ! is 21, @ 40, ~ is 7E
14) The &= operator in Python is a bitwise AND assignment operator. It performs a bitwise AND between the two operands and assigns the result to the variable on the left-hand side.
15) It uses the // operator, which is called floor division. It divides and then rounds down to the nearest whole number (integer).
16) In Python, the / operator performs regular (true) division, even if both operands are integers. 7 / 2 = 3.5
//////////////////////////////////////////////////////////////////////////////////Python Strings and Methods - Quiz
1)A substring is simply a part of a string — a sequence of characters taken from a larger string. space is also a substring.
2) To convert a string into a list, we use the split() method.
3) The join() method joins elements of a list into a string.
////////////////////////////////////////////////////////////////////////////////Boolean, int, and float
1) All the values including negative numbers, are considered True. Except 0 '', [], {}, set(), etc.
2) 

   




