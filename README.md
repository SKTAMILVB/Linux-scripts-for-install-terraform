# Linux-scripts-for-install-terraform
- This document explains how to install Terraform on a Linux system using a shell script. The script downloads the Terraform binary, installs it, and verifies the installation.
  
## Prerequisites
- Before installing Terraform, ensure the following are available on your Linux system:
   - Linux OS (Ubuntu)
   - Internet connectivity
   - wget 
   - unzip utility
   - sudo access

- **Terraform Installation Script**:
The following script performs these actions:
  - Defines the Terraform version
  - Downloads Terraform from HashiCorp official site
  - Extracts the binary
  - Moves Terraform to /usr/local/bin
  - Verifies the installation

- **Steps to Execute the Script**
 - Create a script file.
 - Paste the script content and save the file.
 - Provide execute permission.\
 - Run the script:
