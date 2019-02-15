# pkexec2
is a pkexec wrapper that tries to fix the slightly annoying feature of pkexec: it does not use absolute paths for files/directories
in the current/relative directory. Because of that, pkexec is not as easy to use as e.g. sudo
since you have to write the absolute paths yourself.<br>
Program pkexec2 also adds a new option <b>--verbose</b> that displays the converted command before executing it.<br><br>
DISCLAIMER: this program has not been extensively tested and may contain (serious) bugs. Use it at your own risk!

