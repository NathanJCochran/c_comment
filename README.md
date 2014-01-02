ccmnt
-----

ccmnt is a simple command-line utility, written in Python, for inserting function-level comments into a C source code file. The tool finds all function declarations in the file, and, for each function, prompts the user for key details and a short description. The information is formatted appropriately and inserted into the source code file after the user reviews and commits the changes.

To install, download the script and place it in your PATH.

#### Requirements:

  + Python 2.7.3 (has not been tested with other versions)
  + ctags
