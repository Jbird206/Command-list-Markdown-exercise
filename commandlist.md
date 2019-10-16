# These are the list of commands for Git #
_Commands_
* mkdir- Makes a directory
* touch- creates a file
* ls- list files in the directory
* ls-a- lists hidden files
* mv- move file or directory. "_epicodus-5:intro-to-programming Guest$ mv my-first-webpage.html first-webpage/my-first-webpage.html_"
* rm- remove "rm file-name.txt"
* rm -r removes entire directory and files there in
* cd- navigate to
* cd ~- navigate back to home


## How to initialize a pairs file and project ##
* create a .pairs file
* open the file with Atom, and put in the following lines

_pairs:
 * jm: jason mcgrady
 * SE: samantha egelhoff
email:
 * jm: jbird206.gmail
 * se: samantha.egelhoff@gmail.com_

## Initializing a new Git project ##
* navigate to the directory of the files
*  git init
* ls -a
* git pair jm se
* git add- _git add filename.html for example_
* git status- checks the current status of the git project
* git-pair-commit -m- commits a change to the .pairs project. _"git-pair-commit -m "add initial HTML file with 5 languages saying hello"_
* git remote add- adds remote repository _"git remote add jm https://github.com/epicodus-lessons/hello-world"_
* git remote -v- verifies the remote repo and files were initialized
* git push "initials" master- _"git push jm master"_
