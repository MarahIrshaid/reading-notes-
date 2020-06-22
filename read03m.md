# By using git remote -v, you can view all the remote URLs next to their corresponding short names.
>$ cd example
> $ git remote -v
> remote1 https://github.com/remote1/example (fetch)
> remote1 https://github.com/remote1/example (push)
> remote2 https://github.com/remote2/example (fetch)
> remote2 https://github.com/remote2/example (push)
> remote3 https://github.com/remote3/example (fetch)
> remote3 https://github.com/remote3/example (push)



### To create a new remote Git repository with a short name, use the following format:

> git remote add shortname url

## Fetching :
what is fetching? its Fetching entails pulling data that you don’t have from a remote project.

code? git fetch [remote-name]
what is pushing? uploading a file upto gethub.
code? git push [remote-name][branch-name]
Example: $ git push origin master



## Renaming/Removing Remotes
#### rename:
use the "git remote rename" command
## The command git remote lists our existing remotes
#### Remove:
use the git remote rm command


Commit Mistakes
$ git commit --amend
Unstaging a File
$ git reset HEAD index.html

Unstaged changes after reset:

M index.html




## Branching : 
A branch in Git is simply a lightweight movable pointer to one of these commits.
The default branch name in Git is master . As you start making commits,
you're given a master branch that points to the last commit you made. Every time you commit,
the master branch pointer moves forward automatically


## Merging
Merging is Git's way of putting a forked history back together again. 
The git merge command lets you take the independent lines of development created by git branch 
and integrate them into a single branch.


## rebasing
Rebasing replays changes from one line of work onto another in the order they were introduced,
whereas merging takes the endpoints and merges them together


Command	function
Git status	get the Status of the files
Git add to	Track file
Git commit	to Commit changes
Git push	to Push changes to repo
