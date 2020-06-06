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