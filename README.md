## Project-14

## CONTINUOUS INTEGRATION WITH JENKINS, ANSIBLE, ARTIFACTORY, SONARQUBE, PHP

### ANSIBLE ROLES FOR CI ENVIRONMENT

In addition to our already existing roles, we will go ahead and add two more roles to ansible:


1.	[SonarQube](https://www.sonarqube.org). (Scroll down to the Sonarqube section to see instructions on how to set up and configure SonarQube manually)
1. [Artifactory](https://jfrog.com/artifactory).

**Why do we need SonarQube?**

SonarQube is an open-source platform developed by SonarSource for continuous inspection of code quality, it is used to perform automatic reviews with static analysis of code to detect bugs, code smells, and security vulnerabilities. Watch a short description here. There is a lot more hands on work ahead with SonarQube and Jenkins. So, the purpose of SonarQube will be clearer to you very soon.

**Why do we need Artifactory?**

Artifactory is a product by JFrog that serves as a binary repository manager. The binary repository is a natural extension to the source code repository, in that the outcome of your build process is stored. It can be used for certain other automation, but we will it strictly to manage our build artifacts.

### Configuring Ansible for Jenkins Deployment.

In previous projects, we have been launching Ansible commands manually from a CLI. Now, with Jenkins, we will start running Ansible from Jenkins user interface (UI).

To do this,
Navigate to Jenkins URL
Install & Open Blue Ocean Jenkins Plugin

