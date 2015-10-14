# Dinamap
This is my first attempt to start managing the Dinamap(ProCare) Encounter form

I am planning up uploading the form first

I used the following commands to load files from my local folder

1 On your computer, move the file you'd like to upload to GitHub into the local directory that was created when you cloned the repository..
2	Open Terminal (for Mac and Linux users) or the command prompt (for Windows users).
3	Change the current working directory to your local repository.
4	Stage the file for the first commit to your repository. 
	$ git add .
	# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.

1	Commit the files that you've staged in your local repository. $ git commit -m "First commit"
	# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.

1	Push the changes in your local repository to GitHub. $ git push origin master
	# Pushes the changes in your local repository up to the remote repository you specified as the origin
