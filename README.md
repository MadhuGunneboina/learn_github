Git Commands
============
### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |
| `git reset --hard origin/master` | If any error occurs while pushing code |

Learn Conda:
https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

Learn Django:
https://django-dynamic-preferences.readthedocs.io/

https://medium.com/@himanshuxd/how-to-create-registration-login-webapp-with-django-2-0-fd33dc7a6c67

### Sublime Shortcuts
# Sublime Text 3 - Useful Shortcuts (Windows)

## General

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> | command prompt |
| <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>P</kbd> | switch project |
| <kbd>Ctrl</kbd>+<kbd>P</kbd> | go to file |
| <kbd>Ctrl</kbd>+<kbd>G</kbd> | go to line |
| <kbd>Ctrl</kbd>+<kbd>R</kbd> | go to methods |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd> | go to methods in project |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>B</kbd> | toggle side bar |
| <kbd>Ctrl</kbd>+<kbd>`</kbd> | toggle console |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>N</kbd> | new window |

## Editing

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Ctrl</kbd>+<kbd>L</kbd> | select line (repeat select next lines) |
| <kbd>Ctrl</kbd>+<kbd>D</kbd> | select word (repeat select others occurrences in context for multiple editing) |
| <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Up</kbd> / <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Down</kbd> | select column for multiple editing |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>M</kbd> | select content into brackets |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Enter</kbd> | insert line before |
| <kbd>Ctrl</kbd>+<kbd>Enter</kbd> | inter line after |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>K</kbd> | delete line |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>K</kbd> | delete from cursor to end of line |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>Backspace</kbd> | delete from cursor to start of line |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>D</kbd> | duplicate line(s) |
| <kbd>Ctrl</kbd>+<kbd>J</kbd> | join lines |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>U</kbd> | upper case |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>L</kbd> | lower case |
| <kbd>Ctrl</kbd>+<kbd>/</kbd> | comment line |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>/</kbd> | block comment |
| <kbd>Ctrl</kbd>+<kbd>Y</kbd> | redo or repeat |
| <kbd>Ctrl</kbd>+<kbd>C</kbd> | copy |
| <kbd>Ctrl</kbd>+<kbd>V</kbd> | paste |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>V</kbd> | paste and ident |
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | autocomplete (repeat to select next suggestion) |
| <kbd>Ctrl</kbd>+<kbd>M</kbd> | jump to matching brackets |
| <kbd>Ctrl</kbd>+<kbd>U</kbd> | soft undo (movement undo) |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>U</kbd> | soft redo (movement redo) |

## Code navigation

| Shortcut | Description |
| ---------| ----------- |
| <kbd>F12</kbd> | go to definition |
| <kbd>Alt</kbd>+<kbd>-</kbd> | jump back |
| <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>-</kbd> | jump forward |

## XML / HTML

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>A</kbd> | select content into tag |
| <kbd>Alt</kbd>+<kbd>.</kbd> | close tag |

## Find / Replace

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Ctrl</kbd>+<kbd>F</kbd> | find |
| <kbd>Ctrl</kbd>+<kbd>I</kbd> | incremental find |
| <kbd>Ctrl</kbd>+<kbd>H</kbd> | replace |
| <kbd>F3</kbd> | find next occurrence of searched word |
| <kbd>Ctrl</kbd>+<kbd>F3</kbd> | find next occurrence of current word |
| <kbd>Alt</kbd>+<kbd>F3</kbd> | select all occurrences of current word for multiple editing |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>F</kbd> | find in files |

## Navigation

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Ctrl</kbd>+<kbd>0</kbd> | focus on sidebar |
| <kbd>Esc</kbd> | focus back to edit area when focus on sidebar |

## Splits / Tabs

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>1</kbd> | single column |
| <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>2</kbd> | two columns |
| <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>5</kbd> | grid (4 groups) |
| <kbd>Ctrl</kbd>+[1,2,3...] | focus group |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+[1,2,3...] | move file to group |
| <kbd>Alt</kbd>+[1,2,3...] | select tab |

## Bookmarks

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Ctrl</kbd>+<kbd>F2</kbd> | toggle bookmark |
| <kbd>F2</kbd> | next bookmark |
| <kbd>Shift</kbd>+<kbd>F2</kbd> | previous bookmark |
| <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>F2</kbd> | clear bookmarks |

## Marks

| Shortcut | Description |
| ---------| ----------- |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>Space</kbd> | set mark |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>W</kbd> | delete from cursor to mark |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>A</kbd> | select from cursor to mark |
| <kbd>Ctrl</kbd>+<kbd>K</kbd><kbd>G</kbd> | clear mark |

## More

Go to `Preferences` → `Key Bindings - Default` to explore all default shortcuts and read instructions for packages you installed to find out about their custom key bindings.
