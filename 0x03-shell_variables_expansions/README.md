### 0-alias
Creates an alias named `ls` that runs `rm *`. When sourced, typing `ls` will delete all files in the current directory.
### 1-hello_you
Prints `hello <user>`, where `<user>` is the current Linux user, using the `$USER` environment variable.
### 2-path
Appends `/action` to the end of the `PATH` environment variable, making it the last directory the shell searches for executables.
### 3-paths
Counts the number of directories in the PATH environment variable by converting it to lines and counting them.
### 4-global_variables
Lists all environment (global) variables using the `printenv` command.
### 5-local_variables
Uses the `set` built-in to list all local variables, environment variables, and shell functions.
### 6-create_local_variable
Creates a local variable named `BEST` and assigns it the value `School`.
