
*Checkout*

The action of updating all or part of the working tree with a tree object or blob from the object database, 
and updating the index and HEAD if the whole working tree has been pointed at a new branch.

**Source:** [gitglossary](https://git-scm.com/docs/gitglossary)


[return to index](/README.md)

*Push*

Pushing a branch means to get the branch’s head ref from a remote repository, 
find out if it is an ancestor to the branch’s local head ref, and in that case, putting all objects, 
which are reachable from the local head ref, and which are missing from the remote repository, 
into the remote object database, and updating the remote head ref. 
If the remote head is not an ancestor to the local head, the push fails.

**Source:** [gitglossary](https://git-scm.com/docs/gitglossary)