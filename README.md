# fullStack

#### My Notes around getting started as a full stack engineer
- I Need to get cloud native
- Automation is about stamps, not snowflakes

# Contents
* [Git and Github](#git)
* [Automation](#automation)
* [Scripting](#scripting)
* [REST](#rest)
* [Serverless](#serverless)
* [VM's](#vm)
* [SDN](#sdn)
* [Windows Development](#windows)
* [Container Orchestration](#orchestration)
* [Testing](#testing)


## <a name="git" /> Git / Github 
#### Read pro git 2, first 2 chapters
  * git clone https://github.com/cwdotymn/fullStack
  * git add README.md
  * git commit -m
  * git push

## <a name="automation" /> Automation
  * Ansible - agendless!
    * Ansible: Up and Running
    * Like it because we are 75% Windows and WinRM is used
    * Secure with
      * Ansible Vault
      * Stackoverflow / Blackbox w/ GPG
  * Chef
  * Puppet
    * https://puppet.com/solutions/security-compliance

## <a name="scripting" /> Scripting
  * Python to start
  * GO once you're proficient
  * Don't forget PS for Windows

## <a name="rest" /> REST
  * Postman
    * Postman Interceptor to capture requests and save them to Postman's history
    * [GitHub](http://github.com)
    * [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) 
    * [Building MicroServices](http://search.safaribooksonline.com/book/software-engineering-and-development/9781491950340)
Building Microservices
  * GraphQL (http://graphql.org/)
    * Acts as an endpoint
    * https://github.com/serverless/serverless-graphql
    * Can wrap REST api's

## <a name="serverless" /> Serverless
  * https://serverless.com/
  * AWS Lambda
    * https://github.com/dwyl/learn-aws-lambda
  * Azure Functions

## <a name="vm" /> VM's
  * Docker Images
  * Vagrant
    * Vagrant with Docker (https://www.vagrantup.com/docs/provisioning/docker.html)

## <a name="sdn" /> SDN
  * vmWare NSX
  * Cisco ACI (Application Centric Infrastructure)
  * Juniper Contrail

## <a name="windows" />Windows Development
  * penguiNet for SSH and Telnet

## <a name="orchestration" /> Container Orchestration
  * Kubernetes
    * Run on a laptop: https://github.com/kubernetes/minikube
    * Online Free Course: https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615
    * Intro Course on Github: https://github.com/kelseyhightower/intro-to-kubernetes-workshop
  * Docker Swarm
  * Mesosphere

## <a name="testing" />Testing
  * Selenium
  * Headless Chrome (PhantomJS until then)
