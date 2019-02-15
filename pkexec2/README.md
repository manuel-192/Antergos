# pkexec2
is a <b>pkexec</b> wrapper that is designed to fix the slightly annoying feature of pkexec: it does not use absolute paths for files/directories
in the current/relative directory. Because of that, pkexec is not as easy to use as e.g. sudo
since you have to write the absolute paths yourself.
<br>
<br>
Example: the following commands:
<pre>
cd
touch testfile
pkexec cp testfile ..
</pre>
give the following error message:<br>
<pre>
/usr/bin/cp: cannot stat 'testfile': No such file or directory
</pre>
but using pkexec2 instead of pkexec handles it without issues.
<br>
Using option --verbose:
<pre>
pkexec2 --verbose cp testfile ..
</pre>
provides this output:
<pre>
/usr/bin/pkexec cp /home/user/testfile /home/user/..
</pre>
Program pkexec2 also adds a new option <b>--verbose</b> that displays the converted command before executing it.
<br>
<br>
DISCLAIMER: this program has <b>not</b> been extensively tested and may contain (serious) bugs. Use it at your own risk!

