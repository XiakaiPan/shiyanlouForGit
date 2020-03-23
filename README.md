Some useful operation command:
1.Initialize a local repo in a directory:
	git init
	Notes: It will print "Initialized empty Git repository in ...', '.git' directory can be found by 'ls -a' or 'la -al'
2.Add new changes to buffer/index: git add filename
3.Commit all changes to local repo: git commit (-a as add besides new files) -m '...(notes)'


4.Get the status of current branch: git status

5.Get the difference between workspace and buffer: git diff (all difference) or git diff --cached (current add's difference)

6.Remote link:
	Link local repo with remote repo: git remote add origin https://github.com/Username/Reponame.git
	Sync: git push origin master

