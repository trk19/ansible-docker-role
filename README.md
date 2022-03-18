
# About this Project

 - **PROJECT NAME :**  ansible-docker-role .
 
 - **PROJECT GOAL :**   Apply automation practices to prepare infrastructure ( virtual machine ) with docker + docker-compose installed and fully configured to be used .

 - **USED TOOLS :** 
	-  Virtualisation Platform : [Virtualbox](https://www.virtualbox.org/)
	-  IaC ( Infrastructure as Code ) : [Vagrant](https://www.vagrantup.com/ "Vagrant")
	- Configuration Managament :  [Ansible](https://www.ansible.com/)

- **Motivations of this work :** This works is considered as reference utility in other project . 
 mainly , to prepare a simple **ansible role files** to install and configure docker and docker-compose on VMs running under (Ubuntu 20.04.2 LTS) OS.

# How it works

### Prerequisites

1. Linux / Windows host machine ( I have used Linux Mint 20.2) 
2. Internet Connection
3. [Virtualbox](https://www.virtualbox.org/) installed on Host Machine
3. [Vagrant](https://www.vagrantup.com/ "Vagrant") installed on Host Machine

### How to run it

#####  Setup Vagrantfile

- In the file named `Vagrantfile` , change `wlp3s0` in the code portion `bridge: "wlp3s0"` with your **network interface adapter name** connected to the internet .

#####  Run the project 
- To run this project , navigate to the project directory using a terminal , and tap the command `vagrant up --provision` . 

# Contributing 

- If you want to contribute to this project and make it better with new ideas or fixing issues, your pull request is very welcomed. 
- If you find any issue just put it in the repository issue section.

Thank you.


# Contact

- Email:  **t.mohammedhacene@gmail.com**
- Linkedin : **[Tarek MOHAMMED HACENE](https://www.linkedin.com/in/tarekmh/ "Tarek MOHAMMED HACENE")**

