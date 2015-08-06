# container-devops

#How Containers are Disrupting Devops
Containers are disrupting DevOps by providing ways to automate the delivery process in easily manageable segments. The DevOps pipeline is becoming a continuous delivery process, with continuous development, integration, and deployment.  We asked, “how are containers redefining how DevOps is handled and what vendors and products are leading the change?”


##Containers Make Environments Consistent
Containers provide a common set of building blocks that can be reused in any stage of development to recreate identical environments for development, testing, staging, or production.  Containers extend the idea of "write once, deploy anywhere" to an infrastructure abstraction that application developers can easily consume and operations professionals can predictably manage.

##Containers Make Tooling Consistent
Containers provide a disposable unit of logic and computation that can be used to perform a vital component of the DevOps delivery pipeline in a reusable way.  Now critical code quality, analysis, build, and test functions can be packaged as containers and consistently reused within developer workspaces, continuous integration systems, and release management tools. Code productivity and tooling vendors are now able to inject their solutions into every phase of the pipeline.

##Container Infrastructure
ClusterHQ [Flocker](https://clusterhq.com/2015/06/17/flocker-1-0/) (open source container data volume manager)

ClusterHQ [PowerStrip](https://clusterhq.com/2015/02/02/powerstrip-prototype-docker-extensions-today/) (helps prototype Docker extensions)

Portworx [PWX](http://portworx.com/products/) (scale out block storage for Docker)

[Weave](http://weave.in/) (create a network of Docker containers)

ActiveState [Stackato](http://www.activestate.com/stackato) (agile platform)

Amazon [EC2 Container Service](http://aws.amazon.com/ecs/) (Docker extension tools)

Apache [Mesos](http://mesos.apache.org/) (scale out linux for apps - supports Docker)

CoreOS [Tectonic](https://tectonic.com/) (kubernetes cluster for Docker)

Datawise.io [Project 6](http://www.datawise.io/project-6.html) (deploy and manage Docker 
containers across clusters)

Docker [Swarm](https://docs.docker.com/swarm/) (native clustering for Docker)

EngineYard [OpenDeis](http://deis.io/overview/) (open source paas for Docker)

Joyent [Triton](https://www.joyent.com/) (elastic container infrastructure)

Google [Compute Engine](https://cloud.google.com/compute/) (IaaS)

Google [Kubernetes](http://kubernetes.io/) (manage a cluster of Docker containers)

IBM [Bluemix](https://console.ng.bluemix.net/) (hybrid paas based upon cloud foundry and Docker)

[Jelastic](https://jelastic.com/docker/) (multi-container orchestration platform)

Microsoft [Azure](https://azure.microsoft.com/en-us/) (user + management software)

Mesosphere [DCOS] (https://mesosphere.com/product/) (data center OS works with Docker)

[Nirmata] (http://nirmata.com/tag/docker/) (application deployment and operations with Docker)

OpenStack [Nova](https://wiki.openstack.org/wiki/Docker) (launches containers on a massive scale)

Rackspace [Managed Cloud](http://www.rackspace.com/cloud) (management software)

Red Hat [OpenShift](https://www.openshift.com/) (hybrid PaaS based on Docker)

VMware [Photon](https://vmware.github.io/photon/) (lightweight linux host for containers)

----------------------------------------------------------------------

1st column
##DevOps Pipeline:
1. Author Code & Check In

2. Check Out & Build Code

3. Unit Test

4. Quality Control

5. Package and Archiving

6. Integration Testing

7. Deploy to Test Environment

8. Deploy to pre-production

9. Acceptance testing

10. Deploy to Production

11. Management/Monitoring


2nd Column
##Continuous Delivery:
Continuous Development

Continuous Integration

Continuous Deployment


----------------------------------------------------------------------

###Continuous Development
####Continuous Development
[Codenvy](https://codenvy.com/) (Docker containers as workspace & scalable builders / runners on Docker)

[Vagrant](http://docs.vagrantup.com/v2/provisioning/docker.html) (Docker provisioner)

####Developer Workspace
[Codenvy](https://codenvy.com/) (Docker containers as workspace & scalable builders / runners on Docker)

[Cloud9] (https://c9.io/) (Docker containers as workspace)

Eclipse [Che] (http://www.eclipse.org/che/) (hosted workspaces that use containers for microservices)

JetBrains [IntelliJ Idea](https://www.jetbrains.com/idea/) (manage Docker containers from IDE)

[Nitrous.io](https://pro.nitrous.io/?l=1) (Docker containers as workspace)

[Vagrant](http://docs.vagrantup.com/v2/provisioning/docker.html) (Docker provisioner)

####Source Code Management
Apache [Subversion](https://subversion.apache.org/) (version control)

[Git](https://git-scm.com/) (version control)


###Continuous Integration
####Continuous Integration
[Drone.io](http://blog.drone.io/2014/2/5/open-source-ci-docker.html) (open source continuous integration built on Docker)

[Electric Cloud](http://electric-cloud.com/plugins/directory/p/docker/) (plug-in for to invoke containers while building)

XebiaLabs [Overcast](https://github.com/xebialabs/overcast) (helps use Docker for integration testing with most other services)

Cloudbees [Jenkins CI](https://www.cloudbees.com/jenkins/about/code-quality-analysis) (build slaves runnable within a Docker container)

[CircleCi](https://circleci.com/docs/docker) (CI with Docker)

[Shippable](https://app.shippable.com/) (automated DevOps with Docker)

####Code Quality Analysis
SonarQube (code quality with containers)

Cloudbees Jenkins CI (build slaves runnable within a Docker container)

####Packaging and Build Automation
Atlassian (using Docker containers to create build agents)

CloudBees Jenkins CI (build slaves runnable within a Docker container)

Quay.io (secure hosting and private storage for teams using Docker during deployment)

####Testing Frameworks
Salt (allows unit testing within container)

New Relic (unit testing and monitoring app performance for Docker)

SeleniumEnv (can be run through Docker instead of installed)

PhantomJsEnv (can be run through Docker instead of installed)

RoboCI (aimed to run Travis CI builds locally inside Docker containers)


###Continuous Deployment
####Continuous Deployment
Docker Compose (defining and running multi-container applications)

Screener (helps screen code before and after being Dockerized)

Amazon OpsWorks (how to integrate with Docker can be found here)

Ansible (playbooks will generate consistent app in containers & vms)

Chef (container management, provisioning and automation)

PuppetLabs Puppet Forge (Docker management)

Salt (container management, provisioning and automation)

####Artifact and Image Registry
JFrog Artifactory (doubles as a Docker registry)

[Google Container Registry] (https://cloud.google.com/container-registry/) (secure Docker image storage on Google Cloud platform)

[Tutum Registry] (https://support.tutum.co/support/solutions/articles/5000012183-using-tutum-s-private-Docker-image-registry) (free private Docker registry)

Quay.io (secure hosting for Docker registries)

####Operations Tools
AppDynamics (extension for Docker monitoring)

CenturyLink Labs (tools to visualize & manage containers)

Sysdig (distributed container monitoring)

SignalFx (streaming analytics of Docker apps)

New Relic (distributed container monitoring and analytics)







