c_comment
=========

c_comment is a simple command-line utility for inserting function-level comments into a C source code file.
The tool finds all function declarations in the specified file, and, for each function, prompts the
user for a short description, as well as brief explanations of the parameters and return value.  This 
information is formatted appropriately and inserted into the file after the user reviews and commits the changes.

Requirements:
  Python 2.7.2
  ctags
