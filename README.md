# Webapp Automation Projects

This repository contains automated scripts designed to improve system observability and dependency management, hosted within a secure Microsoft Azure cloud environment.

## Features
* **Automated Logging:** The `hello_world.py` script automatically generates timestamped logs in `app_log.txt` to track execution history.
* **Dependency Management:** Includes a `requirements.txt` file to manage project dependencies.

## Cloud Architecture
This project leverages Azure cloud services to ensure scalability and security.
* **Virtual Machine (VM):** Ubuntu-based compute resource running the automation scripts.
* **Virtual Network (VNet):** A private, isolated network environment for secure communication.
* **Security Implementation:** Network Security Groups (NSGs) are configured to restrict traffic, following the principle of least privilege.

## How it works
1. Run `python3 hello_world.py`.
2. The script prints a message to the console and appends a record to `app_log.txt` with a system-generated timestamp.

## Skills Demonstrated
* **Linux Command Line:** Bash scripting and file management.
* **Python Scripting:** File I/O operations and the `datetime` module.
* **Cloud Infrastructure:** Azure VM, VNet, and NSG configuration.
* **Version Control:** Git and GitHub for collaborative development.
