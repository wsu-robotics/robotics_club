robotics_club
=============

WSU Robotics Club Work



=====***Getting Started With Git***=====


***Terminology***

Repository (repo): A repo is a collection of files whose history is tracked using git (or other version control software)

Branch: A branch is a subcollection of a git repository. Think of it as a miniature repository inside a bigger one. Branches can be created, deleted, merged, further branched, and, like the whole repo, are tracked by git.

Commit: A commit is a discrete (small and unique) change to the files that is saved by the user. Git tracks repos
		by watching the commits made. Every commit made can be seen at any time (by using "git log") and
		mistakes can even be reversed by "reverting" to an earlier commit. All commits need to made with a short 		commit message that tells other (and yourself) what was modified, what was created, etc.

Push/Pull: When you make a commit to a repository the files are stored on your computer but they are NOT uploaded to
		github.com. To do this you need to "push" the files up (using "git push"). A pull is the opposite: it 			will download changes made to a repo by others to your computer.


***Useful Commands***

git clone [url] *This will clone the repo in to the directory that you are currently in.*
Example:
cd /home/yourname/programming_stuff/
git clone https://github.com/wsu_robotics/robotics_club.git  (make sure you put that .git at the end)
Folder Created: /home/yourname/programming_stuff/robotics_club/

git pull *Running this in a git directory will update the directory with any changes others have made to the repo*

git add [path] *This will add a file, multiple files, or a whole directory to the currently tracked files. This will 			allow you to commit these files when you are done modifying them.

git commit *This will commit (save and track) the changes made to files that have been added. To make this step quicker
	    use git commit -m "commit message goes here" 

git status *This will show you the files in the repo that have recently been created, deleted, or modified. It will also
	   tell you which are tracked and untracked. Use git add to track files.*

git push *This will push your locally made commits to the github.com repository (the "remote" repo).

git branch *Running this in a git directory will show you ONLY the local (on your computer) branches of the repository. 	    See git_branching.txt on how to create a new branch.*

git branch -a *Running this in a git directory will show you ALL of the branches of a repository*

git checkout [branch] *This will download the files from a branch and switch you to that branch. Don't be alarmed when 				it seems like your files are gone. They aren't. They are just on a different branch which you 				can easily switch back to.* 
