# Learning About Version Control
Author: Benjamin Frizzell

Solving merge conflicts takes conscious effort, but I can do it!

I think version control is helpful for keeping track of my progress in my commit history.
Being able to reset to past commits has saved me on a few assignments when i've accidentally deleted important code.

Something annoying with version control happened to me during this assignment.
The merge conflict UI for VSCode was not appearing when I attempted to push my changes to the README file.
It took a long time for me to figure out why; 
apparently I needed to specify to git how to reconcile divergent branches with the command: `git config --global pull.rebase false`.
I have had to do this before but I didn't realize I needed to give the `--global` keyword to the command to make this the
default setting for all of my git repos, not just the current one.
