# Ansible_CICD
## _Ansible for my CICD project_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Features
- Provision and install all dependencies on the local machine required to run jenkins on docker 

## Tech

The application uses a number of open source projects to work properly:

- [Ansible] - Infrastructure provisioning tool!

## Installation

The application requires [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) to run

## Run the app

The application is very easy to run.

Just by running a single command you will be able to create and deploy localy a jenkins container able to run docker in it

```sh
cd Ansible_CICD
sudo ansible-playbook -v jenkinsPlaybook.yml
```

This will create the docker container running jenkins and configure all the plugins and jobs required


Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8080
```


