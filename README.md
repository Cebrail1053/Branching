## Git CheatSheet

breif reference of various git commands. Also practice with branching

* `git init` - intialize the git repository


### Work on the New Branch
`git branch` - list new branches
`git checkout newBranch` - merge with main branch?
* _git status_ - show state of local repository
* git log - List commit history
* `git log --oneline` - breif commit history
* `git add . ` - git add all files to be committed
* `git commit -m "msg"` - commit to remote repo with msg

* `git config -l` - list git configuration files

### Remote Repos
* `git remote add alias url` - add `alias` as name for remote repo `url` in
project configuration
* `git push alias aBranch` - push local commmits to `alias`'s  branch `aBranch`
* `git pull alias aBranch` - pull local commmits to `alias`'s  branch `aBranch`
