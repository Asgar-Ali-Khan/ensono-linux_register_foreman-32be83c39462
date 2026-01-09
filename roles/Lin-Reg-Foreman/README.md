# Register the Linux server to Foreman

## Overview

# Steps

1. Check and install subscription-manager package
2. Download and install ca-consumer package to get a copy of the CA certificate from Katello/Foreman Smart Proxy Server
3. Register Linux Server on Foreman based on the Organization and Activation key
4. Add sudoers file for the account with sudo and password less permission
5. Copy foreman-proxy ssh key to the sudo account in the Linux server for remote execution from Foreman via Smart Proxy server

# Use
ansible-playbook site.yml --ask-vault-pass
