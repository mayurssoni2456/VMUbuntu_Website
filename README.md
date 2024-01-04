# Learning - Ubuntu VM Setup and WordPress Deployment using Vagrant

**Description**\n
  This project provides a straightforward guide to setting up an Ubuntu Virtual Machine (VM) using Vagrant and deploying a WordPress website within the VM. It automates the process of creating a development environment for WordPress.

## Technologies Used
Vagrant
VirtualBox (as the default provider)
Ubuntu 20.04 LTS
WordPress

## Requirements
  Vagrant
  VirtualBox

## Setup Instructions
### Installation
  Install Vagrant and VirtualBox on your system.
  Clone or download this repository to your local machine.
### Running the Project
  Open a terminal or command prompt and navigate to the project directory.
  Run the following command to set up the Ubuntu VM and deploy WordPress:

```
  vagrant up
```

## **Usage**
  Once the setup is complete, access the WordPress site at <config.vm.network "private_network", ip: "your ip address"> in your web browser.
  Log in to the WordPress admin panel using the provided credentials.
  Use the VM management commands such as vagrant up, vagrant halt, vagrant destroy, etc., to manage the VM.
