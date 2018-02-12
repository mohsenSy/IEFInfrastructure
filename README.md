IEFInfrastrucure Project
========================

This project contains all the ansible playbooks used for configuring the
Virtual Machines running on the servers in the Information and Engineering
Faculty - Tishreen University - Syria.

There will be multiple playbooks for each service, the hosts file is not included
here it only exists on the system's administrator workstation along with the private
key used to access the servers.


### Monitoring
For the monitoring service [zabbix](https://zabbix.com/) will be used, I created
an ansible role to install zabbix agent and server.

Used `monitoring.yml` playbook to install the server and agent on one of our
Linux servers called `server01`.
