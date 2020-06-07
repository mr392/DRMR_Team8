## Docker

Docker is a platform that is used to package an application and all of its dependencies together in the form of "containers" - standardized units of software - in order to make sure that the application works seamlessly in any development, testing or production environment.

The practice of creating containers is a type of virtualization. Traditional virtualization brings abstraction to the hardware and is the technique of importing a guest operating system on top of a host operation system - for example, creating a virtual machine to run Windows on an Apple computer.

Containerization, on the other hand, brings abstraction to the operating system level - a container uses the host operating system without creating a guest OS, and shares relevant libraries and resources as needed. Application specific binaries and libraries all run on the host kernel, making processing and execution run very efficiently. However, each container is also isolated from the other containers, and are able to host applications without interfering with each other.

Some of the advantages of using containers over virtual machines are:
- Faster boot-up
- Containers are lighter and smaller
- Better resource utilization compared to virtual machines

Through the use of containerization, Docker lets developers create unique environments to explore the capabilities of their software.

![Chart image](/images/git_docker.png)
> **Source:** [Docker](https://www.docker.com/resources/what-container)





**References:**

[Stackshare](https://stackshare.io/stackups/docker-vs-github)

[Codefresh](https://codefresh.io/docker-tutorial/implementing-git-flow-with-dockers/)

[Edureka](https://www.edureka.co/blog/docker-tutorial)

[Geeks for Geeks](https://www.geeksforgeeks.org/containerization-using-docker/)