bash_prompt
===========

This is a nice bash prompt that displays the time, username, host,
current working directory, and current git branch using a color
indicating the git status:

* green: clean
* red: local changes
* yellow: local repo ahead of remote

The script should be pretty self explanatory so feel free to customize it.

## How To Use
You can clone this repository to your local computer and then add the following 
lines to your .bash_profile or .bashrc file:

    # Source the bash_prompt script to set a nice bash prompt
    . <path_to_bash_prompt_repo>/bash_prompt