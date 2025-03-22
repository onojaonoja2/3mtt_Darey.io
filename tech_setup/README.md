# tech set up

This repository documents the setup and configuration of my development environment for the 3mtt_darey project.

## Environment Setup

The following tools have been successfully installed and configured:

* **Visual Studio Code (VS Code):** A versatile code editor used for development.
* **VirtualBox:** A powerful virtualization software used to run virtual machines.
* **Ubuntu Vagrant Virtual Machine:** A lightweight and reproducible development environment running Ubuntu, managed by Vagrant.
* **MobaXterm:** An enhanced terminal for Windows, providing SSH, X11, and other network tools.

## Installation Details

* **VS Code:** Installed using the official installer from the VS Code website. Extensions may be installed as needed for specific project requirements.
* **VirtualBox:** Installed from the official VirtualBox website.
* **Ubuntu Vagrant VM:**
    * Vagrant was installed from the official Vagrant website.
    * An Ubuntu box was added using `vagrant box add ubuntu/focal64`.
    * A `Vagrantfile` was created to configure the virtual machine.
    * The virtual machine was started using `vagrant up`.
* **MobaXterm:** Installed from the official MobaXterm website.

## Usage

* VS Code will be used for code editing and project management.
* VirtualBox will run the Ubuntu Vagrant VM, providing a consistent development environment.
* MobaXterm will be used to access the Ubuntu Vagrant VM via SSH and for general terminal operations.

## Notes

* Ensure that VirtualBox virtualization is enabled in your system's BIOS settings.
* Vagrant and VirtualBox must be installed and configured correctly for the Ubuntu VM to function.
* MobaXterm can be configured to easily connect to the vagrant machine.

## Future Improvements

* Document the specific configurations made to each tool.
* Add instructions for setting up project-specific dependencies within the Vagrant VM.
* Add any scripts and configuration files used to automate the setup process.