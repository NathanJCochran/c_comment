ccmnt
=====

ccmnt is a simple command-line utility, written in Python, for inserting function-level comments into a C source code file. The tool finds all function declarations in a file, and, for each function, prompts the user for a short description, as well as brief explanations of the parameters and return value. This information is formatted appropriately and inserted into the file after the user reviews and commits the changes.

To install, simply download the script and place it in your PATH.

Requires:

  + Python 2.7.3 (has not been tested with other versions)
  + ctags
