# pkexec2
is a <b>pkexec</b> wrapper and is designed to fix the slightly annoying feature of pkexec:
it changes directory to /root before executing the command.
Because of that, pkexec is not as easy to use as sudo
since, for example, you have to write the absolute paths of command parameter files and directories yourself.
<br>
<br>
Example: compare the output of the following commands:
<pre>
pkexec pwd
pkexec2 pwd
</pre>
Program <b>pkexec2</b> and its helper program <b>cmdindir</b> should be put to a directory in your $PATH.
<br>
<br>
DISCLAIMER: this program has <b>not</b> been extensively tested and may contain (serious) bugs. Use it at your own risk!

