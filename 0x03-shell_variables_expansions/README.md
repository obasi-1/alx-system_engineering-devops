# 0x03. Shell, init files, variables and expansions

# Task 0: Create an alias

This project contains a script named 0-alias that creates a shell alias in the current terminal session.

# Description of the script

The script sets up an alias that maps the command ls to rm *.

Alias Name: ls

Alias Value: rm *

# How to Use

To apply the alias, you must source the script in your terminal:

source ./0-alias

Once sourced, typing ls and pressing Enter will execute rm *, which deletes all files in the current directory.

:warning: WARNING :warning:

This alias is destructive and will permanently delete files. It is intended for a specific learning exercise and should be used with extreme caution. To run the original ls command while the alias is active, you can bypass the alias by using a backslash:

\ls
