Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
Use the ls -a to check whether there are hidden folders. If it shows a .git folder, then you are inside a git repository.
Assuming that you are currently within a Git repository, write the command (or commands) that will create a new file named 'hello-world.txt' then stage and commit it.
Type in touch hello-world.txt to create the file. Use git add hello-world.txt to stage the creation of the new file. Use git commit and type in your message in the text to commit, or use git commit -m ""then write your commit message inside the double quotation marks.
Assuming that you are currently within a Git repository that contains a file named 'README.md', write the command (or commands) that will display any uncommitted changes made to this file.
Use git status to display any changes made to a Git repository.
Assuming that you are currently within a Git repository that includes several commits, write the command (or commands) that will display the changes from the commit with the ID of abc123.
Use git show abc123 to display info and changes on the commit.
Assuming that you are currently within a Git repository that includes multiple commits, write the command (or commands) that will display the IDs and commit messages for the 3 most recent commits.
Use git log to show the most recent commits or git log --oneline to view a simplified summary of your commits.