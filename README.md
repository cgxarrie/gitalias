# gitalias
A bunch of useful git aliases to add to .gitignore to boost productivity

In all commands below branchname is part of the name of a branch that is no repeated in any other branch name.
i.e. Given the following branch structure, see the branhcnames to use

| to use this branch    | use this branch name  |
|-----------------------|-----------------------|
| master                | master                |
| develop               | develop               |
| feat/0010-feature1    | 0010                  |
| feat/0020-feature2    | 0020-                 |
| feat/0020/0022-task22 | 0022                  |

### amd
- Add currently staged files to previous local commit without changing the commit message

### ca "commit message"
- commits all staged and unstaged changes with message "commit message"

### sw branchname
- creates a local branch for each remote branch that matches the branchname criteria

### name branchname
 - display the name of the branch that matches branchname criteria

 ### chs branchname
 - Checnkout local branch
 - show status
 
 ### chp branchname
 - Checnkout local branch
 - pull

### sqash branchname
 - Squashes the local branch based on branchname
 - creates a commit with the local branchname as comment.

### chkup branchname  (full branch name)
 - Creates local branch
 - sets upstream to origin branch with same name

### up
 - sets upstream to origin branch with same name for current local branch
 - push current local branch

### rbs branchname
 - rebase current local branch on branchname

### mrg branchname
 - pull branchname
 - merge branchname into current local branch
