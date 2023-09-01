# my_githubwork
my git hub work day to day activity data

VCS (Version Control System):
Version control is a system that records changes to a file or set of files over
time so that you can recall specific versions later. For the examples in this
book, you will use software source code as the files being version controlled,
though in reality you can do this with nearly any type of file on a computer.
It allows you to revert selected files back to a previous state, revert the
entire project back to a previous state, compare changes over time, see who
last modified something that might be causing a problem, who introduced an
issue and when, and more. Using a VCS also generally means that if you
screw things up or lose files, you can easily recover. In addition, you get all
this for very little overhead.

![image](https://github.com/Tejaswini3377/my_githubwork/assets/134936003/1a0abadf-da8d-4af5-9aab-af416e0ef689)

GIT:
Git is a Version Control System (VCS) and that to be Distributed VCS which was developed by Linus Torvalds, the same engineer who developed Linux Operating System. The situation which made him code Git is the actual definition of VCS. Linus Torvalds thought of a version control system for his operating system Linux because there did not match any available system to match his needs. This was much needed since Linux was open source and many developers wanted to contribute to Linux. A VCS would bring about a greater pace in the patch release and the development of this OS. All this made him develop GIT which is a version control system.

Difference between Git and GitHub:
Git: It is a Distributed Version Control System for tracking versions of files. 

Github: It is a web portal and cloud hosting service for your Git repositories.

![image](https://github.com/Tejaswini3377/my_githubwork/assets/134936003/f23420ab-6420-4538-bd0f-7242daca1cc2)

Working with GIT Commands:
Reference:
git scm site contains the full documentation about GIT and its commands
https://git-scm.com/docs


Below are the sequence of commits needs to use for initial commit:
echo "# flipkartrepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/KCTechApps/flipkartrepo.git
git push -u origin master

git remote -v


To check whether our local repo is connected to origin
git remote -v

To get back file from staging to local workspace
git reset <filename>

Setting your Git username for every repository on your computer

Setting user email:
git config --global user.name “MyName”
Set a Git username:
git config --global user.email “abc@xyz.com”


git config --list: To list all your configurations related to GIT



All the files in staging area will comes back to Local workspace

git reset 

git reset --hard  --> Command to hard reset.
This will override the modified (tacked) file changes with the git repo branch code changes (HEAD version) and also removes the untracked files (new files).

git reset HEAD --> Command to hard reset

This will override the modified tacked file changes with the git repo branch code changes. 
But will not do anything to untracked files (created in local but not committed to repo). Untracked files have to be removed by us only.

git clean -f 
Will remove all the new files from work space.

git ls-files -m 
Will give only modified files from working area.

git log
Will give all the commits with commit message, nothing but commit history


