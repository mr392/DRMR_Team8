
## **Checkout**

The act of moving between or creating working branches. If a branch is already created,
it allows to switch to that branch leaving the checked-in branch untouched. 
Usually this is the master branch. The -b parameter creates the branch at checkout. Saving a command.


**Source:** [GitHub glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)


Example:

Issue the command followed by the branch name:

git checkout [<branch>]

![checkout example](/images/checkout_example.PNG)



## **Push**

Push sends the changes to a remote repository. This is done after the changes are comittedted locally. 


**Source:** [GitHub glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)


Example:

Issue the command followed by the branch name:

git push 

![push example](/images/push_example.PNG)

## **Pull**

Git pull refers to pulling down changeds and merging them wiht your local copy of the repository. 

**Source:** [GitHub glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

Example: 

Issue the command:
![pull example](/images/pull_example.PNG)


# Defintions applicable to remotes

## **Add**

Used to manage a set of remote repositories. Can be used to list the URL's of of the remote repositories.  


**Source:** [git reference](https://git-scm.com/docs/git-remote)

Example: 
Issue the command:

git remote -v 

![Remote add example](/images/remote_add.png)






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

**Source:** [GitHub glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

Example:
Issue the command:

git checkout master

to move to the main branch.

![master example](/images/master_example.PNG)







## [return to index](/README.md)

