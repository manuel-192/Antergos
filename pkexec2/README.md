# pkexec2
is a pkexec wrapper.<br>
Tries to fix the slightly annoying feature of pkexec: it does not use absolute paths for files/directories
in the current/relative directory. Because of that, pkexec is not as easy to use as e.g. sudo
since you have to write the absolute paths yourself.<br>
Program pkexec2 also adds a new option --verbose that displays the converted command before executing it.
