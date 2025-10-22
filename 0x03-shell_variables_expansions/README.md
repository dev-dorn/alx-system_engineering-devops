0-alias. It's a script that creates an alias.
1-hello_you. its is a script that greeys the user.
2-path Ensures that any executables placed in /action can be run from anywhere on the system without typing their full path, while keeping /action as the final lookup directory in the PATH.
3-paths Counts and displays the number of directories listed in the current PATH environment variable.
tr replaces colons (:) with newlines, and wc -l counts the resulting lines.
4-global_variables Displays a list of all environment variables and their values in the current shell session using the printenv command.
5-local-variables Lists all local variables, environment variables, and functions currently available in the shell.
The set command prints everything that’s been defined in the current session — not just exported variables.
6-create_local_variable Creates a new local variable called BEST with the value "School".
This variable exists only within the current shell session or subshell where it’s defined
7-create_global_variable This script creates a global environment variable named BEST with the value "School".
Global variables are available to the shell and all child processes