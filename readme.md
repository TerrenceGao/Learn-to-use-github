# Git and Github learning notes (entry-level)

initial the git repository
`git init`

See current state of the project
`git status`

Add new file to staging area
`git add readme.txt`

To store the staged changes, run the **commit** command
`git commit -m "first commit"`

Or we can add all new files
`git add '*.txt'`

Store the changes
`git commit -m 'Add all txt files'`

`git log` is a journal that remembers the changes we've committed so far
`git log`

To push local repo to the GitHub sever (first time)
`git remote add origin https://github.com/try-git/try_git.git`

To push commits to origin repo
`git push -u origin master`

Pull down new changes from GitHub repository
`git pull origin master`

To see different from the last commit
`git diff HEAD`

Create a new branch a
`git branch a`

Switch to that branch
`git checkout a`

Merge the change(Need to switch to master branch first)
`git merge a`

Delete the branch a
`git branch -d a`
 

