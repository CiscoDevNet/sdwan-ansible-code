# Introduction

This repository contains the code for the learning 


# Requirements


# Usage

To run the exercises you first have to clone the repository

`git clone https://github.com/CiscoDevNet/sdwan-ansible-code.git` 

then you have to make sure to install the following requirements (the use of a virtualenv is reccomended)

`python3 -m venv ANSIBLE`
`source ANSIBLE/bin/activate`
`pip install -r requirements.txt`   


# Run from Docker



`docker build -f dockerfile/Dockerfile_sdwan_ansible.cnf -t ansible_sdwan .`

`docker run --rm -it --mount source="$(pwd)/code",target=/home/devnet,type=bind  ansible_sdwan`


