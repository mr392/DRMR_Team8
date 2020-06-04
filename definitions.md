
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

Used to add the origin of a git repository after specifying the URL 

**Source:** [git reference](https://git-scm.com/docs/git-remote)

Example: 
Issue the command:

git remote add origin "https://github.com/user/repo.git" 

![Remote add example](/images/remote_add.PNG)

## **Remove**

Removes the named remote-tracking branches and configuration settings. In the case of services like GitHub it does not delete the repository.
Just the local link pointing to it.

**Source:** [git reference](https://help.github.com/en/github/using-git/adding-a-remote)


Example:
Issue the command:

git remote remove origin  

![remove example](/images/remove_example.PNG)

This will remove the file named "file.txt".

## **Show**

Gives various information about the commit tree.

**Source:** [git reference](https://git-scm.com/docs/git-remote)

Example:
Issue the command:

git show 

The default shows the log of "HEAD"

![show example](/images/show_example.PNG)


## **Status**

Displays differences between the index file and the current HEAD commit. 


**Source:** [git status](https://git-scm.com/docs/git-status)


Example:
Issue the command:

git status  

![status example](/images/status_example.PNG)

 


## **Master**

The default development branch. 
Whenever you create a Git repository, a branch named "master" is created, and becomes the active branch. 
In most cases, this contains the local development branch.

**Source:** [GitHub glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

Example:
Issue the command:

git checkout master

to move to the main branch.

![master example](/images/master_example.PNG)







## [return to index](/README.md)

