# Introduction

This repository contains the code of the SD-WAN DevNet Sandbox learning labs.


# Requirements

ansible==2.5.0
requests==2.18.4

# Usage

To run the exercises you first have to install the requirements (the use of a virtualenv is reccomended):

`python3 -m venv ANSIBLE_VENV`

`source ANSIBLE_VENV/bin/activate`

`pip install -r requirements.txt`  

you can then clone the repository:

`git clone https://github.com/CiscoDevNet/sdwan-ansible-code.git` 

`cd sdwan-ansible-code/code`

Verify that the hostname,username and password are correct:

`cat inventories/inventory.yml`

if not modify them accordingly 

You are now ready to run the playbook and follow along with the exercises:

`ansible-playbook site.yml`  

# Run from Docker

If you prefer running the code from docker first create the docker container:

`position yourself in the sdwan-ansible-code folder`

`docker build -f dockerfile/Dockerfile_sdwan_ansible.cnf -t ansible_sdwan .`

`docker run --rm -it --mount source="$(pwd)/code",target=/home/devnet,type=bind  ansible_sdwan`


rm -Rf ANSIBLE_VENV