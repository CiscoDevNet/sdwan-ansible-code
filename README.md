[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/sdwan-ansible-code)
# Introduction

Create and update banner templates such as the Motto of the Day (MOTD) using SD-WAN automation with Ansible. This repository contains the code for the SD-WAN DevNet Sandbox that is used as the backend for SD-WAN Learning Labs.


## SD-WAN automation with Ansible
Cisco SD-WAN provides a great tool for configuration management and network monitoring: vManage. Within the SD-WAN fabric, vManage is responsible for handling the *management plane*, meaning that all configuration can be performed from its graphical user interface (GUI). vManage also offers a rich REST API. This enables the end user to automate specific workflows using favorite tools, such as Postman, Python, Ansible, and others.

## Objectives
The code here can be used with the Cisco DevNet Learning Lab
[SD-WAN automation with Ansible](https://developer.cisco.com/learning/lab/sdwan_automation_with_ansible/step/1), through which the user will get familiar both with the SD-WAN REST API and with Ansible.

You will:

- Learn how to log into the vManage Dashboard.
- Create a banner Feature Template.
- Delete a template (our example will be focused on a banner - Feature Template).
- Modify a banner Feature Template.

## Get the code

Clone and access it with the following commands:

```git clone https://github.com/CiscoDevNet/sdwan-ansible-code```

Use pip to install the necessary requirements.

```
pip install -r requirements.txt
```

## Requirements

`ansible==2.5.0`
`requests==2.18.4`
