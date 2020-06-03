
## **Checkout**

The action of updating all or part of the working tree with a tree object or blob from the object database, 
and updating the index and HEAD if the whole working tree has been pointed at a new branch.

**Source:** [gitglossary](https://git-scm.com/docs/gitglossary)


Example:

Issue the command followed by the branch name:

git checkout [<branch>]

![checkout example](/images/checkout_example.PNG)



## **Push**

Pushing a branch means to get the branch’s head ref from a remote repository, 
find out if it is an ancestor to the branch’s local head ref, and in that case, putting all objects, 
which are reachable from the local head ref, and which are missing from the remote repository, 
into the remote object database, and updating the remote head ref. 
If the remote head is not an ancestor to the local head, the push fails.

**Source:** [gitglossary](https://git-scm.com/docs/gitglossary)


Example:

Issue the command followed by the branch name:

git push 

![push example](/images/push_example.PNG)

## **Pull**

Pulling a branch means to fetch it and merge it.

**Source:** [gitglossary](https://git-scm.com/docs/gitglossary)

Example: 

Issue the command:
![pull example](/images/pull_example.PNG)


# Defintions applicable to remotes

## **Add**


Adds a remote named "<name>" for the repository at <url>. 
The command git fetch <name> can then be used to create and update remote-tracking branches.

**Source:** [git reference](https://git-scm.com/docs/git-remote)

Example: 
Issue the command:

git add [file name] or git add "." [For all items]

![add example](/images/add_example_2.PNG)

![add example](/images/add_example_1.PNG)




## **Remove**

Remove the remote named [name]. 
Removes the named remote-tracking branches and configuration settings.

**Source:** [git reference](https://git-scm.com/docs/git-remote)


Example:
Issue the command:

git rm file.txt

![remove example](/images/remove_example.PNG)

This will remove the file named "file.txt".

## **Show**

Gives some information about the remote.

**Source:** [git reference](https://git-scm.com/docs/git-remote)

Example:
Issue the command:

git show [<options>] [<object>…​]

The default shows the log of "HEAD"

![show example](/images/show_example.PNG)


## **Status**

Displays paths that have differences between the index file and the current HEAD commit, 
paths that have differences between the working tree and the index file, 
and paths in the working tree that are not tracked by Git

**Source:** [git status](https://git-scm.com/docs/git-status)


Example:
Issue the command:

git status [<options>…​] [--] [<pathspec>…​]

![status example](/images/status_example.PNG)




## **Master**

The default development branch. 
Whenever you create a Git repository, a branch named "master" is created, and becomes the active branch. 
In most cases, this contains the local development, though that is purely by convention and is not required.

**Source:** [gitglossary](https://git-scm.com/docs/gitglossary)

Example:
Issue the command:

git checkout master

to move to the main branch.

![master example](/images/master_example.PNG)




[return to index](/README.md)

