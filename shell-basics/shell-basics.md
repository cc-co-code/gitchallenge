# Shell Basics

## COMMANDS

pwd # Print current directory path
ls # List directories
ls -a|--all # List directories including hidden
ls -l # List directories in long form
ls -l -h|--human-readable # List directories in long form with human readable sizes
ls -t # List directories by modification time, newest first
stat foo.txt # List size, created and modified timestamps for a file
stat foo # List size, created and modified timestamps for a directory
tree # List directory and file tree
tree -a # List directory and file tree including hidden
tree -d # List directory tree
cd foo # Go to foo sub-directory
cd # Go to home directory
cd ~ # Go to home directory
cd - # Go to last directory
pushd foo # Go to foo sub-directory and add previous directory to stack
popd # Go back to directory in stack saved by `pushd`
