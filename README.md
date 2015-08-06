# container-devops

#How Containers are Disrupting Devops
Containers are disrupting DevOps by providing ways to automate the delivery process in easily manageable segments. The DevOps pipeline is becoming a continuous delivery process, with continuous development, integration, and deployment.  We asked, “how are containers redefining how DevOps is handled and what vendors and products are leading the change?”


##Containers Make Environments Consistent
Containers provide a common set of building blocks that can be reused in any stage of development to recreate identical environments for development, testing, staging, and production.  Containers extend the idea of "write once, deploy anywhere" to an infrastructure abstraction that application developers can easily consume and operations professionals can predictably manage.

##Containers Make Tooling Consistent
Containers provide a disposable unit of logic and computation that can be used to perform a vital component of the DevOps delivery pipeline in a reusable way.  Now critical code quality, analysis, build, and test functions can be packaged as containers and consistently reused within developer workspaces, continuous integration systems, and release management tools. Code productivity and tooling vendors are now able to inject their solutions into every phase of the pipeline.

##Container Infrastructure
ActiveState [Stackato](http://www.activestate.com/stackato) (agile platform)

Alpine [Linux](http://www.alpinelinux.org) (Lightweight operating system container-optimized)

Amazon [EC2 Container Service](http://aws.amazon.com/ecs/) (Docker extension tools)

Apache [Mesos](http://mesos.apache.org/) (distributed systems and container kernel)

Apache [Zookeeper](https://zookeeper.apache.org) (centralizes container configurations)

CenturyLink [Cloud] (https://www.ctl.io/) (cloud and management service)

[Ceph](http://ceph.com/) (distributed block storage for Docker)

ClusterHQ [Flocker](https://clusterhq.com/2015/06/17/flocker-1-0/) (open source container data volume manager)

CoreOS [Tectonic](https://tectonic.com/) (kubernetes cluster for Docker)

CoreOS [Flannel](https://coreos.com/flannel/docs/latest/flannel-config.html) (cross-container communication)

Datawise.io [Project 6](http://www.datawise.io/project-6.html) (deploy and manage Docker 
containers across clusters)

Docker [Swarm](https://docs.docker.com/swarm/) (native clustering for Docker)

Docker [Machine](https://www.docker.com/docker-machine) (Automated Docker provisioning)

EngineYard [OpenDeis](http://deis.io/overview/) (open source paas for Docker)

Joyent [Triton](https://www.joyent.com/) (elastic container infrastructure)

Google [Compute Engine](https://cloud.google.com/compute/) (IaaS)

Google [Kubernetes](http://kubernetes.io/) (manage a cluster of Docker containers)

HashiCorp [Packer.io](https://www.packer.io/) (image construction automation)

HashiCorp [Consul.io](https://www.consul.io/) (finds and configure infrastructure services)

IBM [Bluemix](https://console.ng.bluemix.net/) (hybrid paas based upon cloud foundry and Docker)

[Jelastic](https://jelastic.com/docker/) (multi-container orchestration platform)

Microsoft [Azure](https://azure.microsoft.com/en-us/) (user + management software)

Mesosphere [DCOS] (https://mesosphere.com/product/) (data center OS works with Docker)

[Nirmata] (http://nirmata.com/tag/docker/) (application deployment and operations with Docker)

OpenStack [Nova](https://wiki.openstack.org/wiki/Docker) (launches containers on a massive scale)

[Pertino](http://pertino.com/pertino-simplifies-networking-of-docker-containers-across-any-cloud-anywhere) (builds container-level VPC networks)

Portworx [PWX](http://portworx.com/products/) (scale out block storage for Docker)

Rackspace [Managed Cloud](http://www.rackspace.com/cloud) (management software)

RancherLabs [Rancher](http://rancher.com/rancher/) (infrastructure platform for Docker)

RancherLabs [RancherOS](http://rancher.com/rancher-os/) (Linux distribution that runs OS as Docker containers) 

Red Hat [OpenShift](https://www.openshift.com/) (hybrid PaaS based on Docker)

VMware [Photon](https://vmware.github.io/photon/) (lightweight linux host for containers)

[Weave](http://weave.in/) (create a network of Docker containers)

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

VMware [AppCatalyst](http://blogs.vmware.com/cloudnative/vmware-appcatalyst) (desktop hypervisor optimized for containers)

[Wercker](http://wercker.com/) (automating driven development)


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

CodeShip [ParallelCI](https://codeship.com/features/parallelci) (parallel testing with containers)

[Shippable](https://app.shippable.com/) (automated DevOps with Docker)

####Code Quality Analysis
[CodeClimate](https://codeclimate.com/) (static analysis with containers)

[SonarQube](http://www.sonarqube.org/) (code quality with containers)

Cloudbees [Jenkins CI](https://www.cloudbees.com/jenkins/about/code-quality-analysis) (build slaves runnable within a Docker container)

####Packaging and Build Automation
Atlassian [Bamboo](https://www.atlassian.com/software/bamboo)(using Docker containers to create build agents)

[Bitnami](https://bitnami.com/) (image cloud hosting)

Cloudbees [Jenkins CI](https://www.cloudbees.com/jenkins/about/code-quality-analysis) (build slaves runnable within a Docker container)

[Quay.io](https://quay.io/) (secure hosting and private storage for teams using Docker during deployment)


####Testing Frameworks
[Salt](http://docs.saltstack.com/en/latest/ref/states/all/salt.states.dockerio.html) (allows unit testing within container)

[New Relic](http://newrelic.com/docker) (unit testing and monitoring app performance for Docker)

[SeleniumEnv](https://github.com/Codeception/SeleniumEnv) (can be run through Docker instead of installed)

[PhantomJsEnv](https://github.com/Codeception/PhantomJsEnv) (can be run through Docker instead of installed)

[RoboCI](https://github.com/Codegyre/RoboCI) (aimed to run Travis CI builds locally inside Docker containers)


###Continuous Deployment
####Continuous Deployment
Docker [Compose](https://docs.docker.com/compose/) (defining and running multi-container applications)

[Screener.io](https://screener.io/) (helps screen code before and after being Dockerized)

Amazon [OpsWorks](http://aws.amazon.com/opsworks/) (how to integrate with Docker can be found here)

[Ansible](http://www.ansible.com/docker) (playbooks will generate consistent app in containers & vms)

[Chef.io](https://www.chef.io/solutions/containers/) (container management, provisioning and automation)

PuppetLabs [Puppet Forge](https://forge.puppetlabs.com/tags/docker) (Docker management)

[Salt](http://docs.saltstack.com/en/latest/ref/states/all/salt.states.dockerio.html) (container management, provisioning and automation)

####Artifact and Image Registry
JFrog [Artifactory](http://www.jfrog.com/confluence/display/RTF/Docker+Repositories) (doubles as a Docker registry)

[Google Container Registry] (https://cloud.google.com/container-registry/) (secure Docker image storage on Google Cloud platform)

[Tutum Registry] (https://support.tutum.co/support/solutions/articles/5000012183-using-tutum-s-private-Docker-image-registry) (free private Docker registry)

[Quay.io](https://quay.io/plans/) (secure hosting for Docker registries)

Docker [Hub](https://www.docker.com/docker-hub) (Hosted registry service)

Docker [Trusted Registry](https://www.docker.com/docker-trusted-registry) (Private dedicated image registry)

####Operations Tools
[AppDynamics](http://community.appdynamics.com/t5/eXchange-Community-AppDynamics/Docker-Monitoring-Extension/idi-p/14749) (extension for Docker monitoring)

CenturyLink Labs [Panamax.io] (http://panamax.io/) (tools to visualize & manage containers)

[Sysdig] (https://sysdig.com/distributed-container-monitoring-sysdig-cloud-revolution/) (distributed container monitoring)

[SignalFx](http://blog.signalfx.com/signalfx-is-proud-to-join-the-docker-ecosystem-technology-partner-program) (streaming analytics of Docker apps)

[New Relic](https://blog.newrelic.com/2015/05/06/docker-support-2/) (distributed container monitoring and analytics)







