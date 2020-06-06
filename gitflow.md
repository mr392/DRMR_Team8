## GitFlow

### Introduction

GitFlow is is a collaboration methodology using git where the aim is to isolate work in individual sandboxes so that other users work remains untouched during development. The GitFlow methodology was originally created by [Vincent Driessen](https://nvie.com/about/).

![Vincent](/images/vincent.png) 
> source: [nvie](https://nvie.com/about/)

### Working in Teams

The Gitflow method easily scales regardless of team size. Using git, git hub and other versioning tools team members have their own sandbox to work on the assigned feature. If they are called away to assist on another project they can just pick-up right where they left off. Although it woulld be beneficial to commit and push whatever changes were in progress. 

### Don't play with the Master

Driessen's method also relies on the idea of development and staging areas. While code is actively being worked on the development branch essentially becomes the master brancg. Fetaures work is branched off of the developmet branch. 
Once the work is complete it is merged onto the development branch. 

![Feature Branches](/images/GitFlowFeatureBranches.png)   
> source: [Branches](https://nvie.com/posts/a-successful-git-branching-model/)

### Staging and testing

Once the code is finalized and ready for release it is moved onto a release branch and whichen then put into a testing environment. This is where other tools suck as Docker can be utilized. # Note to self: add link to Docker from DR  

