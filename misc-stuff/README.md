# Misc stuff

## cp.completion
A bash completion file for the 'cp' command.<br>
Handles more options and their values than the 'official' cp completion.<br>
Copy this file into <b>/usr/share/bash-completion/completions/cp</b>.<br><br>
Note: in file <b>/usr/share/bash-completion/bash_completion</b> the list of commands using the \_longopt function includes
the 'cp' command. Search for the line beginning with:<pre>
complete -F \_longopt
</pre>
The 'cp' word should be removed from the list in order to use this new cp completion.
