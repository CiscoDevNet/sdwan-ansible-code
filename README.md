# Introduction

This repository contains the code of the SD-WAN DevNet Sandbox learning labs.
Create and update banner templates such as the Motto of the Day (MOTD) using SD-WAN automation with Ansible.

## SD-WAN automation with Ansible
Cisco SD-WAN provides a great tool for configuration management and network monitoring: vManage. Within the SD-WAN fabric, the vManage tool is indeed responsible of handling the 'management plane' - meaning that all the configurations can be performed from its graphical user interface (GUI). The vManage tool also offers a rich set of REST API so that the end user can automate specific workflows using your favorite tool, such as Postman, Python, Ansible, and others.

## Objectives
The code here can be used with the Cisco DevNet Learning Labs
[SD-WAN automation with Ansible](https://learninglabs.cisco.com/lab/sdwan_automation_with_ansible/step/1) the user will get familiar both with SD-WAN REST API and Ansible.

You will:

- Learn how to log into the vManage Dashboard.
- Create a banner Feature Template.
- Delete a template (our example will be focused on a banner - Feature Template).
- Modify a banner Feature Template.

## Get the code

Clone and access it with the following commands:

git clone https://github.com/CiscoDevNet/sdwan-ansible-code
Use pip to install the necessary requirements.

```
pip install -r requirements.txt
```

## Requirements

`ansible==2.5.0`
`requests==2.18.4`
