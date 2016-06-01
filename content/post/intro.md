+++
Categories = ["agenda","workshop"]
Tags = ["logistics","speakers"]
date = "2016-03-15T16:23:23+09:00"
title = "Welcome to the Pivotal Cloud Foundry Workshop@GM Austin"
type = "Introduction"
weight = 1
+++
##### Location

Corvette 2nd Floor Austin

##### Date and Time
Date: **May 9 , 2016**

Time: **9:30AM—4:30PM**

Click to get the Agenda, Prerequisites and Setup for the workshop.

<!--more-->

##### Agenda

Broad Agenda (We will have breaks in between sessions)

    9:30 - 10:30   Walkthrough the Push/Bind/Scale

    10:30 - 11:00  Setting up Cloud Foundry / CLI and Pre-Requisites on Developer laptops

    11:00 - 12:30  Hands on Push/Bind/Scale/Blue Green Deployment

    ==== LUNCH ====

    1:30-4:00 : GM App Classification and hands-on push to platform

    4:00 and beyond : Open discussion on various topics Docker, K8, Monitoring on Platform



Goals and Outcomes:

    Walk through App Classification and Decision tree​ for Pivotal Cloud Foundry​
    Hands on experience doing rapid application deployment, consumption of services and blue-green deployments



##### Prerequisites
1. Java SDK 1.7+

2. Git CLI from [github.com](https://mac.github.com/)

3. Cloud Foundry CLI for [Mac](https://github.com/cloudfoundry/cli/releases) or [Windows](http://docs.cloudfoundry.org/devguide/installcf/install-go-cli.html#windows)

4. Curl from [curl](http://curl.haxx.se/)

5. Use Workshop PCF Env or Pivotal Web Services Account.  Create a free trial account here [Pivotal Web Services](http://run.pivotal.io/)

6. Maven for build (https://maven.apache.org/install.html)

7. Vagrant (In case you want to run Concourse CI/CD using Vagrant)

##### Setup

1. Install the Prerequisites software (cf cli)

2. Check if you are able to use the cf cli to connect to the PCF Workshop Env. Alternatively, you can create a PWS account and check the firewall/connectivity before the Workshop

          cf login -a https://api.pcf2.cloud.fe.pivotal.io  --skip-ssl-validation

3. Check if you are able to connect to Git repo and download / clone the repo using CLI
4. Login to the App Manager Console at

        https://apps.pcf2.cloud.fe.pivotal.io

5. Note: Tiles preinstalled in the PCF Workshop environment which we will be using the workshop. You don't need any setup for these tiles.

          ER
          Spring Cloud Services
          RabbitMQ
          MySQL
          MongoDB
          Neo4J
          Redis
          GitLab
          JFrog Artifactory
          Cloud Bees Jenkins
          


##### Speakers

    Rajesh Jain, Platform Architect
    Marcelo Borges, Platform Architect
    Chris Johnson, Platform Architect

#### Presentation


{{< googleslide "https://docs.google.com/presentation/d/1wNT7il4szv25Tl0KBG4SaetQkwKwyqk_rrQfskDSLgo/embed?start=false&loop=false&delayms=3000" >}}


#### Videos


{{< youtube V75fE_dxuBQ >}}


{{< youtube 7APZD0me1nU >}}
