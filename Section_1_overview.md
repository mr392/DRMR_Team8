## Git

Git is a version control system (VCS) - a category of software tools that helps software developers manage changes to source codes over time. Git is free, open source, and is the most widely used version control system in the world.

Git, like other version control systems, creates a record of every modification made to the codes in a development project database. However, Git is an example of a specific type of VCS known as a distributed version control system - rather than storing a project's revision history in one single place, a DVCS makes every developer's copy of the code a repository that is able to access the whole project's complete history of revisions. This enables multiple developers distributed across different locations to monitor and coordinate their individual changes to code, and facilitates collaboration between people without disrupting the consistency of the project workflow.

Distributed version control systems such as Git have multiple advantages over alternatives:
- Enabling fast branching and merging
- The ability for developers to work offline
- Eliminating the reliance on a single project backup

![Chart image](/images/git_dvcs.png)
> **Source:** [Edureka](https://www.edureka.co/blog/what-is-git/)

While there are several platforms for distributed version control, Git stands apart from the rest because of its unique branching model: Git enables developers to create multiple branches of code that can be entirely independent from each other. The creation, merging and deletion of those branches can also be done extremely quickly.

Compared to other systems, Git makes development faster, more reliable, and less prone to errors. The use of Git allows for the highly efficient construction of software applications by small teams as well as large ones, and the employment of development teams with a mastery of Git can give any company the edge over its competition.

![Chart image](/images/git_branching.png)
> **Source:** [Backlog](https://www.edureka.co/blog/what-is-git/)





**References:**

[Opensource](https://opensource.com/resources/what-is-git)

[Atlassian](https://www.atlassian.com/git/tutorials/what-is-version-control)

[Perforce](https://www.perforce.com/blog/vcs/what-dvcs-anyway)

[Dakota Chambers](https://chambers.io/2018/04/17/git-vs-the-competition.html)

[Git](https://git-scm.com/about)




## Docker

Docker is a platform that is used to package an application and all of its dependencies together in the form of "containers" - standardized units of software - in order to make sure that the application works seamlessly in any development, testing or production environment.

The practice of creating containers is a type of virtualization. Traditional virtualization brings abstraction to the hardware and is the technique of importing a guest operating system on top of a host operation system - for example, creating a virtual machine to run Windows on an Apple computer.

Containerization, on the other hand, brings abstraction to the operating system level - a container uses the host operating system without creating a guest OS, and shares relevant libraries and resources as needed. Application specific binaries and libraries all run on the host kernel, making processing and execution run very efficiently. However, each container is also isolated from the other containers, and are able to host applications without interfering with each other.

Some of the advantages of using containers over virtual machines are:
- Faster boot-up
- Containers are lighter and smaller
- Better resource utilization compared to virtual machines

Through the use of containerization, Docker lets developers create unique digital environments to explore the capabilities of their software. Many developers utilize Git and Docker in tandem with each other, relying on Git to construct their codes and then deploying their repositories into Docker containers in order to check how they operate. Without programs such as Docker, some companies may struggle to quickly roll out updates in code that work correctly across all software and operating systems, web browsers, devices, etc. - but those who are able to leverage containerization tools to their advantage have an easier time applying their code to to different platforms.

![Chart image](/images/git_docker.png)
> **Source:** [Docker](https://www.docker.com/resources/what-container)





**References:**

[Stackshare](https://stackshare.io/stackups/docker-vs-github)

[Codefresh](https://codefresh.io/docker-tutorial/implementing-git-flow-with-dockers/)

[Edureka](https://www.edureka.co/blog/docker-tutorial)

[Geeks for Geeks](https://www.geeksforgeeks.org/containerization-using-docker/)




## Automated Testing

Automated Testing is the process of allowing software to detect and make changes to code without having to rely on the lengthy task of manual human revision. This is often used to quickly catch bugs introduced into the code when implementing new features, and can greatly reduce the amount of errors that often occur when working on a development project.

Automated Testing is often a key component of continuous integration, wherein developers make small, frequent updates to their shared repositories to minimize large changes to code infrastructure. Each integration made can then be verified by an automated build and automated tests.

Github has several automated testing features embedded into its platform: for example, the detection of merge conflicts during pull requests for new commits. If developers were unable to rely on platforms with the ability to catch these issues automatically, the entire development process would rely on manual error correction and become exceedingly more difficult as a result. 





![Chart image](/images/git_testing.png)
> **Source:** [Docker](http://www.effectivedevelopment.org/automation/testing.html)




**References:**

[Effective Development](http://www.effectivedevelopment.org/automation/testing.html)

[CodeShip](https://codeship.com/continuous-integration-essentials)

[Ben Balter](https://ben.balter.com/2015/09/10/blog-style-tests/)


## Continuous Integration

Continuous integration is about creating a devlopment pipeline. Often this process is automated. In traditional software development releases are big production. Releases are done infrequently so therefore there are many changes that have occured. 
Testing is more complicated and instead of one new feature being tested multiple features dependancies and even infrastructure changes complicate the deployment. It easy for mistakes to happen with the multiple processes occuring, and it would be diffiuclt to pinpoint bugs as each feature or depencancy could contribute. 

Continuous integration propses the idea of small, frequent updates. This offers a significant advantage over traditional deployments. One feature or process is updated. This allows for easy tracking of changes in the environment and software. If a bug is found it is easy to rollback to a previous state or track down the bug due to there only being a small amount of code changes. Since development and deployment occur more frequently the team can get more practice and it can take some of the manula labor out of the process. 
These continous development processes due to their small nature make the task of automation easier. Testing, deployment, and code validation can be automated and pushed to repository. 

Tools suck as Docker and other containerization software allow this processs to occur frequently, automatically, and easily reproduced. Using Docker the exact environment used for devoplment can be pushed to deployment. There is a level of abstraction that allows for the Docker image (application image) to house all the dependancies needed for the application. If a new version of a dependancy say say Python 3 vs Python 2.7 is needed it can be deployed inside the container. The infrastructure of the production system reamins untocuhed and bugs can be traced to the current image. The old application image can spun back up in seconds.   

![Chart image](/images/chart.png)
> **Source:** [usersnap](https://usersnap.com/blog/docker-for-web-developers)


  


**References:** 

[infoworld](https://www.infoworld.com/article/3130670/the-hidden-benefits-of-docker-for-qa.html)

[usersnap](https://usersnap.com/blog/docker-for-web-developers)

[Philipp Hauer's Blog ](https://phauer.com/2015/tutorial-continuous-delivery-with-docker-jenkins/)

=====================================
## [Return to index](/README.md)
## [Gitflow](/gitflow.md) 
## [Definitions](/definitions.md)
