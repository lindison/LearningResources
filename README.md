# LearningResources

## A quick repo to display learning resources for different technologies.  
Making a quick area to reference learning tools and resources.

### Microsoft
A lot of focus has been on Linux based systems and models; however, Microsoft has invested heavily in this space, both with the Windows Stack and their Azure offerings. Below are some freely avaialbe courses in getting up to speed on Microsoft's approach to Cloud, building Microsoft centric Cloud native/optimized/friendly apps, and a Microsoft CICD pipeline.  

https://www.edx.org/school/microsoft   

Microsoft’s Introduction to DevOps (12 hours)  
https://www.edx.org/course/introduction-devops-microsoft-dev212x-0  

Building Cloud Apps with Microsoft Azure  (16 hours each)  
https://www.edx.org/course/building-cloud-apps-microsoft-azure-part-microsoft-dev202-1x-0  
https://www.edx.org/course/building-cloud-apps-microsoft-azure-part-microsoft-dev202-2x  
https://www.edx.org/course/building-cloud-apps-microsoft-azure-part-microsoft-dev202-3x  

Architecting Microsoft Azure Solutions (25 hours)  
https://www.edx.org/course/architecting-microsoft-azure-solutions-microsoft-dev205bx-0  

Accelerating Software Delivery Using DevOps  (15 hours)  
https://www.edx.org/course/accelerate-software-delivery-using-microsoft-dev217x  

### Programming

Go Lang  
https://golang.org/#  
https://play.golang.org/p/3VsQMI4Rx5  

Python  
https://courses.edx.org/courses/course-v1:MITx+6.00.1x_7+3T2015/info  
https://www.coursera.org/specializations/python  

Chuck's program learning Website  
http://www.pythonlearn.com/  

### Containers
LXC (Linux Containers)  
https://linuxcontainers.org/  

Docker  
https://www.docker.com/  

RKT  
https://coreos.com/rkt/  

### Container Orchestration

Mesosphere Marathon
https://mesosphere.github.io/marathon/  

Docker Swarm   
https://www.docker.com/products/docker-swarm  

Kubernetes
http://kubernetes.io/  
https://coreos.com/why/#kubernetes  

Google Container Engine  
https://cloud.google.com/container-engine/  

Amazon EC2  
https://aws.amazon.com/ecs/  

Azure Container Service  
https://azure.microsoft.com/en-us/blog/azure-container-service-preview/  

Cloud Foundry
https://docs.cloudfoundry.org/concepts/diego/diego-architecture.html  


### ContainerOSes
Snappy
http://www.canonical.com/

CoreOS

Rancher

Atomic

## Operating Systems
### Linux  
https://www.edx.org/course/introduction-linux-linuxfoundationx-lfs101x-0

Ubuntu  
http://www.canonical.com/  
http://www.ubuntu.com/  

CentOS  
https://www.centos.org/  

Red Hat  
http://www.redhat.com/   

SuSE  
http://www.suse.com/  

### Hypervisors
KVM  
QEMU  
VMWare  

### Configuration Management, Orchestration, and Automation tools
For rapid adoption and ease of implementation I prefer Ansible over others.

Ansible  
http://ansible.com  

Puppet  
https://puppet.com/  

Salt  
https://saltstack.com/  

Chef  
https://www.chef.io/chef/  


### Orchestration VM Deployment tools
For the price of free, I don't think anything comes so ready and easy to use as Vagrant. Using Vagrantfile and bootstrap scripts, I can build systems that are configured the same across many domains. In a dev space, this is awesome because I can push the Vagrantfile up to github, clone it somewhere else, and run a `vagrant up` and get a base system that is fits a predictable configuration.

Vagrant  
https://www.vagrantup.com/   

### Cloud image packaging tools
There are other tools but Packer is my favorite; namely, because it can package in a one to many fashion. Plug packer into your deployment pipeline and new images can automatically get built from the CI tool.  

Packer  
https://www.packer.io/  
