## GitFlow

### Introduction

GitFlow is is a collaboration methodology using git where the aim is to isolate work in individual sandboxes so that other users work remains untouched during development. The GitFlow methodology was originally created by [Vincent Driessen](https://nvie.com/about/).

![Vincent](/images/vincent.png) 
> source: [https://nvie.com/about/nvie](https://nvie.com/about/)

### Working in Teams

The Gitflow method easily scales regardless of team size. Using git, git hub and other versioning tools team members have their own sandbox to work on the assigned feature. If they are called away to assist on another project they can just pick-up right where they left off. Although it woulld be beneficial to commit and push whatever changes were in progress. 

### Don't play with the Master

Driessen's method also relies on the idea of development and staging areas. While code is actively being worked on the development branch essentially becomes the master branch. Fetaures work is branched off of the developmet branch. 
Once the work is complete it is merged onto the development branch. 

![Feature Branches](/images/GitFlowFeatureBranches.png)   
> source: [https://nvie.com/posts/a-successful-git-branching-model/](https://nvie.com/posts/a-successful-git-branching-model/)

### Staging and testing

Once the code is finalized and ready for release it is moved onto a release branch. THe release branch is where testing is done.  This is where other tools suck as Docker can be utilized.  
## Note to self: add link to Docker from DR  
This testing envrionment either a seperate system or a virtualized one is where any bugs and fixes can be applied before the code is moved into a live production envrionment. 
Only bugfixes will commited on this branch.
  
Only when the release is done is the final code merged back onto the master branch and the development branch. 
This is to ensure that when the next round of development is to start all the code is on the development branch.  

### Uh oh we still have a problem
In the real world sometimes bugs make it through the testing phase. In this instance Gitflow allows for the creation of a hotfix branch. This the only other time code can be directly branched From or merged to the master branch. Once the hot fix is complete the hotfix will be simulteanously merged onto the development branch as well so that any future development will have all the fixes in place. 
The completed model is as follows: 

![Updated Model](/images/updated.png)   
> source: [https://nvie.com/posts/a-successful-git-branching-model/](https://nvie.com/posts/a-successful-git-branching-model/)

=====================================
## [Return to index](/README.md)
## [Definitions](/definitions.md)
## [Overview](/Section_1_overview.md)
