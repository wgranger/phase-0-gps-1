# phase-0-gps-1

git clone https://github.com/wgranger/phase-0-gps-1.git
Use this command to clone the local repository, from GitHub, to our local machine.

touch awesome_page.md
Created an empty file using the "touch" command. In this case, we created a Markdown file.

####
git push origin master
Danger!! Do not push before adding and committing your file!
####

git status
Never hurts to use git status to see exactly which files are still to be staged and committed.

git add awesome_page.md
This command staged our file from the local repo in order to commit it.

git commit -m "Add File to Repo"
This command committed, or took a snapshot, of our file and saved.

git push origin master
This command pushed the local file to our remote repo. We are prompted to enter a username and password at this time.

git checkout -b add-command-log
This command added a feature branch to our local repo through the terminal.

subl
Use this command to easily open Sublime through the terminal.