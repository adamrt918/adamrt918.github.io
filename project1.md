[Back to Portfolio](./)

Juniper Nautobot Integration
===============

-   **Skills:** Python, YML, Markdown, Ansible, Juniper, Nautobot, APIs
-   **Source Code Repository:** [Juniper Nautobot Integration][https://github.com/adamrt918/vlan-pruner](https://github.com/adamrt918/ansible_repo/))
    (Please [email me](https://mail.google.com/mail/u/0/?source=mailto&to=thiemann.adam@gmail.com&su=Github_Access&fs=1&tf=cm) to request access.)

## Project description
These scripts go through a set of target devices in the ansible playbook, "sync_nautobot.yml" to get VLAN, Prefix, and Management IP Address information for initial sync with the nautobot application using the Juniper and Nautobot APIs. Once synced, the user can use the native Device Onboarding plugin to sync network data and use yaml overrides to configure the job to perform as necessary.

## Future Developments
My next development is to integrate Palo Alto for useability within the program.

## How to compile and run the program

- Clone the repository onto your ansible server.
- Run 
    > ansible-playbook -i hosts.yml -e "dest=<device_group>"
- The code will compile information from the active network state and sync it to nautobot.

[Back to Portfolio](./)
